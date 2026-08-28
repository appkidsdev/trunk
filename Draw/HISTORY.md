# Draw, baby!

:Author: appkidsdev

:Contact: 
appkidsdev@gmail.com
appdevsup@yandex.ru

## Version 1.1 

* Added Privacy policy for Designed for Families program in in Dialog "About".

## Version 1.2

* Update Privacy policy.
* Added highlight for selected color.
* Added Privacy policy in Dialog "About" as hiperlink (hided whole url path).
* Solved error: java.lang.OutOfMemoryError: Failed to allocate a 92160012 byte allocation with 33554432 free bytes and 56MB until OOM.

That error is thrown when application enters the Paused state, for example, when you make a screenshot and send it by WhatsApp.
In this moment application is trying to save the drawing in order to restore the state later, but due to lack of memory space it cannot be allocated.

Accoding to Google Test Report it was thrown for LG G6 (Android 7.0) and Galaxy S7 edge (Android 6.0).

## Version 1.3

* Update Privacy policy.
* Added saving the pictures.

## Version 2.0 Release

## Version 2.1 Release

* Solved errors during application installation.

That error is thrown when the application is installing while the screen is off.

* Solved errors occure while trying to load pictures.

To avoid java.lang.OutOfMemory exceptions, a resolution version of the picture matchs the size of the UI component that displays that picture is load.

* Added more picture.
* Changed the color scheme to improve performance.

## Version 2.2 Release

* Added more picture.
* Changed Russian letters to English letters.

## Version 3.0 Release

* Up-to-date
* minimum Android 6.0 (Marshmallow)

## Version 4.0 Release.  Available on RuStore.

* Up-to-date
* minimum Android 6.0 (Marshmallow)
* Add lowercase letters
