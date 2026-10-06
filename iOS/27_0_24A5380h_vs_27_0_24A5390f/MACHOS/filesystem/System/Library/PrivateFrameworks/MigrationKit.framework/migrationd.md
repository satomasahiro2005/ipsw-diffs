## migrationd

> `/System/Library/PrivateFrameworks/MigrationKit.framework/migrationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x185f4` | `0x18838` | **`+0x244`** |
| `__TEXT.__objc_methname` | `0x8eb` | `0x94b` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x6b4` | `0x704` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x3a0` | `0x3e0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x31c` | `0x34c` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x370` | `0x38c` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x228` | `0x240` | **`+0x18`** |
| `__DATA.__data` | `0x480` | `0x490` | **`+0x10`** |
| `__DATA.__objc_const` | `0x5f8` | `0x600` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x180` | `0x188` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x7a8` | `0x7b0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x388` | `0x390` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6f8` | `0x700` | **`+0x8`** |
| `__TEXT.__swift5_reflstr` | `0x10d` | `0x107` | **`-0x6`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1421.0.0.0.0
+1426.0.0.0.0

+  - /System/Library/PrivateFrameworks/IDS.framework/IDS

+  - /usr/lib/swift/libswiftCompression.dylib

-  Functions: 411
-  Symbols:   432
-  CStrings:  204
+  Functions: 414
+  Symbols:   434
+  CStrings:  209
Symbols:
+ _OBJC_CLASS_$_IDSIDQueryController
+ __swift_FORCE_LOAD_$_swiftCompression
CStrings:
+ "flushDeviceQueryForCachedPeers"
+ "invalidateIMessageRegistration"
+ "invalidating stale iMessage registration after the exported line went cold"
+ "migrationd/IMessageRegistration.swift"
+ "sharedInstance"
```
