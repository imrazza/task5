# Process Management Report

## Overview
This project demonstrates basic Linux process management tasks, including listing processes, killing processes, understanding process states, managing services, enabling services at boot, and monitoring resource usage.

All steps are documented along with screenshots and observations.

## 1. Listing Running Processes
Commands:
```
ps aux
top
```
Screenshots are placed in `screenshots/` directory.

## 2. Killing Processes
Commands:
```
ps aux | grep jenkins
sudo kill 236
```
Screenshots are placed in `screenshots/` directory.

## 3. Understanding Process States
Common states include R, S, D, T, Z.

## 4. Managing Services Using systemctl
Commands:
```
sudo systemctl start ssh
sudo systemctl stop ssh
sudo systemctl restart ssh
systemctl status ssh
```



## 5. Monitoring Resource Usage
Commands:
```
top
free -h
df -h
ps aux --sort=-%cpu
ps aux --sort=-%mem
```



## Conclusion
This assignment helped me understand how Linux handles processes and services behind the scenes.
