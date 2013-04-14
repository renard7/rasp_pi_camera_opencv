rasp_pi_camera_opencv
=====================

Sample code for using the Raspberry Pi camera with OpenCV

Tested on Raspbian Wheezy release on original Model B.

To setup camera:

sudo apt-get update
sudo apt-get upgrade
sudo apt-get install git-core
sudo wget http://goo.gl/1BOfJ -O /usr/bin/rpi-update
sudo chmod +x /usr/bin/rpi-update
sudo rpiupdate

Edit /boot/config.txt and add these two lines at the end:

start_file=start_x.elf
start_fixup=fixup_x.dat

Reboot.

To install OpenCV:

sudo apt-get install libopencv-dev python-opencv


