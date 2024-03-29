## Betas, release candidates, canary releases, and stable releases

Stable releases along with any current betas and release candidates are available from this page.

Canary releases are available on [ci.android.com](https://ci.android.com/builds/branches/aosp-master-ndk/grid?) for all supported operating systems.

Note: canaries, betas, and release candidates should not be used for production, but are a great way for you to find and report bugs early, before they make it to a stable release.

## Announcements

Subscribe to the [android-ndk-announce@googlegroups.com](https://groups.google.com/g/android-ndk-announce) mailing list if you'd like to be notified whenever we publish a new NDK release (beta or stable).

## macOS 10.15 "Catalina"

A macOS app bundle that is signed and notarized is available. Note that because only bundles may use `RPATH` and pass notarization, the traditional NDK package for macOS cannot be notarized. The SDK will continue to use the traditional package as the app bundle requires layout changes that would make it incompatible with Android Studio. The NDK is not quarantined when it is downloaded via the SDK manager, so is currently allowed by Gatekeeper. The SDK manager is currently the most reliable way to get the NDK for macOS.

## Release Schedule

The NDK releases on a roughly quarterly basis. One release a year is designated
as a Long Term Support (LTS) release that will receive backports until the next
LTS is released. Each version is first released as a beta and then a release
candidate before being shipped to stable. Multiple betas and release candidates
are a possibility if the first beta does not meet our promotion criteria, but
there will always be at least one of each. For details, see [NDK Release
Process](/android/ndk/wiki/NDK-Release-Process).

### NDK r27 (LTS)

NDK r27 is the LTS release that will ship in 2024. Due to bandwidth constraints
there are no major releases planned between r26 and the 2024 LTS. r26 is the
2023 LTS so it will be supported at least until r27 ships.

Release | Expected Release Date
------- | ---------------------
Beta 1  | TBD
RC 1    | TBD
Release | TBD

## Supported Downloads

### Current LTS Release

[[r26b Changelog|Changelog-r26]]

```gradle
android {
    ndkVersion "26.1.10909125"
}
```

<table>
  <tr>
    <th>Platform</th>
    <th>Package</th>
    <th>Size (Bytes)</th>
    <th>SHA1 Checksum</th>
  </tr>
  <tr>
    <td>Windows</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r26b-windows.zip">android-ndk-r26b-windows.zip</a></td>
    <td>661624075</td>
    <td>17453c61a59e848cffb8634f2c7b322417f1732e</td>
  </tr>
  <tr>
    <td>macOS</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r26b-darwin.dmg">android-ndk-r26b-darwin.dmg</a></td>
    <td>1657011580</td>
    <td>c30bdbc77c5bae2faf912591611640ac4d3c2331</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r26b-linux.zip">android-ndk-r26b-linux.zip</a></td>
    <td>669320864</td>
    <td>fdf33d9f6c1b3f16e5459d53a82c7d2201edbcc4</td>
  </tr>
</table>
