rufus:  
https://rufus.ie/zh_TW/

windows os (w10, w11):  
64 bits (x64) format:  
UEFI  
GPT  
4 parts: (Type)  
Partition 1: Recovery (Recovery)  
Partition 2: (System) 100MB  
Partition 3: MSR(Reserved)  
Partition 4: (Primary)
<div >
<img src="https://github.com/kitleong97/software/blob/main/os/rufus/Windows%2010%20UEFI-GPT.png" width="49%" height="600px" alt="english uefi 64 bit" >
<img src="https://github.com/kitleong97/software/blob/main/os/rufus/1517043977-688010571.jpg" width="49%" height="600px" alt="chinese uefi 64 bit"  >  
</div>

Note:  
(default) disk management cant show 4 part (only show 3 parts),  
you need other software to show 4 parts (exp: disk genius)  
<br>


32 bits (x86) format:  
CSM/ Legacy BIOS/ BIOS  
MBR  
2 parts:  
Partition 1: System Reserved (System)  
Partition 2: (Primary)  
<div >
<img src="https://github.com/kitleong97/software/blob/main/os/rufus/Windows%2010%20BIOS-MBR.png" width="49%" height="600px" alt="english mbr 32 bit" >
<img src="https://github.com/kitleong97/software/blob/main/os/rufus/1517044875-722234276.jpg" width="49%" height="600px" alt="chinese mbr 32 bits"  >  
</div>
<br>

reference:  
chinese  
https://ofeyhong.pixnet.net/blog/post/221137125
<br>
english:  
https://www.tenforums.com/installation-upgrade/9053-w10-install-uefi-mode.html  
<br>

linux 64 bits (x64):  
Min 3 parts:  
1) efi (also call esp):  
fat32 (suggest)/ os installer auto default/ vfat  
Max size: 512MB/ 550MB
reference:  
https://www.linux.org/threads/solved-boot-partition-efi-system-partition-file-system-questions.39817/  
https://ubuntuforums.org/showthread.php?t=2412667  
https://forums.linuxmint.com/viewtopic.php?t=396072  
https://forums.linuxmint.com/viewtopic.php?t=360768  
https://forums.linuxmint.com/viewtopic.php?t=341299  

3) /:  
ext4/ btrfs  
4) swap:  
ram size/ double ram size:  
(exp: ram: 8GB, swap: 16GB or  
exp: ram: 8GB, swap: 8GB)  




