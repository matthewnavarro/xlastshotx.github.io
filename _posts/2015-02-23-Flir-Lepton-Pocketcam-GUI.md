---
layout: post
title: Flir Lepton Pocketcam GUI
permalink: short-urls-jekyll
---
Today I had the chance to use the recently released FLIR Pocketcam GUI with my FLIR Lepton PocketCam. Video walkthrough below.



I encountered only one problem during the driver installation on my Windows workstation, the drivers being unsigned means that you have to disable Driver Signature Enforcement.





Below are the steps to temporarily disable this in Windows 8/8.1 or Windows Server 2012 R2:

First press Restart while holding down the shift key





You will see the following screen after your computer has restarted. Select troubleshoot





Then click startup settings





Now restart again





On Windows Server 2012 you will see the screen on the left, choose Disable Driver Signature Enforcement. On Windows 8/8.1 you will see the screen on the right, press 7





Windows will now start up with driver signature enforcement disabled until the next restart.

Now you can install the driver. Instructions on how to install the driver are provided in this file “PocketCam_UserInstallation_Guide(WINDOWS).pdf”.

After I completed the driver setup I ran “FC_USB.exe” in the Software folder then turned on and plugged in my FLIR Lepton PocketCam into my workstation.





Pressed start… It works!









Overall getting everything set up and running was easy with minimal problems.




If you have been using the GUI share what you are doing with it and your Lepton in the comments!

{% include twitter_plug.html %}

{% include comments.html %}