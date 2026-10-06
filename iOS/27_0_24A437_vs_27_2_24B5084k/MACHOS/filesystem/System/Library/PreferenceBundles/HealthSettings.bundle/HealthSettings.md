## HealthSettings

> `/System/Library/PreferenceBundles/HealthSettings.bundle/HealthSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f80` | `0x32f8` | **`+0x378`** |
| `__TEXT.__auth_stubs` | `0x4e0` | `0x550` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x6c` | `0xbc` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x33c` | `0x375` | **`+0x39`** |
| `__DATA_CONST.__auth_got` | `0x278` | `0x2b0` | **`+0x38`** |
| `__DATA.__data` | `0x158` | `0x178` | **`+0x20`** |
| `__TEXT.__cstring` | `0x116` | `0x136` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x140` | `0x158` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x78` | `0x90` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x110` | `0x120` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x10d` | `0x11b` | **`+0xe`** |
| `__TEXT.__const` | `0x1d2` | `0x1da` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x98` | `0xa0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

-  Functions: 61
-  Symbols:   77
-  CStrings:  19
+  Functions: 63
+  Symbols:   80
+  CStrings:  20
Symbols:
+ _objc_release_x19
+ _objc_release_x23
+ _objc_retain_x27
CStrings:
+ "PERSONALIZED_SUGGESTIONS_ITEM"
```
