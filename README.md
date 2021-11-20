# Arduino-Serial-Sender
This code is what allows the connection between the Arduino and Computer. This code gets the status from the server and sends it via terminal to an Arduino.

## Important Information:

This code is limited to use data up to 999, further than that will raise an error. This is a work in progress and it is to be solved.

## Installation Guide:
1. Download the lastest version from releases in this repository or clone the repository using the following command:
```
git clone https://github.com/Shaking-Hands-Overseas/Arduino-Serial-Sender
```
2. Install Necessary Dependencies using pip and the included requirements file:
```
pip install -e requirements.txt
```
or install manually:
```
pip install pyserial
```
3. Connect your Arduino to your computer and through the Arduino IDE find the Serial Port.
Also I recommend using my arduino firmware, but feel free to use whatever you prefer.

4. Open the code via your text editor and specify on the URL Variable your API URL

5. Go to the cnt_index and change it accordingly to your data.

6. Go to the num variable, where the string that will be sent to the arduino is created and modify it according to your data.

With the above should work just fine. For

## Todo List for next Versions:
· Simplify the way in which the API settings are used into a single JSON File
· Add Support for Longer Numbers than 999
