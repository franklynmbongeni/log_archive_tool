# Log Archiving Tool

A simple Python CLI tool to archive and compress log files on Windows or Unix-based systems.  
This helps free up disk space, keep logs organized, and maintain historical records in a compressed format.

---

## Features

- Compresses log directories into `.tar.gz` archives
- Stores archives in a dedicated `archives` folder
- Logs the date and time of each archive in `archive.log`
- Can optionally delete original logs after archiving (with safety checks)
- Cross-platform: works on Windows, Linux, and macOS
- Easy to run from the command line

## What i should add soon
- Option to delete original logs after archiving (with safety checks)


---

## Requirements

- Python 3.6+
- Optional: 7-Zip or `tar` for manual extraction on Windows

---

## Installation

1. Clone the repository:

git clone https://github.com/franklynmbongeni/log_archive_tool.git
cd log_archive_tool
git clone https://github.com/franklynmbongeni/log_archive_tool.git
cd log_archive_tool
