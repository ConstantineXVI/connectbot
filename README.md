Personal fork of connectbot: original may be found at http://code.google.com/p/connectbot/

Hacked (roughly) to make the Ctrl key work, no other modifications as yet.

Original README follows -ap 

Compiling
---------

To compile ConnectBot using Ant, you must specify where your Android SDK is via the local.properties file. Insert a line similar to the following with the full path to your SDK:

sdk.dir=/usr/local/android


ProGuard Support
----------------

Download the ProGuard distribution from its website at http://proguard.sourceforge.net/ and place the proguard.jar into the "tools" subdirectory in the ConnectBot root directory.

When running ant to build ConnectBot and engage ProGuard, use:

ant proguard release
