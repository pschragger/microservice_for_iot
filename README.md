# microservice_for_iot
Experiments to determine how to build a micro service architecture to teach IOT


# Looking at node.js for raspberry pi 

== https://learn.adafruit.com/node-embedded-development/installing-node-dot-js


== https://github.com/adafruit/Pi_Node_Example

== http://thejackalofjavascript.com/getting-started-raspberry-pi-node-js/
  
   ---  wget http://node-arm.herokuapp.com/node_latest_armhf.deb

A simple node.js-based GPIO helper for the Raspberry Pi
Use https://www.npmjs.com/package/pi-gpio and install the software:

Installing nodejs on the PI
sudo apt-get install nodejs npm

Then use the gpio-admin wrapper

git clone git://github.com/quick2wire/quick2wire-gpio-admin.git
cd quick2wire-gpio-admin
make
sudo make install
sudo adduser $USER gpio

In the project directory use:
npm install pi-gpio

Researching the use of a toolkit for node.js
http://senecajs.org/
