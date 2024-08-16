# DNS Configuration Script

## Description

This project contains a Bash script (`configure_dns.sh`) that configures DNS resolution on an Ubuntu server by modifying the `/etc/hosts` file. The script ensures that:

- `localhost` resolves to `127.0.0.2`
- `facebook.com` resolves to `8.8.8.8`

The script is designed to work in most environments, including within Docker containers.

## Requirements

- Ubuntu 20.04 LTS
- Bash (pre-installed on Ubuntu)
- The script must be run with sufficient privileges to modify the `/etc/hosts` file (`sudo` is used within the script).

## Usage

### 1. Download the Script

First, clone the repository or download the script directly.

```bash
git clone <repository_url>
cd <repository_directory>

