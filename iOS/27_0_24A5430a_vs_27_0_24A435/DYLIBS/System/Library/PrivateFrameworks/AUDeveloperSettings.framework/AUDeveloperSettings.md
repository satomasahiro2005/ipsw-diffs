## AUDeveloperSettings

> `/System/Library/PrivateFrameworks/AUDeveloperSettings.framework/AUDeveloperSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ce10` | `0x3cff8` | **`+0x1e8`** |
| `__AUTH_CONST.__cfstring` | `0x3a0` | `0x3e0` | **`+0x40`** |
| `__TEXT.__cstring` | `0xfe2` | `0x1012` | **`+0x30`** |

### Other Changes

```diff

-  CStrings:  137
+  CStrings:  139
Functions:
~ -[AUDeveloperSettingsController specifiers] : 1124 -> 1452
~ -[AUDeveloperSettingsController createSeedCustomerSpecifiers] : 1428 -> 1436
~ -[AUDeveloperSettingsController setSeedParticipation:] : 944 -> 952
~ sub_24f38c118 -> sub_24fde1270 : 1628 -> 1636
~ sub_24f38e98c -> sub_24fde3aec : 5232 -> 5236
~ sub_24f39ab0c -> sub_24fdefc70 : 384 -> 388
~ sub_24f3a1178 -> sub_24fdf62e0 : 260 -> 264
~ sub_24f3a20b4 -> sub_24fdf7220 : 2408 -> 2412
~ sub_24f3a3930 -> sub_24fdf8aa0 : 680 -> 684
~ sub_24f3a4b14 -> sub_24fdf9c88 : 968 -> 972
~ _CBProductIDIsAirPods : 40 -> 44
~ sub_24f3ad738 -> sub_24fe028b4 : 7132 -> 7240
CStrings:
+ "ENABLE_LOG_COLLECTION_FOR_AIRPODS"
+ "LOG_COLLECTION"
```
