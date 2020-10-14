# A list of my used devices in Smart Home with Home Assistant

I write this to bring some knowhow to beginers and intrested people. 
They are a lot of youtube videos available, but a description howto build a SmartHome based on different vendors and techniques are not available.

If you have questions during or after reading, feel free to contact me on facebook messanger or mail

mailto:smarthome_for_all@amrhein.info

Facebook: amrheing

What i love at HomeAssistant is too merge all the differend sensors and actors together. 

Normally we use the HomeAssistant Compagnion App on our iPhones to controll the House.
In addition we can use the SmartHome sith Siri and Google

Therefore they is a HomePod and 2 Google minis in place.

i use a raspberry 4 with an msata ssd and docker for HomeAssistant and deConz

- Raspberry Pi 4 with 4GB Ram
- Geekworm Raspberry Pi 4 mSATA Shield
- Transcend Highspeed 128GB interne mSATA SSD SATA III 

optional:
- ELUTENG 80mm Lüfter mit L/M/H 3 Geschwindigkeit 5V USB Ventilator Leise 
- Anker PowerPort Speed 5, 63W 5 Port US
- Für Raspberry Pi 4 Model B & Raspberry Pi 3 B + Gehäuse 4 Schichten Transparent 
  as i have 4 raspberry in total
- GHT HDMI KVM Switch USB 4 Port
- Perixx PERIDUO-212 DE, Mini Tastatur und Maus Set
- ETEPON 10,1 Zoll Monitor HDMI für Raspberry Pi 4B 1024 x 600 HD LCD Display
- Fundro Für Samsung Galaxy S8 USB C Kabel 0.3m
- Anker Powerline+ Micro USB (0,3 m / 30 cm)


when using the msata as usb 3 device it is necessary to use a usb extension cable for the zwave and zigbee sticks.
otherwise they do not work

- deleyCON 1m USB 3.0 Super Speed Verlängerungskabel
- Sigma Designs Controller Z-Wave Plus USB-Dongle
- ConBee II 

# Shelly

for the most switches i use shelly devices. https://shelly.cloud

i do not use sensors from shelly. 
The window sensors are too big and the smoke sensor was not deliverd in time i needed

The H&T (also with usb power) and also the water sensor goes offline when they are not deliver data to increase the battery live. Then there is a offline state in HA what i do not like.

- Shelly 1
- Shelly 1 PM
- Shelly 2.5 for shutters, sunblind, double switches
- Shelly Dimmer
- Shelly 1 Temperarture Sensor Addon
- IGRMVIN 2 Stück Temperatursensor Wasserdicht Temperaturfühler Edelstahl 


# Zigbee

my first Smart Home device was a Philips Hue bulb. 

Now i am totally migrated to deConz from Dresden Elektronik

https://www.phoscon.de/de/conbee2

The controller is installed as Docker container

- Aqara ZigBee Version Window Door Sensor ordered at Amazon or Bankgood
- Aquara Water Sensor
- Aqara Smart Motion Sensor
- Aqara Smart Wireless Switch
- Xiaomi Intelligent Human Sensor
- Xiaomi Temperature and hunidity sensor
- aquara wireless Smart Switch - double and single switch versions
- philips hue bulbs
- innr bulbs
- tint bulbs , sometimes available at Aldi Süd

# zwave

the zwave controller is integrated in Home Assistant

we are living in a big house with 3 floors and a cellar. 
Not too break the communication is a big step in the mesh networks
Therefore i use Smart Plugs to increase the distance

- FIBARO WALL PLUG FGWP-102

The smoke detectores was a big challange to find.
We wanted somethiing nice and also with addon functionality
The Fibaro sensors are evry small and looks excellent 

- Fibaro SMOKE SENSOR FGSD - ordered at notebooksbilliger.de

Heating Control

for heating purposes i use the eurotronics thermostats
also i have a danfoss thermostat in wc

- Eurotronics zwave spirit
- Danfoss DAN_LC-13

he controlling for them i have written the python scripts here in my repositorys

other sensors:

- NEO COOLCAM NAS-PD02Z - they are two versions: with magnet or a mechanical fitting
- PoPP zweather POPE005206 to measure the wind speed and secure the sunblind on terasse

# Camera

some years ago i always use reolink and sv3c cameras. they was good parts but now i tried

- Hiseeu 4K 8MP POE IP-Kamera 

and i am happy with that. delivered by banggood for around 90€

# WiFi and IT infrastructure

In my former house i had a nice, but complex ubiquity wifi infrastructure. 
Now we bought a new house and decide not to create such a complex network and build it on the AVM Fritz products.

In opposite of some other opinions my netweork is very reliable, quick and stable

- 1x Fritzbox 7590
- 7x Fritz Repeater 2400
  3 connected with wired uplinks
  4 connected as wireless mesh repeater
- 1x Netgear GS724TPP 24-Port Gigabit Ethernet LAN PoE Switch Smart Managed Pro 
- 3x NETGEAR GS105PE 5-Port Gigabit Ethernet LAN PoE Switch Smart Managed Plus



