## racoon

> `/usr/sbin/racoon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x62f28` | `0x62f40` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ sub_100018e2c : 856 -> 860
~ sub_100023ad8 -> sub_100023adc : 1216 -> 1220
~ sub_10003a6c8 -> sub_10003a6d0 : 316 -> 320
~ sub_10004d4d8 -> sub_10004d4e4 : 8984 -> 8996
~ sub_100052e30 -> sub_100052e48 : 44 -> 28
~ sub_100052e5c -> sub_100052e64 : 28 -> 44
```
