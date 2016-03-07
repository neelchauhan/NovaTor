![NovaTor Logo](artwork/logo.png)
# NovaTor
Formerly TorGTK

![Screenshot](artwork/screenshot.png)

NovaTor is a frontend for Tor written in Python and GTK 3. 

## What has been done
 * Logo
 * UI via Glade
 * About box
 * Turning Tor on and off
 * SOCKS port selection
 * Log file viewing
 * Automatic log file refreshing
 * Specific entry and exit countries

## What needs to be done
 * Advanced Tor settings
 * Tor Bridges
 * More polish on documentation, README.md, etc.

## Requirments
 * A local copy of [Tor](http://www.torproject.org/) on your computer
 * Python 2 (Python 3 does not work currently)
 * [Stem](https://stem.torproject.org/)
 * [GTK 3](http://www.gtk.org/) and [PyGObject](https://wiki.gnome.org/action/show/Projects/PyGObject?action=show&redirect=PyGObject)

NovaTor has been tested on FreeBSD 10.2, Ubuntu GNOME 15.10, and Debian
Testing.

# Getting Started

Assuming if you have GTK 3, PyGObject, and Stem installed, you can clone TorGTK
and (even run it) with these following commands:

	$ git clone https://github.com/neelchauhan/NovaTor.git
	$ cd NovaTor/NovaTor
	$ ./main.py

You can also use setup.py to install it into your OS prefix (eg. /usr or
/usr/local).

## License
NovaTor is licensed under the Simplified BSD license.

## Author
NovaTor is authored by Neel Chauhan.
