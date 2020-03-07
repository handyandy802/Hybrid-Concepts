# Hybrid-Concepts

Back in the day (1990s) There was a technical note by Apple Inc. discouraging the use of "hybrid applications" on the Apple IIGS.  I have scoured all of the online Apple Technical Notes written by DTS and have been not been able to locate it.

Being bit of a rebel, then and now, I attempted to write such an application.  My first excursion was converting the Hyper C interpreter or C Engine to 65802/816 native mode.  After I got it working Hyper C transparently worked either in emulation or native mode and native mode ran faster and better especially the Hyper C editor but also the other tools.  The only caveat I can pass on is to only make calls to 6502 ROM code in emulation mode.

The computer I used in development was and is a Laser 128EX with 4 Mhz WDC 65c802 installed.  I also recently acquired an Apple IIGS ROM 3 computer as well and bought a couple of Model 4 Raspberry PIs.  One of the RPis is set up as an Apple IIGS ROM 3 running at 25 Mhz with 16 Megabytes of RAM.

That being said, the WDC 65c802 was for me a good "entry level" cpu for 65816 native mode programming.  It was frustrating dealing with emulation mode code in the ROM but not that much of a road block.  It was nice being able to switch in RAM (Thanks WOZ) in the upper 48K and modifying vectors to support native mode and having a 16 bit stack pointer.  


