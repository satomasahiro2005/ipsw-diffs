## VideosUICore

> `/System/Library/PrivateFrameworks/VideosUICore.framework/VideosUICore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35418` | `0x35700` | **`+0x2e8`** |
| `__AUTH_CONST.__cfstring` | `0x62a0` | `0x6340` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x165b` | `0x16be` | **`+0x63`** |
| `__TEXT.__cstring` | `0x3454` | `0x34b5` | **`+0x61`** |
| `__AUTH_CONST.__objc_const` | `0x8688` | `0x86c0` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x5664` | `0x568c` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x3c98` | `0x3cb0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x650` | `0x658` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1160` | `0x1168` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x560` | `0x564` | **`+0x4`** |

### Other Changes

```diff

-1145.1.3.0.0
+1145.10.20.0.0

+  - /System/Library/PrivateFrameworks/TVAppServices.framework/TVAppServices

-  Functions: 1880
-  Symbols:   3687
-  CStrings:  954
+  Functions: 1883
+  Symbols:   3694
+  CStrings:  963
Symbols:
+ +[VUICoreUtilities setUsePrepareImageForDisplay:]
+ +[VUICoreUtilities usePrepareImageForDisplay]
+ +[VUIDevice isPadOrPhoneWithLandscapeSupport]
+ GCC_except_table48
+ _OBJC_CLASS_$_TVAppBag
+ _OBJC_IVAR_$_VUIApplicationNotificationManager._didStartListeningForApplicationNotifications
+ __OBJC_$_INSTANCE_VARIABLES_VUIApplicationNotificationManager
+ _sUsePrepareImageForDisplay
- GCC_except_table46
CStrings:
+ "VUIApplicationNotificationManager:: listenForApplicationNotifications already registered, skipping"
+ "metadata-sl"
+ "ripple"
+ "sp_personal"
+ "sparkleRelatedV2"
+ "sparkleV2"
+ "sparkle_related_v2"
+ "sparkle_v2"
+ "tricycle"
```
