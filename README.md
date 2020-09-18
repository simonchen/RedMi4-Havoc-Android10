# RedMi4-Havoc-Android10
[Redmi4 Prime]
Full guides How to install Havoc OS, and applying MagiskSu, Extending camera2 API, Enable to save images/videos on SD Card (without formatting as internal storage)

## fbind (magisk 20.4 support)
Although, Storage Access Framework would be helpful for use of SD Card, but some Apps (such as GCam ) still have no interface to permit App. to use SD Card,
I found that 3rd party fbind utility for resolve this issue, that you can mount folder from internal storage pointing to external SD Card folder.

### what's fbind ?
This is an advanced mounting utility for folders, EXT4 images (loop devices), LUKS/LUKS2 encrypted volumes, regular partitions and more.
https://github.com/VR-25/fbind

Downloading the [flash zip](https://github.com/simonchen/RedMi4-Havoc-Android10/blob/master/fbind-2020.9.18-fix-service.zip) from https://forum.xda-developers.com/apps/magisk/module-magic-folder-binder-t3621814/page167/amp/

Autorun(Auto-mount) won't work on boot on Android 10+
### Run fbind as init service:
I've built a new flash zip to resolve this issue

## GCam version choice
This developer - Parrot043 uses Redmi Note x , it's better also for Redmi4 Prime
https://www.celsoazevedo.com/files/android/google-camera/dev-parrot043/

## How to use GCam without GApps »
https://www.celsoazevedo.com/files/android/google-camera/troubleshooting/#help12
GCam requires Google Play Services to run, meaning that it will crash if you try to run it on a phone without GApps. To use GCam, you can't go fully "google free" (GCam itself is a Google product).

microG:

You can use microG, an open-source re-implementation of Google's proprietary libraries. Simply install microG's Service Core app and GCam will work.

Gcam Services Provider: (*Recommended!!!*)

The other alternative is to use the Gcam Services Provider app that "simulates" what GCam needs to run. Download the apk here and visit the project's Github for more information.

## Enable to save images/videos to SD-Card 
Refers to the link below:
https://www.youtube.com/watch?v=f9ny9cOXVPU
[How to Fix write permission error to SD-card in OpenCamera running on Android Oreo !]
