PumpDoublify
========
Huge thanks to Boxx for writing the original 4 panel -> 8 panel converter, this tool is a small modification for making pump doubles charts, with lots of tweaking done to generate (hopefully) comfortable patterns.
## Features
- Converts 4 panel charts to 10 panel.
- Can batch process recursive folders of songs.
- Removes old autogen charts so you can re-doublify charts when a new version comes out.
- Skips charts which have non-autogen double charts so you can doublify your whole Songs folder and you won't lose anything.
- Generates patterns suitable for stamina & footspeed.

## Issues
- Quads & triples will be converted to jumps.
- Holds & rolls are included but don't affect pattern generation, so this can lead to double steps.
- Footswitches will be converted to jacks.
- Does not distinguish between jumps & 1-foot brackets. All will be converted to jumps.
- An all-jump section will not move across the pads.
- Jump patterns are not ideal.

## Usage
- Currently only Windows is supported.
- Install python 3.8 or higher (tested with 3.10): https://www.python.org/downloads/
- Depending on the installation, "python" in pumpdoublify.bat might need to be replaced with "py"
- In File Explorer, drag a folder or simfile onto pumpdoublify.bat
- Wait for the message "Press any key to continue . . ." to appear. This may take a while if there are lots of songs.
- Press any key
