This is a minimal standalone (not needing any Arduino stuff) implementation of @jokkebk's demo of yesteryear. Notes below apply. --Ian Daniher

Props to Joonas Pihlajamaa, Adafruit.






























TrinketKeyboard uses V-USB (http://www.obdev.at/products/vusb/) to implement USB with a bitbang technique. See the folder "usbdrv" for V-USB files.

Adafruit's Trinket and Gemma can do almost anything that V-USB can do, including USB mouse, keyboards, joysticks, gamepads, MIDI devices, and much more (including custom devices that do not fit any existing category).

Copyright (c) 2013 Adafruit Industries
All rights reserved.

TrinketKeyboard is free software: you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as
published by the Free Software Foundation, either version 3 of
the License, or (at your option) any later version.

TrinketKeyboard is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public
License along with TrinketKeyboard. If not, see
<http://www.gnu.org/licenses/>.
