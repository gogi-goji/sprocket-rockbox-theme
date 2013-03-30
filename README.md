Sprocket
========

A Rockbox theme for the iPod Mini, inspired by Apple's original firmware
design.  It attempts to balance displaying enough pertinent information with a
clean aesthetic.  

*   By: Cam Mendoza (gogi-goji) <mendoza.cam@gmail.com>
*   Platform: iPod Mini (138x110, 4 colour grayscale)
*   License: CC-BY-SA 3.0
*   Version: 1.0
*   Last updated: 2013-03-30

This theme lives on GitHub!  You can find the project at
<https://github.com/gogi-goji/sprocket-rockbox-theme>


Installation
------------

Simply extract the zip file onto the root of your iPod Mini's hard drive.  The
.rockbox folder in it contains the appropriate folder/file structure so that
everything should end up in the right place.  

It requires the Rockbox Font Pack for the included Helvetica fonts.  You can
find the latest font pack [here](http://www.rockbox.org/download/byhand.cgi).


Customising
===========

There's some different options you can use to tweak the displayed information
that are floating around in the different config files.  Comment or uncomment
things (lines beginning with a `#` are not executed) as you like to tweak
things.

Easy things you can try:

*   Whether the album date is displayed alternating with the album name, after
    the album name, or not displayed at all
    *   .rockbox/wps/sprocket.wps
    *   See different options around `# Album Name`
*   Next track info, alternating or scrolling
    *   .rockbox/wps/sprocket.wps
    *   See around `# Next track info`
*   If volume/battery levels are displayed as simple icons or with text too
    *(TODO: Enhance volume icon when not using text too to show more levels)*
    *   .rockbox/wps/sprocket.sbs
    *   Comment out the two lines after `# Volume text` and 
        `# Battery Percentage Text`
*   Whether or not to display a sleep timer if it's set
    *   .rockbox/wps/sprocket.wps
    *   Two lines following `# Sleep timer`
*   Whether or not to show the playlist name
    *   .rockbox/wps/sprocket.wps
    *   See `# Playlist position`

At some point in the future, hopefully I'll make a script you can run to make
it easier to customise this theme, choosing between different options and
enabling the appropriate one.  Some day.

License
-------

This work is licensed under a [Creative Commons Attribution-ShareAlike 3.0
Unported License](http://creativecommons.org/licenses/by-sa/3.0/).
