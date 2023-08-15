# blowloris
Slowloris DOS attack utility made in Python

# Overview
The Slowloris Denial of Service Attack is very obsolete nowadays due to a plethora of reasons.
1. Because it only affects the target web server and not the ports or processes running on said web server
2. Website utilities like CloudFlare are able to quickly put a stop to it
3. Technology is mostly designed to migitate this attack.
4. You can limit how many HTML requests come at a time towards the target in question
Unless you understand the web server technology used for the target, and/or understand what it does and what it affects, please do not use this to actually perform a Denial of Service attack.
Besides, this is only for educational purposes only.

This, of course, does not mean that the attack has lost its purposes. In fact, Slowloris attacks are still quite a threat since it leaves connections open on HTML, in which with enough packets, the server cannot respond to anything else. These HTML requests can remain for a long time, and are typically designed to open a connection for as long as possible, preventing anything else from getting through until the connection is closed. This is not accomplished without frequent requests, to ensure that there is no other room for newcoming visitors.
