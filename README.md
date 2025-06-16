# linux-cheatsheet
A beginner-friendly list of essential Linux commands for cybersecurity learners.

📁 File & Directory Commands
Command	Description
ls	Show list of files/directories
ls -la	Show hidden files with permissions
cd dir	Change directory to dir
pwd	Show current directory path
mkdir folder	Create new folder
touch file.txt	Create new empty file
rm file.txt	Delete file
rm -r folder/	Delete folder recursively
cp file1 file2	Copy file
mv file1 newname	Rename or move file

🔐 File Permissions & Ownership
Command	Description
chmod 755 file	Change file permission
chown user:group file	Change ownership
ls -l	Show file permissions

🧠 System Information
Command	Description
uname -a	Show kernel version
df -h	Show disk usage
free -m	Show RAM usage
uptime	Show system uptime
whoami	Show current user
hostname	Show system hostname

🌐 Networking Commands
Command	Description
ping domain.com	Test network connection
ifconfig or ip a	Show IP addresses
netstat -tuln	Show open ports
ss -tuln	Faster version of netstat
curl http://example.com	Download webpage
wget URL	Download file from URL
nslookup domain.com	DNS info
traceroute domain.com	Show network route

📦 Package Management (Debian/Ubuntu)
Command	Description
sudo apt update	Update package index
sudo apt upgrade	Upgrade all packages
sudo apt install package	Install package
sudo apt remove package	Remove package
dpkg -l	List installed packages

🔄 Process Management
Command	Description
ps aux	Show running processes
top	Live system process viewer
htop	Better version of top (if installed)
kill PID	Terminate process by PID
killall processname	Terminate process by name

🗃️ File Compression / Archive
Command	Description
tar -cvf archive.tar dir/	Create tar archive
tar -xvf archive.tar	Extract tar archive
zip file.zip file1 file2	Create zip file
unzip file.zip	Extract zip file

🔎 Search & Filter
Command	Description
grep "text" file	Search text in file
find / -name filename	Find file by name
locate filename	Fast search (needs updatedb)
head file	Show first 10 lines
tail file	Show last 10 lines
tail -f logfile	Live follow a log file

💬 User Management
Command	Description
adduser username	Add new user
passwd username	Change user password
usermod -aG group user	Add user to group
deluser username	Delete user

🧪 Other Useful
Command	Description
alias ll='ls -la'	Create alias
history	Show command history
clear	Clear terminal screen
reboot	Reboot system
shutdown now	Shutdown immediately

✅ Pro Tips
🔒 Use sudo carefully

📝 Use man command to read the manual for any command

📁 Combine commands using |, &&, ; for efficiency
