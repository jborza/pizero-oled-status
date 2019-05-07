# pizero-oled-status

A status display for Raspberry Pi (Zero)
Using Adafruit 128x64 OLED display

Installation:
1. Enable i2c with `sudo raspi-config`
2. Install libraries with `sudo apt-get install -y python-dev python3-dev python-imaging python-smbus i2c-tools`
3. Install adafruit oled library: `git clone https://github.com/adafruit/Adafruit_Python_SSD1306.git`
4. in the library folder run `sudo python3 setup.py install`
5. set this script to run at boot time
