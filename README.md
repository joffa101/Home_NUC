# Home_NUC
Creating my Home NUC

## March 2023

I currently have Ubuntu desktop 22.x running plex as a package and HA as a container.

Problem: I ran HA as a 'core' container and it does not do 'add-ins'

Solution: Install Proxmox virtualization on the NUC bare metal and have 2 VM's - 1 Ubuntu and one HA-OS.

Steps:

Use CloneZilla https://clonezilla.org/ to do a P2V.
https://pve.proxmox.com/wiki/Migration_of_servers_to_Proxmox_VE#Physical_server_to_Proxmox_VE_.28KVM.29_using_Clonezilla_Live_CDs
