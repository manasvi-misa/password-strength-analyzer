# Password Strength Analyzer with Custom Wordlist Generator

## Project Summary

This tool evaluates the strength of a given password and generates a custom wordlist based on user-provided inputs like name, birth year, and pet name. It is designed to support basic security awareness and password audit exercises for personal or educational use.

---

## Features

- Evaluates password strength using Dropbox’s `zxcvbn` library.
- Provides feedback on password guessability and estimated crack time.
- Generates a tailored wordlist using:
  - Personal inputs
  - Leetspeak variants
  - Common suffixes and patterns
- Outputs the wordlist to a `.txt` file, compatible with password audit tools.

---

## Technologies Used

- Python 3.x
- Libraries: `zxcvbn`, `argparse`, `nltk` (optional)

---

## File Structure
password-analyzer/
├── analyzer.py # Password strength evaluation
├── wordlist_generator.py # Custom wordlist creation
├── sample_wordlist.txt # Example output
├── report.pdf # Final project report (2 pages)
└── README.md # Project overview


---

## How to Run

**Analyze password strength:**
bash
python analyzer.py --password "ExamplePassword123"
python wordlist_generator.py --name John --dob 2002 --pet Rex

---

## Usage Scope
This project is intended for educational, ethical, and personal security purposes. Do not use it for unauthorized or malicious activities.
For detailed implementation steps and explanation, refer to the report.pdf file.


---
