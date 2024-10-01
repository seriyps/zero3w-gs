# zero3w-gs (WIP)

Files and installation script for the Radxa Zero 3w to run as an openipc groundstation.

<h2>Instructions</h2>

* Use [rbuild](https://github.com/radxa-repo/rbuild) or [rsdk](https://github.com/RadxaOS-SDK/rsdk) to compile a working cli debian image for the radxa zero 3w and boot into the system.

* Establish a connection to  the internet.

  `nmtui`

  follow the on-screen steps. 


* Clone the repository and cd into the working directory.

  `git clone https://github.com/JohnDGodwin/zero3w-gs.git`

  `cd zero3w-gs/`

  Run the installation script.

  `sudo ./install-gs.sh`


***

The script will do the following:

* update, upgrade, and install some packages with apt
* install AU and EU drivers
* install wfb-ng
* install PixelPilot
* configure hotplugging of wfb-nics
* install a media server for dvr
* setup the /config directory where the user settings and scripts are stored
