# EWB Phishing URL Awareness Checker

**Author:** Rusana Parbin  
**Course:** AI-Powered Cybersecurity Internship, EWB Courses

## Overview

Phishing uses fake links or messages to trick people into sharing personal information. This Python program checks URL text for selected warning signs and asks the user to review links carefully.

## Features

* Detects an `@` symbol.
* Flags URLs longer than 100 characters.
* Detects IP-address hostnames.
* Flags hostnames with five or more segments.
* Detects punycode-style hostnames (`xn--`).
* Flags the HTTP scheme.
* Handles empty and malformed input.
* Allows repeated checks until the user exits.

## Requirements

Python 3.10 or later. No extra packages are required.

## Run

```bash
python phishing\_checker.py
```

## Run tests

```bash
python -m unittest discover -s tests -v
```

## Improvements

1. Input validation for empty or malformed URL text.
2. Repeat-check loop so multiple URLs can be checked in one run.

## Limitations

This is an educational tool. It only reads URL text. It does not visit URLs, scan for malware, use reputation services, or prove that a URL is safe. No warning signs found does NOT mean a URL is safe.

## Ethical Use

Use only sample strings for learning. Do not collect credentials or test websites without permission.

## Author

Rusana Parbin

