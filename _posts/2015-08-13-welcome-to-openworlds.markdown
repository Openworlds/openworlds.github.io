---
layout: post
title:  "Welcome to OpenWorlds"
date:   2015-08-13 20:35:16
categories:
---
After a couple of weeks of research, I've finally decided to bite the bullet and come out with the plan publicly. I've got enough of a concept now to show that it can be done, there is enough prototype code to prove that it is possible, so it is time to kick it in the next gear and actually start hacking on the "real" implementation..

OpenWorlds will be fully opensource, no closed components, and there will be an easy migration path from ActiveWorlds to OpenWorlds (basicaly, a propdump and conversion of the 3D model format). The first client will be web based using WebGL (in the form of [Three.JS](http://threejs.org)) and javascript, using a REST API to connect to the backend world property database, and WebSockets for live updates.

Initially everyone will connect to the central server, but I do want to investigate making it more peer-to-peer. If anyone has ideas on that, please share!

Now back to coding again ;)
