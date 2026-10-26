# Agoda Deep Link Attribution Research Companion PoC

This repository contains the minimal, inert companion Android application (`com.research.zeroclickpoc`) used to demonstrate deep link attribution hijacking.

## Contents
* `AndroidManifest.xml` - Demonstrates that this application declares zero Android permissions.
* `src/com/research/zeroclickpoc/MainActivity.java` - Source code executing `agoda://promocode/?site_id=...` upon launch.
* `build/ZeroClickPoC.apk` - Signed, compiled standalone companion test APK (package: `com.research.zeroclickpoc`).

## Testing Usage
1. Install `ZeroClickPoC.apk` on an Android test device with the official Agoda app installed.
2. Tap the `ZeroClickPoC` app icon once to trigger the `agoda://promocode/?site_id=...` deep link handler.
