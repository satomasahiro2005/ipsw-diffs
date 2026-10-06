## JournalWidgetsSecure

> `/private/var/staged_system_apps/Journal.app/PlugIns/JournalWidgetsSecure.appex/JournalWidgetsSecure`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbb6a0` | `0xbc31c` | **`+0xc7c`** |
| `__TEXT.__eh_frame` | `0x2d44` | `0x2cd4` | **`-0x70`** |
| `__DATA_CONST.__const` | `0x3ae0` | `0x3a90` | **`-0x50`** |
| `__TEXT.__auth_stubs` | `0x42e0` | `0x4330` | **`+0x50`** |
| `__TEXT.__const` | `0x7c14` | `0x7c64` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x14a8` | `0x14d8` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x2f3` | `0x2c3` | **`-0x30`** |
| `__TEXT.__oslogstring` | `0x118a` | `0x11ba` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x2178` | `0x21a0` | **`+0x28`** |
| `__DATA.__data` | `0x6b40` | `0x6b60` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x15d8` | `0x15f0` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x2308` | `0x2320` | **`+0x18`** |
| `__DATA.__bss` | `0x88c8` | `0x88d8` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x23ad` | `0x239d` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1941` | `0x1951` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2140` | `0x2130` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x6c7a` | `0x6c72` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0xc8` | `0xc0` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x1e0` | `0x1e4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-77.0.0.0.0
+84.0.0.0.0

-  Functions: 2916
-  Symbols:   439
+  Functions: 2913
+  Symbols:   440
Symbols:
+ _NSAdaptiveImageGlyphAttributeName
+ _OBJC_CLASS_$_NSAdaptiveImageGlyph
+ _swift_release_x9
- _objc_retain_x12
- _swift_continuation_resume
CStrings:
+ "Device is locked, skipping update"
+ "imageByPreparingForDisplay"
- "prepareForDisplayWithCompletionHandler:"
- "v16@?0@\"UIImage\"8"
```
