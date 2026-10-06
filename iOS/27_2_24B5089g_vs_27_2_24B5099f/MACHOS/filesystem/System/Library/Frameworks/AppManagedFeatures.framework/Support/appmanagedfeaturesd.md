## appmanagedfeaturesd

> `/System/Library/Frameworks/AppManagedFeatures.framework/Support/appmanagedfeaturesd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8674c` | `0x87c54` | **`+0x1508`** |
| `__TEXT.__eh_frame` | `0x66b8` | `0x673c` | **`+0x84`** |
| `__DATA_CONST.__const` | `0x18e8` | `0x1928` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x145d` | `0x149d` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x1260` | `0x12a0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1c28` | `0x1c68` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0xbdf` | `0xc01` | **`+0x22`** |
| `__DATA.__data` | `0x15b8` | `0x15d8` | **`+0x20`** |
| `__TEXT.__const` | `0x341c` | `0x343c` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x5b0` | `0x5c0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x2140` | `0x2150` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x5f4` | `0x600` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x10a8` | `0x10b0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x848` | `0x840` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x37c` | `0x380` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x3d4` | `0x3d8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-58.40.9.0.0
+58.40.13.0.0

-  Functions: 1545
-  Symbols:   997
-  CStrings:  668
+  Functions: 1561
+  Symbols:   999
+  CStrings:  670
Symbols:
+ _$s11Distributed0A23TargetInvocationDecoderP18decodeNextArgumentqd__yKlFTj
+ _$s18AppManagedFeatures18ManagementProviderV16minimumOSVersionSo24NSOperatingSystemVersionavg
+ _$ss6HasherV5_hash4seed_S2i_s6UInt64VtFZ
+ _$ss6UInt64VSHsWP
- _$s14XPCDistributed9XPCSystemC17InvocationDecoderV18decodeNextArgumentxyKSeRzSERzlF
- _swift_conformsToProtocol2
CStrings:
+ "isOperatingSystemAtLeastVersion:"
+ "setAdditionalQueryParams:"
```
