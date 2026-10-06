## CoreServicesInternal

> `/System/Library/PrivateFrameworks/CoreServicesInternal.framework/CoreServicesInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e16c` | `0x2e390` | **`+0x224`** |
| `__TEXT.__oslogstring` | `0x20d1` | `0x2115` | **`+0x44`** |
| `__TEXT.__unwind_info` | `0xaa8` | `0xab8` | **`+0x10`** |
| `__DATA.__data` | `0x9c` | `0xa0` | **`+0x4`** |

### Other Changes

```diff

-609.1.3.0.0
+609.1.7.0.0

-  Functions: 652
-  Symbols:   1214
-  CStrings:  482
+  Functions: 655
+  Symbols:   1216
+  CStrings:  483
Symbols:
+ _MountInfoGetCachedVolumeSize
+ __FSURLGetCachedVolumeTotalCapacity
Functions:
+ __FSURLGetCachedVolumeTotalCapacity
+ _MountInfoGetCachedVolumeSize
+ __FSURLGetCachedVolumeTotalCapacity.cold.1
CStrings:
+ "_FSURLGetCachedVolumeTotalCapacity: false result with no real error"
```
