## MauiAUSP

> `/System/Library/ExtensionKit/Extensions/MauiAUSP.appex/MauiAUSP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x440` | `0x350` | **`-0xf0`** |
| `__TEXT.__auth_stubs` | `0x180` | `0xf0` | **`-0x90`** |
| `__DATA.__objc_const` | `0x1d8` | `0x190` | **`-0x48`** |
| `__DATA_CONST.__auth_got` | `0xc8` | `0x80` | **`-0x48`** |
| `__DATA.__objc_data` | `0x100` | `0xc0` | **`-0x40`** |
| `__TEXT.__constg_swiftt` | `0x80` | `0x50` | **`-0x30`** |
| `__TEXT.__objc_methname` | `0x1e7` | `0x1c1` | **`-0x26`** |
| `__TEXT.__swift5_typeref` | `0x30` | `0x14` | **`-0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0x28` | `0x10` | **`-0x18`** |
| `__TEXT.__swift5_reflstr` | `0x18` | `—` | **`-0x18`** |
| `__DATA.__data` | `0x160` | `0x150` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0xd0` | `0xc8` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x8` | `—` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x16c` | `0x164` | **`-0x8`** |
| `__TEXT.__objc_methtype` | `0x162` | `0x169` | **`+0x7`** |

### Same-size Content Changes

- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_types`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-681.0.0.0.0
+683.2.0.0.0

-  Functions: 12
-  Symbols:   52
-  CStrings:  55
+  Functions: 10
+  Symbols:   42
+  CStrings:  51
Symbols:
- _objc_release
- _objc_release_x20
- _objc_release_x22
- _objc_release_x24
- _objc_release_x8
- _objc_release_x9
- _objc_retain_x19
- _objc_retain_x20
- _objc_retain_x23
- _swift_deletedMethodError
CStrings:
- ".cxx_destruct"
- "auAudioUnit"
- "observation"
- "v16@0:8"
```
