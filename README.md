# vulnscanner

vulnscanner is a simple vulnerability scanning tool designed to help practice basic reconnaissance and security assessment workflows. It focuses on identifying common weaknesses in target hosts and presenting the results in a clear, easy-to-read format suitable for learning and small lab environments.

## Features

- Scans target hosts for open ports and common network services  
- Performs basic checks for known or misconfigured services  
- Collects and displays findings in a structured report  
- Designed for educational and lab use (not production-grade scanning)

## How It Works

1. The tool takes one or more target IPs or hostnames as input.  
2. It probes selected ports/services and gathers basic information.  
3. It flags potential issues based on simple checks and heuristics.  
4. It outputs the results so they can be reviewed, documented, or used for follow-up testing.

## Technologies Used

- Python (core scripting and logic)
- Networking libraries (sockets and related modules)
- Standard Python modules for parsing and output

## Use Cases

- Learning how vulnerability scanners work at a basic level  
- Practicing reconnaissance and enumeration in a lab environment  
- Building a foundation for more advanced penetration testing tools

## Important Notice

This tool is intended **for educational purposes only**.  
Only scan systems and networks you own or have explicit, written permission to test.
