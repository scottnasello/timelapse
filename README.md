timelapse
=========

**timelapse** is a Mac OS X command line utility to turn a series of images into a video.

It uses the AV Foundation to create MPEG-4 or Quicktime movies using the H.264, JPEG, Apple ProRes422, or Apple ProRes4444 codecs. The source images can be anything that NSImage can open; JPEG is most common.

## Downloading

You can download a binary installer package from https://github.com/jimstudt/timelapse/releases/ or build it 
from this archive.

## Status

**timelapse** currently has a single user. I use it several times a day to make movies from a series of image captures and it works beautifully for me. Maybe it will work for you too.

If you misuse an argument or make a mistake in the options, you are going to get a horrific excuse for an error message, usually embedded in a stack backtrace. Put it in an issue on github and I'll make nicer error for it.

I will not add features until someone asks for them. Feel free to browse the issue tracker and ask for what you need.

## Usage

You should look at this copy of the man page: http://htmlpreview.github.com/?https://raw.github.com/jimstudt/timelapse/master/timelapse.html

It is tragically formatted, but you will get the idea.

## History

I wrote **timelapse** years ago when QtKit was new. Since Mac OS 10.9, Mavericks, QtKit is deprecated, so I rewrote it to use AV Foundation instead. This git repository was restarted from scratch so you don't have to see any of that old cruft.


