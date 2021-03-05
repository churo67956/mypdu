Drivers and configuration files for driving a USB-connected Arduino based PDU.

lavapdu.conf - overall pdudaemon config file where you declare what PDUs are connected
localbase.py - locally connected PDU base class
localcmdline.py - driver for command line controlled PDU
strategies.py - declares what drivers are defined
relay-ctrl.py - command line utility to talk to the Arduino 
