```
Ctrl + C - kill a process
cd dir - change directory to dir
cd – change to home
pwd – show current directory
mkdir dir – create a directory dir
rm file – delete file
rm -r dir – delete directory dir
rm -f file – force remove file
rm -rf dir – force remove directory dir *
cp file1 file2 – copy file1 to file2
cp -r dir1 dir2 – copy dir1 to dir2; create dir2 if it doesn't exist
mv file1 file2 – rename or move file1 to file2 if file2 is an existing directory, moves file1 into directory file2
touch file – create or update file
cat > file – places standard input into file
more file – output the contents of file
head file – output the first 10 lines of file
tail file – output the last 10 lines of file
tail -f file – output the contents of file as it grows, starting with the last 10 lines
ls - The most frequently used command in Linux to list directories
pwd - Print working directory command in Linux
cd - Linux command to navigate through directories
mkdir - Command used to create directories in Linux
mv - Move or rename files in Linux
cp - Similar usage as mv but for copying files in Linux
rm - Delete files or directories
touch - Create blank/empty files
ln - Create symbolic links (shortcuts) to other files
cat - Display file contents on the terminal
clear - Clear the terminal display
echo - Print any text that follows the command
less - Linux command to display paged outputs in the terminal
man - Access manual pages for all Linux commands
uname - Linux command to get basic information about the OS
whoami - Get the active username
tar - Command to extract and compress files in Linux
grep - Search for a string within an output
head - Return the specified number of lines from the top
tail - Return the specified number of lines from the bottom
diff - Find the difference between two files
cmp - Allows you to check if two files are identical
comm - Combines the functionality of diff and cmp
sort - Linux command to sort the content of a file while outputting
export - Export environment variables in Linux
zip - Zip files in Linux
unzip - Unzip files in Linux
ssh - Secure Shell command in Linux
service - Linux command to start and stop services
ps - Display active processes
kill and killall - Kill active processes by process ID or name
df - Display disk filesystem information
mount - Mount file systems in Linux
chmod - Command to change file permissions
chown - Command for granting ownership of files or folders
ifconfig - Display network interfaces and IP addresses
traceroute - Trace all the network hops to reach the destination
wget - Direct download files from the internet
ufw - Firewall command
iptables - Base firewall for all other firewall utilities to interface with
apt, pacman, yum, rpm - Package managers depending on the distro
sudo - Command to escalate privileges in Linux
cal - View a command-line calendar
alias - Create custom shortcuts for your regularly used commands
dd - Majorly used for creating bootable USB sticks
whereis - Locate the binary, source, and manual pages for a command
whatis - Find what a command is used for
top - View active processes live with their system usage
useradd and usermod - Add new user or change existing users data
passwd - Create or update passwords for existing users
```
Go to Root user
```
sudo su
```
Update the package
```
sudo apt update
```
Install package
```
sudo apt install package_name
sudo apt install python3
```
Create directory
```
mkdir /projectdir
```
Install virtual environment
```
sudo pip3 install virtualenv
```
A virtual environment named env will be created. Let's activate this virtual environment
```
virtualenv env
source env/bin/activate
```
Installing Django and gunicorn
```
pip install django gunicorn
```
To open a port
```
sudo ufw allow 22
```
To see the firewall status
```
sudo ufw status
```
