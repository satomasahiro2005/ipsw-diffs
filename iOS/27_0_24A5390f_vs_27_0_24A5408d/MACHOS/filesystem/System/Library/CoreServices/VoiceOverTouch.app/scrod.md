## scrod

> `/System/Library/CoreServices/VoiceOverTouch.app/scrod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbd0c` | `0xbcec` | **`-0x20`** |
| `__TEXT.__cstring` | `0x3a6` | `0x392` | **`-0x14`** |
| `__TEXT.__unwind_info` | `0x310` | `0x318` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_ivar`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-327.0.0.0.0
+329.0.0.0.0
Functions:
~ sub_100002e48 : 204 -> 232
~ sub_10000cc64 -> sub_10000cc80 : 288 -> 228
CStrings:
+ "%@[%p] BT Address: %@ Transport: %@"
- "%@[%p]\n\tBT Address: %@\n\tDriver Model: %@\n\tTransport: %@"
```
