## AlarmUIPlugin

> `/System/Library/Snippets/UIPlugins/AlarmUIPlugin.bundle/AlarmUIPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29ec` | `0x2b8c` | **`+0x1a0`** |
| `__TEXT.__auth_stubs` | `0x410` | `0x460` | **`+0x50`** |
| `__TEXT.__const` | `0x26e` | `0x2ae` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0xb4` | `0xe0` | **`+0x2c`** |
| `__DATA_CONST.__auth_got` | `0x208` | `0x230` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x1d8` | `0x1f8` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x150` | `0x168` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__TEXT.__swift5_typeref` | `0x4cc` | `0x4e0` | **`+0x14`** |
| `__DATA.__bss` | `0x210` | `0x220` | **`+0x10`** |
| `__DATA.__data` | `0x238` | `0x248` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x48` | `0x54` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x110` | `0x118` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xc` | `0x10` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3605.9.1.0.0
+3605.13.1.0.0

-  Functions: 65
-  Symbols:   63
+  Functions: 70
+  Symbols:   65
Symbols:
+ _swift_getForeignTypeMetadata
+ _swift_release
```
