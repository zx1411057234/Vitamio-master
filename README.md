# Vitamio
[![](https://img.shields.io/badge/platform-android-orange.svg)](https://github.com/hacknife) [![](https://img.shields.io/badge/language-java-yellow.svg)](https://github.com/hacknife) [![](https://img.shields.io/badge/jcenter-5.2.3-brightgreen.svg)](http://jcenter.bintray.com/com/hacknife/vitamio) [![](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/hacknife) [![](https://img.shields.io/badge/license-vitamio-green.svg)](http://www.vitamio.org/en/License) [![](https://img.shields.io/badge/api-15+-green.svg)](https://github.com/hacknife)<br/><br/>
Vitamio is an open multimedia framework for Android and iOS, with full and real hardware accelerated decoder and renderer.
# New features

Only few important features are listed here, we have fix many bugs and may introduce some new bugs.

1. The latest FFmpeg 2.0 git version, which should fix most playback issues, or bring some issues.
2. Support most FFmpeg AVOptions, which enables custom HTTP headers support.
3. Support more hardwares, e.g. X86 or MIPS.
4. Improve streaming, especially support adaptive bitrate streaming, you need open manually.
5. OpenSSL included, so some SSL related protocols, such as https, tls, rtmps, rtmpts, are supported.
6. Playback speed control from 0.5x to 2.0x.
7. Audio amplify to 2x volume.
8. Improved subtitle support, including external bitmap subtitles.
9. Cache online video to local storage and can be reused until you delete the cache file.
10. More MediaPlayer API, e.g. `getMetadata`, `getVideoTrack`.
11. The full Java code is open to all developers, modify and contribute is welcome.
12. Support RGBA\_8888 rendering, spport switching RGB\_565 or RGBA\_8888 to video rendering.
13. Enhance the hardware decoding in Android 16+.
14. Support ARMV6 CPU, may have some bugs.

# Usage
```
    implementation 'com.hacknife.vitamio:vitamio-java:5.2.3'
    implementation 'com.hacknife.vitamio:vitamio-armv7a:5.2.3'
    implementation 'com.hacknife.vitamio:vitamio-x86:5.2.3'
    implementation 'com.hacknife.vitamio:vitamio-arm64:5.2.3'
```
# How to use
please see [the website](https://github.com/yixia/VitamioBundle/wiki)
# License
Please see [yixia License](http://www.vitamio.org/en/License)
