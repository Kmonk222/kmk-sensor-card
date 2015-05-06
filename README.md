# sensor-card
Sensors found with an Arduino board, and displayed with Polymer.


This element pulls in values from MQTT brokers. The actual sensors
are pushed to the broker using arduino. Currently it will only display 
temperature and lux values, but there are brokers created for humidity 
and air quality, it would just need to be added to the device. 
 
***If the brokers aren't acquiring values, the only display will be the core-header-panel with a title.
