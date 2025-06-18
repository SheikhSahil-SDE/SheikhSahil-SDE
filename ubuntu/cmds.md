## UBUNTU COMMANDS

To check the Ubuntu Version: $```cat /etc/*release* ```

To check Ubuntu(System Architecture):  ``` $ dpkg --print-architecture ```

To disable the Firewalls: ``` $ sudo ufw disable  ```

To enable the firewall: ``` $ sudo ufw enable ```

```
 $ sudo apt install network-manager-openvpn-gnome -y
```

``` 
$ sudo apt update && sudo apt full-upgrade -y
```

To check the logs of the day:``` $ sudo cat /var/log/auth.log ```

Check the space utilization of the <file_name> : ``` $ du -sh <file_name> ```

Check the % disk space usage:```$ df -h ```

Check the primary memory utilization:```$ free -h```

To check the complete log of the services:```$ journalctl```

To check all the logs of <image>: ```$ journalctl -u <image>```

To check all the logs: ```$ journalctl -b```

To check Active Internet connections (only servers): ```$ netstat -tuln```

lisof Open Files: ```$ lsof -i :<PORT>```
To check the <PORT> is used by which process

To check the first <NO_of_line> of logs: ```$ sudo head -n <NO_of_line> /var/log/auth.log```

To check the last <NO_of_line> of logs: ```$ sudo tail -n <NO_of_line> /var/log/auth.log```         

To open the gedit text editor $ ```gedit <program_name>.c```

To compile C-program <program_name> with .c extension $ ```cc <program_name>.c```

To execute the program $ ```./a.out```

# Few shortcuts

Gives all the commands executed over the bash/terminal: ```$ history```

To reverse search the particular cmd: ```Ctrl + R ```

To reflect "<any_name> $:"  in the cli/bash: ```$ export PS1="<any_name> $:"```
          
To check the Present Working Directory: $```export PS1="$PWD :"```
          
To give the access to docker my ubuntu (EC2 instance): ```$ sudo usermod -aG docker ubuntu```

# For Application

Cursor AI: ```~/Applications/Cursor-1.0.0-x86_64.AppImage```

    
If issues occur (e.g., not opening), check logs: ```$ ~/Applications/Cursor-1.0.0-x86_64.AppImage --no-sandbox```


