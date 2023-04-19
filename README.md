# About The Project
MacOS has option to reduce GUI elements transparency. 
Status bar becomes grey (#202020), so it will be cool, if wallpaper will match status bar color.  
This script takes your image and puts it on solid-grey-background.

# Installation
1. Install Imagemagick
2. Copy `mrtw` script somewhere in your PATH.

# Usage

**Use `--help` command to show help**


Example:  
```bash
mrtw -i source-image.png -s 15 -o source-image-grey.png
```
This will scale input image by 15% ( 15% equals **[height * 0.15] x [width * 0.15]**), put it on grey background and save result in `source-image-grey.png.


