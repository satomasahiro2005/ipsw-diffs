## scrod

> `/System/Library/CoreServices/VoiceOverTouch.app/scrod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbcec` | `0xbd0c` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x720` | `0x730` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x3a0` | `0x3a8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   224
+  Symbols:   225
Symbols:
+ _AXDeviceIsViridian
Functions:
~ sub_100003320 : 648 -> 660
~ sub_100006dcc -> sub_100006dd8 : 828 -> 852
~ sub_1000071f4 -> sub_100007218 : 220 -> 216
```
