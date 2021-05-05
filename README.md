Domoticz python plugin for HoneyWell HIH7000 series I2C humidity / temperature sensors


Status
------
Under development. Requires domoticz hardware-timeout to be set to 1 min. 

Prerequesites
-------------
An FTDI USB-I2C module (for example FT232h)

Limitations
------------

Install
-----------
in folder domoticz/plugins  :
git clone https://github.com/nijmeijer/domoticz_hih7000_i2c_ftdi hih7000_ftdi
This will create a folder named hih7000_ftdi, containing the file "plugin.py" as expected by domoticz

Restart domoticz, and add the new HARDWARE.




