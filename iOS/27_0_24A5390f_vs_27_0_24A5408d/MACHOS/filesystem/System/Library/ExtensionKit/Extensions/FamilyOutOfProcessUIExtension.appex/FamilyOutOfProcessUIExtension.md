## FamilyOutOfProcessUIExtension

> `/System/Library/ExtensionKit/Extensions/FamilyOutOfProcessUIExtension.appex/FamilyOutOfProcessUIExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0xd90` | `0x1090` | **`+0x300`** |
| `__TEXT.__text` | `0x1fa74` | `0x1fcb4` | **`+0x240`** |
| `__TEXT.__const` | `0x1050` | `0x11e0` | **`+0x190`** |
| `__TEXT.__swift5_typeref` | `0xbaf` | `0xcfb` | **`+0x14c`** |
| `__TEXT.__eh_frame` | `0x1290` | `0x11e0` | **`-0xb0`** |
| `__TEXT.__auth_stubs` | `0x1670` | `0x1700` | **`+0x90`** |
| `__DATA.__data` | `0xc70` | `0xcd0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xc08` | `0xc58` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0xb40` | `0xb88` | **`+0x48`** |
| `__TEXT.__swift5_assocty` | `0x148` | `0x178` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x67c` | `0x69c` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x548` | `0x564` | **`+0x1c`** |
| `__TEXT.__swift5_proto` | `0x6c` | `0x84` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__TEXT.__swift5_capture` | `0x418` | `0x42c` | **`+0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x490` | `0x4a0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x3a8` | `0x3b8` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x62b` | `0x63b` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x8b8` | `0x8c0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x54` | `0x58` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0xf4` | `0xf0` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x78` | `0x74` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-285.0.0.0.0
+290.0.0.0.0

-  Functions: 588
-  Symbols:   213
+  Functions: 603
+  Symbols:   214
Symbols:
+ _swift_release_x27
CStrings:
+ "Showing alert with flowtype: %ld"
- "shared state updated to: %{bool}d"
```
