Lenovo Thinkpad Yoga Scripts and Drivers for Ubuntu
===================

* run-chrome 
	Runs chrome with support for the Yoga's touchscreen, comes with the google-chrome.desktop file you would put in /usr/share/applications/

## Thouchpad fix
By default on my yoga 2 pro it's really hard to use the touchpad. When you tap it, the pointer moves a bit so you will often miss your target. Adding the file "50-synaptics.conf" to the folder /etc/X11/xorg.conf.d/ solved the problems for me. If the folder xorg.conf.d/ doen't exist, just create it.
