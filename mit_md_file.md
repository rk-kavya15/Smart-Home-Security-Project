ANUJIT JENA

119EI0280

EC-3712 Product Development Laboratory

Title:

SMART HOME SECURITY WITH AUTOMATIC PHONE CALLING

AND IMAGE SENDING SYSTEM USING ARDUINO WITH IOT

Developed By:

ANUJIT JENA

119EI0280

SOURAV RANJAN SOHALA

119EI0295

NITISH KUMAR SONKAR

119EI0296

Report By: Anujit Jena

ANUJIT JENA

119EI0280

Abstract:

This project is about a smart reliable and robust smart security system

that can notify us when someone breaks into our home or shop.

It works as follows-When someone breaks into the home or shop, the

owner automatically gets an image notification on his or her phone.

Also the device has the facility to call a specific number (say cops) upon

detecting unusual activity.

Objectives:

Burglary and break-ins have become quite common in certain areas,

especially during these challenging times. But with our busy lives, it is

not possible to monitor it 24\*7. So, we need a more reliable and robust

smart security system that can notify us when someone breaks into our

shop or home.

This can be of great use in commercial establishments as well. When a

thief enters a jewellery shop, the shop owner automatically gets a

notification on his/her phone. Also, the device can automatically call the

cops instantly and notify as many persons as we want.

Thus, providing security, especially when there is no scope for physical

monitoring is one of the basic objectives of the project.

ANUJIT JENA

119EI0280

System Model:

ARDUINO UNO

BLUETOOTH HC

05

PHONE

PIR MOTION

SENSOR/CAMERA

ACTIVITY

ANUJIT JENA

Circuit Diagram:

119EI0280

ANUJIT JENA

Components(procured):

1. Breadboard and Jumper wires

1. PIR Motion Sensor

119EI0280

ANUJIT JENA

1. Arduino Uno Board

1. HC-05 Bluetooth Module Master Slave

119EI0280

ANUJIT JENA

119EI0280

1. Smartphone to be used for image capturing

ANUJIT JENA

119EI0280

Hardware:

- BREADBOARD AND WIRES
- PIR MOTION SENSOR
- ARDUINO UNO
- BLUETOOTH HC 05
- SMARTPHONE (CAMERA) BATTERY





Software:

- ARDUINO IDE
- MIT APP INVENTOR

Arduino Coding:

-> First of all, take a variable for motion

sensor pin. Here we have used Arduino

digital pin 7.

ANUJIT JENA

119EI0280

-> After that create a set-up function and

set the Bluetooth baud rate (here we have

used baud rate 9600) and set the pin mode

for PIR sensor as input.

-> Then in the next part of the code, create

a loop function and under that create an ‘if

condition’ that checks the status of motion

detection by PIR sensor. When the PIR

motion sensor detects any human motion,

the Arduino sends a number over Bluetooth

to our Android app created.

Arduino code sample:

ANUJIT JENA

119EI0280

The app:

u

The app is built using MIT app inventor.

u

App Inventor is a cloud based tool, using

which means we can create apps for

phones right in our web browser.

u

The Designer is for creating the app's

interface:

u

The Blocks Editor lets us program the

app's behaviour by putting blocks

together:

u

At last, the app can be shared as source

code (.aia) that can be loaded into App

Inventor and remixed. Or, it as an

executable (.apk) that can be installed on

a device.

ANUJIT JENA

119EI0280

How it works?

u When the PIR motion sensor and

camera(cell-phone camera) detects any

human motion, the Arduino sends a number

and the image captured by the camera over

Bluetooth to our Android app.

u Now, whenever intrusion is detected,

arduino will send a number and the

image/images captured to the app and the

app will automatically call on the phone

number and simultaneously send the photo

to the user over whatsapp/ email.

u Next, it is upto the user to take a proper

action if the intrusion is genuine or ignore it

if it’s some animal movement or similar

stuff.

