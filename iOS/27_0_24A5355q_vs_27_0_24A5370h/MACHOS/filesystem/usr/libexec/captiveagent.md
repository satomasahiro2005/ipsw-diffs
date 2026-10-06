## captiveagent

> `/usr/libexec/captiveagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10724` | `0x1074c` | **`+0x28`** |
| `__TEXT.__const` | `0x146` | `0x13e` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-538.0.0.0.1
+539.0.0.0.0
Functions:
~ sub_10000cf30 : 604 -> 600
~ sub_10000ed34 -> sub_10000ed30 : 2936 -> 2972
~ sub_10000fc80 -> sub_10000fca0 : 2776 -> 2784
```
