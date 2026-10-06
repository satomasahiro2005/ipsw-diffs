## MXUIServiceClient

> `/System/Library/PrivateFrameworks/MXUIServiceClient.framework/MXUIServiceClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e58` | `0x1e90` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c8` | `0x2e0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x2dc` | `0x2f4` | **`+0x18`** |
| `__TEXT.__cstring` | `0x450` | `0x464` | **`+0x14`** |
| `__TEXT.__gcc_except_tab` | `0x24` | `0x28` | **`+0x4`** |

### Other Changes

```diff

-360.63.1.11.2
+360.66.1.11.1

-  Functions: 59
-  Symbols:   190
+  Functions: 61
+  Symbols:   192
Symbols:
+ -[MXUIService_Client _promptForAudioMovedBanner:iconType:sourceApp:]
+ -[MXUIService_Client promptForReceiverEnabledBanner:]
+ -[MXUIService_Client promptForSpeakerEnabledBanner:]
- -[MXUIService_Client promptForAudioMovedBanner:]
CStrings:
+ "-[MXUIService_Client _promptForAudioMovedBanner:iconType:sourceApp:]"
- "-[MXUIService_Client promptForAudioMovedBanner:]"
```
