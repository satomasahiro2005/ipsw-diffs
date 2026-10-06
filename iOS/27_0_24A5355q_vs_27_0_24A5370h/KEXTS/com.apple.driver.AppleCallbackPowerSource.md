## com.apple.driver.AppleCallbackPowerSource

> `com.apple.driver.AppleCallbackPowerSource`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x280` | **`+0x280`** |
| `__TEXT_EXEC.__text` | `0x48d8` | `0x4aa0` | **`+0x1c8`** |
| `__DATA.__bss` | `0x14e0` | `0x15f0` | **`+0x110`** |
| `__TEXT.__cstring` | `0xfe5` | `0x10ee` | **`+0x109`** |
| `__DATA.__common` | `0x190` | `0x198` | **`+0x8`** |

### Other Changes

```diff

-2015.0.0.0.1
+2041.0.0.502.1

-  CStrings:  245
+  CStrings:  257
Functions:
~ __ZN24AppleCallbackPowerSource21psCallbackThreadGatedEb : 2276 -> 2280
~ sub_fffffff0089da5c8 -> sub_fffffff0089f17ec : 284 -> 300
~ sub_fffffff0089da6e4 -> sub_fffffff0089f1918 : 316 -> 324
~ sub_fffffff0089da8e4 -> sub_fffffff0089f1b20 : 792 -> 784
~ __ZN24AppleCallbackPowerSource18fixupPropertyTypesEv : 216 -> 224
~ __GLOBAL__sub_I_AppleCallbackPowerSource.cpp : 8408 -> 8836
CStrings:
+ "BatteryModelID"
+ "BatteryNeedsRest"
+ "RebalanceData"
+ "RebalanceEnableStatus"
+ "RebalanceErrorFlags"
+ "RebalanceHWBypassFETStatus"
+ "RebalanceInrushCurrentDebug"
+ "RebalanceNotRebalancingReason"
+ "RebalanceOutputStruct"
+ "RebalanceTimeSeconds"
+ "ShelfLifeModeAutoEntry"
+ "ShelfLifeModeExitCounters"
```
