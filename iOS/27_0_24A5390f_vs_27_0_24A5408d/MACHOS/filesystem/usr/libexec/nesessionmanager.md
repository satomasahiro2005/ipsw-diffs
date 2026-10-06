## nesessionmanager

> `/usr/libexec/nesessionmanager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb6e3c` | `0xb6ea0` | **`+0x64`** |
| `__TEXT.__oslogstring` | `0x1138b` | `0x113c7` | **`+0x3c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2331.0.0.0.1
+2340.0.0.0.4

-  CStrings:  4301
+  CStrings:  4302
Functions:
~ sub_1000a6c84 : 920 -> 1020
CStrings:
+ "%@: %s - Filter not started, skipping reporting timer setup"
```
