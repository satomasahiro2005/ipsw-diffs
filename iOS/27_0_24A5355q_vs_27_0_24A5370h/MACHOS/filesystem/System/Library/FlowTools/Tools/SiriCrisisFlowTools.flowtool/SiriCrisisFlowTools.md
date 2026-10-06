## SiriCrisisFlowTools

> `/System/Library/FlowTools/Tools/SiriCrisisFlowTools.flowtool/SiriCrisisFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0x140` | `0x180` | **`+0x40`** |
| `__TEXT.__text` | `0x172bc` | `0x17280` | **`-0x3c`** |
| `__TEXT.__objc_methname` | `0x257` | `0x287` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x50` | `0x60` | **`+0x10`** |
| `__DATA.__data` | `0xe60` | `0xe68` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1a8` | `0x1b0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x58` | `0x54` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.8.4.0.0
+3600.12.4.1.1

+  - /System/Library/PrivateFrameworks/RegulatoryDomain.framework/RegulatoryDomain

-  Functions: 649
-  Symbols:   143
-  CStrings:  154
+  Functions: 647
+  Symbols:   144
+  CStrings:  156
Symbols:
+ _OBJC_CLASS_$_RDEstimate
CStrings:
+ "countryCode"
+ "currentEstimates"
+ "lastKnownEstimates"
- "ISOcountryCode"
```
