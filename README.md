# What is project init?

**Init is an opportunity to discover system and network basic commands, many of the services used on a server machine, as well as a few ideas of scripts that can be useful for SysAdmins on a daily  basis.**

## Network

- Identify network interfaces, network devices...
- Identify different IP address: DNS, broadcast, addresses on same subnet, external IP of website, etc...

## System

System and scripts parts are done on a Debian virtual machine.
- Few useful commands: determine state of the SSH service, how to reboot it, find its PID, find RSA keys, etc...
- How to connect via SSH, how to kill background command's process, etc...
- List all services at boot time, list the partition tables, list all users on the VM, add a new user, list all packages...

## Scripts

- Script 01: displays only the login, UID and Path of each entry of the /etc/passwd file.
- Script 02: delete an active user.
- Script 03: personal script: ask the user what to install on a new machine. The user select one or several of the choices. The install will be done if the software is not installed yet, or it will update it if it's already installed.

## Example
script 03:  
![Screen Shot 2019-05-03 at 12 56 50 PM](https://user-images.githubusercontent.com/45974214/57133396-f2f85000-6da2-11e9-9d0b-a6594d57bfc3.png)
