# Android web vmstats

Plot real time Android CPU/Mem stats to a dashboard using websocketd and vmstat

Based on [Web vmstats](https://github.com/joewalnes/web-vmstats)

## Requirements

1. bash, any recent version should work
2. Install [websocketd](https://github.com/joewalnes/websocketd)
3. Latest Android-SDK must be installed and ANDROID_HOME set
4. Connect a physical Android device or start an emulator. After connecting the device to the computer, make sure to enable USB debugging.

## Getting started

```bash
chmod +x run.sh
```

Check all available devices:

```bash
adb devices
```

Run the below command to start the service (you need to provide the device id):

```bash
./run.sh DEVICE-ID
```

Go to [http://127.0.0.1:9231/](http://127.0.0.1:9231/)

## Frequently Asked Questions

**Is this just a copy of [Web vmstats](https://github.com/joewalnes/web-vmstats)?**

Yes and yes but for Android vmstats.

## Contribution

Any ideas are welcome. Feel free to submit any issues or pull requests.

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

---
**android-web-vmstats** is developed and maintained by [Mobilebox](http://mobileboxlab.com) team.
