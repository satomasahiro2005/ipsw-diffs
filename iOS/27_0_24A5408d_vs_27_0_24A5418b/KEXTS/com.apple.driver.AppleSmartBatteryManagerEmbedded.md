## com.apple.driver.AppleSmartBatteryManagerEmbedded

> `com.apple.driver.AppleSmartBatteryManagerEmbedded`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x315e4` | `0x317b4` | **`+0x1d0`** |
| `__TEXT.__cstring` | `0x8289` | `0x82e7` | **`+0x5e`** |
| `__DATA.__bss` | `0x5560` | `0x5580` | **`+0x20`** |
| `__TEXT.__const` | `0x2630` | `0x2640` | **`+0x10`** |

### Other Changes

```diff

-2043.0.45.502.1
+2043.2.2.0.0

-  CStrings:  1280
+  CStrings:  1282
Functions:
~ sub_fffffff0097352f0 -> sub_fffffff00969a090 : 2688 -> 3112
~ sub_fffffff009754858 -> sub_fffffff0096b97a0 : 12680 -> 12720
CStrings:
+ "AppleSmartBatteryPack: ID: %d Battery data read aborted. ltd:%d kiosk:%d carrier:%d\n"
+ "IPDRatio"
```
