## MDESettings

> `/System/Library/Settings/DefaultApps/MDESettings.plugin/MDESettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55b8` | `0x6ca8` | **`+0x16f0`** |
| `__TEXT.__swift5_typeref` | `0x51c` | `0x8c2` | **`+0x3a6`** |
| `__TEXT.__const` | `0x594` | `0x794` | **`+0x200`** |
| `__DATA.__bss` | `0x7a0` | `0x930` | **`+0x190`** |
| `__DATA_CONST.__const` | `0x1c8` | `0x318` | **`+0x150`** |
| `__TEXT.__auth_stubs` | `0x950` | `0xa80` | **`+0x130`** |
| `__DATA.__data` | `0x548` | `0x620` | **`+0xd8`** |
| `__DATA_CONST.__auth_ptr` | `0x2b0` | `0x388` | **`+0xd8`** |
| `__DATA_CONST.__auth_got` | `0x4b0` | `0x548` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x210` | `0x298` | **`+0x88`** |
| `__TEXT.__swift5_fieldmd` | `0xf0` | `0x14c` | **`+0x5c`** |
| `__DATA_CONST.__got` | `0x130` | `0x188` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0x204` | `0x24c` | **`+0x48`** |
| `__TEXT.__swift5_reflstr` | `0xd3` | `0x10e` | **`+0x3b`** |
| `__TEXT.__swift5_assocty` | `0x78` | `0xa8` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0xcc` | `0xec` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xa0` | `0xc0` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x10` | `0x30` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x3c` | `0x48` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x18` | `0x20` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-360.58.1.0.0
+360.63.1.11.2

+  - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics

-  Functions: 150
-  Symbols:   109
-  CStrings:  33
+  Functions: 195
+  Symbols:   111
+  CStrings:  34
Symbols:
+ _CGRectGetMidX
+ _CGRectGetMidY
+ _OBJC_CLASS_$_UIColor
+ _free
+ _swift_coroFrameAlloc
+ _swift_getForeignTypeMetadata
+ _swift_retain_x23
- _swift_release_x23
- _swift_release_x27
- _swift_retain_x21
- _swift_retain_x27
- _swift_retain_x28
CStrings:
+ "secondarySystemGroupedBackgroundColor"
```
