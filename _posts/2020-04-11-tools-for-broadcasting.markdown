---
layout: post
title:  "Tools for Broadcasting"
date:   2020-04-11 12:00:00 -0400
categories: update
---

# Broadcasting Music and Voice with DJ Mixing Software (using Mixx)  
If you'd like to do a show that is mostly music, from your own digital music collection, there's a great free DJ software that works on PC or Mac. It's called Mixx and it can connect directly to our online stream. One nice thing about this, is that it'll send some music metadata (artist and song title) up to our online stream, so people can see what you're playing as you play it.  
  
Install Mixx from [their website](http://www.mixxx.org/download/#stable)  
  
Follow the instructions on Mixxx's website to enable MP3 streaming.  
[Instructions for Windows](https://www.mixxx.org/wiki/doku.php/internet_broadcasting#windows).  
[Instructions for Mac OSX](https://www.mixxx.org/wiki/doku.php/internet_broadcasting#mac_osx).  
In Mixxx, locate the “Preferences" tab, under the Options section.  
Scroll to the bottom in the right pane to find the Live Broadcasting option.  
![mixx-preferences](_media/mixx-preferences.png)

Fill out the fields below:  
Type: Icecast 2  
Host:  
Login:  
Mount:  
Port: 8000  
Password:  
  
In 'Encoding" set the following parameters:  
Bitrate	128 kbps  
Format	MP3  
Channels	Stereo  
  
At the top of the screen checkmark Enable Live Broadcasting and hit 'OK'  
  
  
# Broadcasting Pre-Recorded Shows, Live-Talk, Etc (using B.U.T.T. on a PC or Mac)
  
Install B.U.T.T. from [their website.](https://danielnoethen.de/)  
From B.U.T.T., click Settings.  
Under the Server dropdown box, click Add.  
  
Fill out these fields:  
Name	Social Distance Radio  
Type	Icecast  
Address:  
Port:	8000  
Password:  
IceCast mountpoint:  
Icecast user:  
  
Click Add.   
Click Save.  
Click the Play button to start broadcasting.  
  
  
# Broadcasting Live from Your iPhone (using iziCast on an iPhone)  
  
Install iZiCast from [their website.](http://danielnoethen.de/iziCast/)  
Follow instructions [here](http://danielnoethen.de/iziCast/tutorials.html)  

