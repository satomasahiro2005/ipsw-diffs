## ltop

> `/usr/bin/ltop`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd74` | `0xd70` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1066.0.0.0.0
+1068.0.0.0.0
Functions:
~ sub_100000610 : 2064 -> 2068
~ sub_100000f24 -> sub_100000f28 : 292 -> 284
```
