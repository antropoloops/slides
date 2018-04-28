---
title: Antropoloops workshops.
theme: simple
revealOptions:
  progress: true
  controls: true
  transition: 'none'
  width: 960
  height: 700
  margin: 0
  minScale: 0.2
  maxScale: 2.3
---

## danigb

### github.com/danigb

---

## Challenges

---

## Challenges

* Music performance: individual -> collective

---

## Challenges

* Music performance: individual -> collective
* Replicable

---

## Music performance

---

## Music performance

image -> electronic music

---

## Music performance

image -> newspaper

---

## Music performance

We don't want this

---

## Music performance

We want this

---

## Music performance

* Physical (tangible) interfaces

---

## Replication

---

## Replication

* Software should be free
* Hardware should be cheap (open hardware to the rescue)
* We want to reuse the actual hardware of schools (old android tablet devices and linux laptops)
* System setup should be simple
* Software and hardware should be easy to use (specially if the target user are teachers ;-)

---

# Software

---

#### Software

## Antropoloops

* Visuals (processing)
* Audio (ableton)
* Communication: OSC protocol (UDP)

---

#### Software

## Requirements

* Free software
* Should be able to run everywhere
* Easy to setup and use

---

#### Software

## HTML5

* Rewrite the visualization
* Rewrite (the parts we need from) the audio software
  * audio playback ✅
  * audio time synchronization ✅
  * controlling audio parameters real time (👎 yet)
  * realtime audio effects (👎 yet)

---

#### Software

## HTML5

* Distribute the software easily
  * online: internet
  * offline: electron (linux)
* Use the current hardware (as long it can run any modern browser)
  * including computers, tables and phones

---

#### Software

## Websockets

* The websocket protocol allows to communicate different modules using a wireless connection.
* The wireless network could be the one created by a mobile phone, for example (no internet access required)

---

#### Software

## Remote control

We added a thrid component: a remote control (also connected via wireless) that allows to trigger sounds.

---

##### Software

## Scenario

**Outside the classroom**

* The teacher download the linux app into it's guadalinux computer using a internet connection

---

#### Software

## Scenario

**At the classroom**

* Create a wireless network with it's mobile phone
* Connect the computer to the wireless network
* Open the antropoloops app in the computer
* Open the antropoloop app in the phone
* Connect a makey-makey into the phone

---

#### Software

## Demo
