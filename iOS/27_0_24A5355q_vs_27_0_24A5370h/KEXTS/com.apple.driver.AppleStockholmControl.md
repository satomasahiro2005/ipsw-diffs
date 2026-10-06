## com.apple.driver.AppleStockholmControl

> `com.apple.driver.AppleStockholmControl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x500` | **`+0x500`** |
| `__TEXT_EXEC.__text` | `0x14d58` | `0x14da4` | **`+0x4c`** |
| `__TEXT.__cstring` | `0x47ee` | `0x47ef` | **`+0x1`** |

### Other Changes

```diff

-370.33.1.0.0
+370.37.0.0.0
Functions:
~ __ZN24AppleStockholmRingBuffer8initWithEmmb : 532 -> 544
~ __ZN18AppleStockholmSPMI5startEP9IOService : 6308 -> 6336
~ __ZN18AppleStockholmSPMI22_setStandbyEnableGatedEb : 920 -> 924
~ __ZN18AppleStockholmSPMI24requestDebugRegisterInfoEPhPmb : 4304 -> 4376
~ __ZN18AppleStockholmSPMI13_dataReadMbufEv : 2492 -> 2476
~ __ZN21AppleStockholmControl18_requiresPowerToSEEv : 1460 -> 1444
~ __ZN25AppleStockholmDebugDevice14_debugDevWriteEiP3uioi : 400 -> 392
CStrings:
+ "1211111212221212121111111122221221112"
- "121111121222121212111111112221221112"
```
