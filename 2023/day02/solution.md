

Linux Important Commands

 Commands

ls 
       -->listing 
ls -a
       -->listing all files including hidden
mkdir dir
       --> create directory
touch file
       --> create file 
cd  dir
       --> change directory 
cd 
       --> to home directory
cd -  
       --> to previous visiting directory
cd ../   
       --> previous directory
rm file 
       --> remove file
rm -r dir
       --> remove directory
rm -rf dir 
       --> forefully remove the directory
rm file1 file2
       --> rename the filename
mv <source>  <destination>
       --> move file from source to destination
cat file
       -->read the file
head -n file 
       --> output n numbers of first lines
tail -n file 
       --> output n numbers of last lines

Process Management Commands
ps
       --> all process
ps -a 
       --> show all process including hidden 
top 
       -->show all running processes
kill id
       --> to kill the process with process id

Permission Commands
chmod 777 file 
       --> give all permissions
       read - 4
       write - 2
       execute - 1
man <command>
       --> to check the manual of commands

Searching Commands

grep pattern files
       --> to search the pattern from file
grep -r pattern dir 
       --> search from directory recursively

System Commands

date
       --> to check date
cal
       --> to check the calender of this month
w
       -->which user is online
whoami
       -->show logged in user
uname
       --> which kernal is used
uname -a
       -->show the kernal information
df 
       --> for disk usage
du   
       --> directory space usage

Compression Commands

gzip file 
       --> compress the file with gzip name
gzip -d file.gzip
       -->decompress the file


Network Command

ping  host
       --> to ping with host
wget address
       --> to download

