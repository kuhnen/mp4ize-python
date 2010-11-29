# mp4ize, python, mp4ize-python (dev)

Welcome!
====================
This is the current development version of [mp4ize-python](http://github.com/anchepiece/mp4ize-python/).

mp4ize python
====================
This program converts video files to mp4, suitable to be played on an iPod
or an iPhone. It is careful about maintaining the proper aspect ratio.

Usage
====================
A simple script to provide a simple, easy to use interface to calculate a span
of time between two dates.  To be able to calculate a future date based on a
span of time.  To illustrate the difference in time using conventional methods
that are technically accurate.

    usage: mp4ize.py [-h] [--version] [-a RATE] [-b RATE] [-v] [-w WIDTH]
                 [-t HEIGHT] [-i] [-o dir]
                 file [file ...]

    encode videos to mp4 for an iPod or an iPhone

    positional arguments:
      file                  list of file names to process

    optional arguments:
      -h, --help            show this help message and exit
      --version             show program verison
      -a RATE, --audio RATE
                            override default audio bitrate (128k)
      -b RATE, --video RATE
                            override default video bitrate (400k)
      -v, --verbose
      -w WIDTH, --width WIDTH
                            override default width (320)
      -t HEIGHT, --height HEIGHT
                            override default height (240)
      -i, --iphone          utilize iphone width and height (320x480)
      -o dir, --outdir dir  write files to given directory

