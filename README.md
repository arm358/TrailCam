# TrailCam
Open-source Trail/Rock camera. See the trail or road in front of you or position the camera near the lowest clearance parts of your vehicle for peace of mind when offroading.


## Features
- Access camera stream from any smartphone
- Standalone WiFi access point - no internet connection required
- Change resolution, filters, and other options direct from UI

## Parts
- ESP32 Camera Board <a href="https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_1?crid=1A2R6HYT898FH&keywords=esp32%2Bcam&qid=1644586486&sprefix=esp32%2Bcam%2Caps%2C120&sr=8-1&th=1">(such as this board sold by Amazon)</a>
- A camera case <a href="https://www.thingiverse.com/thing:4192843">(such as this 3D printed case)</a>
- 5V power supply (this will differ depending on where you install it)

## Installation and Setup
1. Clone the repo and open the TrailCam.ino sketch in the Arduinio IDE
2. Make sure you have the ESP32 Board Manager installed and select the AI Tinker board
3. Upload the sketch to the board.
4. Install the board into the housing and power it based on your use case.

## Usage

1. Connect to the TrailCam WiFi network (open credentials)
2. In a browser, navigate to `192.168.4.1`
3. Click the gear icon to change the settings
4. Click the "Start Stream" button to view your camera stream


