## AppStoreDaemon

> `/System/Library/PrivateFrameworks/AppStoreDaemon.framework/AppStoreDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x838d4` | `0x83b58` | **`+0x284`** |
| `__AUTH_CONST.__cfstring` | `0x6d60` | `0x6e00` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x164a8` | `0x164d8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x5948` | `0x5960` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xb3b4` | `0xb3cc` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x45c0` | `0x45d0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x628` | `0x630` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x27c0` | `0x27c8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xdf8` | `0xdfc` | **`+0x4`** |

### Other Changes

```diff

-13.0.40.0.0
+13.0.43.0.0

-  Functions: 4482
-  Symbols:   7807
-  CStrings:  1422
+  Functions: 4487
+  Symbols:   7813
+  CStrings:  1426
Symbols:
+ -[ASDTestFlightPackageMetadata diskSpaceMetadata]
+ -[ASDTestFlightPackageMetadata setDiskSpaceMetadata:]
+ _ASDDebugConfigureFileLogging
+ _ASDDebugFileFormatFromOSLogFormat
+ _ASDDebugLogOSStyle
+ _OBJC_IVAR_$_ASDTestFlightPackageMetadata._diskSpaceMetadata
CStrings:
+ "%"
+ "%\\{[^}]*\\}"
+ "DM"
+ "Logs"
```
