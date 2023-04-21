For this task, I chose to incorporate the DHT-11 sensor and the ESP8266 wifi module with a logic level converter from 5v to 3.3v into the Arduino on Cloud platform.

To add these components, I forked the repository (https://github.com/frg-fossee/eSim-Cloud) and created a new branch (feature) from the Develop branch. I added the necessary libraries for the components and modified the existing code to integrate them into the platform. The files that were heavily modified are arduino-1.8.9/libraries/CircuitComponents/DHT11.h, arduino-1.8.9/libraries/CircuitComponents/DHT11.cpp, arduino-1.8.9/libraries/CircuitComponents/ESP8266.h, arduino-1.8.9/libraries/CircuitComponents/ESP8266.cpp, arduino-1.8.9/libraries/CircuitComponents/CircuitComponents.h, arduino-1.8.9/libraries/CircuitComponents/CircuitComponents.cpp, and arduino-1.8.9/libraries/CircuitComponents/CircuitComponents.js.

I then recorded a demo of the new components in action and included it in the SUMMARY.md file. The demo shows how the DHT-11 sensor is used to measure temperature and humidity, and how the ESP8266 wifi module is used to send the data to a remote server.

Finally, I tagged a release on GitHub and noted down the release URL (https://github.com/<username>/eSim-Cloud/releases/tag/v1.0).

Overall, this was a challenging but rewarding task, and I learned a lot about adding new components to an existing platform.