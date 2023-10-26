---
title: "What is Peer-Z?"
excerpt_separator: "<!--more-->"
categories:
  - Info
  - News
tags:
  - about
author: PeerGum
---

Peer-Z is a project I have envisioned for years, whose main purpose is to provide a safe and secure access to information
to people who needed it. I decided to transform the idea into some concrete development in January 2016, under the codename "Peer-X"
 [...]
<!--more-->

The original idea was to develop the project in Golang, and a web service that would provide APIs to apps to use to communicate
with peers. I eventually quit my full-time job the same year, with not much progress on Peer-X, and eventually shelved the
project to focus on another one in 2017, but also started working on a completely different area that year, focusing on firmware
development.

Eventually, after letting the `peer-x.com` domain go to the hands of greedy buyers (still registered and unused to this day),
I decided to go back to the project, around 2020, and eventually came up with the name "Peer-Z", which I found sounded even better.
After buying the `peer-z.com` domain, I reworked a big part of the code, this time adding some integrated services on an
embedded web server. The way I was seeing things, a pure network layer would hardly get any traction if not bundled
with some useful tools, so I decided to add a few base services. Strong of my previous self-taught experience with `sphyn.com`
(now dead/dormant) I integrated these service using VueJS:
- messaging, some equivalent of peer-to-peer self-hosted email service
- profile, a way for people to create a basic `about me` template
- web, an extension of the profile that would allow anyone to host their own mini-webserver
- checkers, a game of... checkers?
- chess, a game of... chess! You got the idea.
- storage, a service allowing to easily share data with peers

Here is where things went, with pictures:
![Home](/images/old-home.png)
![Messaging](/images/old-messaging.png)
![Checkers](/images/old-checkers.png)
![Chess](/images/old-chess.png)

Then I got busy again...

Fast-forward to 2023, when my workload slowed down and my search for a full-time job picked up, rather than a contract, I decided
to get back to it again, hopefully this time with more concrete results.

The plan is now to:
- upgrade the web services to Vue3 and TailwindCSS/TailwindUI
- use Vue Router
- fix/improve the network layer and protocols
- set up a few relay hosts in the cloud that will provide a base core layer for the network.

Here's a preview of some light design changes (WIP)
![Home](/images/new-home.png)
![Messaging](/images/new-messaging.png)


Hopefully, some good news before the end of the year!

And a call to fellow coders: if you want to be part of this, feel free to contact me
[here](mailto:phil@peer-z.com?subject=peer-z+development)
