# libsodium_signature_pinenacl

ED25519 signature and verification

For more information see here: http://fluttercrypto.bplaced.net/libsodium-signature-playground-pinacl/

```plaintext
https://pub.dev/packages/pinenacl


https://pub.dev/packages/url_launcher
url_launcher: ^6.0.12

https://pub.dev/packages/path_provider
path_provider: ^2.0.5
pinenacl: ^0.3.3

in AndroidManifest.xml ergänzen:

    <queries>
        <!-- If your app opens https URLs -->
        <intent>
            <action android:name="android.intent.action.VIEW" />
            <data android:scheme="https" />
        </intent>
    </queries>
    
BundleId/Application ID: de.fluttercrypto.signature_playground_libsodium
Name: Libsodium signature and verification
name: libsodium_signature_playground_pinacl
description: Libsodium signature and verification    
```    

Private key:
```plaintext
RyKvBjdiT8jwK/wYkWN1Dep9zuZHxMRJR2G0fO3hCdFJ1lj4GCMrtFkvyoLu6oTKoJ6LNdd/yk9u5y4KqbPtvQ==
```

PublicKey:
```plaintext
SdZY+BgjK7RZL8qC7uqEyqCeizXXf8pPbucuCqmz7b0=
```

Klartext:
```plaintext
The quick brown fox jumps over the lazy dog
```

Sample ED25519 signature:
```plaintext
{
  "algorithm": "ED25519 signature",
  "plaintext": "VGhlIHF1aWNrIGJyb3duIGZveCBqdW1wcyBvdmVyIHRoZSBsYXp5IGRvZw==",
  "signature": "5TDJ6zGgCCIheik1caFnAdQqI4HWedUEQ0zDWeiXlU3/McIXZTptZdjbXeos9NIOYhwTJ+bwrkzY+M3527R8BQ=="
}
```

Sample
```plaintext

```

development environment:
```plaintext
Android Studio Arctic Fox Version 2020.3.1 Patch 3
Build #AI-203.7717.56.2031.7784292
Runtime version: 11.0.10+0-b96-7249189 aarch64
VM: OpenJDK 64-Bit Server VM
Flutter 2.5.3 channel stable Framework Revision 18116933e7
Dart 2.14.4
```

tested on:
```plaintext
Android Simulator: 
  Android 11 (SDK 30) Emulator,
  Android 12 SV2 (SDK 31) Emulator, 
  Android 6 (SDK 23) Emulator,
  Android 5 (SDK 21) Emulator.
iOS Simulator:  
  iOS 15 Emulator
  iOS 11.4 Emulator 
```


```plaintext
/Users/michaelfehr/flutter/bin/flutter pub global activate rename
/Users/michaelfehr/flutter/bin/flutter pub global run rename --bundleId de.fluttercrypto.signature_playground_libsodium
/Users/michaelfehr/flutter/bin/flutter pub global run rename --appname "Libsodium signature"
```

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
