![Image description](https://github.com/nathalis/NesCat/raw/main/NESCAT_icon.png)

# NesCat 0.5

NESCAT by Nathalis
prototype version: 0.5 (c)2020
Enhanced version Nintendo Emulator for ESP32

Requirements: ESP32 WEMOS D1 MINI, ST7789 LCD, MICROSD CARD slot,
PCM5102 I2S AUDIO MODULE, OTHER PARTS...

Also You need disable fix PSRAM cache: 
in file (for example): C:\Users\ {MYUSERNAME} \AppData\Local\Arduino15\packages\esp32\hardware\esp32\1.0.3\boards.txt

```shell
#esp32.menu.PSRAM.enabled.build.defines=-DBOARD_HAS_PSRAM -mfix-esp32-psram-cache-issue
esp32.menu.PSRAM.enabled.build.defines=-DBOARD_HAS_PSRAM
```

**INFO: I am preparing new version, coming soon. (we made 6 versions over year, I say more later)**

NESCAT1.0_ESP32 project: (Due to increased popularity of NesCat 0.5 project, I remastered old version of NESCAT 1.0 project.)
https://github.com/nathalis/NesCat1.0_ESP32

LINUX VERSION HERE:
https://github.com/nathalis/NESCAT_LINUX

### FEATURES:

- MicroSD card support
- 240*240 1.3" LCD ST7789 display (use max 40MHz SPI speed)                 
- Composite TV OUT Video PAL
- I2S AUDIO support PCM5102 module
- PS2 (USB) KEYBOARD support (wireless not work)
- huge NES ROMs up to 512kB (read from FLASH)
- PS4 DualShock BlueTooth Gamepad (experimental)

Only for personal & educational use! 

### DIAGRAM (NEW)
![Image description](https://github.com/nathalis/NesCat/raw/main/PCB/SCHEMATIC.png)
![Image description](https://github.com/nathalis/NesCat/raw/main/PCB/BOARD.png)


### IMAGES:

![Image description](https://github.com/nathalis/NesCat/raw/main/Images/001.jpg)
![Image description](https://github.com/nathalis/NesCat/raw/main/Images/002.jpg)
![Image description](https://github.com/nathalis/NesCat/raw/main/Images/003.jpg)
![Image description](https://github.com/nathalis/NesCat/raw/main/Images/004.jpg)
![Image description](https://github.com/nathalis/NesCat/raw/main/Images/005.jpg)
![Image description](https://github.com/nathalis/NesCat/raw/main/Images/006.jpg)
![Image description](https://github.com/nathalis/NesCat/raw/main/Images/007.jpg)
![Image description](https://github.com/nathalis/NesCat/raw/main/Images/008.jpg)
![Image description](https://github.com/nathalis/NesCat/raw/main/Images/009.jpg)
![Image description](https://github.com/nathalis/NesCat/raw/main/Images/010.jpg)
![Image description](https://github.com/nathalis/NesCat/raw/main/Images/011.jpg)
![Image description](https://github.com/nathalis/NesCat/raw/main/Images/012.jpg)

New version will be released soon, there is preview (we are still working on it):

![2021-11-20 at 10_11 PM](https://user-images.githubusercontent.com/52428568/150807421-afe76c12-6f6f-4a28-a477-9bc01201a1b4.jpeg)
![2021-10-08 at 19-15-54](https://user-images.githubusercontent.com/52428568/150807435-685631af-9b5e-475a-8aba-f3b9d98b91d7.jpg)

