# HowTo

Hardware : 

1. One Channel Wemos D1 Mini Relay Shield Wemos D1 Mini Relay Module for ESP8266 Development Board 1 channel
    ( https://www.aliexpress.com/item/32728319939.html )
    
    ![Cat](https://github.com/boat-vitals/delay_off_timer/blob/master/relay.jpg)
    

2. Wemos Mini D1 ESP32 WIFI Bluetooth CP2104 Development Board Module 
    ( https://www.aliexpress.com/item/32839344778.html )
    
    ![Cat](https://github.com/boat-vitals/delay_off_timer/blob/master/wemos_esp32.jpg)
	
3. 1x resistor 7.5K and 1x resistor 30K 
    ( https://www.aliexpress.com/item/4000773915011.html )
	
4. DC-DC 9V 12V 24V to 5V 3A Step Down Power Module CAR Charger / Mobile power
    ( https://www.aliexpress.com/item/32833730316.html )
    
     ![Cat](https://github.com/boat-vitals/delay_off_timer/blob/master/dc_dc.jpg)
	
5.  Enclosure 65x50x55mm(LxWxH): AG Series High-end Quality IP67 Waterproof DIY Electrical Junction Box ABS plastic RoHS Enclosure Case Outdoor Distribution box
    ( https://www.aliexpress.com/item/4000375281151.html )
	
Connections:

1. D1 on the Relay Shield to IO22 on the Wemos ESP32 board
2. 3.3v, 5v and GND on the Relay Shield to 3.3v, vcc and GND on the Wemos ESP32 board
3. Resistor 30K to IO23
4. Resistor 7.5K to IO23 and GND
5. DC-DC module outputs to Wemos ESP32 board VCC ("+") and GND ("-")
6. DC-DC module input ("+") to Relay Shield inout ( middle screw terminal of the relay )
7. Relay Shield input ( middle screw terminal of the relay ) to red cable for "+" 12v input/power (with cable terminal on the other end)
8. Resistor 30K ( other end ) to Relay Shield NO ( left screw terminal of the relay )
9. Relay Shield NO ( left screw terminal of the relay ) to red/white cable for "+" 12v to the pump (with cable terminal on the other end)
10. DC-DC module input ("-") to black cable for "-" power supplay 12v (with cable terminal on the other end)
12. Make an opening for the 3 cables on the enclosure box and put everything together and seal with sikaflex

 ![Cat](https://github.com/boat-vitals/delay_off_timer/blob/master/ex1.jpg)
 
 ![Cat](https://github.com/boat-vitals/delay_off_timer/blob/master/ex2.jpg)

For initial software flash or factory reset please follow the steps:

1. Unzip: upload_scripts.zip

2. Copy inside the files for you exact hardware platform (latest release) : e.g. WROOM32/11276

3. Edit the COM port in erase.cmd and execute it

4. Edit the COM port in upload.cmd and execute it

# Configuration

Video of how to setup the monitoring app/link can be found here : 

iOS: https://www.youtube.com/watch?v=SIvRml3169E

Android : https://www.youtube.com/watch?v=eNQJRxOCrkE


# Support

More information and support can always be found at : www.boat-vitals.com 
