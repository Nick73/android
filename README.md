OmniRom GOGH
===========

Getting Started
---------------

To get started with Android/CyanogenMod, you'll need to get setup your
[enviornment](hhttp://vmobi.us/?page_id=8).

To initialize your local repository using the CyanogenMod trees, use a command like this:

    repo init -u git://github.com/Nick73/android.git -b android-4.3

Then to sync up:

    repo sync
    
If you encounter errors, try:

    repo sync -f

For more information on this Github Organization and how it is structured, 
please [read the wiki article](http://wiki.cyanogenmod.org/index.php/Github_Organization)

Building
--------

Depending on what device you are building for you will need to run the following

GOGHSPR - Sprint Version

    . build/envsetup.sh && brunch goghspr

GOGHVMU - Virgin Mobile Version

    . build/envsetup.sh && brunch goghvmu

