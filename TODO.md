TODO
====

Install JDK
http://docs.oracle.com/javase/7/docs/webnotes/install/linux/linux-jdk.html
Installation of the 64-bit JDK on Linux Platforms
This procedure installs the Java Development Kit (JDK) for 64-bit Linux, using an archive binary file (.tar.gz).

These instructions use the following file:

    jdk-7u<version>-linux-x64.tar.gz
1. Download the file. Before the file can be downloaded, you must accept the license agreement. The archive binary can be installed by anyone (not only root users), in any location that you can write to. However, only the root user can install the JDK into the system location.

2. Change directory to the location where you would like the JDK to be installed. Move the .tar.gz archive binary to the current directory.

3. Unpack the tarball and install the JDK.

    % tar zxvf jdk-7u<version>-linux-x64.tar.gz
The Java Development Kit files are installed in a directory called jdk1.7.0_<version> in the current directory.

4. Delete the .tar.gz file if you want to save disk space.


chronos@localhost ~/Downloads/projects/tests/mobtest2 $ meteor run android
Error running /home/chronos/user/.meteor/packages/meteor-tool/.1.0.32.v37egm++os.linux.x86_64+web.browser+web.cordova/meteor-tool-os.linux.x86_64/tools/cordova-scripts/cordova.sh
Error: /home/chronos/u-9bef7280b1b0a117e6979db2331865d71a5c3303/Downloads/projects/tests/mobtest2/.meteor/local/cordova-build/platforms/android/cordova/build: Command failed with exit code EACCES
    at ChildProcess.whenDone (/home/chronos/user/.meteor/packages/meteor-tool/.1.0.32.v37egm++os.linux.x86_64+web.browser+web.cordova/meteor-tool-os.linux.x86_64/dev_bundle/lib/node_modules/cordova/node_modules/cordova-lib/src/cordova/superspawn.js:135:23)
    at ChildProcess.emit (events.js:95:17)
    at Process.ChildProcess._handle.onexit (child_process.js:807:12)


Running command: /home/chronos/u-9bef7280b1b0a117e6979db2331865d71a5c3303/Downloads/projects/tests/mobtest2/.meteor/local/cordova-build/platforms/android/cordova/build

cd /home/chronos/user/.meteor/packages/meteor-tool/.1.0.32.v37egm++os.linux.x86_64+web.bro
wser+web.cordova/meteor-tool-os.linux.x86_64/dev_bundle/lib/node_modules/cordova/node_modules/cordova-lib/src/cordova/

chmod a+x *.*
