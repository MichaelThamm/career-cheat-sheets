# Ubuntu Desktop
- [Install Ubuntu-Desktop](https://www.youtube.com/watch?v=98YuVDj6g8Q)

# Kali
- [Install Kali](https://www.kali.org/get-kali/#kali-installer-images)

# Disks and Mounting List
- df -h `Display the filesystem's space utilization - internal accounting done as blocks are allocated and freed`
- du -h `command adds up the space used by the files that you specified`
- [lsblk](https://man7.org/linux/man-pages/man8/lsblk.8.html) `lists information about the specified block devices`
- [Mounting A Disk](https://unix.stackexchange.com/questions/92803/there-are-4-ssds-but-df-only-listed-one-why)
- [Add To /etc/fstab For Mount On Boot](https://askubuntu.com/questions/303497/adding-an-entry-to-fstab)
- sudo fdisk /dev/sda `modify the partition table for sda (all changes can be undone unless w command is used)`
- e2fsck -f /dev/sda1 `check the filesystem integrity`
- resize2fs /dev/sda1 `resize to file system`

# Directory Actions
- ls
- ls -al
- cd < /dir >
- cd ..
- cd ~
- mkdir
- sudo du -a /home | sort -n -r | head - n 10 `Get the 10 largest directories in /home`

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
- nano < /dir > `edit file`
- cp < filepath > <destpath> `copy file`
- zip < destpath > <filepath> `zip file`
- unzip < filepath > `unzip file`
  
# Piping
[Reference](https://www.guru99.com/linux-pipe-grep.html)
- < some command > | sort -n -r -f `Sort numerically, reverse order, and case insensitive`
- < some command > | grep < options below >
- `-v	Shows all the lines that do not match the searched string`
- `-c	Displays only the count of matching lines`
- `-n	Shows the matching line and its number`
- `-i	Match both (upper and lower) case`
- `-l	Shows just the name of the file with the string`
  
# User Management
- [Add/Modify Users](https://www.youtube.com/watch?v=19WOD84JFxA)
- [Change Dir Ownership](https://linuxize.com/post/linux-chown-command/#:~:text=The%20chown%20command%20allows%20you,the%20group%20members%2C%20and%20others.)
  
# Virtual Network Computing (VNC) with Putty
- [Install & Configure VNC for Ubunutu 20.04](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-vnc-on-ubuntu-20-04)
