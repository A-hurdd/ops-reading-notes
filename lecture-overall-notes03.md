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

- The CPU initalizes, then fetches instructions from the BIOS, loads into RAM
- The BIOS then starts the monitor and keyboard,system checks.
- The BIOS then starts the boot sequence.
  > it will look for the operating system.

  - Control transferred to OS

### Bios
> Stands for Basic Input (and) Output System
 The lowest level of the computer system we are likely to see in day to day computer operations.

- Bios is stored in the mortherboard of a computer and is responsible for initalizing the hardware and loading the operating system.
- Look for in todays lab:
- Boot modes
- UEFI
- Legacy
- Boot order/priority
Dell computers are traditionally F12 in boot up to enter Bios.
Could also possibly be the Del.,  F, FN, ShiftF2.

### CMOS
> Complementary metal-oxide-semiconductor (CMOS) holds BIOS config.

The battery that maintains the settings to your BIOS
Usuallylasts a few years, how to know if its going bad ? you boot up your computer and the date is wrong, or your computer won't boot cause the settings are all messed up.

- Type of disk drivers installed
- System clock date and time
- Boot sequence
- Reset the CMOS memory by removing the CMOS battery to "clear" the CMOS, then reinstalling it.

Todays lab we will be taking the battery out and resetting the CMOS. Unplug the computer and take the battery out and hit the power button and then leave the computer powered down for 5 minutes.
Then we put the battery back and plug it back in and turn it back on. FOLLOW LAB INSTRUCTIONS.
