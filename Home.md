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

### NDK r22

Release | Expected Release Date
------- | ---------------------
Beta 1  | Released!
RC 1    | Released!
Release | Released!

## Supported Downloads

### Current Rolling Release

[[r22 Changelog|Changelog-r22]]

```gradle
android {
    ndkVersion "22.0.7026061"
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
    <td>1210328006</td>
    <td>3445ac326db65141415d24c9833e27827ca00727</td>
  </tr>
  <tr>
    <td>macOS</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r22-darwin-x86_64.zip">android-ndk-r22-darwin-x86_64.zip</a></td>
    <td>1047577432</td>
    <td>9cf3816ed3e4308ff03bd5f69100b373bad12f13</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r22-linux-x86_64.zip">android-ndk-r22-linux-x86_64.zip</a></td>
    <td>1146450986</td>
    <td>82274313aba10da6177fd41868f56a0f9651dd81</td>
  </tr>
  <tr>
    <td>Windows</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r22-windows-x86_64.zip">android-ndk-r22-windows-x86_64.zip</a></td>
    <td>1080471370</td>
    <td>c03f761caf1c6f5efbeb5ccfa573ea922cb955b3</td>
  </tr>
</table>

### Current LTS Release

[[r21 Changelog|Changelog-r21]]

```gradle
android {
    ndkVersion "21.3.6528147"
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
    <td><a href="https://dl.google.com/android/repository/android-ndk-r21d-darwin-x86_64.dmg">android-ndk-r21d-darwin-x86_64.dmg</a></td>
    <td>1258792917</td>
    <td>0bc502aa2bceb63c404707d99fae1a375bdc3aaf</td>
  </tr>
  <tr>
    <td>macOS</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r21d-darwin-x86_64.zip">android-ndk-r21d-darwin-x86_64.zip</a></td>
    <td>1042615469</td>
    <td>ef06c9f9d7efd6f243eb3c05ac440562ae29ae12</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r21d-linux-x86_64.zip">android-ndk-r21d-linux-x86_64.zip</a></td>
    <td>1190667841</td>
    <td>bcf4023eb8cb6976a4c7cff0a8a8f145f162bf4d</td>
  </tr>
  <tr>
    <td>Windows</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r21d-windows-x86_64.zip">android-ndk-r21d-windows-x86_64.zip</a></td>
    <td>1109536102</td>
    <td>99175ce1210258f2280568cd340e0666c69955c7</td>
  </tr>
</table>
