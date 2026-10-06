## AppearanceSettings

> `/System/Library/PreferenceBundles/AppearanceSettings.bundle/AppearanceSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd344` | `0xd4b4` | **`+0x170`** |
| `__TEXT.__cstring` | `0x2c8` | `0x308` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x2fc` | `0x31c` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x3a0` | `0x3c0` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1ac` | `0x1c5` | **`+0x19`** |
| `__TEXT.__swift5_fieldmd` | `0x1c8` | `0x1e0` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0xdf0` | `0xde0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x350` | `0x360` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xf0` | `0xf8` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x700` | `0x6f8` | **`-0x8`** |
| `__DATA_CONST.__const` | `0x400` | `0x408` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-1215.1.3.0.0
+1215.1.5.0.0

-  Functions: 288
-  Symbols:   130
-  CStrings:  65
+  Functions: 290
+  Symbols:   127
+  CStrings:  68
Symbols:
+ _swift_release_x23
+ _swift_retain_x11
+ _swift_retain_x8
- _swift_bridgeObjectRelease_n
- _swift_bridgeObjectRetain_n
- _swift_release_x27
- _swift_retain_n
- _swift_retain_x19
- _swift_retain_x27
CStrings:
+ "AppearanceDarkDuo"
+ "AppearanceLightDuo"
+ "displayEdgeCompensationAvailable"
```
