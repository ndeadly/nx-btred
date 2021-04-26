# nx-btred
nx-btred is a Bluetooth audio driver/redirector for Switch.

It uses the audrec:u service to record game audio, and then outputs it on the new audio bluetooth driver introduced in firmware version 12.0.0.

## ⚠️ Warning ⚠️
YOU USE THIS AT YOUR OWN RISK. Not every headphone brand has been tested. There may be really loud noise. Be careful, start out with a low volume, and then increase, if you like. In case of any type of malfunction, the sound will stop immediately if you hit the power button.

## Installation
1. Install firmware 12.0.0+.
2. Install latest [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere/releases/).
3. Install latest [MissionControl](https://github.com/ndeadly/MissionControl/releases/tag/v0.5.0-alpha).
4. Download nx-btred and unzip to your SD card.

## Usage
1. Enter the homebrew menu.
2. Launch the btpair application.
3. Press X to scan.
4. Select your headphones and click A.
5. Wait for it to pair.
6. Enjoy!

## Limitations
Due to a limitation of the audrec:u service, only games audio can be recorded (not the system applets).

## Thanks
Thanks to ndeadly, SciresM, yellows8 and the rest of the Switchbrew crowd
