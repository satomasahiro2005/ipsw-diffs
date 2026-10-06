## apfs.util

> `/System/Library/Filesystems/apfs.fs/apfs.util`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f34` | `0x2f50` | **`+0x1c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3277.0.0.0.1
+3283.0.0.0.0
Functions:
~ sub_1000007c0 : 3512 -> 3532
~ sub_1000016b4 -> sub_1000016c8 : 60 -> 56
~ sub_100001e58 -> sub_100001e68 : 328 -> 316
~ sub_10000210c -> sub_100002110 : 916 -> 932
~ sub_10000272c -> sub_100002740 : 960 -> 972
~ sub_100002aec -> sub_100002b0c : 1620 -> 1616
```
