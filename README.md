# Simplified Linux-Commands with examples.

![image](https://github.com/GitGuru4DevOps-Venkatesh/Simplified-Linux-Commands-with-examples/assets/128009454/ab919f84-9d68-4a74-b208-0e4473bce19d)

Simplified examples for each of the Linux commands below..!

Provided the single file containing both the Linux commands and their corresponding inputs and outputs:

Explanations and sample outputs for the provided Linux commands:

### 1. `ls` - List directory contents
   - **Input:** `ls`
   - **Output:**
     ```
     file1.txt  file2.txt  directory/
     ```

### 2. `cd` - Change directory
   - **Input:** `cd /path/to/directory`
   - **Output:**
     ```
     /path/to/directory
     ```

### 3. `pwd` - Print working directory
   - **Input:** `pwd`
   - **Output:**
     ```
     /path/to/directory
     ```

### 4. `mkdir` - Create a directory
   - **Input:** `mkdir new_directory`
   - **Output:**
     ```
     (No output, creates a new directory)
     ```

### 5. `touch` - Create a file
   - **Input:** `touch new_file.txt`
   - **Output:**
     ```
     (No output, creates a new empty file)
     ```

### 6. `cp` - Copy files and directories
   - **Input:** `cp file.txt /path/to/destination`
   - **Output:**
     ```
     (No output, copies files/directories)
     ```

### 7. `mv` - Move or rename files and directories
   - **Input:**
     ```
     mv file.txt new_location/  # Move
     mv old_file.txt new_file.txt  # Rename
     ```
   - **Output:**
     ```
     (No output, moves/renames files/directories)
     ```

### 8. `rm` - Remove files and directories
   - **Input:**
     ```
     rm file.txt  # Remove a file
     rm -r directory/  # Remove a directory
     ```
   - **Output:**
     ```
     (No output, removes files/directories)
     ```

### 9. `find` - Search for files and directories
   - **Input:** `find /path/to/search -name "filename"`
   - **Output:**
     ```
     /path/to/search/filename
     ```

### 10. `grep` - Search for patterns in files
   - **Input:** `grep "pattern" file.txt`
   - **Output:**
     ```
     Line with pattern
     ```

### 11. `cat` - Concatenate and display files
   - **Input:** `cat file.txt`
   - **Output:**
     ```
     Content of file.txt
     ```

### 12. `less` - View file contents page by page
   - **Input:** `less file.txt`
   - **Output:**
     ```
     Content of file.txt (paged)
     ```

### 13. `head` - Display the first lines of a file
   - **Input:** `head file.txt`
   - **Output:**
     ```
     First few lines of file.txt
     ```

### 14. `tail` - Display the last lines of a file
   - **Input:** `tail file.txt`
   - **Output:**
     ```
     Last few lines of file.txt
     ```

### 15. `vi/vim` - Text editor
   - **Input:** `vim file.txt`
   - **Output:**
     ```
     (No specific output; opens the file in the vim editor)
     ```

### 16. `nano` - Text editor
   - **Input:** `nano file.txt`
   - **Output:**
     ```
     (No specific output; opens the file in the nano editor)
     ```

### 17. `tar` - Archive and compress files
   - **Input:** `tar -cvf archive.tar file1.txt file2.txt`
   - **Output:**
     ```
     (No specific output; creates an archive file)
     ```

### 18. `gzip` - Compress files
   - **Input:** `gzip file.txt`
   - **Output:**
     ```
     (No specific output; compresses the file)
     ```

### 19. `gunzip` - Decompress files
   - **Input:** `gunzip file.txt.gz`
   - **Output:**
     ```
     (No specific output; decompresses the file)
     ```

### 20. `wget` - Download files from the web
   - **Input:** `wget https://example.com/file.txt`
   - **Output:**
     ```
     (No specific output; downloads the file)
     ```

### 21. `curl` - Transfer data to or from a server
   - **Input:** `curl -O https://example.com/file.txt`
   - **Output:**
     ```
     (No specific output; transfers data to/from a server)
     ```

### 22. `ssh` - Secure shell remote login
   - **Input:** `ssh username@remote_host`
   - **Output:**
     ```
     (Connects to the remote server, no specific output here)
     ```

### 23. `scp` - Securely copy files between hosts
   - **Input:** `scp file.txt username@remote_host:/path/to/destination`
   - **Output:**
     ```
     (Copies files to a remote host, no specific output here)
     ```

### 24. `chmod` - Change file permissions
   - **Input:** `chmod 755 file.txt`
   - **Output:**
     ```
     (No specific output; changes file permissions)
     ```

### 25. `chown` - Change file ownership
   - **Input:** `chown new_owner:new_group file.txt`
   - **Output:**
     ```
     (No specific output; changes file ownership)
     ```

### 26. `chgrp` - Change group ownership
   - **Input:** `chgrp new_group file.txt`
   - **Output:**
     ```
     (No specific output; changes group ownership)
     ```

### 27. `ps` - Display running processes
   - **Input:** `ps`
   - **Output:**
     ```
     PID  CMD
     123  process_name
     ```

### 28. `top` - Monitor system resources and processes
   - **Input:** `top`
   - **Output:**
     ```
     System summary and process list
     ```

### 29. `kill` - Terminate processes
   - **Input:** `kill -9 PID`
   - **Output:**
     ```
     (No specific output; terminates a process)
     ```

### 30. `df` - Display disk space usage
   - **Input:** `df -h`
   - **Output:**
     ```
     Filesystem     Size  Used  Avail  Use%
     /dev/sda1      100G   20G   80G   20%
     ```

### 31. `du` - Estimate file and directory space usage
   - **Input:** `du -sh file.txt`
   - **Output:**
     ```
     Size of file.txt
     ```

### 32. `free` - Display memory usage
   - **Input:** `free -m`
   - **Output:**
     ```
     Total  Used  Free  Shared  Buffers  Cache
     1024   512   512   128     64       256
     ```

### 33. `uname` - Print system information
   - **Input:** `uname -a`
   - **Output:**
     ```
     Linux hostname 4.15.0-101-generic #102-Ubuntu SMP Mon May 11 10:07:26 UTC 2020 x86_64 x86_64 x86_64 GNU/Linux
     ```

### 34. `ifconfig` - Configure network interfaces
   - **Input:** `ifconfig`
   - **Output:**
     ```
     eth0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1500
     inet 192.168.1.100  netmask 255.255.255.0  broadcast 192.168.1.255
     ```

### 35. `ping` - Test network connectivity
   - **Input:** `ping google.com`
   - **Output:**
     ```
     PING google.com (8.8.8.8) 56(84) bytes of data.
     64 bytes from 8.8.8.8: icmp_seq=1 ttl=52 time=10.4 ms
     ```

### 36. `netstat` - Network statistics
   - **Input:** `netstat -a`
   - **Output:**
     ```
     Active Internet connections (servers and established)
     Proto Recv-Q Send-Q Local Address      Foreign Address     State
     ```

### 37. `iptables` - Firewall administration
   - **Input:** `iptables -L`
   - **Output:**
     ```
     Chain INPUT (policy ACCEPT)
     target  prot opt source     destination
     ```

### 38. `systemctl` - Manage system services
   - **Input:** `systemctl status ssh`
   - **Output:**
     ```
     (No specific output; manages system services)
     ```

### 39. `journalctl` - Query the system journal
   - **Input:** `journalctl -u apache2`
   - **Output:**
     ```
     Log entries from the system journal
     ```

### 40. `crontab` - Schedule cron jobs
   - **Input:** `crontab -l`
   - **Output:**
     ```
     (Opens the crontab file in an editor; no specific output here)
     ```

### 41. `useradd` - Create a user account
   - **Input:** `sudo useradd newuser`
   - **Output:**
     ```
     (No specific output; creates a new user account)
     ```

### 42. `passwd` - Change user password
   - **Input:** `sudo passwd newuser`
   - **Output:**
     ```
     (Prompts to enter and confirm the new password)
     ```

### 43. `su` - Switch user
   - **Input:** `su - username`
   - **Output:**
     ```
     (Switches to the specified user; no specific output here)
     ```

### 44. `sudo` - Execute a command as another user
   - **Input:** `sudo ls /path/to/directory`
   - **Output:**
     ```
     (No specific output; executes the command as another user)
     ```

### 45. `usermod` - Modify user account
   - **Input:** `sudo usermod -G newgroup newuser`
   - **Output:**
     ```
     (No specific output; modifies user account)
     ```

### 46. `groupadd` - Create a group
   - **Input:** `sudo groupadd newgroup`
   - **Output:**
     ```
     (No specific output; creates a new group)
     ```

### 47. `groupmod` - Modify a group
   - **Input:** `sudo groupmod -n newgroup oldgroup`
   - **Output:**
     ```
     (No specific output; modifies a group)
     ```

### 48. `id` - Print user and group information
   - **Input:** `id username`
   - **Output:**
     ```
     uid=1000(username) gid=1000(groupname) groups=1000(groupname),4(adm),24(cdrom)
     ```

### 49. `ssh-keygen` - Generate SSH key pairs
   - **Input:** `ssh-keygen -t rsa -b 2048`
   - **Output:**
     ```
     (Prompts for key file location and passphrase; generates SSH key pair)
     ```

### 50. `rsync` - Synchronize files and directories
   - **Input:** `rsync -av source/ destination/`
   - **Output:**
     ```
     (No specific output; synchronizes files and directories)
     ```

### 51. `diff` - Compare files line by line
   - **Input:** `diff file1.txt file2.txt`
   - **Output:**
     ```
     (Shows the differences between file1.txt and file2.txt, if any)
     ```

### 52. `patch` - Apply a patch to files
   - **Input:** `patch -i mypatch.diff`
   - **Output:**
     ```
     (Applies the patch to the specified files)
     ```

### 53. `tar` - Extract files from an archive
   - **Input:** `tar -xvf archive.tar`
   - **Output:**
     ```
     (Extracts files from the archive)
     ```

### 54. `curl` - Perform HTTP requests
   - **Input:** `curl https://example.com/api`
   - **Output:**
     ```
     (Displays the response from the HTTP request)
     ```

### 55. `nc` - Netcat - networking utility
   - **Input:** `nc -l -p 1234`
   - **Output:**
     ```
     (Listens on port 1234; no specific output)
     ```

### 56. `wget` - Download files from the web
   - **Input:** `wget https://example.com/file.zip`
   - **Output:**
     ```
     (Downloads the file from the web)
     ```

### 57. `whois` - Lookup domain registration details
   - **Input:** `whois example.com`
   - **Output:**
     ```
     (Domain Registration Details for example.com)
     ```

### 58. `dig` - DNS lookup utility
   - **Input:** `dig example.com`
   - **Output:**
     ```
     (DNS information for example.com)
     ```

### 59. `sed` - Stream editor for text manipulation
   - **Input:** `sed 's/old/new/g' file.txt`
   - **Output:**
     ```
     (Content of file.txt with 'old' replaced by 'new')
     ```

### 60. `awk` - Pattern scanning and processing language
   - **Input:** `awk '/pattern/ {print $1}' file.txt`
   - **Output:**
     ```
     (Extracts and prints the first field from lines with 'pattern')
     ```

### 61. `sort` - Sort lines in a text file
   - **Input:** `sort file.txt`
   - **Output:**
     ```
     (Sorted content of file.txt)
     ```

### 62. `cut` - Extract sections from lines of files
   - **Input:** `cut -f 1,3 file.csv`
   - **Output:**
     ```
     (Extracts the first and third columns from file.csv)
     ```

### 63. `wc` - Word, line, character, and byte count
   - **Input:** `wc -l file.txt`
   - **Output:**
     ```
     (Number of lines in file.txt)
     ```

### 64. `tee` - Redirect output to multiple files or commands
   - **Input:** `echo "Hello" | tee file1.txt file2.txt`
   - **Output:**
     ```
     (No specific output; writes "Hello" to file1.txt and file2.txt)
     ```

### 65. `history` - Command history
   - **Input:** `history`
   - **Output:**
     ```
     1. ls
     2. cd /path/to/directory
     ...
     ```

### 66. `source` - Execute commands from a file in the current shell
   - **Input:** `source myscript.sh`
   - **Output:**
     ```
     (No specific output; executes commands from myscript.sh in the current shell)
     ```

### 67. `alias` - Create command aliases
   - **Input:** `alias ll='ls -l'`
   - **Output:**
     ```
     (No specific output; creates an alias 'll' for 'ls -l')
     ```

### 68. `ln` - Create links between files
   - **Input:** `ln -s target_file symbolic_link`
   - **Output:**
     ```
     (No specific output; creates a symbolic link)
     ```

### 69. `uname` - Print system information
   - **Input:** `uname -a`
   - **Output:**
     ```
     Linux hostname 4.15.0-101-generic #102-Ubuntu SMP Mon May 11 10:07:26 UTC 2020 x86_64 x86_64 x86_64 GNU/Linux
     ```

### 70. `lsof` - List open files and processes
   - **Input:** `lsof`
   - **Output:**
     ```
     (Processes and files currently in use)
     ```

### 71. `mkfs` - Create a file system
   - **Input:** `mkfs.ext4 /dev/sdX1`
   - **Output:**
     ```
     (No specific output; creates an ext4 file system on /dev/sdX1)
     ```

### 72. `mount` - Mount a file system
   - **Input:** `mount /dev/sdX1 /mnt`
   - **Output:**
     ```
     (No specific output; mounts the file system on /mnt)
     ```

### 73. `umount` - Unmount a file system
   - **Input:** `umount /mnt`
   - **Output:**
     ```
     (No specific output; unmounts the file system from /mnt)
     ```

### 74. `ssh-agent` - Manage SSH keys in memory
   - **Input:** `ssh-agent`
   - **Output:**
     ```
     (No specific output; starts the SSH agent)
     ```

### 75. `grep` - Search for patterns in files
   - **Input:** `grep "pattern" file.txt`
   - **Output:**
     ```
     Line with pattern
     ```

### 76. `tr` - Translate characters
   - **Input:** `echo "Hello" | tr 'a-zA-Z' 'n-za-mN-ZA-M'`
   - **Output:**
     ```
     Uryyb
     ```

### 77. `cut` - Select portions of lines from files
   - **Input:** `cut -d',' -f1,3 file.csv`
   - **Output:**
     ```
     (Selects the first and third fields using ',' as the delimiter from file.csv)
     ```

### 78. `uname` - Print system information
   - **Input:** `uname -a`
   - **Output:**
     ```
     Linux hostname 4.15.0-101-generic #102-Ubuntu SMP Mon May 11 10:07:26 UTC 2020 x86_64 x86_64 x86_64 GNU/Linux
     ```

### 79. `lsof` - List open files and processes
   - **Input:** `lsof`
   - **Output:**
     ```
     (Processes and files currently in use)
     ```

### 80. `mkfs` - Create a file system
   - **Input:** `mkfs.ext4 /dev/sdX1`
   - **Output:**
     ```
     (No specific output; creates an ext4 file system on /dev/sdX1)
     ```

Provided explanations and outputs for the Linux commands..!
