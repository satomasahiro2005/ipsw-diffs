## parsecd

> `/System/Library/PrivateFrameworks/CoreParsec.framework/parsecd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1753e8` | `0x1768f4` | **`+0x150c`** |
| `__TEXT.__unwind_info` | `0x51f0` | `0x54f8` | **`+0x308`** |
| `__TEXT.__const` | `0xefa0` | `0xf0e0` | **`+0x140`** |
| `__DATA.__data` | `0x9c40` | `0x9ce0` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x6216` | `0x6286` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x55a3` | `0x5603` | **`+0x60`** |
| `__DATA.__objc_data` | `0x1630` | `0x1680` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x7590` | `0x75e0` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x4fc8` | `0x500a` | **`+0x42`** |
| `__TEXT.__objc_methname` | `0x6625` | `0x6665` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x41c0` | `0x4200` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x5ab0` | `0x5aec` | **`+0x3c`** |
| `__TEXT.__swift5_fieldmd` | `0x5220` | `0x5254` | **`+0x34`** |
| `__TEXT.__cstring` | `0x6914` | `0x6944` | **`+0x30`** |
| `__DATA.__objc_const` | `0x7760` | `0x7738` | **`-0x28`** |
| `__DATA.__objc_selrefs` | `0x1588` | `0x1598` | **`+0x10`** |
| `__DATA.__common` | `0x5b8` | `0x5c0` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x1f00` | `0x1f08` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x10568` | `0x10570` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1448` | `0x1450` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x49c` | `0x4a0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.56.21.0.0
+3600.56.26.0.0

-  Functions: 9027
-  Symbols:   2347
-  CStrings:  2547
+  Functions: 9057
+  Symbols:   2348
+  CStrings:  2552
Symbols:
+ _OBJC_CLASS_$_RDEstimate
CStrings:
+ "Invalid countryCode: %{sensitive}s received from RegulatoryDomain"
+ "No RegulatoryDomain estimate available; cannot resolve country code"
+ "_parsecdCacheLocations"
+ "currentEstimates"
+ "lastKnownEstimates"
+ "pegasusKitSAMAgenticSearchResponseStream"
- "nil country code received from RegulatoryDomain"
```
