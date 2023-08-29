# NetInfoSeeker

## Overview

NetInfoSeeker is a Python script designed to provide network-related information about your system. It gathers both private and public network information, including IP addresses (IPv4 and IPv6), public IP addresses, and MAC (Media Access Control) addresses. This information can be useful for troubleshooting network issues and understanding your system's network configuration.

## Features

- **Private IPv4 Addresses**: Retrieve and display the private IPv4 addresses associated with your system.

- **Private IPv6 Addresses**: Retrieve and display the private IPv6 addresses associated with your system.

- **Public IPv4 Address**: Attempt to retrieve and display the public IPv4 address of your system using an external API. If unavailable, it falls back to using `curl` to obtain the public IPv4 address.

- **Public IPv6 Address**: Attempt to retrieve and display the public IPv6 address of your system using an external API.

- **MAC Address**: Obtain and display the MAC (Media Access Control) address of your system's network interface.

## Prerequisites

- Python 3.x
- Requests library (for retrieving public IP addresses)
- `curl` (for alternative public IPv4 address retrieval)

## Usage

1. Run the script by executing `python NetInfoSeeker.py` in your terminal.

2. The script will display information about your network configuration, including private and public IP addresses (IPv4 and IPv6) and your MAC address.

3. Note that public IP address retrieval may depend on external services, so availability may vary.

## Disclaimer

This script is meant for informational purposes and may rely on external services to retrieve public IP addresses. The accuracy and availability of public IP address information depend on these external services.


