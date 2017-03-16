# Jordan-s-FED
Based on the original FED from Kravitz Lab, this user-friendly device is designed to reliably dispense 45 mg rodent food pellets with minimal tinkering. A number of changes, described below, were made to the physical structure of the device. Two 'for loops' were added to the code, causing the direction of motor rotation to alternate after either 1) successful pellet dispense or 2) twelve motor steps without successful pellet dispense.  Alternating motor direction alleviates clogs in the silo.  

----------------------------------------------------------------------------------------------------------------------------------------

3D Print Design Changes from original FED are summarized as follows:

Silo:
Pellets are swept single file underneath an oval shaped wall, alleviating strain which caused clogging in the original model. Clogging is greatly reduced, increasing reliability of successful pellet dispenses and extending battery life. 

Disk:
Pellet holes widened and deepened to accomodate one 45 mg pellet at a time. 

Motor mount:
Disk tray deepened to accomodate the now taller disk.

Funnel:
Instead of dropping vertically, pellets now tumble down an ovaloid chute which sweeps laterally, reducing the chance of pellets bouncing out of the well. The new funnel piece is wider than the original and snaps into place without the use of screws.

Base:
(1) Standouts for PCB machine screws were rotated 90 degrees to make the device more user friendly. Now, the SD card is easily reached. The Power Booster lies flat on the floor and battery charging is done with the device standing upright. This increases user friendliness and slightly increases the size of the device. 
(2) Designated battery slot added to improve organization. 
(3) Switch slot was moved from the side of the device to the top, more efficiently using vertical space. 
(4) Pellet ramp was narrowed with the simple addition of walls. Pellets fall through an oval hole instead of a square one. 

Front Plate:
This component was removed from the design, since the funnel piece accomplishes the job of the old front plate. 

Lid and Back Panel:
No changes.

----------------------------------------------------------------------------------------------------------------------------------------

Performance Results:

I built 5 FEDs with these new pieces. The silos were filled completely with 45 mg pellets, and then 150 consecutive dispensing events and errors were recorded. A success counts as a single pellet landing in the well. Errors were of two types: 1) pellet bouncing out of the well; 2) two pellets dropping into the well at once. Mean success rate = 98.8%, median success rate = 98.7%.

Device 1: 
Successes -- 148/150, Errors -- bounce outs, 2.

Device 2: 
Successes -- 150/150, Errors -- none.

Device 3: 
Successes -- 149/150, Errors -- bounce out, 1.

Device 4: 
Successes -- 148/150, Errors -- bounce out, 1. double drop, 1.

Device 5:
Successes -- 148/150, Errors -- bounce out, 1. double drop, 1. 
