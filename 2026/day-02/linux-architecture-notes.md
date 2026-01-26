
# 1. Kernel:

The kernel is the heart of Linux. It has direct access to hardware. Applications never talk to hardware directly. They talk to the kernel, using system calls.

What it does:
      Process management,
      Memory management,
      Device drivers,
      File systems,
      Networking
=============================================================================================================================================
# 2. created and managed Process: 

In the linux, Everythingh is a process created and assigned by kernal.

A process has states like:
      Running
      Sleeping (waiting for I/O)
      Stopped (paused)
      Zombie (finished, but not yet reaped by parent)



=============================================================================================================================================
# 3. systemd: Systemd is the default system and service manager for most modern Linux distributions, acting as the first process (PID 1) to boot the system, mount file systems, and manage user space services. It matters because it provides fast, parallelized service startup, unified configuration, advanced dependency management, and robust resource tracking, replacing older, slower init systems. 
   
      It always has PID 1
      It is responsible for starting, stopping, and managing everything else
      Once the kernel finishes booting, it hands control to systemd.



