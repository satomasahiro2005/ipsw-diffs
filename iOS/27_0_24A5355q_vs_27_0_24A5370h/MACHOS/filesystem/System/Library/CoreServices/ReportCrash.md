## ReportCrash

> `/System/Library/CoreServices/ReportCrash`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x497dc` | `0x4960c` | **`-0x1d0`** |
| `__TEXT.__objc_stubs` | `0x3f20` | `0x3f80` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x2b31` | `0x2b81` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x43f2` | `0x4432` | **`+0x40`** |
| `__TEXT.__const` | `0xc08` | `0xbe0` | **`-0x28`** |
| `__TEXT.__swift5_typeref` | `0x513` | `0x4ec` | **`-0x27`** |
| `__TEXT.__cstring` | `0x5afb` | `0x5b1b` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x420` | `0x440` | **`+0x20`** |
| `__DATA.__data` | `0x908` | `0x8f0` | **`-0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x584` | `0x59c` | **`+0x18`** |
| `__DATA.__objc_const` | `0x25c0` | `0x25d0` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x10e8` | `0x10f0` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1670` | `0x1678` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xf28` | `0xf30` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xb30` | `0xb28` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1049.0.0.502.1
+1056.0.3.0.0

-  Functions: 975
+  Functions: 974

-  CStrings:  2246
+  CStrings:  2250
CStrings:
+ "CPUTrace enabled on ReportCrash"
+ "CPUTraceEnabled not set; skipping tailspin save"
+ "isEligibleForSharingWithThirdPartyDevelopers"
+ "notifIsGameTestModeUnsupported"
```
