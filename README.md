# ScreenCap updates

Signed and notarized builds of [ScreenCap](https://github.com/purpleax/ScreenCap),
a screen capture and annotation app for macOS, and the feed the app uses to
update itself.

- **Download:** the newest disk image is on the [releases page](https://github.com/purpleax/ScreenCap-Updates/releases/latest).
  Open it and drag ScreenCap to Applications. Needs macOS 14 or later.
- **Updates:** ScreenCap checks [`appcast.xml`](appcast.xml) once a day, or when
  you choose **Check for Updates…**, and installs new versions in place.
  Every update is notarized by Apple and signed with ScreenCap's update key.

This repository holds release files only and is updated automatically when a
version is published.
