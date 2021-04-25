---
layout: default
title: DMC Image Converter
description: Information Page
---

## DMC Image Converter

---
### Latest Release [Version 0.05 (.exe)](https://github.com/Ryason/DMC-Image-Converter/releases/tag/v0.05)
---
### About
DMC Image Converter is a tool used to create cross stitch patterns from images.

### How To Use
> Load an image into the application by clicking the Load Image button.

> Controll the size of your cross stich pattern by setting the width, with the width controll box.

> Select from the list of DMC values, which floss' you would like to use with your pattern.

> Or, select how many different threads you would like to used, and the program will find the best suitable DMC colours.

> Pressing the convert button will start the image conversion, and will result in the pattern being displayed on a large grid.

> You can mark a grid cell red (complete) by right clicking on it

### Current Features
- Load an image and have it converted into a pattern for cross stitching with DMC floss.
- Automatic selection of best DMC threads to use, as well as user specified.
- Resize a loaded image to a set width.
- Display grid showing DMC values, representing the converted pixels of the loaded image.
- Double click a grid cell to mark it as stitched.
- Double click a marked cell to unmark it, if it was marked by mistake.
- Select between different colour matching algorithms. Each gives a slightly different result. With the closeest current algorithm being [CIE2000](https://en.wikipedia.org/wiki/Color_difference#CIELAB_%CE%94E*). Although the closest mathematically, you may want to play around with what the other versions produce.

![Converter Screenshot](./screenshot.png)

---
### Features I Would Like To Add
- Save and load previous conversions. As well as saving and loading of marked grid cells, to keep a users stitching progress.
- Bigger floss selection. Such as brands of floss other than DMC.
- Ability to see what the floss colours look like next to the selection panel.
- Track how long a user has been stitching a pattern, and estimate a completion date.
- Display what coloured floss is actually in the converted image, as the entire palette may not be used. Just because a colour has been selected, certain colours may never be matched to pixels in the users image.
- Track each colour floss and the amount required. With a display showing how many stitches of that colour are left to stitch in the image.
- Ability to save a converted iamage pattern to pdf in order to print it out.
- Update button that links to this project's repo, so users can get the latest version. (Could store version number in code and check against current release version number. Then alert if users exe is not the latest)
- Option to paint your own pattern using a pallet selector and drawing(clicking) directly on the grid.

## [Back](./)
