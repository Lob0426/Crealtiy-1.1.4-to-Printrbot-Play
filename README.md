# Crealtiy-1.1.4-to-Printrbot-Play
A firmware and configs to use a Creality 1.1.4 board in a Printrbot Play

UNTESTED as yet. WORK IN PROGRESS, use at own risk.

The Creality 1.1.4 Board can be used in a Printrbot Play to replace an inoperable printrboard. The connectors have to be switched
from Molex and Dupont connectors to JST-XH. There is a set of adapters called "Adaptrboards" https://github.com/Printrbot/Adaptrboard in development that will make this easier as they adapt from Molex/Dupont to JST-XH and adapt the inductive probe without having to mess with the connectors.Unfortunately the Creality board storage is too small to allow a bootloader to be installed and keep features enabled. This means you will have to use a device to upload the firmware to this board. It also means a very limited update path for firmware. Marlin features and updates are coming out all the time and they will not fit on a stock board!

There is NO advantage to switching to this board, other than you may find one you can get for Free, to revive a down and out
Printrbot. The SKR Mini E3 V1.2 board is a whole lot better board and actually cheaper than the Creality 1.1.4 or the 1.1.5 boards.
The SKR board is easy to install firmware to as it has a bootloader and only requires the firmware.bin be copied to an SD card. 
This is what the Adaptrboard set was designed for, but the boards are near twins in layout, size and connectors. The SKR has extra's over
the stock boards and is 32bit, 256K (512K undocumented), this versus the 8bit, 128K on the 1.1.4 and 1.1.5.

Note:
The SKR Mini5.stl is the one I finally used. It is a printable adapter plate from printrboard to SKR MINI. It orients the board 90degrees to the original board position. It lines the MicrSD on the board with the SD port in the Play chassis. This allowed me to use a Stock "CR10" LCD display where you need to use the onboard SD card to load files. The recommended TFT displays have USB and SD ports on them so this is not necessary to do for them. For the TFT displays you can use SKR Mini3.stl, but if you want to update firmware you will have to find a way to get to the MicroSD onboard to carry out that update. I recommend using the SKR Mini5.stl!

You will have to use Arduino IDE to compile this as there is not a PlatformIO file for it. You have to install the Sanguino boards to compile. I have included the file for this here.
