---
title: Antropoloops workshops.
theme: league
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

<!-- .slide: data-background="./assets/presentacion-01.jpg" -->

<br>
<br>
<br>
<br>
<br>

## **Antropoloops workshops**

<hr>

---

<!-- .slide: data-background="./assets/presentacion-02.jpg" -->

<img src="./assets/antropoloops 3 sin fondo.png">

#### is a music remix and data visualisation project

---

<!-- .slide: data-background="./assets/presentacion-03-equipo-antropoloops.jpg" -->

---

<!-- .slide: data-background-video="./videos/introantropoloops.mp4" -->

---

<!-- .slide: data-background-video="./videos/v-cole0.mp4" -->

---

<!-- .slide: data-background="./assets/presentacion-04-equipo-antropoloops.jpg" -->

---

<!-- .slide: data-background="./assets/carasso.png" -->

---

<!-- .slide: data-background-video="./videos/san-jose-obrero.mp4" -->

---

<!-- .slide: data-background="./assets/presentacion-05.jpg" -->

---

<!-- .slide: data-background-video="./videos/01-cole-sonoro-s.mp4" -->

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

## Hello

github.com/danigb

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

## Challenges

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

#### Challenges

### Music performance

**individual ⇒ collective**

### Hardware and software

**replicable**

---

## Music performance

<!-- .slide: data-background="./assets/fondo.jpg" -->

---

<!-- .slide: data-background="./assets/backstage1.jpg" -->

---

<!-- .slide: data-background="./assets/backstage2.jpg" -->

---

## Music performance

<!-- .slide: data-background="./assets/fondo.jpg" -->

---

<!-- .slide: data-background="./assets/individuals.jpg" -->

---

<!-- .slide: data-background="./assets/dance.jpg" -->

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

#### Music performance

### Physical (tangible) interfaces

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

## Replication

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

## Replication

* Free software (OSS)
* Cheap hardware (OSH)
* Reuse actual hardware
* Setup should be simple
* Easy to use

---

<!-- .slide: data-background="./assets/miguel/techno.jpg" -->

## Values and our Philosophy

---

<!-- .slide: data-background="./assets/miguel/mural2.jpg" -->

### Technology as a reinforcement of human values

<div class="fragment"> Tangible interfaces using objects and the body: extended body intuitive interactions </div>

---

<!-- .slide: data-background="./assets/miguel/techno2.jpg" -->

<div class="fragment"> We try to bring the digital world into our analogue everyday world </div>
<div class="fragment"> Allowing new relationships (as making a photography speak) </div>

Note: We want to use digital technology to create environments that enable new, or improve, human connexions.

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

### Real Time: stepping into the unknown

<div class="fragment">  Facilitate the experience of discovering without knowing what is going to happen. </div>
<div class="fragment">  Where we become *genuine creators* and move to a shared-common place. </div>

---

<!-- .slide: data-background="./assets/miguel/participation.jpg" -->

### New environments: new participation

* Creating new interactive environments we also allow that different skills and interests stand out.

Note: For example, kids that do not participate in a standard classroom subject will be active and very focused mixing music in realtime with their feet.

---

<!-- .slide: data-background="./assets/miguel/mural_hardware2.jpg" -->

## Hardware

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

### Environments

<div class="fragment"> Classroom </div>
<div class="fragment"> Installation </div>

Note: We have to design taking into account how and where the hardware will be used. It is extremely important to choose wisely depending on that.
Classroom: hardware has to be kids-proof, with easy installation and re-configuration. To use by/with the teacher/assistant. Installation: hardware has to run automatically. Very stable. Permanent. Used for hours/days without assistance.

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

### Which type of interactions do we explore?

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

<div class="fragment"> Capacitive Touch </div>
<div class="fragment"> Pressure/Conductive Touch </div>
<div class="fragment"> Objects </div>
<div class="fragment"> Computer Vision </div>

---

<!-- .slide: data-background="./assets/miguel/ejemplo_mural2_o.jpg" -->

### Tangible Physical Graphical Interfaces

Note: Yes, let's talk about "graphics".

---

<!-- .slide: data-background="./assets/miguel/ejemplo_mural2.jpg" -->

---

<!-- .slide: data-background="./assets/miguel/ejemplo_mural2_o.jpg" -->

* An extended version of a graphic or visualisation is one that is physical, and allows tangible interactions.
* It is bringing digital graphics into the physical world and making them interactive, touchable, tangible.

Note: This extended graphics has many interesting properties that allow new ways of interaction with a visual representation.

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

### What has been done?

* We design from September 2017.
* In the classroom.

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

* "Sonic Landscapes, life histories"
* "Interactive Music Pads"

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

### Sonic Landscapes, life histories.

---

<!-- .slide: data-background-video="./videos/mural.mp4" -->

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

### Interactive Music Pads

---

<!-- .slide: data-background-video="./videos/floorpads.mp4" -->

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

## Software

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

#### Software

## Antropoloops

* Visuals (processing)
* Audio (ableton)
* Communication: OSC protocol (UDP)

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

#### Software

## Requirements

* Free software
* Should be able to run everywhere
* Easy to setup and use

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

#### Software

## HTML5

* Rewrite visualization software (Espe)
* Rewrite audio software (Dani)
  * audio playback ✅
  * audio time synchronization ✅
  * controlling audio parameters real time (👎 yet)
  * realtime audio effects (👎 yet)

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

#### Software

## HTML5

* Distribute the software easily
  * online: internet
  * offline: electron (linux)
* Use the current hardware (as long it can run any modern browser)
  * including computers, tables and phones

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

#### Software

## Websockets

* The websocket protocol allows to communicate different modules using a wireless connection.
* The wireless network could be the one created by a mobile phone, for example (no internet access required)

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

#### Software

## Remote control

We added a thrid component: a remote control (also connected via wireless) that allows to trigger sounds.

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

##### Software

## Scenario

**Outside the classroom**

* Download the app

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

#### Software

## Scenario

**At the classroom**

* Create a wireless network with it's mobile phone
* Connect the computer to the wireless network
* Open the antropoloops app in the computer
* Open the antropoloop app in the phone
* Connect a makey-makey into the phone

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

#### Software

## Demo

---

<!-- .slide: data-background="./assets/fondo.jpg" -->

### DEMO

#### WIFI: **antropoloops**

<br>

## http://192.168.0.158:3333
