## neagent

> `/usr/libexec/neagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ae4c` | `0x1af1c` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0x3ebe` | `0x3efa` | **`+0x3c`** |

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

-  CStrings:  1174
+  CStrings:  1175
Functions:
~ sub_10000dc68 : 920 -> 1020
~ sub_10001a204 -> sub_10001a268 : 2404 -> 2512
CStrings:
+ "%@: %s - Filter not started, skipping reporting timer setup"
```
