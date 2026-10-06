## BuiltinAudioPlugin

> `/System/Library/Audio/Plug-Ins/HAL/BuiltinAudioPlugin.driver/BuiltinAudioPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12b0` | `0x1284` | **`-0x2c`** |
| `__DATA_CONST.__got` | `0x140` | `0x138` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-200.15.0.0.0
+200.16.0.0.0

-  Symbols:   88
+  Symbols:   87
Symbols:
- _kASDTConfigKeyAddNonSecurePathEnableProperty
Functions:
~ sub_1178 : 3236 -> 3192
CStrings:
+ "200.16"
- "200.15"
```
