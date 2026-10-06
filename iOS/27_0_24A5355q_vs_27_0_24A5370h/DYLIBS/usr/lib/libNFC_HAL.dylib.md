## libNFC_HAL.dylib

> `/usr/lib/libNFC_HAL.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x180a0` | `0x180cc` | **`+0x2c`** |
| `__TEXT.__unwind_info` | `0x250` | `0x238` | **`-0x18`** |
| `__TEXT.__oslogstring` | `0x2570` | `0x2578` | **`+0x8`** |

### Other Changes

```diff

-370.33.1.0.0
+370.37.0.0.0
CStrings:
+ "Error : read received after shutdown : %p / %p. Driver controller type 0x%x, Controller config type %d"
- "Error : read received after shutdown : %p / %p. Driver context %llu, Controller config type %d"
```
