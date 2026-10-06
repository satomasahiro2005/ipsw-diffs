## com.apple.driver.AppleSmartBatteryManagerEmbedded

> `com.apple.driver.AppleSmartBatteryManagerEmbedded`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x301dc` | `0x304b8` | **`+0x2dc`** |
| `__TEXT.__cstring` | `0x7b68` | `0x7bf6` | **`+0x8e`** |
| `__DATA.__bss` | `0x52e0` | `0x5350` | **`+0x70`** |
| `__TEXT.__os_log` | `0x2937` | `0x2970` | **`+0x39`** |
| `__TEXT.__const` | `0x2410` | `0x2440` | **`+0x30`** |

### Other Changes

```diff

-2043.0.13.502.1
+2043.0.31.0.0

-  CStrings:  1247
+  CStrings:  1254
Functions:
~ sub_fffffff0097250d4 -> sub_fffffff009748ed4 : 2428 -> 2672
~ sub_fffffff0097261c4 -> sub_fffffff00974a0b8 : 9108 -> 9156
~ sub_fffffff00973cf8c -> sub_fffffff009760eb0 : 696 -> 932
~ sub_fffffff009743518 -> sub_fffffff009767528 : 14004 -> 14144
~ sub_fffffff009749fd0 -> sub_fffffff00976e06c : 3188 -> 3252
CStrings:
+ "AppleSmartBatteryPack: ID: %d Battery pack is missing/bad\n"
+ "Failed to read shipping charge limit UISOC smcResult:%d\n"
+ "IlimFrzReason"
+ "RxPwrLimitReason"
+ "ShipChargeLimitComplianceStatePending"
+ "UISoc"
+ "VmaxNcc"
```
