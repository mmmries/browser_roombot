# Browswer Roombot

A starter kit for driving a roombot.

## Driving The Simulator

There is an online simulator you can use to test your code at http://roombots.riesd.com/simulator.
Once you have a simulation open it will tell you which channel you should connect to.
Now clonse this repository to your computer and edit the `index.html` file like so:

```html
<script type="text/javascript">
  var roombot_host = "roombots.riesd.com"; // LEAVE THIS THE SAME
  var channel = "<the-channel-you-get-from-the-simulator-goes-here>";
  ...
```

Now use your browser to open the `index.html` file and open your developer tools to see the websocket connection that has been opened to the simulator :+1:.
You should also see the simulator roomba start driving in a circle.

At this point you should see some log messages about joining the channel and maybe some heartbeat messages going back and forth.
You can start editing the the javascript to change what it should do when it gets sensor updates.

## Driving a Real Roombot
Real roombots always use `roomba` as the channel name so you can edit your `index.html` file and set `channel = "roomba";`.
You will need to know the IP address of the roombot.
You can check the [recent bots page](http://roombots.riesd.com/bots) online.
Edit your `index.html` file and set `roombot_host = "<IP-of-the-roombot>";`.
Now when you open the file (or refresh) in the browser you should be connected to the real roombot.

Good luck on your driving adventures! :tada: :+1:
