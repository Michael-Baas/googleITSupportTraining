# Google IT Support Professional Certificate Notes

* Richard Stallman created GNU as a free alternative to Unix
* 8 bits is a byte which is 256 possible values.
* Device imaging refers to wiping a system and reinstalling a fresh OS
* The Motherboard is split into two "bridges" north bridge is responsible for CPU
  and Ram (computing) and the south bridge is responsible for hard
  drives, input devices, peripherals (I/O devices)

What does the kernel do in the kernel space?
  1. Process Manager
    `What is a process manager?`
      * A process manager handles processes (program that is executing). A
        program can have many processes at the same time. A process can be
        for only one program tho and is a single "task" for an
        application.
    `How does a CPU run multiple processes at once?`
      * It doesn't, it uses time slicing (A time slice is a very short interval of time
        that gets allocated to a process for CPU execution)
    `How does the Kernel deal with processes?`
      * The Kernel creates processes, efficiently schedules them, and
        manages how processes are terminated.
  2. Memory Manager
    `What is Virtual Memory?`
      * The combination of hard drive space and RAM that acts like
        memory that our processes can use.
    `Why is Virtual Memory Important?`
      * Virtual Memory allows programs to load partial parts of program
        into Physical RAM, rather than having to dump the entire program
        in using up all of the system's RAM.
    `What is Swap Space?`
      * Swap Space is storing virtual memory on the hard drive.
  3. File Manager
  4. I/O Manager
    Drivers, data exchange, inter-device communication is all handled by
    the Kernel

`What is the user space of an Operating System?`
  * How the humans interact with the OS.
    * GUI/Graphical
    * CLI/Shell
Firmware - Software that's permanently stored on a computer component.

