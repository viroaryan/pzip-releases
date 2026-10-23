# pzip releases

Official signed APK releases for [pzip](https://github.com/viroaryan/open-pzip), the Android file, archive and media app by Abhiraj Aryan and Nirvana Team.

## Download

Use the [latest GitHub Release](https://github.com/viroaryan/pzip-releases/releases/latest) and choose `pzip-universal.apk` for most Android phones. Architecture-specific APKs are available for smaller downloads. Android 8.0 or newer is required.

## Current release

Version 1.0.1 improves local video startup, retries software decoding after a playback error, and keeps subtitles clear of the player controls. See the [full changelog](https://pzip.in/changelog) and the matching [source tag](https://github.com/viroaryan/open-pzip/tree/v1.0.1).

## Verify

Each release contains `SHA256SUMS.txt`. After downloading, compare your APK's SHA-256 hash to the matching line in that file. The production signing certificate SHA-256 fingerprint for v1.0.0 is:

`a6b77cc6ecf9112506449b25c2c2ab0f025b6d6a331422584bfc79306fa0b84a`

Only files attached to this repository's Releases are official downloads. Source code, build instructions and third-party notices are in [open-pzip](https://github.com/viroaryan/open-pzip).

## Upgrading from a test APK

The official release uses a production signing key. If you installed an earlier debug/test APK, Android cannot install this release over it. First move any files out of pzip's Safe folder and back up app data you need, then uninstall the test build before installing the official APK. Uninstalling can remove app-private files and settings.

