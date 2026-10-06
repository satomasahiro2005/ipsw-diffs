## MobileBackup

> `/System/Library/PrivateFrameworks/MobileBackup.framework/MobileBackup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x5700` | `0x56e0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x7a46` | `0x7a30` | **`-0x16`** |
| `__TEXT.__text` | `0x2e0dc` | `0x2e0c8` | **`-0x14`** |
| `__TEXT.__const` | `0x590` | `0x598` | **`+0x8`** |

### Other Changes

```diff

-3038.0.0.0.0
+3039.0.1.0.0

-  Functions: 1571
-  Symbols:   2592
-  CStrings:  1139
+  Functions: 1570
+  Symbols:   2591
+  CStrings:  1138
Symbols:
- _MBDeviceCoverGlassColor
Functions:
~ _MBIsTransientErrorCode : 144 -> 148
+ _MBDeviceTotalDiskCapacity
- _MBDeviceTotalDiskCapacity
- _MBMarketingName
~ ____MBGetCachedGestaltValues_block_invoke : 700 -> 688
CStrings:
- "DeviceCoverGlassColor"
```
