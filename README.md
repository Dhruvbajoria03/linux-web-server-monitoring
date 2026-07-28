# Linux Web Server Monitoring 

> A Linux system administration project demonstrating web server deployment, firewall configuration, log monitoring, network diagnostics, and server automation using Bash scripting.

---

# Project Overview

This project focuses on configuring and managing a Linux-based web server using **Nginx** while applying essential Linux system administration practices. The server was configured with firewall protection, monitored through system and web server logs, and enhanced with Bash scripts that automate routine administrative tasks.

The project covers the complete workflow of deploying a web server, securing network access, verifying server health, monitoring logs, and automating service management. It reflects practical skills commonly used by Linux System Administrators, DevOps Engineers, and Infrastructure Engineers.

---

# Objectives

- Install and configure an Nginx web server
- Create and host a custom website
- Configure firewall rules for secure access
- Monitor Nginx access and error logs
- Perform Linux networking diagnostics
- Automate server health monitoring
- Create Bash scripts for Nginx service management
- Schedule automated tasks using Cron

---

# Technologies Used

| Technology | Purpose |
|------------|---------|
| Ubuntu Linux | Operating System |
| Nginx | Web Server |
| Bash | Automation & Shell Scripting |
| Firewalld | Firewall Management |
| Cron | Task Scheduling |
| Curl | HTTP Testing |
| Wget | File Download Testing |
| Grep & Awk | Log Analysis |
| Systemctl | Service Management |

---

# Features

### Web Server Configuration

- Installed and configured Nginx
- Enabled automatic startup
- Hosted a custom HTML website
- Verified server availability using Curl

---

### Firewall Configuration

- Installed Firewalld
- Allowed HTTP (80)
- Allowed SSH (22)
- Tested custom firewall rules
- Verified active firewall configuration

---

### Log Monitoring

- Monitored access logs
- Monitored error logs
- Generated HTTP requests
- Filtered logs using Grep
- Analyzed traffic using Awk

---

### Network Diagnostics

Performed common Linux networking tasks including:

- Ping
- Nslookup
- Dig
- Wget
- Curl
- SS
- Netstat

---

### Server Health Automation

Created an automated Bash script that verifies:

- Nginx service status
- Firewall status
- HTTP response
- Open ports
- Disk utilization
- Memory usage

The script automatically attempts to restart services if they are unavailable and records all results in a log file.

---

### Nginx Service Manager

A second Bash script provides simple command-line management of the Nginx service.

Supported commands:

```bash
./manage_nginx.sh start
./manage_nginx.sh stop
./manage_nginx.sh restart
./manage_nginx.sh status
```


# Skills Demonstrated

- Linux System Administration
- Bash Scripting
- Nginx Administration
- Firewall Configuration
- Service Management
- Linux Networking
- Log Analysis
- Task Automation
- Server Monitoring
- Command Line Operations

---

# Learning Outcomes

Through this project I gained practical experience with:

- Deploying and managing Linux web servers
- Configuring firewall security
- Monitoring server activity through logs
- Diagnosing network connectivity
- Writing reusable Bash scripts
- Automating routine maintenance tasks
- Using Cron for scheduled jobs
- Managing Linux services using Systemctl

---

# Future Improvements

Potential enhancements for a production environment include:

- HTTPS using Let's Encrypt
- Fail2Ban integration
- Log rotation and centralized logging
- Email alerts for health checks
- Resource usage dashboards
- Backup automation
- Docker container deployment
- CI/CD integration
- Monitoring with Prometheus and Grafana

---

