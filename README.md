# Vulnerability Scanner

This project is an in-depth vulnerability scanner written in Python, inspired by the Nuclei project. It supports various protocols such as HTTP, DNS, TCP, UDP, FTP, and SMTP. The scanner uses predefined templates to perform scans and logs the results.

## Features

- Supports multiple protocols (HTTP, DNS, TCP, UDP, FTP, SMTP)
- Template-based scanning
- Detailed logging and reporting
- Concurrency for faster scanning

## Installation

To get started with the vulnerability scanner, clone the repository and install the required dependencies.

```bash
git clone https://github.com/yourusername/vulnerability_scanner.git
cd vulnerability_scanner
pip install -r requirements.txt
```

## Usage

1. Create templates, add scan templates to the templates directory.
2. Run the scanner by using ```python3 main.py```.
