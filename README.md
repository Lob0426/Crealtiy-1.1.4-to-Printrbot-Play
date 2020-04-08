# Crealtiy-1.1.4-to-Printrbot-Play
A firmware and configs to use a Creality 1.1.4 board in a Printrbot Play

UNTESTED as yet.

The Creality 1.1.4 Board can be used in a Printrbot Play to replace a inoperable printrboard. The connectors have to be switched
from Molex and Dupont connectors to JST-XH. There is a set of adapters called "Adaptrboards" in development that will make this 
easier as they adapt from Molex/Dupont to JST-XH and adapt the inductive probe without hacveing to mess with the connectors.
Unfortunately the Creality board storage is too small to allow a bootloader to be installed and keep features enabled. This means
You will have to use a device to upload the firmware to this board.

There is no real advantage to switching to this board other than you may find one you can get for Free, to revive a down and out
printrbot Play The SKR Mini E3 V1.2 board is a whole lot better board and actually cheaper than the Creality 1.1.4 or the 1.1.5 boards.
The SKR board is easy to install firmware too as it has a bootloader and only requires the firmware.bin be copied to an SD card. 
This is the Adaptrboard set was designed for,but the boards are near twins in layout, size and connectors. The SKR has extra's over
the stock boards and is 32bit, 256K (512K undocumented), this versus the b bit, 128K on the 1.1.4 and 1.1.5.
