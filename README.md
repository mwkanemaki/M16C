# M16C

https://webpages.uncc.edu/~jmconrad/ECGR4101Common/SKP16C62P/App_Notes/M16C62_Flash_Parallel_Programming.pdf
APPLICATION NOTE
M16C/62
Programming the M16C/62 in Flash Parallel Mode

The M16C/62 flash can be programmed using one of three methods: 
Parallel I/O Mode, 
Standard Serial I/O Mode, 
CPU Rewrite Mode. 

The flash memory is divided into two major blocks, 
a user program area 
and 
a boot ROM area. 
The user program area 
is 
for the normal application program and data. 

Any program in the boot ROM area 
is accessed 
only when a special hardware reset sequence is initiated. 

This boot ROM area 
has 
a control program stored in it when shipped from the factory. 

The program 
allows 
asynchronous or synchronous serial programming of the user area of the flash. 
Changes to the boot area of the flash 
can only be made 
using Parallel I/O Mode.
















