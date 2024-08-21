# Subdomain Finder

This Python script is designed to find and list active subdomains for a given domain. It prints a custom banner, loads subdomains from a text file, and checks each subdomain to see if it is active.

## Features

- Prints a visually appealing banner with a custom message.
- Loads subdomains from a text file.
- Checks each subdomain for activity by sending HTTP requests.
- Displays discovered subdomains in the terminal.

## Requirements

- Python 3.x
- `requests` library (install via `pip install requests`)

## Usage

1. **Clone the repository** (if applicable) or download the script.

2. **Create a `subdomains.txt` file** in the same directory as the script. This file should contain one subdomain per line.

   Example `subdomains.txt`:
