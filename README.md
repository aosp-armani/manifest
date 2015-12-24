The Android Open Source Project Lollipop 5.1
===========

To initialize your local repository using the AOSP trees, use a command like this:
````bash
repo init -u git://github.com/aosp-armani/manifest.git -b lollipop-5.1
```
```
Then to sync up:
````bash
repo sync
```
Finally to build:
````bash
./build.sh device_codename
```
Example:
````bash
./build.sh falcon
```
