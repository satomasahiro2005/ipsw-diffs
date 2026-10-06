## com.apple.driver.AppleSmartBatteryManagerEmbedded

> `com.apple.driver.AppleSmartBatteryManagerEmbedded`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x325e8` | `0x32650` | **`+0x68`** |
| `__TEXT.__cstring` | `0x85e9` | `0x863f` | **`+0x56`** |

### Other Changes

```diff

-2043.40.43.0.0
+2043.40.44.0.0

-  CStrings:  1307
+  CStrings:  1308
Functions:
~ sub_fffffff0097def4c -> sub_fffffff0097e091c : 108 -> 112
~ sub_fffffff0097df0e0 -> sub_fffffff0097e0ab4 : 144 -> 148
~ sub_fffffff0097e1ff4 -> sub_fffffff0097e39cc : 2196 -> 2292
CStrings:
+ "AppleSmartBatteryPack: ID: %d updateRebalanceData: rebalancing not supported, ret=%d\n"
```
