## IOMFB_bics_daemon

> `/usr/libexec/IOMFB_bics_daemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x5f44` | `0x2c94` | **`-0x32b0`** |
| `__TEXT.__cstring` | `0x5a1c` | `0x5c2c` | **`+0x210`** |
| `__TEXT.__text` | `0x321bc` | `0x32308` | **`+0x14c`** |
| `__DATA_CONST.__auth_ptr` | `0x538` | `0x590` | **`+0x58`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-700.50.108.0.0
+700.50.112.5.0

-  CStrings:  848
+  CStrings:  854
Functions:
~ sub_10000e1f4 : 1388 -> 1720
CStrings:
+ "modeInfoUpdate: ICC curve loc %u is tabular (type %u), skipping the ICC cache and saving mode/preset/UA only\n"
+ "modeInfoUpdate: no write, EAN mode caching unsupported by the driver\n"
+ "modeInfoUpdate: no write, EAN storage not present\n"
+ "modeInfoUpdate: no write, throttled: avg interval %llu s < threshold %llu s (%llu updates over %llu s), persisted record stays stale\n"
+ "modeInfoUpdate: no write, v1CRC 0x%x unchanged, validMask 0x%llx\n"
+ "modeInfoUpdate: writing %u bytes to EAN, validMask 0x%llx (mode %d preset %d iccMat %d iccCurve %d ua %d)\n"
```
