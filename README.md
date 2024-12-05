# zmk-config-39key
ZMK config setup for a 39 key keyboard

![PXL_20241127_135601698](https://github.com/user-attachments/assets/65fa34a7-ce6a-42f3-b8c5-c33e47b49a4c)

3D printed keyboard link:
[https://www.thingiverse.com/thing:4592203]

Link to ZMK documentation: [https://zmk.dev/docs]

This build I used single switch PCBs which can be printed with a PCB fab company like JLCPCB or PCBWay

Link to the MxLEDBitPCB: [https://github.com/swanmatch/MxLEDBitPCB]

## Parts used in build:

- 39 MX style switches
- 39 1N4148 diodes
- 39 kailh hot swap sockets
- 15 sk6812mini-e LEDs
- 39 Single Switch PCBs
- 22 gauge tinned copper wire
- 28 AWG Flexible Silicone Wire
- 1 NiceNano controller
- 1 Battery helper PCB from [https://www.boardsource.xyz/]
- Hot glue (needed to hold the switches/pcbs to the plate).
- 9 screws

##Build Guide

- print the case and plate

- put switches into plate

> I had fo make modifications to the plate and case to fit the Nicenano controller. plate was modified to remove some of the legs as they were in the way of the pcbs.

- solder the pcb components and then connect to the switches

- solder connections for row and column to all fhe pcbs/switches

- using the silicone wire, connect all power and negative together for fhe switches that will have LEDs

- using silicone wire connect to Data IN ok pcb. connect the data in/out to all the pcbs. Be sure to connect data OUT on the last switch back to data pin used on the controller.

- using the hot glue, glue the pcbs/switches to plate

> I used some 1mm foam connected to the plate.

- pop in the controller after connecting and gluing in battery

- screw the case and plate together. then test. Be careful when having to unscrew the case multiple times as the plate legs can easily snap off.


# License

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p>

You are free to:

Share — copy and redistribute the material in any medium or format

Adapt — remix, transform, and build upon the material

The licensor cannot revoke these freedoms as long as you follow the license terms.
Under the following terms:

Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

NonCommercial — You may not use the material for commercial purposes.

ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

