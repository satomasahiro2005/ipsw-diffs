## com.apple.driver.AppleStockholmControl

> `com.apple.driver.AppleStockholmControl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x14da4` | `0x14bd8` | **`-0x1cc`** |
| `__TEXT.__cstring` | `0x47ef` | `0x478b` | **`-0x64`** |

### Other Changes

```diff

-370.37.0.0.0
+370.38.2.0.0

-  CStrings:  467
+  CStrings:  465
Functions:
~ __ZN18AppleStockholmSPMI20_setVirtualGPIOGatedEh : 924 -> 776
~ __ZN18AppleStockholmSPMI22_setStandbyEnableGatedEb : 924 -> 768
~ __ZN18AppleStockholmSPMI16_vGPIOWriteGatedEhi : 716 -> 560
CStrings:
+ "[%llu] %s::%s:%d write to SPMI[0x%02X] - %02x, attempt %d"
- "[%llu] %s::%s:%d attempt %d"
- "[%llu] %s::%s:%d second write to SPMI was NACKed, ignore NACK since this is a reset"
- "[%llu] %s::%s:%d write to SPMI[0x%02X] - %02x"
```
