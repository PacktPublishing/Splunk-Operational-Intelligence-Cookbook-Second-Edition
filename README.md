# Splunk-Operational-Intelligence-Cookbook-Second-Edition


This is the code repository for [Splunk Operational Intelligence Cookbook Second Edition] (https://www.packtpub.com/big-data-and-business-intelligence/splunk-operational-intelligence-cookbook-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781785284991), published by Packt. It contains all the supporting project files necessary to work through the book from start to finish.
## Detailed installation steps (software-wise)
The steps should be listed in a way that it prepares the system environment to be able to test the codes of the book.
*	Splunk Enterprise 6.1.2
   Register for an account at www.splunk.com and download Splunk Enterprise based on your operating system.

   ## Linux RPM:
     * Move the downloaded rpm file into an appropriate directory and install it using rpm -i <splunk package>.rpm
     *	Splunk is installed in the /opt directory by default, change to the Splunk bin directory
     *	Start Splunk and tell it to accept the license ./splunk start --accept-license
     
   ## Linux Debian DEB:
     *	Move the downloaded deb file into an appropriate directory and install it using dpkg -i <splunk package>.deb
     *	Splunk is installed in the /opt directory by default, change to the Splunk bin directory
     *	Start Splunk and tell it to accept the license./splunk start --accept-license
     
   ## Mac OS X:
     *	Move the downloaded .dmg file into an appropriate and double click it
     *	After the finder window opens, double click on splunk.pkg
     *	Click Continue
     *	Click Continue
     *	Click Install
     *	Click Finish when Splunk has completed the installation. A shortcut will also appear on the desktop
     *	Double click the desktop icon
     *	Click OK to let Splunk initialize itself
     *	Select Start and Show Splunk
     
   ## Windows:
     *	Move the downloaded .msi file into an appropriate and double click it
     *	Click Next
     *	Select “I accept the terms in the license agreement” and click Next
     *	Click Next
     *	Click Next
     *	Click Next
     *	Click Next
     *	Click Install
     *	When finished the Installation complete panel will display. Splunk will automatically start
     
## Notes:
*	After starting Splunk you will be able to access it using a web browser at http://localhost:8000
*	The default credentials are username: admin password: changeme (Splunk will prompt you to change these on your first login) 



 
 ## Related Redis books and videos

* [Mastering Splunk] (https://www.packtpub.com/big-data-and-business-intelligence/mastering-splunk?utm_source=github&utm_medium=repository&utm_campaign=9781782173830)
* [Splunk Developer's Guide - Second Edition] (https://www.packtpub.com/big-data-and-business-intelligence/splunk-developers-guide-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781785882371)
* [Splunk Essentials - Second Edition] (https://www.packtpub.com/big-data-and-business-intelligence/splunk-essentials-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781785889462)




