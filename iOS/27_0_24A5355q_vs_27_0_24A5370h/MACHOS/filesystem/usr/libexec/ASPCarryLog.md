## ASPCarryLog

> `/usr/libexec/ASPCarryLog`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x262dc` | `0x26698` | **`+0x3bc`** |
| `__TEXT.__cstring` | `0x8536` | `0x8864` | **`+0x32e`** |
| `__TEXT.__unwind_info` | `0x520` | `0x528` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-835.0.0.0.0
+843.0.0.0.0

-  CStrings:  2439
+  CStrings:  2471
Functions:
~ sub_100001df8 : 848 -> 864
~ sub_10000229c -> sub_1000022ac : 1404 -> 1400
~ sub_100002818 -> sub_100002824 : 196 -> 188
~ sub_100002984 -> sub_100002988 : 168 -> 164
~ sub_100004f84 : 384 -> 380
~ sub_10000a8c8 -> sub_10000a8c4 : 288 -> 312
~ sub_10000dbe0 -> sub_10000dbf4 : 784 -> 776
~ sub_10000def0 -> sub_10000defc : 364 -> 360
~ sub_10000e05c -> sub_10000e064 : 336 -> 332
~ sub_10000f534 -> sub_10000f538 : 704 -> 700
~ sub_10000f9dc : 772 -> 768
~ sub_100011af4 -> sub_100011af0 : 836 -> 832
~ sub_100011ff0 -> sub_100011fe8 : 520 -> 516
~ sub_1000121f8 -> sub_1000121ec : 532 -> 528
~ sub_100012864 -> sub_100012854 : 340 -> 336
~ sub_100012c50 -> sub_100012c3c : 340 -> 336
~ sub_100014508 -> sub_1000144f0 : 63408 -> 64440
~ sub_100023e44 -> sub_100024234 : 1208 -> 1188
~ sub_1000242fc -> sub_1000246d8 : 2284 -> 2224
~ sub_100024ca8 -> sub_100025048 : 808 -> 812
~ sub_1000254a8 -> sub_10002584c : 448 -> 436
~ sub_10002572c -> sub_100025ac4 : 1120 -> 1136
~ sub_100025b8c -> sub_100025f34 : 1272 -> 1292
CStrings:
+ "TPB_maxPower"
+ "TPB_minPower"
+ "TPB_perExtLoopPerLevel_100ms"
+ "TPB_perExtLoopPerLevel_count"
+ "TPB_perExtLoopPerLevel_throttled"
+ "TPB_perIntLoopPerLevel_100ms"
+ "TPB_perIntLoopPerLevel_count"
+ "TPB_perIntLoopPerLevel_throttled"
+ "TPB_unblockGcThrottlingBP"
+ "TPB_unblockGcThrottlingStarve"
+ "gcRoundTime"
+ "gcSlowInlineWritesVCCAutoHint"
+ "gcSlowInlineWritesVCCNonRec"
+ "gcSlowInlineWritesVCCRec"
+ "idleStackActiveStatus"
+ "idleStackBadListLBAs"
+ "idleStackHistory"
+ "idleStackPingResetPhase"
+ "massRefreshThrottleDisable"
+ "massRefreshThrottleEvict"
+ "massRefreshThrottleMassScan"
+ "massScanRequestWhileET"
+ "numOfThrottlingEntriesPerReadLevel"
+ "numOfThrottlingEntriesPerWriteLevel"
+ "shutdownGCTimeoutQLC"
+ "shutdownGCTimeoutTLC"
+ "shutdownSpbxEvictQLC"
+ "shutdownSpbxEvictTLC"
+ "timeOfThrottlingPerLevel"
+ "timeOfThrottlingPerReadLevel"
+ "timeOfThrottlingPerWriteLevel"
+ "vccGCWritesAutoHint"
+ "vccGCWritesNonRec"
+ "vccGCWritesRec"
- "ricMPRVFail"
- "ricSPRVFail"
```
