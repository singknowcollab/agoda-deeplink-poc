# Agoda Deep Link Attribution Research Companion PoC

This repository contains the minimal, inert companion Android application (`com.research.zeroclickpoc`) used to demonstrate deep link attribution hijacking.

## Structure
* `AndroidManifest.xml` - Demonstrates that this application declares zero Android permissions.
* `src/com/research/zeroclickpoc/MainActivity.java` - Source code executing `agoda://promocode/?site_id=...` upon launch.
* `build/base-aligned.apk` - Signed, compiled standalone APK for independent verification.

## Testing Usage
1. Install `base-aligned.apk` on a test device with Agoda installed.
2. Launch the app once to trigger the `agoda://promocode/?site_id=...` deep link handler.
