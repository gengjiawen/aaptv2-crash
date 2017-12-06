# A reproduce lib to demo aapt2 crash

Steps to reproduce
* yarn install
* cd android && ./gradlew assembleRelease

Add `android.enableAapt2=false` to gradle.properties is a workaround.