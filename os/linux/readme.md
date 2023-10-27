# linux 64 bits (x64/amd64 are 64 bits, because i386 is 32 bits):  
Min 3 parts:  
1) efi (also call esp):  
fat32 (suggest)/ os installer auto default/ vfat  
Max size: 512MB/ 550MB (suggest 550MB)  
(why 550MB because of avoid MiB/MB confusion and accidentally creating FAT16)  
https://askubuntu.com/questions/1313154/how-to-know-the-proper-amount-of-needed-disk-space-for-efi-partition  
https://www.linuxquestions.org/questions/linux-newbie-8/boot-partition-efi-system-partition-file-system-questions-4175710247/
<br>


reference:  
https://www.linux.org/threads/solved-boot-partition-efi-system-partition-file-system-questions.39817/
<br>
https://ubuntuforums.org/showthread.php?t=2412667
<br>
https://forums.linuxmint.com/viewtopic.php?t=396072
<br>
https://forums.linuxmint.com/viewtopic.php?t=360768
<br>
https://forums.linuxmint.com/viewtopic.php?t=341299  
<br>

2) / (this is root partition, where your os lives, don't delete it):  
ext4/ btrfs (more easily backup XD)

3) swap:  
ram size/ double ram size/ at least 1GB:  
(exp: ram: 8GB, swap: 16GB or  
ram: 8GB, swap: 8GB or  
ram: 8GB, swap: 1GB)  

4) /home (home partition which is optional choice, but perfer make it)  
(home partition which under root partition, where u *data lives, perfer seperate it as 4th partition because it more safer while u update or do any thing to your root partition)  
(even home partition is under root partition, u do any recovery operation to root partition will no affect home partition, that allows u *data become safe)  
(*data means data that u edit, create and download, exp: ???.mp4, ???.txt, ???.c, ???.ppt..., but no your ???.exe)
(???.exe, firmware, software will install in root partition (/), *data will store in home partition (/home))
(even home partition is under root partition,home partition is independent to root partition)  

https://distrowatch.com/
<br>

ubuntu  
https://ubuntu.com/download/desktop  

mint (Cinnamon Edition)  
https://www.linuxmint.com/download.php  

debian  
https://www.debian.org/CD/http-ftp/  

fedora  
https://fedoraproject.org/  

manjora (KDE Plasma)  
https://manjaro.org/download/  

opensuse (Leap which is stable version)  
https://www.opensuse.org/  

deepin  
https://www.deepin.org/zh/download/  

elementary os  
https://elementary.io/  

zorin  
https://zorin.com/os/download/  

EndeavourOS (XFCE)  
https://endeavouros.com/  

MX Linux (Xfce)  
https://mxlinux.org/download-links/  

kali  
https://www.kali.org/get-kali/#kali-platforms  

arch linux  
https://archlinux.org/download/  

KDE neon (KDE Plasma)  
https://neon.kde.org/download  

solus (budgie)  
https://getsol.us/download/  

pop os  
https://pop.system76.com/  

FreeBSD  
https://www.freebsd.org/zh-tw/where/  





