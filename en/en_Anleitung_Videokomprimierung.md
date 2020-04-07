---
tags: KIT_corona, Anleitung
---
![](https://i.imgur.com/eAg9Fgb.png)

# Prepare videos for upload
```
last update: 31.03.2020
```
In order to keep the amount of data that is generated when producing videos for uploading as small as possible, you should **compress the videos before uploading them**. This means that you reduce the file size without significantly reducing the quality of the video.
This way you can accelerate the upload and minimize the server load of the KIT resources at the same time. How to achieve this is shown in this guide.

#### Overview
[TOC]

---

:::warning
Important notes are marked yellow.
:::

:::info
Additional information is marked in blue.
:::
---

## Step 1: Video compression software
We recommend the free software Handbrake for the compression of videos.

1. Download Handbrake from the official website [Download Handbrake](https://handbrake.fr)

:::info
Handbrake is an open source software, which is available for all common operating systems: Windows (also as portable version), macOS and Linux.
:::

2. Install Handbrake on your computer. You may have to ask your ITB or administrator for help if your own user account does not have the necessary rights.


## Step 2: Compress videos

1. Open the Handbrake program. 
2. Unless the software prompts you to do so immediately after opening, select the first video to be compressed by clicking on "Open Source" in the upper left corner.

:::warning
You can also select an entire folder containing several video files. Handbrake will then load all videos at once. The next two sections are therefore slightly different.
::::

#### The following steps are for _individual_ compressions

3. Navigate to your saved videos in the file browser and select **a** video to compress:
![](https://i.imgur.com/B5VyHFf.jpg)
4. Select "Very Fast 720p30" in the "Preferences" drop-down menu under the "General" category
![](https://i.imgur.com/m9uaGaI.jpg)
5. Select a location for the compressed video at the bottom of the window
![](https://i.imgur.com/JKNKcEN.jpg)
6. Click on the green "Start" button in the menu bar.
![](https://i.imgur.com/PKDFM8w.jpg)
7. Jump to point 15.


### The following steps are for compressing _several_ videos at once

8. Navigate to your saved videos in the file browser and select **the entire folder** where each video is saved.
9. Select the first video to be compressed in the "Title" drop-down menu
![](https://i.imgur.com/WSvKP8K.jpg)
10. Select "Very Fast 720p30" in the "Preferences" drop-down menu under the "General" category
![](https://i.imgur.com/m9uaGaI.jpg)
11. Click on the button "Add to queue" in the menu bar
![](https://i.imgur.com/MV7m2gV.jpg)
12. At the bottom of the window, select a location for the compressed video.
13. 🔄 Repeat points 4 to 6 for *every* video in the selected folder or in the list under the "Title" selection.
14. Click the "Queue" button on the menu bar to display all videos in the queue.
![](https://i.imgur.com/2V9ZwTj.jpg)

### :arrow_forward: Get back in here, no matter if you compress only one or several videos.
15. Click on the green button "Start" in the menu bar. 
16. Wait until all compression processes are finished.
![](https://i.imgur.com/g9rVi3N.jpg)

:::danger
**Video compression is a very CPU-intensive process**, and depending on the performance of your computer, the process may take some time and affect the performance of the rest of the system.
:::info
We therefore recommend that you set up your workflow so that the compression is running as long as you _not_ work on the computer yourself.
:::


## Step 3: Completion

**Congratulations, you've successfully compressed your video.**

:::success
For an example video of an iPhone 11 of 6 minutes length, the file size could be reduced from 533 MB to almost 30 MB with this process, while maintaining almost the same quality!
The process took about 3 minutes on a notebook from 2015.
:::

How to make the recordings available to your students is explained in a separate manual.

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
