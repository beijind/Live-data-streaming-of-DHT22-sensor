# Live data streaming of DHT22 sensor
HTTP server and AJAX web page for live data streaming of DHT22 tempreture and humidity sensor with Raspberry Pi or Beaglebone Black.

![alt text](https://raw.githubusercontent.com/beijind/Live-data-streaming-of-DHT22-sensor/master/demo-image.jpg)

# How to use it
- Make sure you have both Python and [Adafruit_DHT](https://github.com/adafruit/Adafruit_Python_DHT) installed in your system.
- Configure 'PIN' (pin to which your sensor is connected to) and 'PORT' (server port) constants in server.py if needed.
- Run the server with 'python server.py'.
- Access the web page through internet browser by entering server's adress 'IP_ADRESS:PORT' ('127.0.0.1:80' for default local connection).
