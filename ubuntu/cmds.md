## UBUNTU COMMANDS

    $ cat /etc/*release* 
            - To check the Ubuntu Version
  
    $ sudo ufw disable 
            - To disable the Firewalls
  
    $ sudo ufw enable 
            - To enable the firewall
  
    $ sudo apt install network-manager-openvpn-gnome -y
  
    $ sudo apt update && sudo apt full-upgrade -y 

    $ sudo cat /var/log/auth.log
            - To check the logs of the day
    
    $ du -sh <file_name> 
            - Check the space utilization of the <file_name>
    $ df -h
          - Check the % disk space usage

    $ free -h
          - Check the primary memory utilization
          
    $ journalctl
          - To check the complete log of the services

    $ journalctl -u <image>
          - To check all the logs of <image>

    $ journalctl -b
            - To check all the logs

    $ netstat -tuln
          - To check Active Internet connections (only servers)

    $ lsof -i :<PORT>
        - lisof Open Files
        - To check the <PORT> is used by which process

    $ sudo head -n <NO_of_line> /var/log/auth.log
        - - To check the first <NO_of_line> of logs

    $ sudo tail -n <NO_of_line> /var/log/auth.log
        - To check the last <NO_of_line> of logs
        
    
    
```
$ gedit <program_name>.c To open the gedit text editor,
$ cc <program_name>.c - To compile C-program <program_name> with .c extension
$ ./a.out - To execute the program

Few shortcuts

    $ history
        - Gives all the commands executed over the bash/terminal

    Ctrl + R
        - To reverse search the particular cmd

    $ export PS1="<any_name> $:"
            - To reflect "<any_name> $:"  in the cli/bash

    $ export PS1="$PWD :"
            - To check the Present Working Directory

```



```
$ sudo usermod -aG docker ubuntu //To give the access to docker my ubuntu (EC2 instance)


```





# For Application

    ~/Applications/Cursor-1.0.0-x86_64.AppImage
    
```
If issues occur (e.g., not opening), check logs:

    $ ~/Applications/Cursor-1.0.0-x86_64.AppImage --no-sandbox

```


