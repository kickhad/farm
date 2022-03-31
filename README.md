Clone into /OctoFarm

Setup virtualenv
>>> cd octoprint
>>> bash setup.sh

Install systemd services:

>>> sudo cp services/*.service /etc/systemd/system/

Udev rules:
>>> cat 99-usb.rules > /etc/udev/rules.d

