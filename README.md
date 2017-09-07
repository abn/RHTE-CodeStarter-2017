# RedHat-CodeStarter-RHTE APAC 2017

## Get Started:
Download the Presentation at: https://goo.gl/WYDoi6

### On your host PC:
 - Install Virtual Box from here: https://www.virtualbox.org/wiki/Downloads selecting the proper distribution, depending on your host operating system and architecture;
 - Download the CodeStarter VM from here: https://s3-us-west-2.amazonaws.com/kura-repo/RedHatSummit/vagrant_codestarter_default_v3.ova
 - Start your Virtual Box installation and import the downloaded VM image by selecting the Import Appliance option from the File menu. When importing, please remember to reset the VM MAC address by clicking on the proper option;

### On your Raspberry Pi:

- Connect the sensors and actuators following what described in the following table:

| Component Name          | GrovePi+ Connector      |
| ----------------------- | ------------- |
| Grove - Red LED         | D4            |
| Grove - Buzzer          | D6             |
| Grove - Digital Light Sensor               | I2C-2             |
| Grove - Water Sensor                | D2             |
| Grove - Mini Fan v1.1                | D3            |
| Grove - Temperature&Humidity Sensor (SHT31)              | I2C-1             |

- Start the Raspberry Pi

### Start the VM and test the emulated environment
At this point you can start your VM and, following the slides, create your own Wire graph experimenting with the simulated PLC running in your VM.

For Complete instructions, code used for CodeStarter at Summit: https://github.com/eurotech/RedHat-CodeStarter-2017/tree/opcua-server-grovepi
