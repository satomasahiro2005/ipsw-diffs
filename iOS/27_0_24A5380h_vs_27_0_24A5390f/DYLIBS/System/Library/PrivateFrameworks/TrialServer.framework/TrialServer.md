## TrialServer

> `/System/Library/PrivateFrameworks/TrialServer.framework/TrialServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x1398` | `0x1258` | **`-0x140`** |
| `__DATA_DIRTY.__objc_data` | `0x4e48` | `0x4f88` | **`+0x140`** |
| `__TEXT.__delay_helper` | `0x8cc` | `0x794` | **`-0x138`** |
| `__TEXT.__lazy_helpers` | `—` | `0xe8` | **`+0xe8`** |
| `__TEXT.__cstring` | `0x1698c` | `0x16925` | **`-0x67`** |
| `__DATA.__bss` | `0x118` | `0xb8` | **`-0x60`** |
| `__DATA_DIRTY.__bss` | `0x3d8` | `0x438` | **`+0x60`** |
| `__TEXT.__text` | `0x151730` | `0x151768` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0xeea0` | `0xee80` | **`-0x20`** |
| `__AUTH_CONST.__lazy_load_got` | `—` | `0x10` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1440` | `0x1430` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x6940` | `0x6938` | **`-0x8`** |

### Other Changes

```diff

-507.0.0.0.0
+508.0.0.0.0

-  - /System/Library/PrivateFrameworks/TrialEncryption.framework/TrialEncryption

-  Symbols:   9386
-  CStrings:  4228
+  Symbols:   9387
+  CStrings:  4226
Symbols:
+ _OBJC_CLASS_$_TRICryptoKitBridge$lazyGOT
+ _OBJC_CLASS_$_TRICryptoKitBridge$lazyGOT$loadHelper_x8
+ _OBJC_CLASS_$_TRICryptoKitBridge$lazyGOT$loadHelper_x8$for$+[TRIAES256GCMCrypto _decryptDataWithCryptoKit:withKey:aad:error:]+0
+ _OBJC_CLASS_$_TRISelfSignedCertificateGenerator$lazyGOT
+ _OBJC_CLASS_$_TRISelfSignedCertificateGenerator$lazyGOT$loadHelper_x8
+ __dyld_lazy_load
+ _lazyLoadFlag$TrialEncryption
- _OBJC_CLASS_$_TRICryptoKitBridge$loadHelper_x8
- _OBJC_CLASS_$_TRICryptoKitBridge$loadHelper_x8$for$+[TRIAES256GCMCrypto _decryptDataWithCryptoKit:withKey:aad:error:]+0
- _OBJC_CLASS_$_TRISelfSignedCertificateGenerator$loadHelper_x8
- _dlopenHelper$TrialEncryption
- _dlopenHelperFlag$TrialEncryption
- _kAssistantPublicPreferenceDomain
Functions:
~ -[TRIPushNotificationHandler _handleDeploymentNotification:] : 644 -> 676
~ -[TRIPushNotificationHandler _handleRollbackNotification:] : 1168 -> 1192
CStrings:
+ "Jul 10 2026"
+ "TrialXP-508"
- "/System/Library/PrivateFrameworks/TrialEncryption.framework/TrialEncryption"
- "Jun 26 2026"
- "TrialXP-507"
- "com.apple.assistant.public"
```
