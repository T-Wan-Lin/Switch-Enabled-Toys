# Quick Start

## System requirements (should the designated device not be used)
1. Ensure that you have Python 3.70 (and above) installed. Visit this [site](https://www.python.org/downloads/release/python-370/) to install Python (including IDLE).
2. (Only if you have to upload the Arduino code, else, skip this step) Ensure that Arduino IDE is installed on your personal computer.
3. Ensure that these 2 python modules are installed: pyserial and pynput for the program to run
4. 


## Instructions for use


 If the designated device is used,


1. Plug in the switch interface on the *RIGHT* USB port. This is the COM5 port that will be used for Bluetooth communication. Should any other USB ports be used, change the port number accordingly in the Controller.py file. To find which port the switch interface is connected to visit this [site](https://help.fleetmon.com/en/articles/2010900-how-do-i-get-my-com-port-number-windows)


2. Ensure that the computer's Bluetooth is ON and it is connected to a device named `HC-05`. Should you need a PIN to connect to the device, it is either `0000` of `1234`.


3. Ensure that the FIRST light on the switch interface module is GREEN as shown in this [picture]().

4. Run the executable file. Press the switches. Give the bot some time to receive the first signals (latency). If the executable file cannot be located, proceed to step 5.


5. Download the Controller.py file and put it in the Desktop directory (preferable). Open the file in IDLE. In the uppermost toolbar, click `Run` and in the dropdown, click `Run Module`. Should there be no errors, `Start` should be printed. Should there be errors (in red text) check if the relevant python modules are installed or if the Bluetooth connection is working. This step applies to other computers that are used other than the designated one.

6. Press the switches to move the bot. Give the bot some time to receive the first signals (latency).



## Uploading of Code 

NOTE: This section is relevant in the case the Arduino Board is forcefully reset.


Should the reset button be pressed on either the motor shield or the Arduino board, connect the Arduino Board with the black cable provided to your computer. 


Steps: 

1. Download the ENTIRE folder called `EGSC_car` from the G-Drive folder or this repository and place it in the Desktop directory.
2. Open it with Arduino IDE, which should be installed.
3. Follow the instructions provided at the top of the EGSC_car.ino file to install the libraries before the upload.
4. Select the correct board and port.
5. Upload the code. 

You may visit this (site)[https://support.arduino.cc/hc/en-us/articles/4733418441116-Upload-a-sketch-in-Arduino-IDE] for more detailed steps on troubleshooting.


Back-up code can be found in [G-Drive](https://drive.google.com/drive/folders/1xDtzrKRc55RQwkxslrCCrbxYAzH-E_bL?usp=sharing):


### Glossary
1. IDE: Integrated Development Environment
2. IDLE: Python IDE

