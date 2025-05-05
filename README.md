# ece40862-lab-5--real-time-motion-detection-system-using-esp32-thingspeak-and-ifttt-solved
**TO GET THIS SOLUTION VISIT:** [ECE40862 Lab 5 –Real-Time Motion Detection System using ESP32, ThingSpeak and IFTTT Solved](https://www.ankitcodinghub.com/product/ece40862-lab-5-real-time-motion-detection-system-using-esp32-thingspeak-and-ifttt-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94437&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE40862 Lab 5 –Real-Time Motion Detection System using ESP32, ThingSpeak and IFTTT Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

1. Overview

In this assignment, you are going to design a Real-Time Motion Detection System using the ESP32 Feather board and the Adafruit Sensor Featherwing. In addition, you will be using ThingSpeak IoT platform and IFTTT service (If-This-Then-That) and integrate with ESP32- Sensor Assembly to build this motion detection system.

One application of this system is bag theft detection. Consider that you have put the system inside your bag, kept the bag in a stationary place and you are going to workout/gym. You put the system in Armed state via Google Assistant voice commands, and the ESP32 starts detecting motion using the accleromenter sensor. As soon as any motion is detected, the system sends an IFTTT notification to your phone (on the IFTTT app), thereby alerting you of possible theft. On the other hand, you might want to disarm the system using Google Assistant when you are ready to take the bag yourself or when you are at home, as you might not want to receive unnecessary notifications. Fig. 1 shows a high-level overview of this system.

</div>
</div>
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
Use Command phrase ACTIVATE/DEACTIVATE to Update ThingSpeak Channel

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
System is Disarmed

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Check last updated Channel Value every 30s

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
IFTTT APPLET 1

Trigger Action

Voice Command:

<ul>
<li>Motion Sensor ACTIVATE</li>
<li>Motion Sensor DEACTIVATE</li>
</ul>
</div>
<div class="column">
ThingSpeak

(Server)

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
System is Armed Turn on Green LED

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Measure Sensor Data Acceleration x, Acceleration y, Acceleration z,

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
IFTTT APPLET 2

Action Trigger

</div>
<div class="column">
VALUE

= DEACTIVATE

VALUE = ACTIVATE

</div>
<div class="column">
Channel Value

</div>
</div>
<div class="layoutArea">
<div class="column">
if ANY of these conditions meet

</div>
</div>
<div class="layoutArea">
<div class="column">
X &gt; X m/s2 Y &gt; y m/s2 Z &gt; Z m/s2

</div>
</div>
<div class="layoutArea">
<div class="column">
Accel

Accel

Accel

Turn ON Red LED

</div>
</div>
<div class="layoutArea">
<div class="column">
Send Notification to IFTTT app

Notification Text

Motion Detected

Accel X, Y, Z = xxx, yyy, zzz

</div>
</div>
<div class="layoutArea">
<div class="column">
Fig 1. High level overview of Motion Detection System

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Motion Detector

(Client)

</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2. Hardware Assembly

The featherwing consists of two specific sensors from Analog Devices: ADXL343 triple-axis Accelerometer and ADT7410 precision Temperature Sensor. Both sensors are connected over the shared I2C bus. Some of the features of the accelerometer sensor are described here.

• ADXL343 is an I2C accelerometer sensor with three axes of measurements, X, Y, Z. You can set the sensitivity level to either ±2g, ±4g, ±8g or ±16g. The lower ranges give more resolution for slow movements, so are more sensitive, whereas the higher ranges are good for high-speed tracking as they have wider measurement range.

To start with this assignment, you should solder the Short Feather Male Headers (12 pin and 16 pins) with the sensor Featherwing. As shown in Fig. 2(a), the 12 pin headers should be soldered to the 12 pin breakout pads and 16 pin headers should be soldered to the 16 pin breakout pads on the featherwing. You must solder the headers to the outer breakout pad.

Before you begin soldering, remember that the short pins of the male headers should poke through the featherwing TOP SIDE. It will be easier to solder if you insert both the headers into a breadboard – LONG SIDE down. Place the featherwing over the pins so that the short side poke through the breakout pads on both the sides (12 and 16 pins) and solder all the 28 pins. More details can be found on this link (check the section ‘Soldering in Plain Headers’): https://learn.adafruit.com/adafruit-huzzah32-esp32-feather/assembly#soldering-in-plain- headers-3-7. Although this link shows soldering of headers on the ESP32 board, the instructions should be same as pins and size of the ESP32 and sensor Featherwing are the same.

Once you have successfully soldered both the headers on to the featherwing, you can directly insert it into female headers on your ESP32 board. The complete assembly is shown in Fig. 2(b). The 3V, GND, and I2C (SCL, SDA) pins of the ESP32 coincide with the same pins on the featherwing. You do not need to make additional connections between ESP32 and sensor.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
SOLDER HERE

TOP SIDE

</div>
<div class="column">
LONG SIDE

SHORT SIDE

SOLDER HERE

</div>
</div>
<div class="layoutArea">
<div class="column">
Fig 2. (a) Soldering Headers on Sensor Featherwing (b) ESP32 and Sensor Featherwing Assembly

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
3. ESP32 and Sensor Initialization 3.1. Hardware Interfacing

Interface the following components to the ESP32 board:

• Two external LEDs (red, green) as GPIO OUTPUTs.

The featherwing already has pull-up resistors attached to the I2C pins (SCL and SDA). You do not need to attach separate resistors to communicate with ESP32.

3.2. Software Initialization

Both the accelerometer sensor and temperature sensor are connected to the shared I2C bus on the featherwing. You can use the I2C driver in MicroPython (machine.I2C) to communicate with ONLY THE ACCELEROMETER sensors by constructing I2C bus on your ESP32. You do not need to use the temperature sensor. Perform the following operations:

<ul>
<li>Initialize LEDs, Timers (also Interrupts if you need).</li>
<li>Use the schematics and ESP32 manuals to create the I2C bus using proper pins.
3.3. Interfacing Sensors

I2C sensors like ADXL343 expose data using memory or register addresses. This means you can interact with sensor using both its I2C address and the address of a register or memory location in the device. Tutorials on I2C communication are available here. Check ADXL343 datasheet to understand how they expose data and the memory or register addresses to use.

3.3.1. InitializeAccelerometer

Start the accelerometer initialization process by checking the device ID (find out from the corresponding datasheet). If the device ID is inaccessible or incorrect, your program should return an error message. Upon successful checking, configure the following settings in the ADXL343 using I2C. Your program should display adequate messages on the terminal after completion of all the initialization steps. You can also use values other than recommended here but ensure that you are able to read sensor data properly.
</li>
<li>Set to 10-bit full-resolution mode for output data (X-, Y-, and Z-axis)</li>
<li>Set range to ±2g</li>
<li>Set output data rate (ODR) to 400 Hz (optional)
3.3.2. CalibrateAccelerometer

The accelerometer data needs to be calibrated before use. For instance, if your ESP32 and Featherwing assembly remains flat and stands still, output data for X and Y should be 0 m/s2 or 0 g and for Z should be 9.8 m/s2 or 1 g which is the default acceleration of gravity. Check datasheet for more details on offset calibration. Your program should display appropriate message on the terminal after completion of the calibration.
</li>
</ul>
</div>
</div>
<div class="layoutArea"></div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
4. Setup ThingSpeak and IFTTT 4.1. IFTTT Applets Setup

IFTTT stands for “If This Than That”, and it is a free web-based service to create chains of simple conditional statements called applets. This means you can trigger an event when something happens. In this lab, you need to create two different applets.

4.1.1. CreateIFTTTAccount

The first step is to setup an account in IFTTT. You can easily do this by signing up at www.ifttt.com using your email address (its free). You also need to install the IFTTT app on your phone and login, for the applets to work.

4.1.2. Applet 1

The purpose of the 1st applet is to arm and disarm (activate and deactivate) your motion detection system, as shown in Fig. 1. Creating an IFTTT applet is simple: You simply pick a trigger, or an “if this,” then pick a “then that” action. For the 1st applet, you should use ‘Google Assistant’ as the trigger and write a phrase to control your motion detection system. For example, you can use ‘Motion sensor $’ as the phrase, where $ can be either Activate or Deactivate. For the action, you should use ‘Webhooks’ to send data (in this case $) to ThingSpeak channel.

4.1.3. Applet 2

The purpose of the 2nd applet is to receive a web request from your ESP32 if any motion is detected and send a notification to your phone. In this case, you should use ‘Webhooks’ as the trigger and Notifications as the action. Whenever any motion is detected, the ESP32 should make a web request to Webhooks and pass on the accelerometer sensor values (X, Y, Z axis), which in turn should send a notification to the IFTTT app on your phone. Fig. 3 shows examples of these two applets. Fig. 4 shows an example notification received on the phone.

NOTE: You must find out how you can use Webhooks to send data to ThingSpeak (applet 1) and receive data from ESP32 (applet 2). Webhooks is used as an action in applet 1 while as a trigger in applet 2. Create the IFTTT applets accordingly. You can use the following tutorial as a guidance. Make sure to keep things simple!

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Fig 3. Example of (a) IFTTT Applet 1 (b) IFTTT Applet 2. Once you build the applets, they appear under ‘My Applets’ on the IFTTT website.

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
Fig 4. Notification received on IFTTT app on the phone

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
4.2. ThingSpeak Setup

The purpose of ThingSpeak is to act as the server, a medium of communication between ESP32 and your Google Assistant. You have used ThingSpeak in lab 4 and should already have an account. Login into the account and create a new channel “Google Assistant Data” and enable one field “sensor_state” to receive data from Webhooks you create in IFTTT applet 1.

Unlike lab4 where you posted data to channel using ESP32, here you will read data from channel using ESP32 every 30 seconds (use a Hardware Timer). You need to use your specific Read API Key to read data from your channel. You can use any MicroPython package to read data from ThingSpeak server.

4.3. Google Assistant Setup

Generally, android phones have Google Assistant installed, however, if your phone doesn’t have it preinstalled (e.g., in iPhone), you need to download it from your App/Play store, install it and login with your Google account.

5. Overall Application Workflow (Fig. 1)

The overall flow of tasks executed by your motion detection system is described here. These steps can be only performed after you have completed Section 3 and Section 4. Before proceeding forward, ensure that ESP32 has been properly interfaced with the sensor featherwing and you are able to read accelerometer readings in all 3 axes. It is highly recommended that you test each of the individual components of your system, viz., ESP32 and sensor assembly, IFTTT applets and ThingSpeak server separately before integrating everything together.

1. Give the voice command to Google Assistant: Ok Google, Motion Sensor ACTIVATE. The IFTTT applet 1 gets triggered and sends the value ‘ACTIVATE’ to the ThingSpeak channel.

2. ESP32 is working as a client and reads the last updated channel value from ThingSpeak server. As the last value is ‘ACTIVATE’, turn on the GREEN Led to indicate that system is in armed state. You can consider that your system has detected MOTION if any of the following conditions occur. Also turn on RED Led to indicate motion.

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
<ul>
<li>Acceleration in ±X direction &gt; X m/s2 i.e., back and front</li>
<li>Acceleration in ±Y direction &gt; Y m/s2 i.e., left and right</li>
<li>Acceleration in ±Z direction &gt; Z m/s2 i.e., up and down.

The 3 different axes of motion: X, Y, Z, and corresponding motions are indicated in Fig. 5.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Z Axis

</div>
</div>
<div class="layoutArea">
<div class="column">
Y Axis

X Axis

</div>
</div>
<div class="layoutArea">
<div class="column">
UP

</div>
</div>
<div class="layoutArea">
<div class="column">
LEFT

</div>
</div>
<div class="layoutArea">
<div class="column">
BACK

</div>
</div>
<div class="layoutArea">
<div class="column">
RIGHT

</div>
</div>
<div class="layoutArea">
<div class="column">
DOWN

</div>
</div>
<div class="layoutArea">
<div class="column">
FRONT

</div>
</div>
<div class="layoutArea">
<div class="column">
Fig 5. Motion Detector Axes Orientation and Motion Notations

<ol start="3">
<li>Move the featherwing assembly. ESP32 should now trigger IFTTT applet 2 and send Notification to your phone (IFTTT app) like Fig. 4.</li>
<li>ESP32 should check ThingSpeak channel every 30 seconds. If channel value is ‘ACTIVATE’, continue detecting motion and send notifications for around 1 minute. You should show that you are receiving notifications in your video.</li>
</ol>
5. Give the voice command to Google Assistant: Ok Google, Motion Sensor DEACTIVATE. The IFTTT applet 1 gets triggered and sends the value ‘DEACTIVATE’ to the ThingSpeak channel.

6. ESP32 now sees that the channel value is ‘DEACTIVATE’. Stop measuring sensor values and Turn OFF Green Led to indicate that system is disarmed now. Moving the featherwing assembly SHOULD NOT SEND any notification to your phone. You also have to show this in your video.

NOTE: You need to move the ESP32 and FeatherWing assembly by hand. You are free to choose the values for X, Y, Z m/s2 as the threshold acceleration in 3 axes to decide if there is any motion or not. You are also free to choose the Time Interval between two consecutive readings from the sensor. However, make sure to choose values such that you do not end up getting hundreds of notifications on your phone every minute.

</div>
</div>
</div>
