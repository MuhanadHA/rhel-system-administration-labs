
# RHEL System Administration Labs

A personal hands-on lab portfolio documenting my practical experience with Red Hat Enterprise Linux (RHEL) 10.

## About This Project

This repository contains Linux system administration exercises, configurations, and troubleshooting scenarios completed as part of my ongoing RHCSA preparation.

My goal is to strengthen my Linux administration skills through practical experience and document what I learn along the way.

## Lab Environment

- Operating System: Red Hat Enterprise Linux 10
- Virtualization: VMware
- Environment: Local virtual machines

## Topics Covered

- User and group administration
- File permissions and ACLs
- SELinux configuration and troubleshooting
- Storage management (LVM, Stratis, VDO)
- Networking, NFS, and autofs
- systemd and service management
- Podman containers
- Bash scripting and automation


## Completed Labs

### SELinux & Web Server Administration

1. [Apache Custom DocumentRoot and Port Configuration](selinux/apache-custom-documentroot/README.md)
   - Configured Apache with a custom document root (`/webdata`) and TCP port `8090`.
   - Applied persistent SELinux file contexts and permitted the custom HTTP port.
   - Configured firewall access and investigated an Apache startup error.
   - Verified service availability and configuration persistence after reboot.
  

## Repository Status

Work in progress. Labs and documentation will be added progressively.
  
