android_device_samsung_serranolteusc
====================================

This device tree is setup for building TWRP only.
Your roomservice.xml will need:

  <project name="omnirom/android_bootable_recovery" path="bootable/recovery-twrp" remote="github" revision="android-7.1" />
  <project name="omnirom/android_external_busybox" path="external/busybox" remote="github" revision="android-7.1" /> 

  As of 12/23/16 this commit was needed in bootable/recovery-twrp:  https://gerrit.omnirom.org/#/c/20879/

