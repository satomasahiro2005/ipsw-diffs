## uarphidd

> `/usr/libexec/uarphidd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x47c8` | `0x4844` | **`+0x7c`** |
| `__TEXT.__oslogstring` | `0x777` | `0x79f` | **`+0x28`** |
| `__DATA_CONST.__got` | `0xb8` | `0xc0` | **`+0x8`** |

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

-1587.0.3.0.3
+1587.0.21.0.0

-  CStrings:  349
+  CStrings:  350
Functions:
~ sub_10000351c : 852 -> 976
CStrings:
+ "%s: Failed to create UARP HID Device %@"
```
