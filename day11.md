# ASSIGNMENT
## DAY 11
   - Today is the first day of third week in the internship program.today I
completed PPT for door step service applications.then I learned about booting 
process of computer system.
   - there are four stages in booting process namely:
     1.BIOS
       - BIOS stands for Basic Input/Output System
       - Performs some system integrity checks
       - Searches, loads, and executes the boot loader program.
       - It looks for boot loader in floppy, cd-rom, or hard drive.
       - Once the boot loader program is detected and loaded into the memory, BIOS gives the control to it.
       - So, in simple terms BIOS loads and executes the GRUB boot loader.
      2.MBR
       -  MBR stands for Master Boot Record.
       -  It is located in the 1st sector of the bootable disk. 
       -  MBR is less than 512 bytes in size. This has three components 1) primary boot loader info in 1st 446 bytes 2) partition table info in next 64 bytes 3) mbr validation check in last 2 bytes.
       - It contains information about GRUB (or LILO in old systems).
       -  So, in simple terms MBR loads and executes the GRUB boot loader.
      3.kernel
       - Kernel executes the /sbin/init program
       - Since init was the 1st program to be executed by Linux Kernel.
       - initrd stands for Initial RAM Disk.
       - initrd is used by kernel as temporary root file system until kernel is booted and the real root file system is mounted. It also contains necessary drivers compiled inside, which helps it to access the hard drive partitions, and other hardware.
      4.Init
       - Init identifies the default initlevel from /etc/inittab and uses that to load all appropriate program.
       - Init executes the run level program which used to start and stop the operation of system.
    these  are the booting process of a system.then I newly heard about GRAMMARILY Plugins for firefox,It uses to correct the grammar mistakes and
leads for good commiunnication skill.these are the things I learned in today internship program.
thankyou 

