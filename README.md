# Browswer Roombot

A starter kit for driving a roombot.

## Getting Started

* Clone this repository to your computer
* find the [IP address of a roombot](http://roombots.riesd.com/bots) you want to drive
* Edit the `index.html` file in this repository with the IP address of the roombot you want to drive
* Use your browser to open the `index.html` file and open your developer tools to see the websocket connection that has been opened to the roombot

At this point you should see some log messages about joining the channel and maybe some heartbeat messages going back and forth.
If you move your hand in front of the roombot you should see a flurry of log messages about sensor updates and you should be able to see that the `light_bumper` sensors are turning on and off because of your hand.

## Driving the Roombot

The `index.html` file contains a comment with a sample drive command.
It's up to you to figure out when to send drive commands and how to react to the sensor updates from the roombot.

Good luck!
