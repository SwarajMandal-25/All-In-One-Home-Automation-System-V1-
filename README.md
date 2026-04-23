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
