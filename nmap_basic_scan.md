# Nmap Basic Scan

## Objective

The goal of this task was to perform a basic Nmap scan against a target host in a controlled lab environment.

## Command Used

```bash
nmap <target-ip>
```

## What this command does

This scan checks the most common ports on the target and reports which ports are open.

## Example Finding

Example results may include:

- Port 22 open – SSH
- Port 80 open – HTTP
- Port 443 open – HTTPS

## Security Relevance

A basic port scan helps identify which services are exposed on a system.  
This is important because open ports may represent possible entry points that should be reviewed and secured.
