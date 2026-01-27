This is a PC XT Clone based on IBM5160 design.


Why Dubai Xt clone? The board was designed in Dubai :) Certainly Dubai’s First Turbo PC/XT Clone Motherboard!

I had great pleasure designing, studifying existing other clones and creating this board as the board I wanted to have. Minimal amount of TTL chips for a turbo design with static ram, with zero DMA issues/drama.

I hope you enjoy too.

Felipe Spencer Picada
The creator of the DubaiXTClone 8088 PC/XT Compabible Motherboard

DubaiXTClone & IBM5160 
![Alt text](../pictures/image_010.jpg)


Indicator LEDs
![Alt text](../pictures/image_006.jpg)

Top view
![Alt text](../pictures/image_004.jpg)

TLDR;
8088 Turbo 8Mhz motherboard IBM5160/5150/PC-XT Compatible with static memory.


It cannot really be called clone since it's a fundamentally different design from the original IBM5160.

This is a Turbo 8Mhz board PC/XT compatible with static RAM and delayed DMA clock signal.

The board was built with a view to reduce component number yet keeping the PC XT era feeling.

There are plenty of areas of improvement like replacing ROM decoder logic with GAL/PAL, the circuit is already there for this very purpose.

Also the board has above 1MB of RAM and the existing PAL can be programmed to use this memory as extended memory (few mod required for bank switch usage), since it's little anyway it has been left as enhancement.

640Kb is available for use for now.

Another goal of the board is to become a test bench for new designs and since it's a brand new build, one does not have to test things into original boards, being clone or original those boards today are hard to find and becomeing more expensive.

So to assemble the board all you need is Ali Express or Ebay (not afiliated) or just another way to find TTL ICs.

Inspiration for this board came from the famous Taiwanese clones produced around 1987, turbo boards :)

The BIOS is  a fork with modifications from Anonymous BIOS and it should be compatible with other bios that do not care about Parity Check.

Parity check has been removed from the circuit and there are other differences from the original IBM5160, some listed below:

- Clock for timer  
- Speaker circuitry
- DRAM Refresh
- Bus arbitration circuit
- DMA Clock
- Keyboard clock
- Reset Circuit
- J8 slot removed and J7 is gone too.
- 6 slots is a great number and should keep costs down too. Rarely more than 5 are used anyway.

Just like every turbo XT board it has the capability to switch turbo and normal operation without buttons, by pressing ctrl+alt+ + or -.

And other differences making this a unique design.

On the back of the DRAM to SRAM conversion some logic gates were left unused and they became LED drivers for some LED onboard. They look super cool IMO.

This board would not be possible without the effort made Madcat by found at https://github.com/madcatse, I understand Madcat used some kicad components from MTM Scientific, so I printed some thanks to him too as he released his IBM 5150 design to the public.

For future work, I see the work done By Tedd on Microcorelabs the most promising on Software defined ISA cards since his choice of a high speed devices, as such this board is prepared to receive the first software defined 386SX processor emulated in SW. Are you up for the challenge? I tested the SW defined v20 processor and 8088 and it works here too!

I see XTMax project and the V20 drop in replacement as one of of a kind and literally removing hardware boundaries from the PC XT era.

I have included the source code for the PLD ATF16V8 there too, see CODE.PLD for details. Few more equations and a 74LS138 and some other chips can be replaced too for ROM address match.

Why Dubai Xt clone? The board was designed in Dubai :)

I had great pleasure designing, studifying existing clones and creating this board as the board I wanted to have.

I hope you enjoy too.

Felipe Spencer Picada
The creator of the DubaiXTClone 8088 PC/XT Compatible Motherboard

Running Windows 3.0
![Alt text](../pictures/image_011.jpg)


close ups
![Alt text](../pictures/image_009.jpg)

processor and latches
![Alt text](../pictures/image_007.jpg)

Leds
![Alt text](../pictures/image_006.jpg)

Designed in UAE
![Alt text](../pictures/image_005.jpg)

top view
![Alt text](../pictures/image_004.jpg)

running diagnostics
![Alt text](../pictures/image_003.jpg)

coming from production
![Alt text](../pictures/image_001.jpg)


