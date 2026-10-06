## tvremoted

> `/usr/libexec/tvremoted`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x110bc` | `0x110d4` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x26cb` | `0x26d7` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-627.0.19.0.0
+627.0.28.0.0
Functions:
~ sub_10000ca00 : 936 -> 960
CStrings:
+ "Device disconnected: %@ reason: %ld"
- "Device disconnected: %@"
```
