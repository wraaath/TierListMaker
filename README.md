# TierListMaker

A fun side-project to make tier lists in your browser.
**All** credits go to [SuperFola/TierListMaker](https://www.github.com/SuperFola/TierListMaker)


## New additions
**Added:**
* No "G"-row, no reason just thought it was pointless
* Colors that more closely represent those of a tierlist from TierMaker.com
* Removed unnecessary stuff
* Dark/Black-theme

**TODO:**
* Actual support for drag'n'drop to rows
* Better way to remove images, clicking just is kinda weird idunno
* Make the tier list fill more of the screen
* Feature to edit names of tiers
* Just bigger icons for adding images and swapping rows, they really small rn.
* Picture thumbnail while dragging


## Features

* drag-to-upload (one or more images)
* drag and drop images between tiers to reorder them
* change the color of a given tier
* stretch (to a square) or not an image when uploading it using the `+`
* export as an image
* everything stays in your browser, nothing is uploaded to the server: you keep your data


## Launching

```shell
git clone https://github.com/SuperFola/TierListMaker.git
cd TierListMaker/
python -m http.server
```

Then open your webbrowser and go to http://localhost:8000/
