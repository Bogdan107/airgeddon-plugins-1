# airgeddon-plugins
Plugins for airgeddon https://github.com/v1s1t0r1sh3r3/airgeddon

# Author:     KeyofBlueS
# Repository: https://github.com/KeyofBlueS/airgeddon-plugins
# License:    GNU General Public License v3.0, https://opensource.org/licenses/GPL-3.0

### DESCRIPTION

* **Captured-Handshakes (minimum airgeddon version: 10.20):**
Put Your captured handshakes files in a directory of Your choice, then choose one of them inside airgeddon itself. Default path is plugins/captured_handshakes/HANDSHAKES_FILES

* **Custom-Portals (minimum airgeddon version: 10.20):**
Put Your custom captive portal files in a directory of Your choice. Default path is plugins/custom_portals/PORTAL_FOLDER/PORTAL_FILES.
You can have multiple PORTAL_FOLDER, then choose one of them inside airgeddon itself. Take a look at custom_portals/OpenWRT_EXAMPLE for a custom captive portal example.

* **Default-Save-Path:**
Set the default directory for saving files. Default is plugins/output/

* **Regdomain (minimum airgeddon version: 10.20):**
Set regulatory domain to affect the availability of wireless channels and txpower.
You can check the country codes database i.e. here https://git.kernel.org/pub/scm/linux/kernel/git/sforshee/wireless-regdb.git/tree/db.txt

* **Sort-Targets (minimum airgeddon version: 10.20):**
When selecting targets, sort them by one of the following value:
bssid, channel, power, essid, encryption, default

* **UI-Boost (maximum airgeddon version: 10.11):**
Make a specifc language strings file instead of using the complete one, speeding up ui.
The advantages of using this plugin are a more reactive ui (not needed in airgeddon >=10.20).
Potentially this plugin could lowering ram usage, useful in devices with limited ram memory e.g smartphones, tablets ecc..., but this is not possible with airgeddon as it is right now. I'm discussing with airgeddon's developers to make it possible. Hopefully we will get this feature, meanwhile this plugin is deprecated for airgeddon >=10.20.

### INSTALL
Simply put the .sh file of your choice in airgeddon's plugins folder.
For more detailed instructions, please refer to airgeddon's documentations here https://github.com/v1s1t0r1sh3r3/airgeddon/wiki/Plugins%20System

### USAGE
Some plugins can be configured, so please take a look at # USER CONFIG SECTION # inside the .sh file before use.

### DONATIONS
If You enjoyed my work and found it useful please give a star, You can support the project by making a donation through Paypal. Any amount, not matter how small (1, 2, 5 $/€) is welcome.
https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=EFJW5YSFSLGRU&source=url

and don't forget airgeddon too!
https://github.com/v1s1t0r1sh3r3/airgeddon/wiki/Contributing-&-Code-of-Conduct
