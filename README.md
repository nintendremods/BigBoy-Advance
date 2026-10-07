# BigBoy-Advance
The BigBoy Advance is a variation of a Game Boy Macro, that uses the larger screen of a Nintendo DSi XL and is housed in a custom designed shell. The GBA cartridge is inserted from the top of the console (like the original GBA) and is hidden. The console uses tactile buttons like the GBA SP. Together, these features provide the ultimate native GBA playing experience.
![BigBoy Advance](Images/hero.jpg)
## Features
- Nintendo DSi XL display (~30% larger than DS Lite display)
- Game Boy Advance SP-style tactile buttons
- Top-mounted GBA cartridge
- SLA, SLS/MJF and CNC aluminium shell options
- USB-C charging port
## Buy the Kit
The BigBoy Advance electronics kit is available from my Etsy store.

[Buy the BigBoy Advance Kit on Etsy](ETSY-LINK)

## System Overview
A visual representation of the mod’s electronic architecture can be seen in the figure below.
[Image here]

The BigBoy Advance consists of three custom PCBs. They are:
-	Button PCB
-	Button Extender Flex PCB
-	Trigger Button PCB (x2)

The button extender flex PCB is soldered directly to various pads on the Nintendo DS Lite motherboard and sits flush on the motherboard. It serves as the “translator” between the button PCB and the motherboard. Its purpose is to connect various signals, including audio, buttons, status LEDs and volume levels, between the motherboard and button PCB.

The button PCB repositions components such as the buttons, volume wheel, status LED and charge port to fit into the newly designed shell for the larger screen. It contains circuitry to reroute the DS Lite lower screen signals to be compatible with the DSi XL lower screen. The lower screen FPC connector on the motherboard is connected to the button PCB via a 39-pin ribbon cable. The signal is then rerouted to the corresponding pins of a 37-pin and 4-pin FPC connector that are compatible with the Nintendo DSi XL lower screen ribbon cable configuration.

The trigger buttons PCBs are used to mount right angle tactile buttons in the correct position in the shell so that they can be actuated by the trigger buttons. These PCBs contain solder pads and are connected to the motherboard using soldered wires.
