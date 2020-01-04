# cPanel Disk Cleaner

cPanel Disk Cleaner is a simple bash script to clean some "trash" from cPanel servers, reducing the disk space usage. This script remove:

#### 1-Trash from YUM
#### 2-Archived and compressed log files
#### 3-Useless files in /home
# PLEASE READ THIS BEFORE RUN THE SCRIPT!

This script is NOT intended to ALL cPanel servers, or at least all the commands in it.

The brain must be used before run the script "just for fun".

This should be safe for standard cPanel instalations, in CentOS 5/6/7 and Cloudlinux. Also should be safe for ALL the cPanel versions.

#How Run the script
## (Recommended)

Open the cpanel-disk-cleaner file and use the commands one by one. Don't use ALL the commands without know what each one does.

OR

## (NOT RECOMMENDED AT ALL)

```bash
wget https://raw.githubusercontent.com/diyarit/Cpanel-Disk-Cleaner/master/cpanel-disk-cleaner
sh cpanel-disk-cleaner
```

This is intended to be a simple and quick script. IM NOT RESPONSIBLE FOR ANY DAMAGE, INCLUDING DATA LOST - except trash -, NUCLEAR WAR OR EXPLOSIONS!
