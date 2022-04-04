# Disks and Mounting List
- df -h
- fdisk -l
- lsblk -f
- [Mounting A Disk](https://unix.stackexchange.com/questions/92803/there-are-4-ssds-but-df-only-listed-one-why)
- [Add To /etc/fstab For Mount On Boot](https://askubuntu.com/questions/303497/adding-an-entry-to-fstab)
- sudo du -a /home | sort -n -r | head - n 10
`Get the 10 largest directories in /home`

# Directory List
- ls
- ls -al
- cd </dir>
- cd ..
- cd ~
- mkdir

# Check Active Sessions
- w

# Networking
_Note: Ubuntu 18.04 and above use netplan to configure your network_
- [Set IP Address](https://vitux.com/how-to-configure-networking-with-netplan-on-ubuntu/)
- hostname
- hostname -I
- hostname -I | awk '{print $1}'
- ip a
- ip link

# File Manipulation
- sudo nano </dir>
- cp <filepath> <destpath>
- sudo unzip <filepath>

# Ubuntu Desktop
- [Install Ubuntu-Desktop](https://www.youtube.com/watch?v=98YuVDj6g8Q)
  
# User Management
- [Add/Modify Users](https://www.youtube.com/watch?v=19WOD84JFxA)
- [Change Dir Ownership](https://linuxize.com/post/linux-chown-command/#:~:text=The%20chown%20command%20allows%20you,the%20group%20members%2C%20and%20others.)
  
# Virtual Network Computing (VNC) with Putty
- [Install & Configure VNC for Ubunutu 20.04](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-vnc-on-ubuntu-20-04)
