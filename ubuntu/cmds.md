## UBUNTU COMMANDS

# System Information Commands
- Diaplay all system info: $```uname -a ```
- Shows current hostname & details: $```hostnamectl```
- Lists CPU architecture info: $```Iscpu```
- Show system time: $```timedatectl status```

# System Monitoring & Management
- Display real-time system processes: $```top```
- An interacive process viewer: $```htop```
- Shows disk usage in human-readable formate: $```df -h```
- Displays free and used memory in MB: $```free -m```
- Terminates a process: $```kill <Process_ID>``` 

# Directory navigation
- Displays the current directory path: $```pwd```
- Changes the current directory: $```cd <directory>```
- Creates a new directory: $```mkdir <dir_name>```

<https://in.pinterest.com/pin/9570217952553735/>


- To check the Ubuntu Version: $```cat /etc/*release* ```
- To check Ubuntu(System Architecture):  ``` $ dpkg --print-architecture ```
- To disable the Firewalls: ``` $ sudo ufw disable  ```
- To enable the firewall: ``` $ sudo ufw enable ```
- ```$ sudo apt install network-manager-openvpn-gnome -y```
- ```$ sudo apt update && sudo apt full-upgrade -y ```
- To check the logs of the day:``` $ sudo cat /var/log/auth.log ```
- Check the space utilization of the <file_name> : ``` $ du -sh <file_name> ```
- Check the % disk space usage:```$ df -h ```
- Check the primary memory utilization:```$ free -h```
- To check the complete log of the services:```$ journalctl```
- To check all the logs of <image>: ```$ journalctl -u <image>```
- To check all the logs: ```$ journalctl -b```
- To check Active Internet connections (only servers): ```$ netstat -tuln```
- lisof Open Files: ```$ lsof -i :<PORT>```
- To check the <PORT> is used by which process
- To check the first <NO_of_line> of logs: ```$ sudo head -n <NO_of_line> /var/log/auth.log```
- To check the last <NO_of_line> of logs: ```$ sudo tail -n <NO_of_line> /var/log/auth.log```        
- To open the gedit text editor $ ```gedit <program_name>.c```
- To compile C-program <program_name> with .c extension $ ```cc <program_name>.c```
- To execute the program $ ```./a.out```

# SSH

- ```ssh user@host``` - connect to host as user
- ```ssh -p post user@host``` - connect using post p
- ```ssh -D post user@host``` - connect and use bind port

# Installation

- ```./configure```
- ```make```
- ```make install```

# Network

- ```ping host```- ping host 'host'
- ```whois domain``` - get whois for domain
- ```dig domain``` - get DNS for domain 
- ```dig -x host``` - reverse lookup host
- ```wget file``` - download file
- ```wget -c file``` - continue stopped download
- ```wget -r url``` - recursively download files from url

# System Info 
- Shows current date/time - ```date```
- Show this month's calender - ```cal```
- Show uptime - ```uptime```
- Display who is online - ```w```
- Who are you logged in as - ```whoami```
- Show kernel config - ```uname -a```
- cpu info - ```cat /proc/cpuinfo```
- Memory info - ```cat /proc/meminfo```
- Show manual for command - ```man command```
- Show disk usage - ```df```
- Show directory space usage - ```du```
- Human readable size in GB - ```du -sh```
- Show memory and swap usage - ```free```
- Show possible locations of app - ```whereis app```
- Show which app will be run by default - ```which app```

# Searching

- ```grep pattern files``` - search for pattern in files 
- ```grep -r pattern dir``` - search recursively for pattern in dir 
- ```command | grep pattern``` - search for pattern in the output of command 
- ```locate file``` - find all instances of file

# Process Management

- ```ps```- display currently active processes
- ```ps aux```- ps with a lot of detail
- ```kill pid``` - kill process with pid 'pid'
- ```killall proc``` - kill process named proc
- ```bg``` - lists stopped/background jobs, resume stopped job, resume stopped job in the background 
- ```fg``` - bring most recent job to foreground
- ```fg n``` - brings job n to foreground

# File Permission

- ```chmod octal file``` - Change permission of file
  ```
  4 - read (r)
  2 - write (w)
  1 - execute (x)
  ```
  ```order: owner/group/world```
  
- ```eg:``` - 
- ```chmod 777``` - rwx for everyone
- ```chmod 755``` - rw for owner, rx for group/world

# Compression

- ```tar cf file.tar``` - tar files into file.tar
- ```tar xf file.tar``` - untar into current directory
- ```tar tf file.tar``` - show contents of archive

tar flags:

            c - create archive      j - compression
            t - table of content    k - do not overwrite
            x - extract             T - files from file
            f - specifies filename  W - ask for confirmation
            z - use zip/gzip        v - verbose


- ```gzip file``` - compress file and rename to file.gz
- ```gzip -d file.gz``` - decompress file.gz

# Few shortcuts
- Gives all the commands executed over the bash/terminal: ```$ history```
- To reverse search the particular cmd: ```Ctrl + R ```
- To reflect "<any_name> $:"  in the cli/bash: ```$ export PS1="<any_name> $:"```          
- To check the Present Working Directory: $```export PS1="$PWD :"```          
- To give the access to docker my ubuntu (EC2 instance): ```$ sudo usermod -aG docker ubuntu```
  
# For Application
- Cursor AI: ```~/Applications/Cursor-1.0.0-x86_64.AppImage```
- If issues occur (e.g., not opening), check logs: ```$ ~/Applications/Cursor-1.0.0-x86_64.AppImage --no-sandbox```


