## Micro Speech experient based on Arduino Nano 33 BLE Sense with Edge Impulse Studio

I know the company [Edge Impulse](https://www.edgeimpulse.com) from this book [TinyML: Machine Learning with TensorFlow Lite - Pete Warden & Daniel Situnayake](https://www.adafruit.com/product/4526), which Daniel is the co-founder. This is my experient of micro-speech using [Edge Impulse Studio](https://studio.edgeimpulse.com/) based on Arduino Nano 33 BLE Sense.

This experient recognizes Mandarin audio (with duration of less than one second) in 4 labels:
1. Forward - "前進"
2. Left - "左"
3. Right - "右"
4. Stop - "停" 

I already use the Edge Impulse Studion for training, and it generate the TinyML machine learning model and parameters into Arduino .ino files. You may download it and go straight for machine learning inference (of course, it recognizes Mandarin only.)

1. Download the file "ei-marconijiang-project-1-arduino-1.0.20.zip", but don't unzip it, as Arduino accepts the .ZIP file.

2. Launch Arduino IDE, go to menu, and select  "Sketch - include Library - Add .ZIP Library". And go to the directory where you saved the file "ei-marconijiang-project-1-arduino-1.0.20.zip".

<img src="https://github.com/marconi1964/marconi1964.github.io/blob/master/images/ArduinoAddZIP.png?raw=true" width=400>

3. Go to menu "File - Examples", and browse down to the bottom to find "MarconiJiang-project-1 Inferencing - Edge Impulse", and select the example of "nano_ble33_sense_microphone"

<img src="https://github.com/marconi1964/marconi1964.github.io/blob/master/images/ArduinoExamples.png?raw=true" width=400>

4. Upload the sketch and run it on Nano 33.

