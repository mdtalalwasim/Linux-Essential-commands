# Linux-Essential-commands
Linux Essential Command are listed here. Linux commands are added here which i used day to day of my life.


#### To check the timezone on a Linux server:
```bash  
timedatectl
```
#### To Set the timezone on a Linux server:
```bash  
sudo timedatectl set-timezone Asia/Dhaka
```


#### Tomcat Command through linux terminal:
```bash  
For checking status:
sudo systemctl status tomcat

Restart Tomcat:
sudo systemctl restart tomcat

Stop Tomcat:
sudo systemctl stop tomcat   

Restart Tomcat:
sudo service tomcat restart

Stop Tomcat Manually: 
sudo /path/to/tomcat/bin/shutdown.sh

Start Tomcat Manually: 
sudo /path/to/tomcat/bin/startup.sh

```
#### Remote Server Login through Linux Terminal:

```bash
ssh root@70#.9#2.2#.55 -p 22 [Note: this is demo ip, then ask for password. Enter password and login]
```


<h4> Remove directory:</h4>

```bash

rm -r directory_name
```
#### Remove file from directory:

```bash

rm file_name
```


#### Copy file from local directory to remote directory:
Go to the source file directory

```bash

scp -P port source_file_name user@hostname:destination_file_path
```

#### Copy file from local directory to remote directory:

```bash

scp source_file_name user@hostname:destination_file_path

```




#### See heap size

```bash

java -XX:+PrintFlagsFinal -version | grep HeapSize

```

#### Linux Server Login command

```bash

ssh username@hostname -p Port_Number

```
then Enter your password.

#### MySql Login Command

```bash

mysql -u user_name -p

```
then Enter your password.


#### Show Current Directory (pwd = present working directory)

```bash

pwd

```



#### move File from one directory to another directory

```bash

mv file_name_with_extension dir_path

```
Note: open your terminal inside your source file directory


#### Linux verstion:

```bash

lsb_release -a

```

###############################* XAMPP on Linux *#########################################
# XAPMPP:
#### 1. Command to Start XAMPP GUI:
```bash   
   sudo /opt/lampp/./manager-linux-x64.run
```
#### 2. Xampp directory:
```bash
cd /opt/lampp
```

#### 3. MySql Login Command
```bash
mysql -u user_name -p
```

#### 4. Check MySql status
```bash
sudo service mysql status
```
#### 5. Start MySql
```bash
sudo service mysql start
```
#### 6. MySql Login Command
```bash
sudo service mysql stop
```
#### 7. check status of MySql
```bash
sudo systemctl status mysql
sudo systemctl restart mysql
sudo systemctl stop mysql
```





