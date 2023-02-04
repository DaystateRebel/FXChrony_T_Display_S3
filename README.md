# FXChronyDisplay For TTGO T-Display-S3

1. Download and install Arduino:
https://www.arduino.cc/en/software

2. Add the ESP32 Board definitions

File | Preferences | Additional Board Manager URLs

Add this to the list

https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json

3. Get the OpenFontRender Library

Go here: https://github.com/takkaO/OpenFontRender

Click the green code button and download the OpenFontRender-master zip

Open that .zip and extract the folder to you Arduino libs directory. Rename it OpenFontRender

4. Get the sketch

https://github.com/DaystateRebel/FXChrony_T_Display_S3 

Click the green code button and choose download Zip. Unzip the file somewhere

5. Get the TTGO T-Display TFT_eSPI library 

Open the lib/TFT_eSPI.zip and extract the TFT_eSPI directory to you Arduino libs directory.

6. Start Arduino, click File | Open and navigate to the FXChrony_TTGO_v1.1 directory. 
Select the FXChrony_TTGO_v1.1.ino file

7. Install the OneButton & PNGdec library
Click Sketch | Include Library | Manage Libraries ...
Use the "Filter your Search" to search for and install "onebutton"
Repeat for "PNGdec"

8. Select the hardware: Tools | Boards Manager ... | esp32 | ESP32-S3 Dev Module

9. Select the serial port your TTGO T-Display-S3 is connected to

10. Click the Arrow button to build and flash the software
