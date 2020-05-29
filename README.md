<h1 align="center">
  <br>
  <a href="https://github.com/CrystalX127/Shield.git"><img src="https://image.freepik.com/free-vector/golden-shield-retro-design_12454-5380.jpg" alt="Logo" width="500"></a>
  <br>
  Shield:
  <br>
</h1>

<p align="center">
  <a href="https://github.com/Marten4n6/EvilOSX/blob/master/LICENSE.txt">
      <img src="https://img.shields.io/static/v1?label=<Liscence>message=<MIT>color=<informational>"alt="License">
  </a>
  <a href="https://github.com/Marten4n6/EvilOSX/blob/master/LICENSE.txt">
      <img src="https://img.shields.io/badge/python-2.7,%203.7-blue.svg?style=flat-square" alt="Python">
  </a>
  <a href="https://github.com/Marten4n6/EvilOSX/issues">
    <img src="https://img.shields.io/github/issues/Marten4n6/EvilOSX.svg?style=flat-square" alt="Issues">
  </a>
  <a href="https://travis-ci.org/Marten4n6/EvilOSX">
      <img src="https://img.shields.io/travis/Marten4n6/EvilOSX/master.svg?style=flat-square" alt="Build Status">
  </a>
  <a href="https://github.com/Marten4n6/EvilOSX/blob/master/CONTRIBUTING.md">
      <img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat-square" alt="Contributing">
  </a>
</p>


Shield is a zero configuration, single file shell script made to be run to harden and secure a newly installed Debian or Debian based OS.

- Zero installation 
- Zero configuration
- Single file shell script

## Usage:
Clone the script and follow these instruction below, and then run it as root and select which sections to run when prompted.
```
   1. git clone https://github.com/CrystalX127/Shield.git
   2. chmod +x ./Shield.sh
   3. ./Shield.sh
```
## Warning:
This shell script reverts the ssh port to `652`, and it restricts the ssh key to the admin user.
## Supported OS types:
- Debian 10
- Debian 8
- Debian based OS's

## What does this shell script do?
- Adds a legal banner to /etc/issue and /etc/issue.net
- Adds an automatic updater
- Adds daily cronjob to update system packages on the server
- Configures the iptables
- Configures the kernel
- Disables core dumps
- Disables firewire and usb storage
- Disables uncommon filesystems
- Disables uncommon network protocols
- Enables process accounting
- Installs and configures auditd with reasonable rules
- Installs and sets up aide
- Installs fail2ban
- Installs packages recommended by lynis
- Moves tmp to tmpfs
- Purges old and removed packages
- Remounts /tmp, /proc, /dev, /run to be more restrictive
- Restrict access to compilers
- Restricts access to /root 
- Restricts firewall to only allow ssh on port `652`
- Restricts logins
- Restricts ssh, and enables ssh only for the admin user
- Updates system packages

## Contributing:
Please open issues and pull requests on anything you come across.
