## Integrating Docker and Splunk
##### <span style="font-family:Helvetica Neue; font-weight:bold"><span style="color:#e49436">SplunkersDC Meetup, 31-May-2017</span>
<span style="color:#e49436">dougtoppin@gmail.com</span>
<span style="color:#e49436">[https://www.meetup.com/SplunkersDC/](https://www.meetup.com/SplunkersDC/)</span>

View this using [GitPitch](https://gitpitch.com/dougtoppin/presentation-splunk-docker)
---

## Agenda

* Overview
* What is Docker?
* Data Produced by Docker
* Methods of getting Docker data to Splunk
* Challenges in collecting data from Docker


---

## Overview


---
## What is Docker?

+++

Docker is tbd

+++

a little more tbd

---

## Data produced by Docker

* engine logs
* container logs
* clustered engine logs
* docker events

--
## Methods of getting Docker data to Splunk

* log files and forwarder
* Docker logging driver
* output to text files and forwarder
* container to syslog

---

## Challenges in collecting data from Docker

* engines can log a lot
* microservices means many services
* correlating entries in the many log files
* there are many events
* clusters mean there are many more of all of the above
