## sysdiagnose_helper

> `/usr/libexec/sysdiagnose_helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23bb8` | `0x23f30` | **`+0x378`** |
| `__TEXT.__cstring` | `0x8e98` | `0x91f6` | **`+0x35e`** |
| `__DATA_CONST.__cfstring` | `0x1d00` | `0x1d40` | **`+0x40`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1587.0.0.0.0
+1593.0.0.0.0

-  CStrings:  2087
+  CStrings:  2121
Functions:
~ sub_100004610 : 1904 -> 1900
~ sub_10000a2bc -> sub_10000a2b8 : 456 -> 452
~ sub_10000ce30 -> sub_10000ce28 : 384 -> 432
~ sub_10000fdb8 -> sub_10000fde0 : 280 -> 276
~ sub_100010d0c -> sub_100010d30 : 2160 -> 2056
~ sub_10001157c -> sub_100011538 : 1260 -> 1256
~ sub_100011d18 -> sub_100011cd0 : 63408 -> 64440
~ sub_1000214c8 -> sub_100021888 : 640 -> 648
~ sub_1000218e0 -> sub_100021ca8 : 1208 -> 1188
~ sub_100021d98 -> sub_10002214c : 2284 -> 2224
~ sub_100022744 -> sub_100022abc : 808 -> 812
~ sub_100023550 -> sub_1000238cc : 1512 -> 1504
~ sub_100023fb0 -> sub_100024324 : 576 -> 580
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
+ "com.apple.OmniSearch"
+ "com.apple.parsecd"
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
