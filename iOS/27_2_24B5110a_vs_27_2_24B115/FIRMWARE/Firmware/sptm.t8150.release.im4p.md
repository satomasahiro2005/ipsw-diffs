## sptm.t8150.release.im4p

> `Firmware/sptm.t8150.release.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x622cc` | `0x625f0` | **`+0x324`** |
| `__TEXT.__cstring` | `0x1606e` | `0x16126` | **`+0xb8`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__LATE_CONST.__late_const`

### Other Changes

```diff

-  CStrings:  2582
+  CStrings:  2585
Functions:
~ sub_fffffff0270e3e08 : 6620 -> 6992
~ sub_fffffff0270e5d90 -> sub_fffffff0270e5f04 : 2956 -> 3372
~ sub_fffffff0270ea9b0 -> sub_fffffff0270eacc4 : 3764 -> 3772
~ sub_fffffff0270eb864 -> sub_fffffff0270ebb80 : 13496 -> 13504
~ sub_fffffff027116288 -> sub_fffffff0271165ac : 72 -> 68
CStrings:
+ "%s: dart %p (%s:%u): Inconsistent unganged clock protection configuration"
+ "(&dart_gapf_ungang_map[state->gapf_ungang_map_index].lock)"
+ "SPTM-820.40.24|2026-10-03:14:50:35.671934|"
+ "sptm_t8110dart_skip_disable_clock_protection_write"
- "SPTM-820.40.24|2026-10-03:20:11:40.632663|"
```
