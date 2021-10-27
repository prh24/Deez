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

### NDK r24

NDK r24 is the next rolling release.

Release       | Expected Release Date
------------- | ---------------------
Beta 1        | TBD
RC 1          | TBD
Release       | TBD

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

### Current Beta Release

[[r24 Changelog|Changelog-r24]]

```gradle
android {
    ndkVersion "24.0.7856742-beta1"
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
    <td><a href="https://dl.google.com/android/repository/android-ndk-r24-beta1-darwin.dmg">android-ndk-r24-beta1-darwin.dmg</a></td>
    <td>1512656443</td>
    <td>54074195e5280ac556a3a95847392e063ae8035a</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r24-beta1-linux.zip">android-ndk-r24-beta1-linux.zip</a></td>
    <td>684615573</td>
    <td>4e43e498699b00cab8b07d431b65a0c1aa022313</td>
  </tr>
  <tr>
    <td>Windows</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r24-beta1-windows.zip">android-ndk-r24-beta1-windows.zip</a></td>
    <td>690364848</td>
    <td>ade5412e9ac0dd206824e9249a5fbc11c9c248bf</td>
  </tr>
</table>
