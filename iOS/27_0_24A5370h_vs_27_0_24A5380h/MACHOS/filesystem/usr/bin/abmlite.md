## abmlite

> `/usr/bin/abmlite`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c960` | `0x1c8d8` | **`-0x88`** |
| `__TEXT.__gcc_except_tab` | `0x20f4` | `0x20f0` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1570.0.0.0.0
+1576.0.0.0.0
Functions:
~ sub_100004aa0 : 17072 -> 17048
~ sub_100008f20 -> sub_100008f08 : 796 -> 684
```
