adbscripts
==========

useful scripts for uninstalling, running w/o needing package name, just the apk  (Windows requires linux command line)

adb-uninstall myapp.apk

adb-run myapp.apk

referenced here: http://stackoverflow.com/questions/4567904/how-to-start-an-application-using-android-adb-tools/17289998#17289998

also some common adb commands for android wear (more to come)

adb-uninstallw (uninstalls targeting wearable device on localhost:4444)


note: don't forget to put these in one of your runtime paths (e.g. /usr/local/bin or ~/bin) and make then runnable (chmod +x adb-uninstall)


