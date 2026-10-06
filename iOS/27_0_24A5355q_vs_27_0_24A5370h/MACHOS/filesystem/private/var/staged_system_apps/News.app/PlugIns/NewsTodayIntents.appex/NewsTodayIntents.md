## NewsTodayIntents

> `/private/var/staged_system_apps/News.app/PlugIns/NewsTodayIntents.appex/NewsTodayIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__objc_const` | `0x59b8` | `0x5a00` | **`+0x48`** |
| `__TEXT.__objc_methname` | `0x9b95` | `0x9bd5` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x3018` | `0x3040` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x1f48` | `0x1f60` | **`+0x18`** |
| `__TEXT.__text` | `0xcd0c` | `0xcd24` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-5916.1.0.0.0
+5920.0.0.0.0

-  CStrings:  1418
+  CStrings:  1421
Functions:
~ sub_1000024dc : 576 -> 572
~ sub_10000279c -> sub_100002798 : 392 -> 388
~ sub_1000080d4 -> sub_1000080cc : 1252 -> 1256
~ sub_1000086e4 -> sub_1000086e0 : 248 -> 252
~ sub_1000093f4 : 344 -> 340
~ sub_100009ec8 -> sub_100009ec4 : 152 -> 164
~ sub_10000a968 -> sub_10000a970 : 256 -> 264
~ sub_10000b1c0 -> sub_10000b1d0 : 380 -> 384
~ sub_10000c294 -> sub_10000c2a8 : 560 -> 564
CStrings:
+ "isWiFiAvailable"
+ "offlineModeOfflineVerificationTimeoutInterval"
+ "sportsEventLiveActivityStartTimeThreshold"
+ "sportsEventOpenInTVStartTimeThreshold"
- "articleEmbeddingsScoringEnabled"
```
