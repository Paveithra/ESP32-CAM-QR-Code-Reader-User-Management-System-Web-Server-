**Step 1:** Save all the html and css file in the same folder including the ESP32 cam code file

**Step2:** Then, make sure that your ESP32 have littlefs installed. If not do the following.  Go to the releases page and click the .vsix file to download.On your computer, go to the following path: C:\Users\<username>\.arduinoIDE\. Create a new folder called plugins if you haven’t already.Move the .vsix file you downloaded previously to the plugins folder (remove any other previous versions of the same plugin if that’s the case).

Restart or open the Arduino IDE 2. To check if the plugin was successfully installed, press [Ctrl] + [Shift] + [P] to open the command palette. An instruction called ‘Upload Little FS to Pico/ESP8266/ESP32‘ should be there (just scroll down or search for the name of the instruction).

**Step 3:** Then download the libraries ESPAsyncWebServer by ESP32Async and AsyncTCP by ESP32Async

**Step 4:** Make sure you format your microSD card as FAT32.

**Step 5:** Then Upload the Code to ESP32Cam. Note that all the html and css code files are included in the Code which is being uploaded to ESP32 Cam

**Step 6:** Now you can use the cam module to have the proper QR code reader which can be used as a attendance system
