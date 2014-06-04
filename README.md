
IOCipher Camera Example
================

This is an example app for the IOCipher framework, which provides encrypted virtual disks for Android. 

This app aims to show how to capture a still photo (as an in memory byte[] array) directly from the Camera sensor, store that as an encrypted JPEG file directly inside of IOCipher, and then later share that file as a stream directly from a ContentProvider.

It also handles recording video (without audio) into IOCipher using the MPEG_TS streaming video container format. This cannot be played on the device in that format, but through use of ffmpeg and converting it to a stock mp4 container, it can be.

This example does not handle proper password/phrase management. Please see our CacheWord library at https://github.com/guardianproject/cacheword for help with that.

![Screenshot 1](screenshot1.png)
![Screenshot 2](screenshot2.png)

Please report bugs here:
https://dev.guardianproject.info/projects/iocipher/issues

Find out all about IOCipher here:
https://guardianproject.info/code/iocipher/

We'd like to hear from you if you have included IOCipher in your app!
support@guardianproject.info
