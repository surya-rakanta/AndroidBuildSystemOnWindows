# AndroidBuildSystemOnWindows
Modified Android Lollipop (5.1.1) Build System for Windows OS

This is the modified Android build system to be used to compile existing Android's apk file taken from android-5.1.1_r38.

This modification allows the compilation process to be run on Windows OS Host. 

This is proven to be successfully run on Windows OS version 7 (Windows-7-6.1.7601-SP1).

Follow the instructions below:

Download from android-5.1.1_r38 source tree, for example to directory D:\Projects\Lollipop\platform the folders as follows:

build  
dalvik  
development  
external  
frameworks  
libcore  
manifest  
packages  
prebuilts  
sdk  

These are required applications inside external directory/folder:  

antlr  
apache-http  
bouncycastle  
conscrypt  
doclava  
guava  
jarjar  
jsilver  
jsr305  
junit  
libphonenumber  
nist-sip  
okhttp  
proguard  
stlport  
tagsoup  

These are required applications inside frameworks folder:  

base  
ex  
multidex  
opt  
support  

The package folder is downloaded with your choice of Android's internal APK, for example Contacts, that is used by this modified build system.
  
For other folder, just download the entire content inside it.  

Suppose your downloaded Android build system is in D:\Projects\Lollipop\platform\build, copy the envsetup.sh to this location.

Copy other modified build files inside core folder to the D:\Projects\Lollipop\platform\build\core of your local drive.

Activate bash shell and execute envsetup.sh, for example:

D:\Projects\Lollipop\platform\build>bash  
bash-3.1$ ./envsetup.sh
