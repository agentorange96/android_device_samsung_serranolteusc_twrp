android_device_samsung_serranoltevzw
====================================

This device tree is setup for building TWRP only.
Your roomservice.xml will need:

  project name="omnirom/android_bootable_recovery" path="bootable/recovery-twrp" remote="github" revision="android-7.1" 
  project name="omnirom/android_external_busybox" path="external/busybox" remote="github" revision="android-7.1"  

  As of 12/23/16 these commits are needed in bootable/recovery-twrp so we can build with CM sources:  
	https://gerrit.omnirom.org/#/c/20879/
	https://gerrit.omnirom.org/#/c/20837/

