# Reading Notes 03

When having problems with the pc beepcodes matter. listen to them and document.

###Why start up sequence?

- Trouble shooting a computer that is not correctly booting
- Repairing a corrupt master boot record (MBR)
  > MBR hold partition and fyle system info
  > Boot loader for OS
  
  - Isolated a problem in the start up sequence
  - Acessing bios
  - Booting to the correct OS
  - Configuring dual-boot
  - Understanding behind the scenes
The MBR is where the data to boot the OS is stored

### ROM
> Rom is read-only memory

BIOS was origionally stored in ROM but newer BIOS use flash memory, less secure.
Hard-coded into the motherboard and cannot be altered or deleted.
Newer devices use flash memory instead of ROM. An example of a ROM is the boot sequence of a computer.
Flash memory (Flash ROM) is volatile memory.
Now you can actually flash the memory, download software from manufacture ,upload it to motherboard or even overwrite the software.
Flash memory can be written and erased.

### Startup
> Computer start up

- The CPU inittalizes, then fetches instructions from the BIOS, loads into RAM
- The BIOS then starts the monitor and keyboard,system checks.
- The BIOS then starts the boot sequence.
  > it will look for the operating system.

  - Control transferred to OS

