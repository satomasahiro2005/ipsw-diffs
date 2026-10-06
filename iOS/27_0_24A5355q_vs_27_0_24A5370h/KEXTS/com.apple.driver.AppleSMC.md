## com.apple.driver.AppleSMC

> `com.apple.driver.AppleSMC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0xac0` | **`+0xac0`** |
| `__TEXT_EXEC.__text` | `0x2b1ac` | `0x2b570` | **`+0x3c4`** |
| `__TEXT.__cstring` | `0x9560` | `0x9603` | **`+0xa3`** |

### Other Changes

```diff

-790.0.0.0.0
-  Functions: 1007
+793.0.0.0.0
+  Functions: 1010

-  CStrings:  1104
+  CStrings:  1110
CStrings:
+ "19:40:42"
+ "19:40:44"
+ "AppleSMCPMU::%s(): %s vectorNumber=%d key=%08x cmd=%08x (%s)\n"
+ "AppleSMCPMU::%s(): %s vectorNumber=%d pcIO(gpio%d) cmd=%016llx (%s)\n"
+ "AppleSMCPMU::%s(vn=%d): %s %x cmd=%08x, value=%x [%s]\n"
+ "AppleSMCPMU::%s(vn=%d): %s pcIO(gpio%d) cmd=%016llx, value=%x [%s]\n"
+ "AppleSMCPMU::%s(vn=%d): value=%x vt=%s [%s]\n"
+ "AppleSMCPMU::start: has_smc_extended_keys = %u\n"
+ "ICFG"
+ "ICLR"
+ "IENA"
+ "Jun 18 2026"
+ "_readSmcGpioKey"
+ "_writeSmcGpioKey"
+ "has_smc_extended_keys"
- "22:51:43"
- "22:51:45"
- "AppleSMCPMU::%s(): ICLR vectorNumber=%d key=%08x cmd=%08x (%s)\n"
- "AppleSMCPMU::%s(vN=%d): key=%08x IENA=%08x [%s]\n"
- "AppleSMCPMU::%s(vN=%d): key=%08x IENA=%x [%s]\n"
- "AppleSMCPMU::%s(vn=%d): ICFG %x cmd=%08x, value=%x vt=%s [%s]\n"
- "May 27 2026"
- "disableVectorHard"
- "enableVector"
```
