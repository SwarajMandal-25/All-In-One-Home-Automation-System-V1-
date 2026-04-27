# All-In-One-Home-Automation-System-V1-
## All In One Home Automation System (V1)

##### Required Softwares 
- Arduino IDE (PC/ MAC/ LUNUX)
+ ESP RainMaker (Android/ IOS)
+ Optionals: Google Home, Amazon Alexa

##### Required libraries
 **ESP32** (boards package version:2.0.4) https://dl.espressif.com/dl/package_esp32_index.json
- DHT library(Version: 1.4.3) https://github.com/adafruit/DHT-sensor-library
- Sleep Timer library(Version: 1.0.0) https://github.com/kiryanenko/SimpleTimer
- Ace Button library (Version: 1.9.2) https://github.com/bxparks/AceButton


## Configuration
Download and instal Arduino IDE. Open Arduino IDE and go to files and then preferences, copy and paste the ESP32 board package version link (Provided in the required libraries section) in the additional boards manager url section, and click **OK**.
![image]()
![image]()

And download ESP32 board library version 2.0.4.
![image]()
![image]()

Now download other three libraries, provided in th required libraries section. Now in Arduino Ide go to 'Sketch' tab and then click 'Include library, now add the libraries one by one. 
![image]()
![image]()

Now extract the zip file named firmare.zip, and open the 'AIO_Home_Automation.ino' file with Arduino IDE. connect the ESP32 with your PC. In Arduino IDE, go to the **Tools** tab, under **Boards:** menu, inside **esp32**, select "**ESP32 Dev Module**".
![image]()

Again go to **Tools** tab, under **Port:** select the right **COM Port** associated to your **ESP32 Board**.
![image]()

Again go to **Tools** tab, under **Partition Scheme:** select **RainMaker**.
![image]()

Now click the **Upload** button on the top left corner of the Arduino IDE.
![image]()

Now open the **Serial Monitor** by clicking the icon on the top right corner of the screen.
![image]()

Now press and hold the **EN/ Reset** button for more than **10 seconds**.
![image]()

After 10 seconds, release the button. Then on the serial monitor an URL will appair. Copy your URL and paste it in a browser search box and hit "**Enter**". You will get a QR code on the browser screen.
![image]()
![image]()

Now go to the **"ESP RainMaker App"** on your Android/ IOS device. Make sure that your Bluetooth, Wifi and Location is turned on and currently connected to a Wifi network. Tap on **Add Device"**, a QR scanner will appear. Now scan the QR code appeared on the browser using the scanner. After that it will ask for Wifi SSID & Password. Provide the same SSID & Password where your Android/ IOS device is connected. it will take some time to connect with Wifi. After connection is successful tap on the **"Done"** button.
![image]()

Now you can see all the devices are online on the Device tab.
