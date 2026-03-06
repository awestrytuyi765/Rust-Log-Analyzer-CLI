# Rust Log Analyzer CLI

A high-performance command-line tool written in Rust that analyzes application log files and generates statistics for different log levels such as INFO, WARNING, and ERROR.

This project demonstrates efficient file processing and log parsing using Rust’s standard library.

---

## 🚀 Overview

Modern applications generate large volumes of logs that contain valuable information about system behavior, errors, and warnings.

The Rust Log Analyzer CLI reads a log file and provides a summary of log levels including:

- INFO
- WARNING
- ERROR

It processes the log file line by line and counts the occurrences of each log level.

This tool is useful for developers and system administrators who need quick insights into log data.

---

## ✨ Features

- Fast log file parsing
- Counts INFO, WARNING, and ERROR messages
- Simple and lightweight CLI tool
- Built using Rust standard library
- Minimal dependencies
- Efficient memory usage

---

## 🛠 Tech Stack

- Rust
- Rust Standard Library

---

## 📂 Project Structure

rust-log-analyzer-cli
│
├── src
│   └── main.rs
│
├── sample.log
│
└── README.md

---

## 📄 Sample Log File

Example `sample.log`:

INFO User logged in
ERROR Database connection failed
WARNING Disk usage high
INFO Payment completed
ERROR Network timeout

---

## ▶️ How to Run

### 1. Clone the repository

git clone https://github.com/yourusername/rust-log-analyzer-cli.git

cd rust-log-analyzer-cli

---

### 2. Compile the program

rustc src/main.rs

---

### 3. Run the executable

Linux / Mac

./main

Windows

main.exe

---

## 📊 Example Output

Log Analysis Result
-------------------
INFO: 2
WARNING: 1
ERROR: 2
Total Logs Processed: 5

---

## 🧠 How It Works

The program:

1. Opens the log file
2. Reads the file line by line
3. Detects log level keywords
4. Counts occurrences of each log level
5. Prints a summary report

This approach ensures efficient processing even for large log files.

---

## 🎯 Learning Objectives

This project demonstrates several important Rust concepts:

- File handling
- String pattern matching
- Iterating over file lines
- Command-line program structure
- Error handling
- Efficient data processing

---

## 📌 Future Improvements

Possible enhancements include:

- Support for custom log formats
- Regex-based log filtering
- Export results to JSON or CSV
- Log visualization dashboard
- Multi-file log analysis
