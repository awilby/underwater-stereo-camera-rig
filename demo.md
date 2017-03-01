Instructions
===

Assuming everything is already plugged into the Minnowboard except for power (this includes 2 WiFi adapters and the microSD) then you should start by plugging in the Minnowboard
* Within the next 30 seconds you should start the camera to make sure that after the Minnowboard is done booting, the camera’s network will be available
* When you see the LEDs on the WiFi adapters start flashing, it should mean that the Minnowboard is booted and is now broadcasting it’s own WiFi network
* On the tablet connect to the WiFi network “dk_net” (it should take just a few seconds to handle dhcp for you)
* Now either open up Safari and type in the address “10.0.1.4” or open the app
* Note, you may have to kill the app and restart it. Refreshing the page doesn’t always seem to work.
* After a couple seconds you should now be seeing the UI!


Debugging
===

* There should hopefully be little to do for debugging, but rebooting and trying all over again is always a good try
* The Sony Qx1 turns itself off after being turned on for something like 5 minutes if it hasn’t detected activity or something, so if you are rebooting the Minnowboard it’s probably just a good idea to turn off and back on the Qx1 as well
