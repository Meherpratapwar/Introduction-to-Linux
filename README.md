# Introduction-to-UNIX

*What is Operating System?
=> 1. An operating system is a set of programs which acts an interface between users and computer hardware.
   2. It is the heart of any machine software and provides an environment in which a user can execute programs.
   3. In other words, it is a low level software which manages hardware by controlling the execution of all kind of programs.
   4. It controls the allocation of resources and services such as memory, processors, devices, information and so on.
   5. It supports computer basic functions such as scheduling tasks, controlling peripherals and so on.
   6. Most used OS are DOS, Microsoft Windows, Mac OS X and UNIX/Linux.

*Important functions of Operating System:
=>1. Memory management
  2. Processor management
  3. Device management 
  4. File management
  5. Security
  6. Control over System performance
  7. Job scheduling
  8. Error detecting
  9. Co-oradination between users and other softwares

*What is UNIX?
=> 1. UNIX is a multi-user,multi-tasking and multi processing operating system.
   2. It is a command line interpreter.
   3. Developed in AT&T Bell Laboratories Research center, USA in 1969 by Ken Thompson and Denis Ritchie.
   4. Earlier UNIX was written in assembly language and originally spelled as UNICS.
   5. Later it was re-written in C language and named as UNIX.
   6. UNIX is not a open source OS.
   7. UNIX is used on mainframes, webservers and supercomputers.

*Features of UNIX
=> 1. Multi-user: More than one user can use the machine simultaneously supported via terminals.
   2. Multi-tasking: Multiple programs can be run at a time. (ex. image processing, sort the file)
   3. Multi-process: Each user can execute several processes simultaneously.
   4. Hierarchical structure: UNIX directories are present like a tree structure to support the organization and maintenance of files.
   5. Programming facility: UNIX shell can be used as a Programming/Scripting language.
   6. Portability: It is the ability of the software that operates from one machine to another machine having different configuration. UNIX allows user to transfer data from one system to another.
   7. Security: Unix has a sytem level security controlled by system administrator and file level security controlled by owner of the file.
   8. Tools and Utilities: Supports many of the tools, libraries and utilities to aid software development.
   9. Piping: In piping concept, output of the first command becomes the input of the next command/process.
   10. Modularity: UNIX consists of multiple number of independent modules or programs which performs different elementary tasks.
   11. Help facility: IN UNIX, "man" command is used to view help content on any command.


*Similarities between UNIX and MS-DOS
=> 1.Command Line interface
   2.Pipes and I/O redirect concept
   3.Hierarchical structure with the root directory at the top
   4.Read, write and execution permission on file
   5.Wildcard character concept
   
   
 *Similarities between UNIX and MS-Windows
 => 1.Multi-tasking operating system (OS)
    2.Built-in Networking with TCP/IP as the standard protocol
    
    
  *Difference between UNIX and MS-Windows
  =>UNIX
    1.UNIX file system is a hierarchical model
    2.UNIX is a command line interface
    3.UNIX is a multi-user and multi-tasking OS
    4.UNIX is a free-source OS
    5.UNIX has dumpy terminals (without hard disk)
    6.UNIX is a case sensitive
    7.UNIX is not user friendly
    8.UNIX supports programming facility
    9.UNIX have muktiple vendors

=>MS-Windows
  1.Windows file system is a flat model
  2.Windows is a Graphical user interface
  3.Windows is a single user and multi-tasking OS
  4.Windows is licensed OS
  5.Windows do not support dumpy terminals
  6.Windows is not a case sensitive
  7.Windows is a user friendly
  8.Windows do not support programming facility
  9.Windows have only one vendor i.e. Microsoft

*Flavours/Variant of UNIX
=>1.AIX - IBM
  2.HP Ux - HP
  3.Solaris - Sun
  4.Xenix - Microsoft
  5.TRIX - Silicon graphics
  6.Linux - Redhat

*UNIX Architecture
=>1.Hardware/Physical
  .The hardware layer of the UNIX Operating System controls the use of physical system resources, such as memory manager, process manager, disk drivers, devices and so on.
  .Hardware consists of all peripheral devices (RAM,HDD,CPU and so on)
  
  2.Kernel 
  .Kernel is heart of UNIX Operating system
  .IT acts as an interface between hardware and shell layer
  .Most of the tasks such as memory management, task scheduling, file management and so on are performed by Kernel
  .It manages external commands in UNIX
  
  3.Shell
  .Shell is an interface between a user application and kernel.
  .This layer processes your request. When we type a command at the terminal,shell interpretes the command and call the corresponding program.
  .Shell uses the standard syntax for all commands.
  .A file "/etc/shells" contains the list of all the shells supported and avilable in the system.
  .Different shell available in most of the UNIX flavours are:
   1.C shell (csh)
   2.Burne shell (sh)
   3.Korn shell (ksh)
   4.Born Again Shell (bash)

   4.Application programs
   .Utility programs and applicaations iven by the user are handled in this layer.
   .Data in UNIX are organized into files and files are organized into directories which are futher organized into a tree-like structure called the file system.
   .A file sytem consists a sequence of four blocks:
     1. BOOT block
     2. Super block 
     3. Inode block
     4. Data block
