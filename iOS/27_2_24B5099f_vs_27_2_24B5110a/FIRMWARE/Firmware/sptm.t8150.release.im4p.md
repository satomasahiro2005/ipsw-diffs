## sptm.t8150.release.im4p

> `Firmware/sptm.t8150.release.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x62038` | `0x622cc` | **`+0x294`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__LATE_CONST.__late_const`
- `__TEXT.__cstring`

### Other Changes

```diff

-820.40.23.0.0
+820.40.24.0.0
Functions:
~ sub_fffffff0270d5d04 : 996 -> 1648
~ sub_fffffff0270db48c -> sub_fffffff0270db718 : 608 -> 616
~ sub_fffffff027115ff4 -> sub_fffffff027116288 : 76 -> 72
CStrings:
+ "SPTM-820.40.24|2026-10-03:20:11:40.632663|"
- "SPTM-820.40.23|2026-09-27:19:59:11.633384|"
```
