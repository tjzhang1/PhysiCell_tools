# PhysiCell_scripts

```
$ python svg2other.py 0 56 2 20 jpg      # convert .svg files to .jpg (new files)
```

Assuming you've got ImageMagick (https://www.imagemagick.org/script/download.php) installed, you can create movies using the `convert` command, e.g.:
```
$ convert -delay 1x2 *.jpg mymovie.gif   # animated gif: delay 1/2 sec between frames
$ convert -delay 1x4 *.jpg mymovie.mp4   # mp4 video: if ffmpeg is installed; 1/4 sec delay
$ magick animate mymovie.gif
$ vlc mymovie.mp4                        # if VLC is installed (allows zooming)
```