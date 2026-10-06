## diskimagespawner

> `/usr/libexec/diskimagespawner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24ff8` | `0x25078` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x2658` | `0x2654` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-596.0.0.0.0
+598.0.0.0.0
Functions:
~ sub_1000099f8 : 308 -> 316
~ sub_100011870 -> sub_100011878 : 564 -> 504
~ sub_100011af0 -> sub_100011abc : 556 -> 736
```
