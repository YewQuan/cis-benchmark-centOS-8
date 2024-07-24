# cis-benchmark-centOS-8
This repository contains automated scripts and guides to ensure compliance with the Center for Internet Security (CIS) benchmarks for hardening CentOS 8 servers at Level 1 - Server.

# CIS Level 1 Server Benchmarks Covered
1. Initial Setup
2. Services
3. Network Configuration
4. Logging and Auditing
5. Access, Authentication and Authorization
6. System Maintenance

Caveat 1: This script only covered the automated assessment status.

Caveat 2: There are some missing automated assessment status item which are:
* Ensure firewalld default zone is set
* Ensure nftables rules are permanent
* Ensure iptables rules are saved
* Ensure authselect includes with-faillock

# Prerequisites
Before running the scripts, ensure the following:

* You are running CentOS 8.
* You have root or sudo access to the server.
* A wired network connection is enabled.

# Usage
cd cis-benchmark-centOS-8

sudo ./script.sh

cat result.txt
