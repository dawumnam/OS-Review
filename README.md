# Operating Systems

## Intro to OS

### What is OS?

Abstraction

- Hides details of different hardware configs
- Apps dont need to tailered to hardware specific

Arbitration

- Manages shared access to hardware resources
- Orchestrates multiple apps to use hardware simultaneously

### Hardware Resources

CPU

- Executes program instructions
- Multiple CPU cores execute instructions in parallel

Memory

- Registers and cache are the fastest
- RAM is slower
- Disks are the slowest

IO Devices, Power Supply, and Cooling system

Layers of the System is as following

- Application (Userspace)
- Library and Utilities (Userspace)
- Operating System ( Kernel in the OS is the minimal pieces of software used to share hardware)
- Hardware

OS allows applications to communicate with hardware by working as a middle man in between

## Linux System

Layers of the Linux System is as following

- Computer Hardware
- Kernel with libraries for memory managment, processes, file systems, networking, and etc..
- GNU C Library
- Gcc GNU coreutils bash
- Addon Softwares like Gnome, APache, PHP, and etc.

## Disk I/O

- Disk attachment is enabled by using protocols like SATA, M.2 and etc

## Paging

- is a memory management scheme that eliminates the need for contiguous allocation of physical memory.
- A logical address and a physical address is divided by page size
- Each logical page is mapped to physical frame
- When logical page does not exist in a ram it is called page fault
- Since accessing page table from main memory and accessing its physical frame according to page table costs double access of main memory,
- TLB (translation Look-aside buffer) which is cache specific for storing transactions of pages.
