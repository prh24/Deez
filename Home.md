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

### NDK r25

NDK r25 is the next LTS release.

Release | Expected Release Date
------- | ---------------------
Beta 1  | Released!
Beta 2  | Released!
Beta 3  | Released!
Beta 4  | Released!
RC 1    | 8 June 2022
Release | 8 July 2022

### NDK r26

NDK r26 is the LTS release that will ship in 2023. Due to bandwidth constraints there are no major releases planned between r25 and the 2023 LTS. r25 is the 2022 LTS so it will be supported at least until r26 ships.

Release | Expected Release Date
------- | ---------------------
Beta 1  | TBD
RC 1    | Q3 2023
Release | Q3 2023

## Supported Downloads

### Current LTS Release

[[r23 Changelog|Changelog-r23]]

```gradle
android {
    ndkVersion "23.2.8568313"
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
    <td><a href="https://dl.google.com/android/repository/android-ndk-r23c-windows.zip">android-ndk-r23c-windows.zip</a></td>
    <td>788336993</td>
    <td>f2c5def76a9de371f27d028864fe301ab4fe0cf8</td>
  </tr>
  <tr>
    <td>macOS</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r23c-darwin.dmg">android-ndk-r23c-darwin.dmg</a></td>
    <td>1542594243</td>
    <td>da6f63d3eef041e1cceca449461c6d9148e879b7</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r23c-linux.zip">android-ndk-r23c-linux.zip</a></td>
    <td>724733960</td>
    <td>e5053c126a47e84726d9f7173a04686a71f9a67a</td>
  </tr>
</table>

### Current Stable Release

[[r24 Changelog|Changelog-r24]]

```gradle
android {
    ndkVersion "24.0.8215888"
}
```

<table>
  <tr>
    <th>Platform</th>
    <th>Package</th>
    <th>Size (bytes)</th>
    <th>SHA1 Checksum</th>
  </tr>
  <tr>
    <td>macOS</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r24-darwin.dmg">android-ndk-r24-darwin.dmg</a></td>
    <td>1465702648</td>
    <td>a04581fe13173ea731168c6a1e73390ab628d1aa</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r24-linux.zip">android-ndk-r24-linux.zip</a></td>
    <td>667731974</td>
    <td>eceb18f147282eb93615eff1ad84a9d3962fbb31</td>
  </tr>
  <tr>
    <td>Windows</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r24-windows.zip">android-ndk-r24-windows.zip</a></td>
    <td>663076813</td>
    <td>75f9c281c64762d18c84da465f486c60def47829</td>
  </tr>
</table>

### Current Beta Release

[[r25 Changelog|Changelog-r25]]

```gradle
android {
    ndkVersion "25.0.8528842-beta4"
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
    <td><a href="https://dl.google.com/android/repository/android-ndk-r25-beta4-windows.zip">android-ndk-r25-beta4-windows.zip</a></td>
    <td>464031742</td>
    <td>668b063c7c535c4f8be52c84acebb5779935203b</td>
  </tr>
  <tr>
    <td>macOS</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r25-beta4-darwin.dmg">android-ndk-r25-beta4-darwin.dmg</a></td>
    <td>1270034756</td>
    <td>332a390ac63fdb0a7d5993008d101c87ab1598c2</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r25-beta4-linux.zip">android-ndk-r25-beta4-linux.zip</a></td>
    <td>531018178</td>
    <td>d13f688fd286709f0d950c75119ec9fcad8a47ff</td>
  </tr>
</table>
