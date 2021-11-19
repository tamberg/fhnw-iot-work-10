# IoT Engineering
## Hands-on of lesson 10
For slides and example code, see [lesson 10](../../../fhnw-iot/blob/master/10/README.md)

> *Note: Do not work on this repository right away.*<br/>
> *[Check existing forks to find the specific repository for your class.](../../network/members)*

### a) Where is the logic?, 5'
* Who decides what a scene means in terms of color, the lamp/device, a room/gateway or the backend?
* Which information is required to make a decision?
* Which devices are affected by changing a scene?
* Which trade-offs does placing the logic involve?

### b) Node-RED, 15'
* Install Node-RED on the Raspberry Pi or your laptop.
* Create a new flow or import & analyse one from [here](https://flows.nodered.org/?type=flow&num_pages=1).
* Use the debug node to build your flow step-by-step.

### c) IFTTT Webhook trigger, 15'
* Imagine an IFTTT Webhook enabled button device.
* Create an applet to send SMS if the button is pressed.
* Emulate the button_pressed event using the curl tool.
* Sketch the hardware and code to build such a button.
* If time permits, implement your connected button.

### d) IFTTT Webhook action, 15'
* Create an IFTTT applet to show the weather on a LED.
* Design a Web API* to set weather conditions or colors.<br/>
  (*Which would run e.g. on the ESP8266 or a Pi.)
* Where would you map weather conditions to colors?
* Create a Postb.in to receive the IFTTT Webhook call.
