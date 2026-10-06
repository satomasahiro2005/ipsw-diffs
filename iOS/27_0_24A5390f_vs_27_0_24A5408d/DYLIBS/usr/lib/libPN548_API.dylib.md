## libPN548_API.dylib

> `/usr/lib/libPN548_API.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f97c` | `0x3fe34` | **`+0x4b8`** |
| `__TEXT.__cstring` | `0x9261` | `0x92f1` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x789e` | `0x791c` | **`+0x7e`** |
| `__DATA_CONST.__const` | `0xe18` | `0xe38` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x598` | `0x5a0` | **`+0x8`** |

### Other Changes

```diff

-370.40.2.0.0
+370.42.1.0.0

-  Functions: 415
-  Symbols:   348
-  CStrings:  1782
+  Functions: 417
+  Symbols:   350
+  CStrings:  1790
Symbols:
+ _NFDriverSetReaderModeDynamicBBA
+ _NFPlatformHasAlternateRFSettingsForPACE
CStrings:
+ "%s:%i %s reader mode dynamic BBA control"
+ "%s:%i %s reader mode static BBA control"
+ "%s:%i CRC error 0x%x"
+ "%s:%i Running build from (B&I) Stockholm_Base-370.42.1"
+ "%{public}s:%i %s reader mode dynamic BBA control"
+ "%{public}s:%i %s reader mode static BBA control"
+ "%{public}s:%i CRC error 0x%x"
+ "%{public}s:%i Running build from (B&I) Stockholm_Base-370.42.1"
+ "CRC error"
+ "NFDriverSetReaderModeDynamicBBA"
- "%s:%i Running build from (B&I) Stockholm_Base-370.40.2"
- "%{public}s:%i Running build from (B&I) Stockholm_Base-370.40.2"
```
