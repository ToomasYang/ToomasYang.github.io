---
layout: project
type: project
image: images/vacay-square.png
title: FaIR - Federated Incumbent Detection in CBRS Band
permalink: projects/vacay
# All dates must be YYYY-MM-DD format!
date: 2015-12-15
labels:
  - Research Paper

summary: The CBRS band is open for all users to communicate over. However, when a high priority user needs to use this channel, other users would interfere with the priority user's usage of the channel. We propose FaIR, which when requested, determines all non-priority users on the band and lowers their transmission to an acceptable rate.
---

<img class="ui medium right floated rounded image" src="../images/vacay-home-page.png">

The Citizen Broadband Radio Service (CBRS) band operates at ~3.6 GHz, and was originally used exclusively for government applications, such as the Navy. Recently, this band was opened up for all users to utilize. However, there will be times where federal operators will need to use this band, of which will be saturated with other user's transmissions. Informed users of this band will be able to lower or stop their transmissions to make way for such a high priority operator. However, some of these users may also be uninformed, or incumbent. This is where we propose FaIR, Federated Incumbent Detection in CBRS Band.

The FaIR model consists of sensors, such as radio towers, and a master, such as a central server. The radio towers collect data of its surroundings, such as what users are connected and at what location. One special thing to note is that since data is collected at which locations users could be at, we can also determine which locations users are unlikely to be located. The master can use this data to train a model that eliminates the search space for incumbent users, and distribute the model for use in the FaIR system. This gives way to a low communication overhead, and high detection accuracy of incumbent users.

The full paper is available [here.](https://ieeexplore.ieee.org/document/8935736)
