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

### NDK r23

NDK r23 is expected to be the next LTS release. When NDK r23 ships to stable
support for NDKs r21 and r22 will end.

Release | Expected Release Date
------- | ---------------------
Beta 1  | Released!
Beta 2  | Released!
Beta 3  | Released!
Beta 4  | Released!
Beta 5  | Released!
RC 1    | TBD
Release | TBD

As NDK r23 is the release that will support Android S developer previews and
betas, it will remain in beta until the new APIs are finalized.

## Supported Downloads

### Current Beta Release

[[r23 Changelog|Changelog-r23]]

```gradle
android {
    ndkVersion "23.0.7421159-beta5"
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
    <td>macOS App Bundle</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r23-beta5-darwin.dmg">android-ndk-r23-beta5-darwin.dmg</a></td>
    <td>984306127</td>
    <td>adc46894da63ae4c76e71250606ee17cb8ac1e8d</td>
  </tr>
  <tr>
    <td>macOS</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r23-beta5-darwin.zip">android-ndk-r23-beta5-darwin.zip</a></td>
    <td>694850942</td>
    <td>9ef60fcc7a4bb0477d4189c711853cbc12b24efe</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r23-beta5-linux.zip">android-ndk-r23-beta5-linux.zip</a></td>
    <td>724438684</td>
    <td>453ba0ca124e43337318f8a40d26cab114e7092c</td>
  </tr>
  <tr>
    <td>Windows</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r23-beta5-windows.zip">android-ndk-r23-beta5-windows.zip</a></td>
    <td>785543078</td>
    <td>ace75623181ce86bc70df312155c04b9d8ff3e46</td>
  </tr>
</table>

### Current Rolling Release

[[r22 Changelog|Changelog-r22]]

```gradle
android {
    ndkVersion "22.1.7171670"
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
    <td>macOS App Bundle</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r22-darwin-x86_64.dmg">android-ndk-r22-darwin-x86_64.dmg</a></td>
    <td>1212443975</td>
    <td>ecd9ce035394e227cba741f48732661055caa251</td>
  </tr>
  <tr>
    <td>macOS</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r22b-darwin-x86_64.zip">android-ndk-r22b-darwin-x86_64.zip</a></td>
    <td>1049337733</td>
    <td>dc80e8a2cfcb28db74c1931d42c652e9d17ff2c3</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r22b-linux-x86_64.zip">android-ndk-r22b-linux-x86_64.zip</a></td>
    <td>1148198368</td>
    <td>9ece64c7f19763dd67320d512794969930fce9dc</td>
  </tr>
  <tr>
    <td>Windows</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r22b-windows-x86_64.zip">android-ndk-r22b-windows-x86_64.zip</a></td>
    <td>1082301775</td>
    <td>96ba1a049303cf6bf3ee84cfd64d6bcd43486a50</td>
  </tr>
</table>

### Current LTS Release

[[r21 Changelog|Changelog-r21]]

```gradle
android {
    ndkVersion "21.4.7075529"
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
    <td>Linux</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r21e-linux-x86_64.zip">android-ndk-r21e-linux-x86_64.zip</a></td>
    <td>1190670072</td>
    <td>c3ebc83c96a4d7f539bd72c241b2be9dcd29bda9</td>
  </tr>
  <tr>
    <td>Mac OS X</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r21-darwin-x86_64.dmg">android-ndk-r21-darwin-x86_64.dmg</a></td>
    <td>1258923497</td>
    <td>d8ab6d1ebb5499a3604db4134372bfbaff96a94e</td>
  </tr>
  <tr>
    <td>Mac OS X</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r21e-darwin-x86_64.zip">android-ndk-r21e-darwin-x86_64.zip</a></td>
    <td>1042617180</td>
    <td>3f15c23a1c247ad17c7c271806848dbd40434738</td>
  </tr>
  <tr>
    <td>Windows 64-bit</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r21e-windows-x86_64.zip">android-ndk-r21e-windows-x86_64.zip</a></td>
    <td>1109665123</td>
    <td>fc44fea8bb3f5a6789821f40f41dce2d2cd5dc30</td>
  </tr>
</table>
