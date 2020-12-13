# Custom Overlays
Edit fwb and SystemUI values and drawables via RRO

## To build:
First sync latest AOSP and prepare environment to build 
```
. build/envsetup.sh
tapas <package name> arm64 user
make -j$(nproc --all)
```

Availables packages:
- **AOSPTuner**: To modify [frameworks/base/core/res*](https://android.googlesource.com/platform/frameworks/base/+/refs/heads/master/core/res/res/) values
- **SystemUIGoogleTuner**: To modify [frameworks/base/packages/SystemUI/res*](https://android.googlesource.com/platform/frameworks/base/+/refs/heads/master/packages/SystemUI/res/) values
- **SettingsGoogleTuner**: To modify Settings App overlays
