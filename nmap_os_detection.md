# Nmap OS Detection

## Objective

The goal of this task was to use Nmap to estimate the operating system of a target host.

## Command Used

```bash
sudo nmap -O <target-ip>
```

## What this command does

This scan attempts to identify the target operating system based on network responses.

## Example Finding

Example results may include:

- Linux 5.x
- Windows Server 2019
- FreeBSD

## Security Relevance

Operating system detection helps build a clearer picture of the target environment.  
Knowing the likely operating system helps both defenders and penetration testers understand what types of services, configurations and vulnerabilities may be relevant.
