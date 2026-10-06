## proximitycontrold

> `/usr/libexec/proximitycontrold`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2608e4` | `0x260cdc` | **`+0x3f8`** |
| `__DATA.__bss` | `0x2b270` | `0x2b370` | **`+0x100`** |
| `__TEXT.__const` | `0x210a8` | `0x21168` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x7c69` | `0x7d19` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x15368` | `0x153e8` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x98e3` | `0x9943` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0xd674` | `0xd6b0` | **`+0x3c`** |
| `__TEXT.__swift5_fieldmd` | `0x9298` | `0x92cc` | **`+0x34`** |
| `__TEXT.__objc_methname` | `0xde19` | `0xde49` | **`+0x30`** |
| `__DATA.__data` | `0x179a8` | `0x179c8` | **`+0x20`** |
| `__DATA.__objc_const` | `0x187d8` | `0x187f8` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x3570` | `0x3580` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x6b80` | `0x6b90` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1ac0` | `0x1ac8` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x1a50` | `0x1a58` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x11c` | `0x124` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1788` | `0x1790` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x8ac` | `0x8b0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-376.0.14.0.0
+376.1.2.0.0

+  - /System/Library/PrivateFrameworks/BackBoardServices.framework/BackBoardServices

-  Functions: 10266
-  Symbols:   1631
-  CStrings:  4151
+  Functions: 10273
+  Symbols:   1632
+  CStrings:  4156
Symbols:
+ _$s7Combine9PublishedV18_enclosingInstance7wrapped7storagexqd___s24ReferenceWritableKeyPathCyqd__xGAHyqd__ACyxGGtcRld__CluiMZ
CStrings:
+ ", isDeviceStateSupported="
+ "<OrientationContext orientation="
+ "Device state configuration does not support Handoff"
+ "_forceIsInterfaceOrientationSupported"
+ "forceIsInterfaceOrientationSupported"
+ "orientationChanged( "
- "orientationChanged( orientation="
```
