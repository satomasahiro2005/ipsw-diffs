## powerd

> `/System/Library/CoreServices/powerd.bundle/powerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x78230` | `0x78568` | **`+0x338`** |
| `__TEXT.__objc_methname` | `0x722c` | `0x7303` | **`+0xd7`** |
| `__TEXT.__oslogstring` | `0xe258` | `0xe309` | **`+0xb1`** |
| `__TEXT.__objc_stubs` | `0x5920` | `0x59a0` | **`+0x80`** |
| `__DATA.__objc_const` | `0x56b8` | `0x5718` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x26c0` | `0x2680` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x2c8c` | `0x2cbc` | **`+0x30`** |
| `__TEXT.__cstring` | `0x6ebc` | `0x6ee1` | **`+0x25`** |
| `__DATA.__objc_selrefs` | `0x1c38` | `0x1c58` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x7700` | `0x7720` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x1bf0` | `0x1c10` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xe08` | `0xe18` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x3d4` | `0x3dc` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2043.40.44.0.0
+2043.40.52.0.2

-  Functions: 2652
-  Symbols:   575
-  CStrings:  4077
+  Functions: 2658
+  Symbols:   577
+  CStrings:  4088
Symbols:
+ __CFPreferencesSetMultipleWithContainer
+ _objc_setProperty_nonatomic
CStrings:
+ "%@: collecting (connState=%u ncrs=%@ connChanged=%d ncrChanged=%d)"
+ "DataCollectOnNotChargingReasonChange"
+ "Failed to initialize new pack data (packId=%u status=0x%x)"
+ "Failed to write to CFPreferences (status=0x%x)"
+ "Not initializing due to auth not passing (packId=%u failedAuthServiceFlags=%llx)"
+ "T@\"NSMutableDictionary\",&,N,V_lastNotChargingReasons"
+ "TB,N,V_collectOnNCRChange"
+ "_collectOnNCRChange"
+ "_lastNotChargingReasons"
+ "collectOnNCRChange"
+ "lastNotChargingReasons"
+ "setCollectOnNCRChange:"
+ "setLastNotChargingReasons:"
- "Connected state changed to %u"
- "Failed to initialize new pack data (packId=%u)"
```
