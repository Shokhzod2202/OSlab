# OSlab repo

## WEEK2:

*    I installed VMware, Ubuntu, Git, and ROS operation system.
*    I uploaded my repository link.
*    I performed all the given tasks for Week 2, and uploaded my code via Ubuntu VMware to the remote Git repository.
*    I updated the Github readme file.
*    I created a Shell file and practiced useing it with sh command.


## Assignment (Last Assignment Submited in this repository as a folder "AssignmentLast"

# Assignment
## Week 6 Lab:
```
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ touch date_parse.sh
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ ls
archive.tar  date_parse.sh  file1.txt  file2.txt  file3.txt  README.md
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ nano date_parse.sh 
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ bash date_parse.sh 
Thu 01 Jun 2023 12:35:42 PM KST
Current Date is: 01-06-2023
Current Time is: 12:35:%Second
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ 

shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ date > saved-timestamp
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ ls
archive.tar    file1.txt  file3.txt  saved-timestamp
date_parse.sh  file2.txt  README.md
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ cat < saved-timestamp 
Thu 01 Jun 2023 12:40:33 PM KST


shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ nano all-four-in-one 
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ ls -a > my-file-names
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ cat < my-file-names 
.
..
all-four-in-one
archive.tar
date_parse.sh
file1.txt
file2.txt
file3.txt
my-file-names
README.md
saved-timestamp
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ 

shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ ls -l /usr/bin | less

shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ ls | wc -l
\11

shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ ps au
USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
shokhzod    1726  0.0  0.0 172652  6472 tty2     Ssl+ 03:16   0:00 /usr/lib/gdm3
shokhzod    1728  1.0  1.5 426932 122152 tty2    Sl+  03:16   5:56 /usr/lib/xorg
shokhzod    1739  0.0  0.1 196848 13772 tty2     Sl+  03:16   0:00 /usr/libexec/
shokhzod  159874  0.0  0.0  20736  6440 pts/0    Ss   11:26   0:01 bash
shokhzod  161440  0.0  0.0  20128  3272 pts/0    R+   13:09   0:00 ps au
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ 

shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ chmod go-rw file1.txt 
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ chmod a+x file2.txt 
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ chmod 750 sampledir
chmod: cannot access 'sampledir': No such file or directory
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ mkdir sampledir
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ chmod 750 sampledir
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ ls -l
total 44
-rw-rw-r-- 1 shokhzod shokhzod    16 Jun  1 12:51 all-four-in-one
-rw-rw-r-- 1 shokhzod shokhzod 10240 May 31 23:20 archive.tar
-rw-rw-r-- 1 shokhzod shokhzod   212 Jun  1 12:35 date_parse.sh
-rw------- 1 shokhzod shokhzod    16 Jun  1 12:48 file1.txt
-rwxrwxr-x 1 shokhzod shokhzod     0 May 31 23:18 file2.txt
-rw-rw-r-- 1 shokhzod shokhzod     0 May 31 23:18 file3.txt
-rw-rw-r-- 1 shokhzod shokhzod    24 Jun  1 12:58 many-lines-of-information
-rw-rw-r-- 1 shokhzod shokhzod   117 Jun  1 12:55 my-file-names
-rw-rw-r-- 1 shokhzod shokhzod     0 May 31 23:27 README.md
drwxr-x--- 2 shokhzod shokhzod  4096 Jun  1 13:16 sampledir
-rw-rw-r-- 1 shokhzod shokhzod    32 Jun  1 12:40 saved-timestamp
-rw-rw-r-- 1 shokhzod shokhzod    22 Jun  1 13:00 tracking-changes-made
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ ls -a
.                file1.txt                  README.md
..               file2.txt                  sampledir
all-four-in-one  file3.txt                  saved-timestamp
archive.tar      many-lines-of-information  tracking-changes-made
date_parse.sh    my-file-names
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ 

shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ chmod -R g+rwx demodir
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ ls -l
total 48
-rw-rw-r-- 1 shokhzod shokhzod    16 Jun  1 12:51 all-four-in-one
-rw-rw-r-- 1 shokhzod shokhzod 10240 May 31 23:20 archive.tar
-rw-rw-r-- 1 shokhzod shokhzod   212 Jun  1 12:35 date_parse.sh
drwxrwxr-x 2 shokhzod shokhzod  4096 Jun  1 13:22 demodir
-rw------- 1 shokhzod shokhzod    16 Jun  1 12:48 file1.txt
-rwxrwxr-x 1 shokhzod shokhzod     0 May 31 23:18 file2.txt
-rw-rw-r-- 1 shokhzod shokhzod     0 May 31 23:18 file3.txt
-rw-rw-r-- 1 shokhzod shokhzod    24 Jun  1 12:58 many-lines-of-information
-rw-rw-r-- 1 shokhzod shokhzod   117 Jun  1 12:55 my-file-names
-rw-rw-r-- 1 shokhzod shokhzod     0 May 31 23:27 README.md
drwxr-x--- 2 shokhzod shokhzod  4096 Jun  1 13:16 sampledir
-rw-rw-r-- 1 shokhzod shokhzod    32 Jun  1 12:40 saved-timestamp
-rw-rw-r-- 1 shokhzod shokhzod    22 Jun  1 13:00 tracking-changes-made
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ 

shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ ps aux
USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root           1  0.0  0.1 171636 13160 ?        Ss   03:15   0:10 /sbin/init au
root           2  0.0  0.0      0     0 ?        S    03:15   0:00 [kthreadd]
root           3  0.0  0.0      0     0 ?        I<   03:15   0:00 [rcu_gp]
root           4  0.0  0.0      0     0 ?        I<   03:15   0:00 [rcu_par_gp]



```
### Week 7 Lab 
Week 7 Lab is installing and running oracle cloud and repetition of week 6th Lab materials.

