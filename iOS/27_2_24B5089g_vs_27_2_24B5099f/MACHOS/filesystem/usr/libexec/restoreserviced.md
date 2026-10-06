## restoreserviced

> `/usr/libexec/restoreserviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13f34` | `0x13f2c` | **`-0x8`** |

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

```text
Functions:
~ sub_1000131f0 : 12 -> 24
~ sub_1000131fc -> sub_100013208 : 24 -> 12
~ sub_100013214 : 12 -> 28
~ sub_10001489c -> sub_1000148ac : 56 -> 48
~ sub_1000148d4 -> sub_1000148dc : 56 -> 48
~ sub_10001490c : 56 -> 48
```
