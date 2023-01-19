
Automate to create the directories

- ``` #!/bin/bash ```
- ``` prefix= $1 ```
- ``` start= $2 ```
- ``` end=$3 ```
- ``` if ((i=$start; i<end; i++)) ```
- ``` do ```
- ```mkdir "prefix$i" ```
- ``` done ```


Backup the Data
- ```#!/bin/bash```
- ```tar -zcvf work_$(date +%Y-%m-%d).tar.gz ~/work```

Cron 
Cron is a Linux utility that is used to schedule and automate tasks, and crontab is the command used to interact with the Cron daemon and schedule tasks.

User Managemnet
User management is the process of creating, modifying, and deleting user accounts on a computer system or network. It involves managing the user's access rights, permissions, and privileges


adding two users in a simple way

- ```sudo useradd -m -d /home/user1 user1```
- ```sudo useradd -m -d /home/user2 user2```

- ```echo "User1: $(id -un user1)" ```
- ```echo "User2: $(id -un user2)" ```
