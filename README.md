# Hardware

	- Intel Edison
	- Sparkfun Base Block

	![Intel Edison](https://raw.githubusercontent.com/calvernaz/edison/master/IMG_20181224_140922.jpg)

# Flash the device

*	https://software.intel.com/en-us/flashing-firmware-on-your-intel-edison-board-linux

	-  sudo dnf install dnf-util
	-  sudo ./flashall

- Alternatively, you can try balenaOS

* https://www.balena.io/docs/learn/getting-started/intel-edison/nodejs/

# Connect

	- sudo screen /dev/ttyUSB0 115200

# Wifi

	- configure_edison --wifi

# SSH

	- configure_edison --password
