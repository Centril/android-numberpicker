#This library is provided as-is and is not under active development** [![](https://jitpack.io/v/FranziskaHuth/android-numberpicker.svg)](https://jitpack.io/#FranziskaHuth/android-numberpicker)

A backport of the Android 4.2 NumberPicker.


Requires adding a single attribute to your theme. Check the sample app for how this is done.

##How to

To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:

    allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}

Step 2. Add the dependency

    dependencies {
	       compile 'com.github.FranziskaHuth:android-numberpicker:1.0.1'
	}