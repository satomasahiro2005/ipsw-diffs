## com.apple.driver.AppleHapticsSupportLEAP

> `com.apple.driver.AppleHapticsSupportLEAP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0xdd0` | `0xe60` | **`+0x90`** |
| `__TEXT_EXEC.__text` | `0x3b724` | `0x3b780` | **`+0x5c`** |
| `__TEXT.__cstring` | `0x78d3` | `0x78b7` | **`-0x1c`** |
| `__TEXT.__const` | `0x3d0` | `0x3e0` | **`+0x10`** |

### Other Changes

```diff

-11.2.0.0.0
+11.4.0.0.0

-  CStrings:  1302
+  CStrings:  1300
Functions:
~ sub_fffffff008fbc87c -> sub_fffffff008fd711c : 1852 -> 1944
CStrings:
- "HRFault"
- "hallResistanceFault"
```
