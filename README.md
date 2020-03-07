# Hybrid-Concepts

Back in the day (1990s) There was a technical note by Apple Inc. discouraging the use of "hybrid applications" on the Apple IIGS.  I have scoured all of the online Apple Technical Notes written by DTS and have been not been able to locate it.

Being bit of a rebel, then and now, I attempted to write such an application.  My first excursion was converting the Hyper C interpreter or C Engine to 65802/816 native mode.  After I got it working Hyper C transparently worked either in emulation or native mode and native mode ran faster and better especially the Hyper C editor but also the other tools.  The only caveat I can pass on is to only make calls to 6502 ROM code in emulation mode.
