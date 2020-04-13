# Knockerz
Author: paul.knight@delmarvacomputer.com
Date: 6/17/17

Based on the work of brian@bevey.org in 2013, this smartapp notifies when someone knocks on a door, but does not open it. Alerts are by push, SMS, PushBullet, audio, and/or by turning on a switch and/or dimming the device.

Use of Amazon Echo devices will require installation of Echo Speaks.

If, like myself, you have an electronic door lock, it may cause false notifications when it locks and unlocks. To get around that, I created a simulated switch, and specified that switch to be on in this app. Then, any other routine that activates the lock, I turn this simulated switch off. I then have Knockerz turn that switch back on.

Updates:
* 4/13/20
  * Added Echo Speaks support
* 2/12/20
  * Added notification restrictions
  * Added text-to-speech text
* 6/17/17
  * Initial release
