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
Beta 3  | April 2021
RC 1    | TBD
Release | TBD

As NDK r23 is the release that will support Android S developer previews and
betas, it will remain in beta until the new APIs are finalized.

## Supported Downloads

### Current Beta Release

[[r23 Changelog|Changelog-r23]]

```gradle
android {
    ndkVersion "23.0.7196353-beta2"
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
    <td><a href="https://dl.google.com/android/repository/android-ndk-r23-beta2-darwin-x86_64.dmg">android-ndk-r23-beta2-darwin-x86_64.dmg</a></td>
    <td>859876198</td>
    <td>039cb1122eac888b4528c81187d49ce8ef856f17</td>
  </tr>
  <tr>
    <td>macOS</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r23-beta2-darwin-x86_64.zip">android-ndk-r23-beta2-darwin-x86_64.zip</a></td>
    <td>674507658</td>
    <td>454fd0c1e8385896ad465d7cfd653e28fbf3523f</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r23-beta2-linux-x86_64.zip">android-ndk-r23-beta2-linux-x86_64.zip</a></td>
    <td>705747711</td>
    <td>290e8c39bb9732ac8784855e1f22342eb488228e</td>
  </tr>
  <tr>
    <td>Windows</td>
    <td><a href="https://dl.google.com/android/repository/android-ndk-r23-beta2-windows-x86_64.zip">android-ndk-r23-beta2-windows-x86_64.zip</a></td>
    <td>747953762</td>
    <td>00194ae44ce90f2052ab8e42f1a11a0db8d50c2a</td>
  </tr>
</table>

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
