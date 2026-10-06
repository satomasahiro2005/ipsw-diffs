## libnfshared.dylib

> `/usr/lib/libnfshared.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x550` | `—` | **`-0x550`** |
| `__DATA_DIRTY.__objc_data` | `0x640` | `0xb90` | **`+0x550`** |
| `__TEXT.__text` | `0x25b30` | `0x25b0c` | **`-0x24`** |
| `__TEXT.__const` | `0x2c0` | `0x2c8` | **`+0x8`** |
| `__TEXT.__cstring` | `0x4de0` | `0x4dde` | **`-0x2`** |

### Other Changes

```diff

-371.7.0.0.0
+371.8.0.0.0
Functions:
~ sub_23ef2f024 -> sub_23fef9f8c : 208 -> 188
~ sub_23ef47ddc -> sub_23ff12d30 : 148 -> 128
~ sub_23ef47e70 -> sub_23ff12db0 : 120 -> 124
CStrings:
+ "NFTimer: popTimeInSeconds: %f"
- "NFTimer: popTimeInSeconds: %llu"
```
