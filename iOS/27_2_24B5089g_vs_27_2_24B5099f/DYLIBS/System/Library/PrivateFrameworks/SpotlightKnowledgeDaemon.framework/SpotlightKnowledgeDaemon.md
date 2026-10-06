## SpotlightKnowledgeDaemon

> `/System/Library/PrivateFrameworks/SpotlightKnowledgeDaemon.framework/SpotlightKnowledgeDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4b1c98` | `0x4b1aec` | **`-0x1ac`** |
| `__TEXT.__eh_frame` | `0x15898` | `0x15960` | **`+0xc8`** |
| `__AUTH_CONST.__cfstring` | `0x9400` | `0x93c0` | **`-0x40`** |
| `__TEXT.__cstring` | `0x162f3` | `0x162c3` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0xcd60` | `0xcd90` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x19778` | `0x19750` | **`-0x28`** |
| `__AUTH_CONST.__objc_const` | `0x18508` | `0x18528` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0xd608` | `0xd5e8` | **`-0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0xa30` | `0xa20` | **`-0x10`** |
| `__TEXT.__const` | `0x17a68` | `0x17a78` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x9618` | `0x9628` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x3900` | `0x38f0` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x37f0` | `0x37f8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x5e80` | `0x5e88` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x5c6c` | `0x5c64` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xb90` | `0xb94` | **`+0x4`** |

### Other Changes

```diff

-2465.1.3.0.0
+2465.1.7.0.0

-  Functions: 16839
-  Symbols:   11652
-  CStrings:  3765
+  Functions: 16850
+  Symbols:   11654
+  CStrings:  3763
Symbols:
+ -[SKDLocationProcessor isRecentRecord:]
+ -[SKGDataDetector enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:enablePIR:entityBlock:rangeBlock:errorBlock:]
+ -[SKGDataDetector enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:enablePIR:entityCategories:entityBlock:rangeBlock:errorBlock:]
+ -[SKGDataDetector enumerateDetectedLocationsInString:locale:enablePIR:entityBlock:rangeBlock:errorBlock:]
+ -[SKGDataDetector locationFromAddress:locale:enablePIR:errorBlock:]
+ _OBJC_IVAR_$_SKGDataDetector._defaults
+ ___swift_closure_destructor.26Tm
- -[SKDLocationProcessor shouldLookupOnlineLocationsForRecord:]
- -[SKGDataDetector enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:entityBlock:rangeBlock:errorBlock:]
- -[SKGDataDetector enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:entityCategories:entityBlock:rangeBlock:errorBlock:]
- -[SKGDataDetector enumerateDetectedLocationsInString:locale:entityBlock:rangeBlock:errorBlock:]
- ___swift_closure_destructor.30Tm
CStrings:
- "enableOfflineLocations"
- "enableOnlineLocations"
```