ANUJIT JENA

119EI0280

Progress:

Circuit building

Order was placed for items unavailable nearby and procurement of

remaining from local shops, mean while learning Arduino IDE was

procured from online sources.

After the arrival of items ordered one by one, a camera module was

to be added to our project, as per the feedback from the instructors.

Various means to connect smartphone camera and ways to trigger it

were pondered upon.

Thereafter, individual components were tested, one defective

product replaced.

A basic circuit experiment was performed to detect motion and

trigger LED with a message on serial monitor along with successfully

connecting to the Bluetooth of the app under progress.

Currently, various applications to trigger smartphone camera shutter

through Arduino, upon motion detection by PIR Sensor are being

looked out for. With this being done, we will be reaching to the

completion of project.

ANUJIT JENA

Results so far

119EI0280

ANUJIT JENA

Arduino Code:

119EI0280

ANUJIT JENA

119EI0280

Progress in the app:

Components of the app:

Function of the various components:

Screen 1: Holds the visible components

ANUJIT JENA

119EI0280

Vertical Arrangement 1: To hold the various visible

components in place in the app interface.

List Picker1: Holds the list of the Bluetooth devices paired

with the smartphone on which the app is to be used. This is

used to connect the direct the Bluetooth client to connect to

the required Bluetooth device.

Label1 & TextBox1: Display the status of connection with the

Bluetooth.

Label2 & TextBox2: Display the phone call status.

Label3: Displays whether a phone number has been set for

calling or not.

Non-visible components

Bluetooth Client 1: Used to connect the Bluetooth HC 05

module to the device so that it can transmit the necessary data

across the Arduino and the application.

Phone Call1: Used to dial to the registered number, if

triggered.

ANUJIT JENA

119EI0280

Clock1: Set a delay/ timer for phone calls.

Sharing 1: Used for transfer of the image/ video clip of the

suspect to the required device using any medium of

choice(email/ whatsapp/ text).

Camera1: Used to control the camera in the device since the

cell-phone camera is to be used to capture image of the

suspect.

Camcorder 1: Used to capture a short clip of the break-in.

Code:

➔ Code to set Listpicker1 with the names and addresses of available

Bluetooth devices.

➔ Code to connect to the HC05 blue-tooth module after pairing and

selecting the device from the list of available devices.

ANUJIT JENA

➔

119EI0280

Code to make the phone call

➔ Code to display status of phone call

➔ Sample code to connect the app via Bluetooth to the HC05 module(Tried

and tested on the HC05 module)

ANUJIT JENA

119EI0280

➔ Sample code to share the image of the intruder and make a phone call if

manually trigerred.( Tried & tested!)

ANUJIT JENA

119EI0280

Snapshots of the app interface:

The main screen

ANUJIT JENA

119EI0280

The sample app for connecting the HC05 to the device

using Bluetooth.

Has been tested on the HC05 module and works perfectly.

ANUJIT JENA

119EI0280

Sample app to make phone call and share image in case of a trigger.

Here, it has been triggered manually but in the final app, it will be

triggered automatically.

ANUJIT JENA

119EI0280

ANUJIT JENA

119EI0280

The future of smart homes:

Homes are things we own that we can interact with a lot

more, and from a distance too! ‘’Smart homes’’ refer to smart

home devices like the Philip hue lights you can automate and

control using Wi-Fi/BLUETOOTH.

The onset of COVID-19 accelerated the adoption of the

smart home. Due to the pandemic, people are spending

most of their time at home. Trends such as working from

home, education from home, shopping from home, and

healthcare from home, are driving the consumer adoption of

technologies such as remote monitoring, video conferencing,

vital signs monitoring and more. While COVID-19 has

significantly reduced consumer spending on travel and

hospitality, the savings from unspent holiday money is going

into home improvement projects, making homes smarter

and more comfortable.

As security is one of the key features of a safe household,

this project is a step in the similar direction!



