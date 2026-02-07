# Linux_learns
Learning of Linux for the Devops role based.
# Day 1:
# Operating System:
Linux is opensource and it is super secure compared to other O/S.
O/S: It is an intermediate s/w layer that acts as a bridge between s/w and h/w and it performs process, device, memeory, disk, network management.
For windows o/s it provides GUI and for Linux o/s it provides CLI.

# Components of Linux:
1. User application ( VIM, Docker, Apache, etc )
2. Shell ( Bash, etc )
3. System Libraries ( Lib, OpenSSL, etc ) 
4. System Utilities ( ls, grep, systemctl, etc )
5. Kernel ( process, device, memeory, disk, network, etc )
6. Hardware ( CPU, ram, disk, network, etc )

**Linux Kernel:** Interacts with the hardare such process, device, memeory, disk, network management handled by Linux kernel.
On top of the kernel it has system layers and on top of it have CLI.
Have used WSL as well as Docker containers to simulate the Linux environment in my PC.
Package managers:
It helps to deploy, upgrade, delete, maintain and install the dependencies.
For ubuntu the package is - apt
**HOSTINGER**
It provides diffenrt types of O/S with have annual plans for practice Linux.
**Must know Linux Commands for productions:**
1. cd then enter - returns back to home folder
2. ls - lists the files and folders
3. rm filename - to delete the filename
4. rm -r directorname - to delete the directory
5. pwd - which the present working directory
6. When we are working on Linux we should be aware on which shell we working for? to check - echo $SHELL - which will show the /bin/bash
7. mkdir sunha - to create a directory
8. mkdir -p subha/new/{folder1,folder2} - to create folders inside the folders with multiple folders
9. touch filename1 filename2 filename3 - to create single or multiple files
10. cp file1 file2 - which will copy all the contents inside the files
11. mv file1 file11 - to rename the already exiting filename
12. cat file1.txt - to display the contents inside the file
13. vi file1.txt OR vim file1.txt OR nano file1.txt - to edit or write the contents inside the files
14. less file1.txt - shows the first page contents in a file
15. head -n 2 file1.txt - shows the first 2 lines from th head of file
16. tail -n 2 file1.txt - shows the last 2 lines from the bottom of file
17. grep "who" file1.txt - to search the word who inside the file1.txt
18. touch script.sh - to create a shell script file
19. ls -l - to display long listing of the files and folders
20. ls -l filename - to display the particular file
21. ./script.sh - to execute the shell script
22. ps aux | grep 200 - to check the processes
23. htop - to chekc the cpu load
24. curl urlwebsite -
25. wget copyurl - will get the zip file
26. unzip filename - to unzip
27. ctrl + l - to clear the screen in terminal
28. uptime - to check the time
29. ss -tuln | grep 4000 - to check the listening port
# Day 2:
Linux Folder structure:
docker exec -it containerid /bin/bash -- to enter into the container
/ -- it is a parent location of the file system path and PWD
sudo su - switches to the root user
cd / -- moves to the root directory of the file system
ls -ltr -- lists all the folders and files in the root user
1. sbin - it is system binaries ( basically this are commands or files to manage the system )
2. lib - it is a libraries
3. boot - restarting the linux m/c
4. bin - it is for user binaries
5. usr - it has sbin, bin, lib
6. srv - it is a server where we can store the configuration files related to web servers
7. opt - it is used to store the 3rd dependinces inside it
8. mnt - it is used to mount new volumes/disks
9. var - it is used to store log files, libraries
10. data - it is used for storing any data
11. run - it stores the run data of the processes
12. etc - it has all the system configuration files and using this files we can configure and modify the file systems
13. PATH - it will tell the linux system when somebody enters the commands, it checks all the folders within the path and if it is in one of the folders you can directly execute it.
14. 
