## SafariCore

> `/System/Library/PrivateFrameworks/SafariCore.framework/SafariCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ed8b0` | `0x1ed910` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x1af00` | `0x1af20` | **`+0x20`** |
| `__TEXT.__cstring` | `0x17047` | `0x17067` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x16308` | `0x16318` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xd124` | `0xd134` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x59b8` | `0x59c0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x7608` | `0x7610` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x9b78` | `0x9b80` | **`+0x8`** |

### Other Changes

```diff

-625.1.29.10.29
+625.1.29.10.33

-  Functions: 11246
-  Symbols:   12025
-  CStrings:  5271
+  Functions: 11247
+  Symbols:   12027
+  CStrings:  5272
Symbols:
+ +[WBSFeatureAvailability isNotifyMeWhenJitterEnabled]
+ _WBSDebugNotifyMeWhenJitterEnabledKey
Functions:
+ +[WBSFeatureAvailability isNotifyMeWhenJitterEnabled]
CStrings:
+ "WBSDebugNotifyMeWhenJitterEnabled"
```
