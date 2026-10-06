## BuiltinAudioPlugin

> `/System/Library/Audio/Plug-Ins/HAL/BuiltinAudioPlugin.driver/BuiltinAudioPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1284` | `0x12dc` | **`+0x58`** |
| `__TEXT.__auth_stubs` | `0x1e0` | `0x1f0` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x198` | `0x1a4` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x100` | `0x108` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-200.16.0.0.0
+200.17.0.0.0

-  Symbols:   87
+  Symbols:   88
Symbols:
+ _objc_release_x23
Functions:
~ sub_1178 : 3192 -> 3280
CStrings:
+ "200.17"
- "200.16"
```
