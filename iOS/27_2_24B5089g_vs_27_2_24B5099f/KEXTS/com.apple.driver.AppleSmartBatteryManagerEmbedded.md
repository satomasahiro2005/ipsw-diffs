## com.apple.driver.AppleSmartBatteryManagerEmbedded

> `com.apple.driver.AppleSmartBatteryManagerEmbedded`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x32650` | `0x3275c` | **`+0x10c`** |
| `__DATA.__bss` | `0x5668` | `0x5768` | **`+0x100`** |
| `__TEXT.__const` | `0x2650` | `0x2670` | **`+0x20`** |
| `__TEXT.__cstring` | `0x863f` | `0x8657` | **`+0x18`** |

### Other Changes

```diff

-2043.40.44.0.0
+2043.40.52.0.2

-  CStrings:  1308
+  CStrings:  1310
Functions:
~ sub_fffffff0097e4c30 -> sub_fffffff00976a080 : 11180 -> 11284
~ sub_fffffff009807e64 -> sub_fffffff00978d31c : 2524 -> 2496
~ sub_fffffff009809e1c -> sub_fffffff00978f2b8 : 3088 -> 3280
CStrings:
+ "AgingTlcTime"
+ "IsDevFused"
```
