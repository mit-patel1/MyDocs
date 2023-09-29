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
'''
sudo ufw status
'''
