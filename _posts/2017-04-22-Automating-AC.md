---
layout: post
current: post
cover:  assets/images/automating-ac/ac-block-diagram.PNG
navigation: True
title: Automating Dorm Room Air Conditioner
date: 2017-04-22 10:00:00
tags: projects
class: post-template
subclass: 'post tag-projects'
author: swapnil
---

One of the biggest frustrations about sharing a room is the battle over control of the AC - who gets to choose the room temperature. This was one of the biggest point of contention between my freshman year roommates. 

Our problem was slightly more nuanced. It wasn't that that we preferred different temperatures, but that the thermostat did a terrible job of maintaining a set temperature because of its poor placement in the room. Since the hope of a comfortable room was lost, we regressed to the extremes. One roommmate preferred that we kept the AC on a full blast constantly, making the room feel like the frozens section in a grocery store. The other roommate wanted us to just leave it off and let the summer heat of Nashville regulate the room temperature (also a terrible alternative).

I, on the other hand, did not prefer either and instead looked to technology to fix the problem.

### Initial Idea
My initial idea was simple: build an arduino device that measures the room temperature from a central location and uses a servo to adjust the AC setting to maintain our desired temperature. The first step was creating an interface between the servo motors and the dials that control the temperature and fan speed on the thermostat. I designed these two parts in CAD and 3D printed them.

<p><img src="(assets/images/automating-ac/control-dials.png" alt="Control Dial Interfaces"></p>

The holes on these interfaces were designed to fit the servo horns I had with each servo. 