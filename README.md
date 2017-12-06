# A reproduce repo to demo aapt2 crash

Steps to reproduce
* yarn install
* cd android && ./gradlew assembleRelease

Add `android.enableAapt2=false` to gradle.properties is a workaround.

## Related issue
* https://issuetracker.google.com/issues/70258562
* https://github.com/react-community/react-navigation/issues/1976