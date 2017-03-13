squeezeberry
============

SqueezeBerry Project UI
by Emmaanuel

Tutorials on http://www.emmaanuel.com

###Why the fork?

Since this excellent project was parked 4 years ago, the world has moved on....
The main issue is that the gaugette project now uses wiringPi so all the GPIO stuff has to change.
But also, for testing, I wanted to be able to control the player without all the hardware, or with some of the hardware present.
So the plan is to do a bit of separation between the various parts - mostly this is already done as each part already has its own class.
Eventually should be able to 'plug in' alternative hardware without changing the basic code.
For example, it would be nice to have a few preset buttons for favourite channels / playlists
