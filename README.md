# Minecraft Randomiser

This program randomises every single image, sound, shader, and language file of a resource pack and automatically installs it into your resource pack folder.

This has been confirmed to work on Minecraft 1.13.2 & 1.14, and likely works on other versions aswell due to its safe way of randomizing files.

The default Minecraft resource pack is included by default. The images, sounds, and other files included in said resource pack are owned and created by Mojang AB and I
take no credit for creating them.

## Usage

To use, simply run `randomiser.py` in python3. Options can be viewed using `randomiser.py -h`

### Examples

`python3 randomiser.py -h` - Get the program's help and list of options.

`python3 randomiser.py --pack faithful` - Randomises the resource pack from the "faithful" folder.

`python3 randomiser.py --notextures --nosounds --pack faithful` - Randomise everything except the textures and sounds from the resource pack in the "faithful" folder.

## Bugs

Please report any bugs you experience, especially on Windows and Mac, as neither have been tested. Feature requests are also allowed.
