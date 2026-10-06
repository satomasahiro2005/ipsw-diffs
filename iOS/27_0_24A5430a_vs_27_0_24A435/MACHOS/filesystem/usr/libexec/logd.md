## logd

> `/usr/libexec/logd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27694` | `0x276a4` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__os_assumes_log`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ sub_100000fe8 : 1508 -> 1512
~ sub_10000ae3c -> sub_10000ae40 : 212 -> 216
~ sub_10000fcc8 -> sub_10000fcd0 : 324 -> 328
~ sub_10000fed0 -> sub_10000fedc : 572 -> 576
~ sub_10001010c -> sub_10001011c : 224 -> 228
~ sub_1000119f4 -> sub_100011a08 : 1088 -> 1084
```
