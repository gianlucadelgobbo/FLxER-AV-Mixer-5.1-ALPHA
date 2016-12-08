FLxER AV Mixer 5.1 ALPHA
=============
PC / MAC / LINUX

https://flxer.net

Published
------------
21-01-2010

```
///////////////////////////////////////////
/                                         /
/ XXXXX X     X   X xxxxx xxxx            /
/ X     X      X X  x     x   x           /
/ XXX   X       X   xxx   xxxx            /
/ X     X      X X  x     x  x            /
/ X     XXXXX X   X xxxxx x   x    5      /
/                                         /
///////////////////////////////////////////
```
New version based on version 5.0 and finally an FLV, H.264 and SWF player for iPhone and iPad (maybe more... a AV mixer).

Updates
------------
- New version for iPhone and iPad, now you can add your files in the library only with ssh (jailbreak) or you can upload files directly from the Web by typing the URL
- New Recorder, you can now save your set on a xml file like all programs!
- New manager of the resize, not only on the larger side but also on the narrow one, ideal for adapting old 4:3 movies to 16:9
- New DV-IN
- New external application for Mapping (SVGwipesDrawer)
- New application External Oscillator (not to be missed! thx to vj² aka Flavio Distefano)
- Many bug fixes in particular MIDI, TXT EDITOR, etc.

The pack contains
------------
- FLxER5.1alpha (Application)
- FLxER5.1alphaMonitorOut
- FLxER5.1alphaRemoteOut
- FLxEReasyPlaylistsBuilder.jar
- FLxERremoteServer.jar
- FLxERmidiManager.jar
- OaxoaTiles
- SVGwipesDrawer
- Default Library
- Sources files for Wipes, PlugIn and DV-IN

BEFORE START 
------------
FLxER is a free software made with internet tecnology so for security reasons doesn't read the content of your hard disk. every video file and plug-in, wipe, effect, has to be addeed to the xml files that the application loads before to start.

STARTING 
------------
1) NO ISTALLATION IS REQUIRED, launch the application FLxER5alpha.app (MAC) / FLxER5alpha.exe (PC) / FLxER5alpha.swf (LINUX - YOU NEED ADOBE FLASH PLAYER 9 STANDALONE http://labs.adobe.com/technologies/flashplayer9/) and take a tour of the funcnionality start from "select playlist" and load some movie.

2) If you enjoy FLxER and you want to try playing with your movies and files you have to modify the configuration files manually or using "FLxEReasyPlaylistsBuilder.jar".

2.a) First step: copy your files into a folder (the name of the folder will be tha name of the playlist) into "library/".

2.b) Run FLxEReasyPlaylistsBuilder.jar

3) Run FLxER


UPGRADING FLxER 3.0.1 
------------
1) Unzip FLxER4 in a new folder

2) overwrite the library folder with your FLxER3 library folder

3) open your old "preferences/flxer_pref.flx" and copy all the rows of of librarys files name (inside the node <librarys>)

4) open the new "preferences/playlists.xml" and paste it into the node (<playlists>)


FLxER 5 FEATURES 
------------
- 7 channels video mixer

- Supported media: .swf (full ActionScrpt 8 support), .flv, .jpg, .gif, .png, .txt, .mp3

- Advanced live text editor over all channels

- DV-IN Analog and digital over all channels

- HD output resolution starting from 800x600

- Full Colors and Trasform palette

- 14 Blend options over all channels

- Effects and Analog effects as blur over all channels

- Completly customizable list of Wipes

- Video Sequencer  over all channels

- XML VIDEO RECORDER to share or recall your livesets in a few bytes

- XML VIDEO PLAYER

- BROADCAST VIDEO DELIVERY to share in real time your liveset all over the world or to use more pc to do a live set

- BROADCAST VIDEO PLAYER

##Oscillator plugin (by Flavio Distefano)
------------
This update contains a plug-in that allows to change some flxer's movies properties according to a wave form generator.
the properties are:
position (x,y,z)
scaling(x,y)
rotation(x,y,z)
colors(r,g,b)

###Start up:
- Open Monitor Out

- Open FLxER in "multi monitor" mode

- Open Oscillator Plug-in

- Enjoy

###How to install:
- copy the folder "Oscillator" and its content in your FLxER "plug-in" folder 
- copy the Oscillator_plug-in application in your FLxER folder at the same level of your FLxER application


###How to use:
The interface has 7 control panels, one for each FLxER channel.
- first select the wave form from FUNCTION combobox
- set the amplitude of the wave; default is 50, max 100
- set the speed with the button tap 
- then choose the property or the properties you want to change  according with the wave form
- press the button "APPLY TO CH" to start the plug-in and you will see the results in monitor out 
