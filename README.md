# SamsungHealthForXamarin
If you are developing on Xaramin and are trying to get the Samsung Digital Health API working, this library should help.

# Getting Started
* Download the SDK from http://developer.samsung.com/health and copy the data jars into Jars/ .
* In Xamarin, add these jars to the project.
* Compile and you should be good to go

# Permissions
To add read permissions, right click on Properties/AndroidManifest.xml and select Open With Source Code Editor.  Once there, in the application section, add:

	    <meta-data
    		android:name="com.samsung.android.health.permission.read"
        	android:value="permission1;permission2" />

for write permissions, add:

	    <meta-data
    		android:name="com.samsung.android.health.permission.write"
        	android:value="permission1;permission2" />
