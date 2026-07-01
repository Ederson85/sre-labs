# Lab 01 - Server Health Check

## Objective

Practice a basic Linux server health check using commands commonly used by SREs during incident investigation.

---

## Scenario

A production server is reported as slow.

Your goal is to collect basic system information before taking any corrective action.

---

## Commands

### System identity
```bash
hostname
whoami
pwd
uptime
df -HT
free -m
top
ps aux --sort=-%cpu | head
ps aux --sort=-%mem | head
ip addr
ip route


## Questions
Is the server overloaded?
Is memory usage high?
Is disk usage critical?
Are there processes consuming too much CPU?
Is the network interface available?