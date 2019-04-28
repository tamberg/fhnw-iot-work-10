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
* Be ready to present your Node-RED flow.

### c) IFTTT Webhook trigger, 15'
* Imagine an IFTTT Webhook enabled button device.
* Create an applet to send SMS if the button is pressed.
* Emulate the button_pressed event using the curl tool.
* Sketch the hardware and code to build such a button.
* If time permits, implement your connected button.

### d) IFTTT Webhook action, 15'
* Create an IFTTT applet to show the weather on a LED.
* Design a Web API to map weather conditions to colors.
* Create a Postb.in to receive the IFTTT Webhook call.
* How does the post request from IFTTT look?
* If time permits, implement the LED API on ESP8266.

### Submitting results
* [Commit and push](#git) local changes to your repository.
* Want a review? [Create an issue](../../issues/new), mention me (@tamberg).

## Tools
### Git
On your computer
* In the hands-on repository [fork for your class](../../network/members), in README.md, click the _GitHub Classroom link_.
* Once you accept the assessment, you get a personal, private repository URL for your _USER_NAME_:<pre>
http://github.com/fhnw-iot-CLASS/fhnw-iot-work-11-USER_NAME</pre>

On your computer or Raspberry Pi
* Clone the repository<pre>
    $ cd ~
    $ git clone REPO_URL</pre>
* Add a file<pre>
    $ git add FILE</pre>
* Commit changes<pre>
    $ git commit FILE -m "Fixed all bugs"</pre>
* Push changes<pre>
    $ git push</pre>

## Wiki
- [IoT Engineering Wiki](https://github.com/tamberg/fhnw-iot/wiki)

## Support
- [IoT Engineering Slack](https://fhnw-iot.slack.com/)
