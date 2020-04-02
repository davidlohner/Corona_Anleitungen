---
tags: KIT_corona, Anleitung
---
![](https://i.imgur.com/eAg9Fgb.png)

# Record videos with Open Broadcaster software 
```
last update: 31.03.2020
```
If you have your teaching content in digital form on your computer, you can record a lecture and this digital content with a special broadcaster software. This tutorial describes which steps in Open Broadcaster Software (OBS) are necessary for this.

#### Overview
[TOC]

---

::: warning
Important notes are marked yellow.
:::

::: info
Additional information is marked in blue.
:::

---

### Required equipment
* PC or Mac with:
    * Microphone (preferably a headset) 
    * optional: (integrated) webcam
* Open Broadcaster Software (OBS)
* Your teaching content in digital form

## Step 1: Install OBS
1. Please download OBS from the official website [Download OBS](https://obsproject.com)
:::info
OBS is an open source software that is available for all common operating systems: Windows, macOS and Linux.
:::
2. Install OBS on your computer. You may have to ask your ITB or administrator for help if your own user account does not have the necessary rights.
    * You do not need to install any additional plugins.

## Step 2: Configure OBS

1. Run the auto-configuration wizard that OBS offers after the first startup
![](https://i.imgur.com/XbxBcDl.jpg)
2. Select that you mainly want to **record**.
![](https://i.imgur.com/PH7F3ho.jpg)
3. Please specify 1280x720 for the basic (screen) resolution. For the FPS (Frames per Second) 30. 
![](https://i.imgur.com/mjukTGW.jpg)
* **Every operating system** OBS then tests your system and checks if the selected settings work with the performance of your computer:
![](https://i.imgur.com/86Q0k8S.jpg)
4. Apply the settings.
![](https://i.imgur.com/NS1RhCC.jpg)

:::danger
If you receive an error message at this point, please contact the ZML.
:::


## Step 3: Set up recording
1. Under "Sources", select "Screen recording" by clicking on the plus symbol
![](https://i.imgur.com/4C9vjZp.jpg)
2. Select the monitor whose screen content you want to record. If you have only one monitor, only one source is displayed in the drop-down list.
![](https://i.imgur.com/9SFSYgO.jpg)

:::warning
### Additional settings under macOS:

You must allow the OBS software to take screen shots via the system settings. You can find the setting under

**System settings - Security - Privacy**.

![](https://i.imgur.com/SsiuQ2y.jpg)

![](https://i.imgur.com/1E9HPvM.jpg)
:::

3. If your screen has a higher resolution than the base canvas, you need to (virtually) reduce the screen by scaling to the red frame around the image until it fits into the canvas.
![](https://i.imgur.com/b3XdPZa.jpg)

* Touch the red control points, the aspect ratio of the image is not changed.
:::warning
* If you only see the upper left point, you can drag it to the middle of the screen and then reposition the screen content by clicking in the middle of the video image. Repeat this procedure until you see all control points and the screen content is correctly fitted into the canvas!
* The screen has a 16:9 aspect ratio and some notebooks have a 16:10 monitor aspect ratio - so you will need to "cut off" something from the top/bottom end. 
:::

![](https://i.imgur.com/ypjgZOE.jpg)

4. Open the **settings**
![](https://i.imgur.com/VxDH7Pb.jpg)
5. Select "Output" under the tab
    * select the output path where you want to save the recordings. OBS automatically takes the date and time as file name.
    * the recording quality **High quality, medium size files**
    * the output format **mp4**
![](https://i.imgur.com/0jVMp1E.jpg)
6. save the settings with a click on the button **Okay**
7. Your microphone/headset should be visible in the audio mixer. If necessary, deactivate all other signal sources, unless you want to play a video with sound in your presentation (then desktop audio must be activated).
![](https://i.imgur.com/jQW5Tjo.jpg)
8. Test a short recording if everything works according to your imagination
![](https://i.imgur.com/DJiQKua.jpg)

## Step 4: Add more recording sources
You can add other image sources for your recording, such as a webcam or a second screen. Please note that you will only have one screen on which to display your content. If the font is easy to read, please make sure that the font size is selected accordingly.

**For the example of an additional webcam**: 
1. Add another source under "Sources".
2. Select "Video capture device".
![](https://i.imgur.com/Du6MoN9.jpg)
3. Name the source for your recording setting. This naming is only used to organize the sources in OBS.
![](https://i.imgur.com/9TaDr9Z.jpg)
4. Select your webcam in the "Device" selection box
![](https://i.imgur.com/imQJ6HT.jpg)
5. Scale and position the image of the webcam on your screen as you have already done with your screen content
![](https://i.imgur.com/mK1FJGW.jpg)

:::danger
* If you are recording several image sources, position them so that no content from the other source is obscured!
:::

## Some tips
* Don't record a 90-minute lecture all at once! Divide the recordings into **smaller sections of about 10-20 minutes**. This way you can reassemble each time, take breaks and don't have to re-record everything if you make mistakes.
* You should speak **free and not too softly if possible**. Imagine that the students are sitting opposite you: Use a direct approach and avoid long and complex sentences.
* OBS saves files with date and time as file names. Rename the video files on your computer using a common nomenclature and organize them in a well thought-out folder structure. This will help you to find and access the individual learning units later. 


## Next steps
* This guide shows how to prepare the recordings for upload and create the smallest possible files with the same quality: [Video Compression Guide](https://s.kit.edu/tutorial-videokomprimierung).
* How to make the recordings available to your students via ILIAS is explained in a separate manual.



---
## Info & Contact

### License notice
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">These tutorials for the creation of digital teaching material</span> of <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">the center for Technology-Enhanced Learning (ZML) at the Karlsruhe Institute of Technology (KIT)</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

### Imprint

**Publisher**
Karlsruher Institut für Technologie (KIT)
Kaiserstraße 12
76131 Karlsruhe

**Contact**
Karl-Friedrich-Str. 17
76133 Karlsruhe
Germany
Tel.: +49 721 608-48200
Fax: +49 721 608-48210
E-Mail: info@zml.kit.edu

