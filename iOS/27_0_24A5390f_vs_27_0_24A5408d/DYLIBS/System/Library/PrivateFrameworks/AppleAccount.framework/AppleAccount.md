## AppleAccount

> `/System/Library/PrivateFrameworks/AppleAccount.framework/AppleAccount`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a8e0c` | `0x1a99b4` | **`+0xba8`** |
| `__TEXT.__oslogstring` | `0x138ed` | `0x1397d` | **`+0x90`** |
| `__DATA.__bss` | `0x17640` | `0x176c0` | **`+0x80`** |
| `__TEXT.__const` | `0x10d30` | `0x10db0` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0xd330` | `0xd3a0` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0x7768` | `0x77a0` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x1538` | `0x1508` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x26aa0` | `0x26ad0` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x5278` | `0x52a0` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xb5c4` | `0xb5ec` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x2630` | `0x2654` | **`+0x24`** |
| `__AUTH_CONST.__cfstring` | `0xd620` | `0xd640` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x161a` | `0x163a` | **`+0x20`** |
| `__DATA.__common` | `0xa8` | `0xc0` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x3c0` | `0x3d8` | **`+0x18`** |
| `__DATA.__data` | `0x4114` | `0x4104` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x3f80` | `0x3f90` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x2a68` | `0x2a74` | **`+0xc`** |
| `__AUTH.__objc_data` | `0x1128` | `0x1130` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x4b78` | `0x4b80` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xc70` | `0xc74` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1064.0.0.0.0
+1067.0.0.0.0

-  Functions: 9148
-  Symbols:   10007
-  CStrings:  3731
+  Functions: 9165
+  Symbols:   10009
+  CStrings:  3735
Symbols:
+ +[AAAppStateProvider appStateForBundleID:appRecord:]
+ +[AAPreferences isWalrusPreEncryptionBlobLoggingEnabled]
+ -[NSError(AppleAccount) aa_isTermsOfServiceUpdateRequired]
+ _kAAProtocolPrefWalrusLogPreEncryptionBlob
- _CGRectEqualToRect
- _CGRectStandardize
CStrings:
+ "AAAppStateProvider: %{public}@ installed=%@ restricted=%@ (rawRestricted=%@ reason=%ld)"
+ "AAWalrusLogPreEncryptionBlob"
+ "Extracted device list ETag: %{private,mask.hash}s"
+ "com.apple.appleaccount.recoveryContact.custodian.privateChannelCreated"
+ "com.apple.appleaccount.recoveryContact.owner.CustodianCountMatchServerCount"
+ "com.apple.appleaccount.recoveryContact.owner.GetCodeLanding"
+ "com.apple.appleaccount.recoveryContact.owner.RecoveryLanding"
+ "cropRect"
+ "imageData"
- "com.apple.appleaccount.recoveryContact.owner.custodianCountMatchServerCount"
- "com.apple.appleaccount.recoveryContact.owner.getCodeLanding"
- "com.apple.appleaccount.recoveryContact.owner.privateChannelCreated"
- "com.apple.appleaccount.recoveryContact.owner.recoveryLanding"
- "com.apple.appleaccount.setupbase"
```
