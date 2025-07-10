# Docker Compose Repository

This repository contains my personal collection of Docker Compose files for various services and applications.

## ⚠️ Important Notice

**These Docker Compose files do not represent the final version.** They are working configurations that may be subject to changes, improvements, and updates as needed.

## Services Included

- **Emby Server** - Media server for streaming content
- **Nextcloud with MariaDB** - Self-hosted cloud storage solution
- **Nginx Proxy Manager** - Reverse proxy with SSL management
- **phpMyAdmin** - Web interface for MySQL/MariaDB administration
- **Pi-hole** - Network-wide ad blocker and DNS server
- **Wireguard + qBittorrent** - VPN-protected torrent client

## Usage

Each Docker Compose file is designed to be run independently. Make sure to:

1. Create appropriate `.env` files with required environment variables
2. Ensure external networks and volumes are created as needed
3. Review and customize configurations for your specific environment

## Security Notes

- Environment variables are used for sensitive data (passwords, usernames)
- Ensure `.env` files are not committed to version control
- Review port mappings and network configurations for your security requirements

## Disclaimer

These configurations are provided as-is and may require modifications for your specific use case. Always review and test configurations before deploying to production environments.
