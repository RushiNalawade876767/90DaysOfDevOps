
1)What is Kernel?

The kernel is the heart of Linux.
It directly talks to hardware (CPU, RAM, Disk, Devices).

 Main Responsibilities:

Process management

Memory management

File system handling

Device drivers

Security & permissions

Networkig 

Without kernel, OS cannot work

2) User Space

User space is where:

Applications run (Chrome, VS Code, etc.)

Commands run (ls, cd, grep)

User programs execute

It cannot directly access hardware.
It requests the kernel using system calls.

3) Init/Systemd 
 
When Systems Start the first process that runs is :-

init (older systems ) systemd (modernLinux)

Today mostly distributors use systemd

*HoW PROCESS WORKS*

A running Program is called as Process

ex) when tou open a chrome process is created .

*fork()* creates a copy of current object 




















