[![header](https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=300&section=header&text=DATAMOSHER%20PRO&fontSize=90&fontAlignY=30&desc=Automatic%20Datamoshing!&descAlign=50&descSize=30&animation=scaleIn)](https://akascape.gumroad.com/l/Datamosher-Pro)
# Datamosher Pro Standalone
<b> Datamosher Pro is an automatic video-glitching application for free! (python version) <br>
<br><img align="right" src="https://user-images.githubusercontent.com/89206401/141642297-7c62cf6f-7024-430f-88a2-c9cbbf0dc655.png" width="300">

### What's this?
This is a compiled version of Akascape's Datamosher Pro for macOS, using py2app and some trickery. It's way heavyer than the original python version, since it contains all the packages, modules and binaries for it to function on its own.

### Why did I make it?
I was working on a digital animation projects for uni, and I realized not all my team mates were tech-savy enough to be able to install a Python program and use it. This made our workflow and lives easier.

# DOWNLOAD
### Just donwnload the latest version from the Releases tab.

# Installation?
Copy Datamosher Pro.app to your Applications folder and enjoy. App is not signed, thus may require to open via ctrl+click and/or allow it in System Preferences/System Settings.

# Documentation
- A detailed documentation can be found in this [Wiki](https://github.com/Akascape/Datamosher-Pro/wiki) page.

## Gallery (Example Videos)
[![forthebadge](https://forthebadge.com/images/badges/check-it-out.svg)](https://github.com/Akascape/Datamosher-Pro/blob/Datamosher-Pro-v1.7/Demos.md)
# Effects List

**Main datamosh effects:**
| Effect Name     | Description                                                           |
| ----------------| --------------------------------------------------------------------- |
| Void            | gives the standard datamosh cuts based on video vectors (automatic i-frame removal) |
| Classic         | gives the avidemux type datamosh within a range |
| Rise            | gives you the ffglitch datamosh by manually removing a range of i frames |
| Shuffle         | randomly shuffles chunks of frames and then moshes them with the normal ffglitch datamosh |
| Sort            | sorts video frames by data size and merges them with the classic datamosh |
| Motion Transfer | transfer the vector motion data from one video to another |

**Frame Repeatation datamosh:**
| Effect Name     | Description                                                           |
| ----------------| --------------------------------------------------------------------- |
| Bloom           | duplicates a key-frame multiple times with void mode|
| Water Bloom     | duplicates any frame multiple times with ffglitch (more precise than bloom)|
| Repeat          | repeats a **series** of frames multiple times |
| Glide           | duplicates macroblocks multiple times in a continuos order |
| Pulse           | duplicates groups of some p-frames every n times (heavy to render) |

Other Glitch/datamosh modes
| Effect Name     | Description                                                           |
| ----------------| --------------------------------------------------------------------- |
| Buffer          | creates glitchy ring buffers in the video |
| Delay           | random delaying mosh effect |
| Invert-Reverse  | randomly applies both inverse and reverse datamosh |
| Mirror          | mosh with vertical mirrored part of the video|
| Noise           | makes large noisy buffers |
| Shear           | tilt and mosh the video clockwise |
| Shift           | shifts random blocks of the video againt the gravity |
| Sink            | drowns the next frame of the video with the previous one|
| Slam Zoom       | applies zoom with the sink effect |
| Slice           | randomly slices the video into multiple parts |
| Stop            | similar to sink but stops the XY values randomly |
| Vibrate         | randomize the pixels continuosly |
| Zoom            | simply zooms inside the moshed video |
| Fluid           | ffglitch's average motion effect which gives a smooth liquid type effect |
| Stretch         | stretches the macroblock of video both horizontally and vertically |
| Echo            | duplicates the single video and apply the mosh effect in the midpoint  
| Random          | randomizes frame order |
| Reverse         | reverses frame order |
| Invert          | switches each consecutive frame witch each other |
| Overlap         | copy group of some frames taken from every nth position |
| Jiggle          | take frame from around current position |
| Custom Script   | You can experiment with your own ffglitch script with this mode |

## Conclusion
You will not find this type of software anywhere with so many effects only for datamoshing. This program can be your companion while editing cool glitchy videos :)
<br> As it is a new piece of software some users may find small bugs, but updates will be on their way.
<br> The effects are all inspired from ItsKaspar's [tomato.py](https://github.com/itsKaspar/tomato) script, [pymosh](https://github.com/grampajoe/pymosh) and [FFglitch](https://ffglitch.org/). 
All the logos and ui designs are created by Akascape.

<br>[<img src="https://img.shields.io/badge/-Follow_Akascape_on_Github-informational?style=flat&logo=github&logoColor=black&color=grey">](https://github.com/Akascape)
<br>
## License
[<img src="https://user-images.githubusercontent.com/89206401/168461242-884f25ce-eb67-406a-9d98-cf8d0f28cb43.png" width=100>](https://github.com/Akascape/Datamosher-Pro/blob/Datamosher-Pro-master/LICENSE)

Note that **FFglitch** and **FFmpeg** are under GPL license and are NOT included in this license.
All the required licenses (mostly MIT) are provided in their folder/blocks respectively (can be accessed by opening the .app folder, right-clicking on it and selecting "Show package contents") and it must be taken into account that multiple licenses are involved.
<br>

## DATAMOSH MADE EASY!
### Current Version-1.91
<br> [![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/) [![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://github.com/Akascape/Datamosher-Pro) [![forthebadge](https://forthebadge.com/images/badges/not-a-bug-a-feature.svg)](https://github.com/Akascape/Datamosher-Pro)
