# WeatherStation
Implement an Arduino based WiFi "WeatherStation" with Android user interface for less than 30 EUR.

This project shows how to implement a cheap (under 30 EUR) Weather Station with the help of an Arduino board (as example we use Arduino Pro Mini but other Arduino boards work as well).
We use the ESP8266 WiFi module, and Arduino Pro Mini, a DHT22 humidity and temperature sensor and a few other cheap components.

## Dependencies
This project requires the [DHTLib](https://github.com/RobTillaart/Arduino/tree/master/libraries/DHTlib) and [Arduino-ESP8266](https://github.com/dimircea/Arduino-ESP8266) Arduino libraries.

## Hardware Design
The hardware design is made by using [Fritzing](fritzing.org). The Breadboard and Schematic is ready, but the PCB Layout (for etching) is currently work in progress. All the required files are available under the `documents` folder.

## Software Design
The user interface is implemented as an Android application, and the sensors data is obtained via WiFi. 
We only tested it with Android 4.3.1 (API 18), 4.4.2 (API 19) and 5.0.1 (API 21), and we know that it does not work with Android 2.3.3 (API 10). You are welcome to test other Android versions and report if it works or not.

The WeatherSensor node uses Arduino code.

## Want to Contribute ?
You are welcome to contribute! Please contact me: dimircea[at]gmail.com.

## License
All the code and examples are available under the [GNU General Public License](http://www.gnu.org/licenses/gpl.html)
