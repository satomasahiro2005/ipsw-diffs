## logd_helper

> `/usr/libexec/logd_helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x140` | `0x130` | **`-0x10`** |
| `__TEXT.__text` | `0x5d9c` | `0x5d8c` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA.__os_assumes_log`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1958.0.0.0.1
+1965.0.0.0.0
Functions:
~ sub_100002914 : 1068 -> 1060
~ sub_100002d40 -> sub_100002d38 : 452 -> 444
```
