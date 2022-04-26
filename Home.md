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
Beta 3  | TBD
RC 1    | TBD
Release | TBD

## Supported Downloads

### Current LTS Release

[[r23 Changelog|Changelog-r23]]

```gradle
android {
    ndkVersion "23.1.7779620"
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
    <td><a href="https://dl.google.com/android/repository/android-ndk-r23b-darwin.dmg">android-ndk-r23b-darwin.dmg</a></td>
    <td>1537571116</td>
    <td>e67c17f9763d160368383f05446d605e9e533195</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r23b-linux.zip">android-ndk-r23b-linux.zip</a></td>
    <td>725122099</td>
    <td>f47ec4c4badd11e9f593a8450180884a927c330d</td>
  </tr>
  <tr>
    <td>Windows</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r23b-windows.zip">android-ndk-r23b-windows.zip</a></td>
    <td>788638042</td>
    <td>6e3fb50022c611a2b13d02f5de5c21cc7206a298</td>
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
    ndkVersion "25.0.8355429-beta3"
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
    <td><a href="https://dl.google.com/android/repository/android-ndk-r25-beta3-windows.zip">android-ndk-r25-beta3-windows.zip</a></td>
    <td>506142216</td>
    <td>7d2c398045f6bbad03f6fb2f2ba419a2a48ab1e7</td>
  </tr>
  <tr>
    <td>macOS</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r25-beta3-darwin.dmg">android-ndk-r25-beta3-darwin.dmg</a></td>
    <td>1285263336</td>
    <td>7502129d66a319c8a99e5ebca35fd58c63bcb90c</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r25-beta3-linux.zip">android-ndk-r25-beta3-linux.zip</a></td>
    <td>510520692</td>
    <td>79c8db05e20edde0cbb02d2326e7b8405f7eb977</td>
  </tr>
</table>
