---
title: Tools for Opencast
description: The Opencast community offers several tools, mostly open source, that work together with Opencast to increase the functionality. These tools can improve the capture, offer a export or integration into other systems, can give you a choice of different players and much more.
---

# Tools

<img class="feature-image-left" src="http://www.opencast.org/wp-content/uploads/2015/07/ls-running.png">
## LectureSight
LectureSight is a free and open-source tracking tool that allows to steer a pan-tilt camera based on data gathered by a separate webcam. The aim of this project is to offer a more vivid video of the lecture and show more details of what is going on in the classroom. This will enable an automated recording of a lecture that uses the blackboard, i.e.
[LectureSight Homepage](https://opencast.jira.com/wiki/spaces/LECTURESIGHT/overview "LectureSight Homepage")

<img class="feature-image-right" src="http://www.opencast.org/wp-content/uploads/2015/07/galicaster-ui.png">
## Galicaster

Galicaster, from Teltek, is currently the most popular capture software that works together with Opencast. Additional to recording devices with the Galicaster software that can be purchased from Teltek, this software under a non-commercial open-source licence that allows universities to use the software for free on their computers.
[Galicaster Homepage](https://wiki.teltek.es/display/Galicaster/Galicaster+project+Home "Galicaster Homepage")

<img class="feature-image-left" src="http://www.opencast.org/wp-content/uploads/2015/07/Screenshot-from-2017-03-13-17-43-53.png">
## PyCA

PyCA is a fully functional Opencast capture agent written in Python. It is free software, licensed under the terms of the GNU Lesser General Public License.

PyCA can be run on almost any kind of devices: A regular PC equipped with capture cards, a server to capture network streams, small boards or embedded devices like Raspberry Pi, Beagleboard, …
[PyCA on Github](https://github.com/opencast/pyCA "PyCA on Github")

<img class="feature-image-right" src="http://www.opencast.org/wp-content/uploads/2015/07/mhri.jpg">
## MHRI

The Matterhorn Remote Inbox is a free and open-source tool that was designed to improve the workflow of ingesting content from a desktop PC into Opencast. The user creates a directory structure on a local PC and MHRI watches these directories. Series from Opencast can be assigned to top directories, the name of a subdirectory will be the title of an episode if no further episode information will be provided.
[MHRI Homepage](http://zentrum.virtuos.uos.de/mhri/ "MHRI Homepage")


<img class="feature-image-left" src="http://www.opencast.org/wp-content/uploads/2015/07/therec.png">
## TheRec

TheRec is a free and open-source recording software for Windows 7+. Currently TheRec does not offer all features that a regular capture agent provides, as it does not support scheduling and uploading from Opencast. For an automated upload it relies on MHRI. Unlike other recording tools TheRec is easy to install and to configure. It supports a wide variety of capture cards that are compatible with Microsoft DirectShow. The number of simultanous streams that can be recorded is only limited by the speed of the computer.
[TheRec Homepage](https://elan-ev.de/produkte_av_therec_english.php "TheRec Homepage")

<img class="feature-image-right" src="http://www.opencast.org/wp-content/uploads/2015/07/gc-dashboard.png">
## Galicaster Dashboard

The Galicaster Dashboard is designed to monitor Capture Agents, especially Galicaster Capture Agents. The Tool gives you an overview of your recording devices, with their current status and a preview of the signals that the agent is currently recording.
[Galicaster Dashboard Homepage](https://wiki.teltek.es/display/Galicaster/Galicaster+Dashboard "Galicaster Dashboard Homepage")


<img class="feature-image-left" src="http://www.opencast.org/wp-content/uploads/2015/07/paellaplayer.png">
## Paella Player

The Paella Player is a free and open-source alternative player for Opencast. It is an alternative to the player included within Opencast and offers an appealing design and some unique features like virtual trimming. It is using HTML5 video with a fallback to Flash. The Paella Player can also be embedded into edX.
[Paella Player Homepage](http://paellaplayer.upv.es/ "Paella Player Homepage")


<img class="feature-image-right" src="http://www.opencast.org/wp-content/uploads/2015/07/annotationtool.png">
## Annotating Academic Video Tool

Annotating Academic Video is a free and open-source annotation tool. The aim of this software is provide teacher and learners with an easy to use tool to annotate videos.
[Annotating Academic Video Tool Homepage](https://bitbucket.org/opencast-community/annotation-tool "Annotating Academic Video Tool Homepage")


<img class="feature-image-left" src="http://www.opencast.org/wp-content/uploads/2015/07/login-1203603_960_720.png">
## Opencast Stream Security Plugins

Opencast supports URL signing to provide additional protection of resources against unauthorised access. While the Opencast core provides both facilities to sign URLs and verify signed URLs, additional efforts are required in setups that take advantage of dedicated download and/or streaming servers. Such dedicated distribution servers need to be capable to at least verify signed URLs to offer the same level of protection for distribution artefacts they are providing access to.

Currently, there are two Opencast Stream Security plugins available:

- [Apache HTTP Stream Security Plugin](https://bitbucket.org/opencast-community/apache-httpd-stream-security-plugin "Apache HTTP Stream Security Plugine")
- [Wowza Stream Security Plugin](https://bitbucket.org/opencast-community/wowza-stream-security-plugin/src "Wowza Stream Security Plugin")

