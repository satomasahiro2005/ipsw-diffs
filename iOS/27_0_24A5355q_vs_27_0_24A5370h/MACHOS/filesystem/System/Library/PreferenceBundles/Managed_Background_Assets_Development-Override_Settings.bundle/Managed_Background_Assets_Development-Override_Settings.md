## Managed Background Assets Development-Override Settings

> `/System/Library/PreferenceBundles/Managed Background Assets Development-Override Settings.bundle/Managed Background Assets Development-Override Settings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22dc` | `0x345c` | **`+0x1180`** |
| `__TEXT.__swift5_typeref` | `0x219` | `0x3d9` | **`+0x1c0`** |
| `__TEXT.__auth_stubs` | `0x4e0` | `0x5f0` | **`+0x110`** |
| `__DATA_CONST.__auth_got` | `0x278` | `0x300` | **`+0x88`** |
| `__TEXT.__const` | `0x118` | `0x182` | **`+0x6a`** |
| `__DATA.__data` | `0xb0` | `0x118` | **`+0x68`** |
| `__TEXT.__cstring` | `0x19a` | `0x1ea` | **`+0x50`** |
| `__TEXT.__eh_frame` | `—` | `0x48` | **`+0x48`** |
| `__DATA_CONST.__auth_ptr` | `0xd0` | `0x110` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x90` | `0xd0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xc0` | `0xf0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xf8` | `0x120` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `—` | `0x10` | **`+0x10`** |
| `__DATA.__bss` | `0x80` | `0x88` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-2.0.26.0.0
+2.0.27.0.0

-  Functions: 29
-  Symbols:   59
-  CStrings:  25
+  Functions: 46
+  Symbols:   64
+  CStrings:  26
Symbols:
+ _objc_release_x27
+ _swift_allocObject
+ _swift_deallocObject
+ _swift_getKeyPath
+ _swift_release_x25
+ _swift_retain_x25
- _objc_release_x25
CStrings:
+ "Xcode is currently controlling the URL override though a debugging session."
```
