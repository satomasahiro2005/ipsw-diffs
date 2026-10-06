## sptm.t8140.release.im4p

> `Firmware/sptm.t8140.release.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x5fa5c` | `0x5fa30` | **`-0x2c`** |
| `__TEXT.__cstring` | `0x15859` | `0x1587f` | **`+0x26`** |
| `__DATA_CONST.__const` | `0x7bf8` | `0x7c00` | **`+0x8`** |

### Same-size Content Changes

- `__LATE_CONST.__late_const`

### Other Changes

```diff

-820.40.18.0.0
+820.40.20.0.0

-  CStrings:  2536
+  CStrings:  2537
Functions:
~ sub_fffffff0270e061c : 1104 -> 1080
~ sub_fffffff0270f0954 -> sub_fffffff0270f093c : 1300 -> 1280
~ sub_fffffff0270f7a18 -> sub_fffffff0270f79ec : 72 -> 68
CStrings:
+ "SPTM-820.40.20|2026-09-13:19:38:35.360456|"
+ "VIOLATION_T8110_DART_UNGANG_GAPF_RACE"
- "SPTM-820.40.18|2026-09-04:20:09:28.017559|"
```
