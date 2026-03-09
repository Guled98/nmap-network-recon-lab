# Nmap Service and Version Detection

## Objective

The goal of this task was to identify services and versions running on open ports.

## Command Used

```bash
nmap -sV <target-ip>
```

## What this command does

This scan attempts to determine which services are running on open ports and which versions are being used.

## Example Finding

Example results may include:

- OpenSSH 8.2
- Apache httpd 2.4.41
- Microsoft IIS 10.0

## Security Relevance

Service version detection is important because outdated or vulnerable software versions may be exploitable.  
This information helps defenders prioritize patching and helps testers understand the attack surface.
