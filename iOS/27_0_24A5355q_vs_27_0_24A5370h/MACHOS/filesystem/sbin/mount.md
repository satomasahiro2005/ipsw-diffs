## mount

> `/sbin/mount`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4dcc` | `0x4e0c` | **`+0x40`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ sub_1000045cc : 236 -> 240
~ sub_1000046b8 -> sub_1000046bc : 172 -> 196
~ sub_100004764 -> sub_100004780 : 2252 -> 2276
~ sub_100005030 -> sub_100005064 : 140 -> 164
~ sub_100005158 -> sub_1000051a4 : 180 -> 156
~ sub_10000521c -> sub_100005250 : 408 -> 432
~ sub_1000053b4 -> sub_100005400 : 224 -> 212
~ sub_1000054ac -> sub_1000054ec : 104 -> 108
~ sub_100005514 -> sub_100005558 : 256 -> 252
```
