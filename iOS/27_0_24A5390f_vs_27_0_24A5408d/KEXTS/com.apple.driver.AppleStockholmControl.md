## com.apple.driver.AppleStockholmControl

> `com.apple.driver.AppleStockholmControl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x14bd8` | `0x14ccc` | **`+0xf4`** |
| `__TEXT.__cstring` | `0x478b` | `0x47a9` | **`+0x1e`** |

### Other Changes

```diff

-370.40.2.0.0
-  Functions: 239
+370.42.1.0.0
+  Functions: 240
Functions:
~ __ZN18AppleStockholmSPMI20_setVirtualGPIOGatedEh : 776 -> 844
~ __ZN18AppleStockholmSPMI22_setStandbyEnableGatedEb : 768 -> 836
+ sub_fffffff009775e8c
CStrings:
+ "ERR: %s::%s:%d failed to write to SPMI[0x%02X]:0x%02x - 0x%x, %d attempts\n"
+ "[%llu] ERR: %s::%s:%d failed to write to SPMI[0x%02X]:0x%02x - 0x%x, %d attempts"
- "ERR: %s::%s:%d failed to write to SPMI[0x%02X]:0x%02x - %x\n"
- "[%llu] ERR: %s::%s:%d failed to write to SPMI[0x%02X]:0x%02x - %x"
```