### No Lab until 13th week

## Week 13 Lab:

```

shokhzod@ubuntu:~/Documents/OSlab$ mkdir AssignmentLast
shokhzod@ubuntu:~/Documents/OSlab$ ls
AssignmentLast  README.md  Week2  Week3  Week4
shokhzod@ubuntu:~/Documents/OSlab$ cd AssignmentLast/
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ ls
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ touch file1.txt file2.txt file3.txt
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ ls
file1.txt  file2.txt  file3.txt
shokhzod@ubuntu:~/Documents/OSlab$ mkdir AssignmentLast
shokhzod@ubuntu:~/Documents/OSlab$ ls
AssignmentLast  README.md  Week2  Week3  Week4
shokhzod@ubuntu:~/Documents/OSlab$ cd AssignmentLast/
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ ls
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ touch file1.txt file2.txt file3.txt
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ ls
file1.txt  file2.txt  file3.txt
shokhzod@ubuntu:~/Documents/OSlab/AssignmentLast$ tar tf archive.tar 
file1.txt
file2.txt
file3.txt


```

## Week 14 Lab:

```
shokhzod@ubuntu:~$ ls -l /dev/sda
brw-rw---- 1 root disk 8, 0 Apr 22 03:26 /dev/sda
shokhzod@ubuntu:~$ 

shokhzod@ubuntu:~$ df
Filesystem     1K-blocks     Used Available Use% Mounted on
udev             4012436        0   4012436   0% /dev
tmpfs             810584     2032    808552   1% /run
/dev/sda5       19947120 16893956   2014572  90% /
tmpfs            4052912        0   4052912   0% /dev/shm
tmpfs               5120        4      5116   1% /run/lock
tmpfs            4052912        0   4052912   0% /sys/fs/cgroup
/dev/loop0           128      128         0 100% /snap/bare/5
/dev/loop2        119680   119680         0 100% /snap/core/14784
/dev/loop1         56960    56960         0 100% /snap/core18/2714
/dev/loop4         64896    64896         0 100% /snap/core20/1852
/dev/loop5         93952    93952         0 100% /snap/gtk-common-themes/1535
/dev/loop9        119680   119680         0 100% /snap/core/14946
/dev/loop7         56960    56960         0 100% /snap/core18/2721
/dev/loop12        55552    55552         0 100% /snap/snap-store/558
/dev/loop14       358144   358144         0 100% /snap/gnome-3-38-2004/137
/dev/loop13        47104    47104         0 100% /snap/snap-store/638
/dev/loop10        54528    54528         0 100% /snap/snapd/18933
/dev/sda1         523248        4    523244   1% /boot/efi
tmpfs             810580       56    810524   1% /run/user/1000
/dev/loop16         9856     9856         0 100% /snap/canonical-livepatch/209
/dev/loop3          9856     9856         0 100% /snap/canonical-livepatch/229
/dev/loop17       358144   358144         0 100% /snap/gnome-3-38-2004/140
/dev/loop8         54656    54656         0 100% /snap/snapd/19361
/dev/loop11        65024    65024         0 100% /snap/core20/1891
shokhzod@ubuntu:~$ 

shokhzod@ubuntu:~$ df -h
Filesystem      Size  Used Avail Use% Mounted on
udev            3.9G     0  3.9G   0% /dev
tmpfs           792M  2.0M  790M   1% /run
/dev/sda5        20G   17G  2.0G  90% /
tmpfs           3.9G     0  3.9G   0% /dev/shm
tmpfs           5.0M  4.0K  5.0M   1% /run/lock
tmpfs           3.9G     0  3.9G   0% /sys/fs/cgroup
/dev/loop0      128K  128K     0 100% /snap/bare/5
/dev/loop2      117M  117M     0 100% /snap/core/14784
/dev/loop1       56M   56M     0 100% /snap/core18/2714
/dev/loop4       64M   64M     0 100% /snap/core20/1852
/dev/loop5       92M   92M     0 100% /snap/gtk-common-themes/1535
/dev/loop9      117M  117M     0 100% /snap/core/14946
/dev/loop7       56M   56M     0 100% /snap/core18/2721
/dev/loop12      55M   55M     0 100% /snap/snap-store/558
/dev/loop14     350M  350M     0 100% /snap/gnome-3-38-2004/137
/dev/loop13      46M   46M     0 100% /snap/snap-store/638
/dev/loop10      54M   54M     0 100% /snap/snapd/18933
/dev/sda1       511M  4.0K  511M   1% /boot/efi
tmpfs           792M   56K  792M   1% /run/user/1000
/dev/loop16     9.7M  9.7M     0 100% /snap/canonical-livepatch/209
/dev/loop3      9.7M  9.7M     0 100% /snap/canonical-livepatch/229
/dev/loop17     350M  350M     0 100% /snap/gnome-3-38-2004/140
/dev/loop8       54M   54M     0 100% /snap/snapd/19361
/dev/loop11      64M   64M     0 100% /snap/core20/1891
shokhzod@ubuntu:~$ 

shokhzod@ubuntu:~$ du /root
du: cannot read directory '/root': Permission denied
4	/root
shokhzod@ubuntu:~$ du -h /var/log
12K	/var/log/vmware
177M	/var/log/journal/65beecfe3cc64c948da94165483cbbfb
177M	/var/log/journal
2.5M	/var/log/installer
4.0K	/var/log/firebird
du: cannot read directory '/var/log/gdm3': Permission denied
4.0K	/var/log/gdm3
4.0K	/var/log/hp/tmp
8.0K	/var/log/hp
du: cannot read directory '/var/log/speech-dispatcher': Permission denied
4.0K	/var/log/speech-dispatcher
36K	/var/log/cups
204K	/var/log/apt
24K	/var/log/unattended-upgrades
4.0K	/var/log/openvpn
du: cannot read directory '/var/log/private': Permission denied
4.0K	/var/log/private
4.0K	/var/log/dist-upgrade
64K	/var/log/apache2
181M	/var/log
shokhzod@ubuntu:~$ 

shokhzod@ubuntu:~$ blkid
/dev/sda5: UUID="d519848c-9961-4b4c-bcc3-142980688169" TYPE="ext4" PARTUUID="3df5002a-05"
shokhzod@ubuntu:~$ 



```


