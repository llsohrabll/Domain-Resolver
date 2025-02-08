# Domain Resolver Script

This Python script allows you to resolve domain names from a file and print the IP addresses of the domains using the `dig` command.

## Features

- Reads a list of domain names from a specified file.
- Resolves each domain name to an IP address using the `dig` command-line tool.
- Handles errors for missing files, invalid domains, and other exceptions.
- Outputs the resolved IP address or an error message for each domain.

## Requirements

- Python 3.x
- The `dig` command-line tool (commonly available on Linux and macOS).
  
### Installing `dig`

- **Ubuntu/Debian**:
  ```bash
  sudo apt-get install dnsutils
