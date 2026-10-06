## com.apple.driver.AppleSmartBatteryManagerEmbedded

> `com.apple.driver.AppleSmartBatteryManagerEmbedded`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x303ec` | `0x301dc` | **`-0x210`** |
| `__TEXT.__cstring` | `0x7d34` | `0x7b68` | **`-0x1cc`** |

### Other Changes

```diff

-2041.0.0.502.1
+2043.0.13.502.1

-  CStrings:  1253
+  CStrings:  1247
Functions:
~ sub_fffffff009722f4c -> sub_fffffff0097239dc : 328 -> 164
~ sub_fffffff009723094 -> sub_fffffff009723a80 : 328 -> 164
~ sub_fffffff0097257c4 -> sub_fffffff00972610c : 168 -> 176
~ sub_fffffff009729198 -> sub_fffffff009729ae8 : 932 -> 940
~ sub_fffffff00972c5e0 -> sub_fffffff00972cf38 : 396 -> 444
~ sub_fffffff00972fb40 -> sub_fffffff0097304c8 : 2112 -> 2120
~ sub_fffffff00973e7b0 -> sub_fffffff00973f140 : 344 -> 336
~ sub_fffffff00974a2bc -> sub_fffffff00974ac44 : 344 -> 176
~ sub_fffffff00974bdf0 -> sub_fffffff00974c6d0 : 180 -> 188
~ sub_fffffff00974c0b0 -> sub_fffffff00974c998 : 328 -> 164
~ sub_fffffff00974c55c -> sub_fffffff00974cda0 : 804 -> 860
~ sub_fffffff00974cacc -> sub_fffffff00974d348 : 132 -> 136
CStrings:
+ "1211111212221212112121212"
- "121111121222121211212112"
- "AppleChargerData: ID: %d failed to read key '%c%c%c%c' retry:%zu rc:%#x=%s\n"
- "AppleSmartBatteryBank: DBG: Pack ID: %d Bank ID: %d WriteSMCKey attempt %lu/%u"
- "AppleSmartBatteryBank: Pack ID: %d Bank ID: %d failed to write key '%c%c%c%c', retry:%zu\n"
- "AppleSmartBatteryPack: DBG: ID: %d WriteSMCKey attempt %lu/%u"
- "AppleSmartBatteryPack: ID: %d failed to read key '%c%c%c%c' retry:%zu rc:%#x=%s\n"
- "AppleSmartBatteryPack: ID: %d failed to write key '%c%c%c%c', retry:%zu\n"
```
