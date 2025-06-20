## 📄 Project Description

**Webserver Log Analysis – MapUp Take-Home Assessment**

This project is part of a take-home assignment provided by MapUp and involves analyzing the **Calgary HTTP dataset**, which contains one year's worth of HTTP request logs from the University of Calgary’s Computer Science web server.

The goal is to process, clean, and analyze real-world Apache server logs using Python, demonstrating data handling, pattern discovery, and insight generation skills.

### 📚 Dataset Information

- **Source**: confidential
- **Format**: Apache Common Log Format (one HTTP request per line)
- **Size**: ~52 MB uncompressed
- **Fields**: Host, Timestamp, Filename, HTTP Status Code, Bytes Transferred

### 🧪 Assessment Tasks Overview

The project includes:
- **Data Loading and Cleaning**
  - Decompress `.gz` file
  - Parse timestamps and extract useful fields
  - Handle malformed or missing entries
- **Analysis Tasks**
  - Total log records
  - Unique host count
  - Daily unique filename counts
  - HTTP 404 error analysis
  - Bandwidth usage per day (July 1995)
  - Hourly traffic distribution
  - Most requested files
  - Status code distribution

### 🛠️ Tools Used

- Python 3.10
- Jupyter Notebook
- Libraries: `pandas`, `datetime`, `collections`, `gzip`, `matplotlib` (if visualization added)

This analysis demonstrates real-world log parsing and data exploration skills aligned with backend monitoring, performance evaluation, and anomaly detection.

> ⚠️ Note: This repository is based on a **confidential assignment**. Shared here only for educational and portfolio purposes, **do not redistribute the dataset**.

