# Archon-Vane
A Project dedicated to show how file integrity is monitored for any miscellaneous tampering on files. 
A lightweight File Integrity Monitoring (FIM) application built in Python that detects unauthorized file modifications using SHA-256 hashing and stores integrity data in a JSON-based baseline database.

📌 Project Overview

This project monitors selected files or directories and detects:

File modifications

File creation

File deletion

It works by generating SHA-256 checksums for files and comparing them against a trusted baseline stored in a JSON file.

If a file’s checksum changes, the system reports a potential integrity violation.
