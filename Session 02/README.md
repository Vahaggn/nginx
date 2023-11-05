# Nginx Tutorial - Session 02: Basics of Installing Nginx
- Video of this Session: [Link](https://www.youtube.com/watch?v=I_Qul4thJMU&list=PL63NzugBawGe1nUhAveIBfYHtbiXvKKEb&index=2) 

Welcome to Session 02 of the Nginx Persian Tutorial, where we'll explore the basic installing of Nginx and learn how to install it on Ubuntu and CentOS.

- **Vahag Gragoosian**
  - DevOps Enthusiast
  - GitHub: [Vahag's GitHub](https://github.com/Vahaggn)
  - LinkedIn: [Vahag's LinkedIn](https://www.linkedin.com/in/vahag-gragosian/)
  - Youtube Channel: [Vahag's Youtube](https://www.youtube.com/@vahaggn) 

## Table of Contents

1. [Directories](#directories)
   - [/var/www/html](#/var/www/html)
   - [/etc/nginx](#/etc/nginx)
   - [/etc/nginx/nginx.conf](#/etc/nginx/nginx.conf)
   - [/etc/nginx/sites-available/](#/etc/nginx/sites-available/)
   - [/etc/nginx/sites-enabled/](#/etc/nginx/sites-enabled/)
   - [/etc/nginx/conf.d/](#/etc/nginx/conf.d/)
   - [/etc/nginx/stream.conf.d/](#/etc/nginx/stream.conf.d/)
   - [/etc/nginx/snippets/](#/etc/nginx/snippets/)
   - [/var/log/nginx/access.log and error.log](#/var/log/nginx/access.log-and-error.log)
   - [/etc/ssl/certs](#/etc/ssl/certs)
2. [Preparation Before Installing](#preparation-before-installing)
   - [Update and Upgrade](#update-and-upgrade)
   - [Time Zone and Time](#time-zone-and-time)
   - [Firewall](#firewall)
3. [Installing Nginx](#installing-nginx)
   - [On Ubuntu](#on-ubuntu)
   - [On CentOS](#on-centos)


## Directories

Nginx uses various directories and files for its configuration and operation.

- `/var/www/html`: The default web content directory.
- `/etc/nginx`: Nginx configuration files.
- `/etc/nginx/nginx.conf`: Main Nginx configuration file.
- `/etc/nginx/sites-available/` and `/etc/nginx/sites-enabled/`: Configuration for sites.
- `/etc/nginx/conf.d/` and `/etc/nginx/stream.conf.d/`: Additional configurations.
- `/etc/nginx/snippets/`: Reusable configuration snippets.
- `/var/log/nginx/access.log` and `/var/log/nginx/error.log`: Nginx log files.
- `/etc/ssl/certs`: SSL certificate storage.

## Preparation Before Installing

Before installing Nginx, it's essential to prepare your server environment.

- Update and upgrade your system.
- Set your server's time zone and time settings.
```bash
timedatectl set-timezone {{YOUR TIMEZONE}}
```
https://timezonedb.com/time-zones

- Adjust firewall rules for Nginx operation.

## Installing Nginx

### On Ubuntu
Update and Install Nginx
```bash
sudo apt update
sudo apt upgrade
sudo apt install nginx
```
### On CentOS
Update and Install Nginx
```bash
sudo yum update
sudo yum install nginx
```
