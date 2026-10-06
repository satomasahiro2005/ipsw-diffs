## dhcp6d

> `/usr/libexec/dhcp6d`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8154` | `0x8138` | **`-0x1c`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-553.0.0.0.0
+554.0.0.0.0
Functions:
~ sub_100002e5c : 820 -> 800
~ sub_100006098 -> sub_100006084 : 424 -> 428
~ sub_100007770 -> sub_100007760 : 908 -> 900
~ sub_100007e8c -> sub_100007e74 : 1916 -> 1912
```
