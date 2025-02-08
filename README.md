# Domain Resolver Script

This Python script resolves domain names from a specified file using the `dig` command-line tool. It reads domain names from a file and fetches their IP addresses, printing the results or any errors encountered.

## Features

- Resolves multiple domain names from a file.
- Uses the `dig` command-line tool to fetch domain information.
- Handles errors for missing files, invalid domains, and other issues.
- Provides a command-line interface to specify the domain file.

## Requirements

- Python 3.x
- The `dig` command-line tool (commonly available on Linux and macOS).

### Installing `dig`

- **Ubuntu/Debian**:
  ```bash
  sudo apt-get install dnsutils
  ```
  ```bash
  python3 resolve_domains.py -p domains.txt
  example.com --> 93.184.216.34
  google.com --> 142.250.185.78
  github.com --> 140.82.121.4
  ```
