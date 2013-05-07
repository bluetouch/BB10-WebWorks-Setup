BB10-WebWorks-Setup
===================

a Gradle script that automates the setup of the BB10 WebWorks training course on Mac OSX, Windows XP and Windows 7

This is a place to experiment with the idea of completely and entirely automating the installation and configuration of all the software required to run the BB10 WebWorks training course. I'm not sure where this will end up but this is the first step in getting this project off the ground.

One requirement that _MUST_ be met if this is going to work is this: everything has to be completely self contained and %100 automated.  

Software
========
Student Files
JDK
JCE Unlimited Strength Jurisdiction Policy Files
Google Chrome
Ripple Emulator
BlackBerry 10 WebWorks SDK
BlackBerry 10 Dev Alpha Simulator
VMware® Player for Windows or VMware® Fusion for Mac OSX

Configuration Tasks
===================
Extract student files
Add JDK bin folder to path
Set JAVA_HOME to JDK root folder
Install WebWorks SDK
Install latest Google Chrome
Install Ripple extension
Install simulator
Install VMware Player or Fusion
Deploy sample app to simulator
Customize ANT properties files 
Install JCE Policy Files

Paths
=====
Windows 7
---------------
- user home : C:\User\username
- SDK path : C:\Program Files (x86)\Research In Motion\BlackBerry 10 WebWorks SDK 1.0.4.11
- RippleSites : C:\Users\username\RippleSites
- build path : C:\bb10archives
- virtual machine install folder : C:\Users\username\Documents\Virtual Machines\BlackBerry10Simulator-BB10_0_09-386
- simulator IP address : get this from your simulator
- device IP address : get this from your device

Windows XP
-----------------
- user home : C:\Documents and Settings\username
- SDK path : C:\Program Files\Research In Motion\BlackBerry 10 WebWorks SDK 1.0.4.11
- RippleSites : C:\Documents and Settings\username\RippleSites
- build path : C:\bb10archives
- virtual machine install folder : C:\Documents and Settings\username\My Documents\Virtual Machines\BlackBerry10Simulator-BB10_0_09-386
- simulator IP address : get this from your simulator
- device IP address : get this from your device

Mac OS X
--------------
- user home : /Users/username
- SDK path : /Developer/SDKs/Research In Motion/BlackBerry 10 WebWorks SDK 1.0.4.11
- RippleSites : /Users/username/RippleSites
- build path : /Users/username/bb10archives
- virtual machine install folder : /Users/username/Documents/Virtual Machines/virtual machine file
- simulator IP address : get this from your simulator
- device IP address : get this from your device

