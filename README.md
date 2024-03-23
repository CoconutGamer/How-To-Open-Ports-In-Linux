# How-To-Open-Ports-In-Linux

## Introduction
UFW (uncomplicated firewall) is a firewall configuration tool that runs on top of iptables, included by default within Ubuntu distributions. It provides a streamlined interface for configuring common firewall use cases via the command line.

# Verify UFW Status

```
sudo ufw status
```

# Enable UFW
If you got a Status: inactive message when running ufw status, it means the firewall is not yet enabled on the system. You’ll need to run a command to enable it.

```
sudo ufw enable
```
# Opening Ports
This command below is to allow the port 3306 which allows the port for MYSQL, You can open more ports like ``sudo ufw allow 22``

```
sudo ufw allow 3306
```