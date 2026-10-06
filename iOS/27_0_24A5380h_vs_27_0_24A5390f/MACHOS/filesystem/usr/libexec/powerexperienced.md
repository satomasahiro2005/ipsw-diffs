## powerexperienced

> `/usr/libexec/powerexperienced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a93c` | `0x1ad74` | **`+0x438`** |
| `__TEXT.__oslogstring` | `0x308e` | `0x31b3` | **`+0x125`** |
| `__TEXT.__objc_stubs` | `0x38e0` | `0x39c0` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x414c` | `0x41f5` | **`+0xa9`** |
| `__DATA_CONST.__cfstring` | `0x1340` | `0x13e0` | **`+0xa0`** |
| `__TEXT.__objc_methtype` | `0x840` | `0x8a6` | **`+0x66`** |
| `__TEXT.__auth_stubs` | `0x6d0` | `0x730` | **`+0x60`** |
| `__TEXT.__cstring` | `0x12f1` | `0x1341` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x1138` | `0x1180` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x237c` | `0x23bc` | **`+0x40`** |
| `__DATA.__objc_const` | `0x56e0` | `0x5710` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x378` | `0x3a8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x8d8` | `0x8f8` | **`+0x20`** |
| `__DATA_CONST.__objc_intobj` | `0xf0` | `0x108` | **`+0x18`** |
| `__DATA.__bss` | `0x258` | `0x268` | **`+0x10`** |
| `__TEXT.__const` | `0x138` | `0x148` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x748` | `0x758` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x268` | `0x26c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-168.0.0.0.0
+173.0.0.0.0

-  Functions: 835
-  Symbols:   169
-  CStrings:  1416
+  Functions: 843
+  Symbols:   175
+  CStrings:  1440
Symbols:
+ _CFEqual
+ _CFRelease
+ _MGCopyAnswer
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _sysctlbyname
CStrings:
+ "DataMigration: cached clean boot UUID=%{public}@"
+ "DataMigration: currentBootUUID=%{public}@, cachedBootUUID=%{public}@"
+ "DataMigration: failed to get boot UUID, skipping cache write"
+ "DataMigration: skipping check, already complete this boot (%@)"
+ "DataMigrationLastCleanBootUUID"
+ "NonUI"
+ "ReleaseType"
+ "Restricted perf mode not supported on non-UI build"
+ "T@\"NSMutableDictionary\",&,N,V_currentContext"
+ "T{os_unfair_lock_s=I},N,V_lock"
+ "VendorNonUI"
+ "_lock"
+ "contextSnapshot"
+ "copy"
+ "currentBootSessionUUID"
+ "isMigrationNeeded"
+ "kern.bootsessionuuid"
+ "lock"
+ "setLock:"
+ "setObject:forKey:"
+ "stringForKey:"
+ "stringWithUTF8String:"
+ "v20@0:8{os_unfair_lock_s=I}16"
+ "{os_unfair_lock_s=\"_os_unfair_lock_opaque\"I}"
+ "{os_unfair_lock_s=I}16@0:8"
- "T@\"NSMutableDictionary\",&,V_currentContext"
```
