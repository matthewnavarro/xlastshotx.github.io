---
layout: post
title: Flir Lepton Pocketcam GUI
permalink: flir-lepton-pocketcam-gui
---
<div class="hi">
<img src="https://groupgets-files.s3.amazonaws.com/blog/posts/flir_lepton_pocketcam_gui-banner.jpg">
</div>
Today I had the chance to use the recently released FLIR Pocketcam GUI with my FLIR Lepton PocketCam. Video walkthrough below.

<iframe src="https://player.vimeo.com/video/122367662?byline=0" width="800" height="450" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe><br>


I encountered only one problem during the driver installation on my Windows workstation, the drivers being unsigned means that you have to disable Driver Signature Enforcement.

![Windows problem](https://groupgets-files.s3.amazonaws.com/blog/posts/flir_lepton_pocketcam_gui/1.png)

Below are the steps to temporarily disable this in Windows 8/8.1 or Windows Server 2012 R2:

First press Restart while holding down the shift key

![Computer Picture](https://groupgets-files.s3.amazonaws.com/blog/posts/flir_lepton_pocketcam_gui/2.png)

You will see the following screen after your computer has restarted. Select troubleshoot

![Choose option](https://groupgets-files.s3.amazonaws.com/blog/posts/flir_lepton_pocketcam_gui/3.png)

Then click startup settings

![Advanced option](https://groupgets-files.s3.amazonaws.com/blog/posts/flir_lepton_pocketcam_gui/4.png)

Now restart again

![Startup Settings](https://groupgets-files.s3.amazonaws.com/blog/posts/flir_lepton_pocketcam_gui/5.png)

On Windows Server 2012 you will see the screen on the left, choose Disable Driver Signature Enforcement. On Windows 8/8.1 you will see the screen on the right, press 7

![Options](https://groupgets-files.s3.amazonaws.com/blog/posts/flir_lepton_pocketcam_gui/6.png)

Windows will now start up with driver signature enforcement disabled until the next restart.

Now you can install the driver. Instructions on how to install the driver are provided in [this file](http://www.groupgets.net/Lepton_Foxcam_Demo.zip) “PocketCam_UserInstallation_Guide(WINDOWS).pdf”.

After I completed the driver setup I ran “FC_USB.exe” in the Software folder then turned on and plugged in my FLIR Lepton PocketCam into my workstation.

![FoxCamDemo](https://groupgets-files.s3.amazonaws.com/blog/posts/flir_lepton_pocketcam_gui/7.png)

Pressed start… It works!

![Works](https://groupgets-files.s3.amazonaws.com/blog/posts/flir_lepton_pocketcam_gui/8.png)

Overall getting everything set up and running was easy with minimal problems.

![Thermal Cooking](https://groupgets-files.s3.amazonaws.com/blog/posts/flir_lepton_pocketcam_gui/9.png)