## AirPlaySupport

> `/System/Library/PrivateFrameworks/AirPlaySupport.framework/AirPlaySupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcc6f4` | `0xcc33c` | **`-0x3b8`** |
| `__TEXT.__cstring` | `0x33eb1` | `0x33c69` | **`-0x248`** |
| `__AUTH_CONST.__cfstring` | `0x7380` | `0x72e0` | **`-0xa0`** |
| `__DATA_CONST.__const` | `0x3070` | `0x3040` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x38c` | `0x374` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x6a8` | `0x698` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x374` | `0x368` | **`-0xc`** |
| `__TEXT.__unwind_info` | `0x1e08` | `0x1e00` | **`-0x8`** |

### Other Changes

```diff

-980.71.1.0.0
+980.75.1.0.0

-  Functions: 2630
-  Symbols:   4980
-  CStrings:  4488
+  Functions: 2624
+  Symbols:   4969
+  CStrings:  4458
Symbols:
+ GCC_except_table1156
+ GCC_except_table1182
+ GCC_except_table1183
+ GCC_except_table1184
+ GCC_except_table1305
+ GCC_except_table1471
+ GCC_except_table1473
+ GCC_except_table1600
+ GCC_except_table1796
+ GCC_except_table1799
+ GCC_except_table1802
+ GCC_except_table1971
+ GCC_except_table2221
+ GCC_except_table2522
+ GCC_except_table2527
+ GCC_except_table2536
+ GCC_except_table2592
+ GCC_except_table2595
+ GCC_except_table2596
+ GCC_except_table589
+ GCC_except_table975
+ _FigSignalErrorAtGM
+ _TapToRadarKitLibraryCore
- -[APSTimeSyncNetworkClock disablePort:]
- -[APSTimeSyncNetworkClock enablePort:]
- GCC_except_table1160
- GCC_except_table1186
- GCC_except_table1187
- GCC_except_table1193
- GCC_except_table1309
- GCC_except_table1475
- GCC_except_table1477
- GCC_except_table1608
- GCC_except_table1800
- GCC_except_table1803
- GCC_except_table1810
- GCC_except_table1975
- GCC_except_table2227
- GCC_except_table2528
- GCC_except_table2533
- GCC_except_table2542
- GCC_except_table2598
- GCC_except_table2601
- GCC_except_table2602
- GCC_except_table593
- GCC_except_table979
- _CM8021ASClockDisablePort
- _CM8021ASClockEnablePort
- _FigSignalErrorAt3
- _TapToRadarKitLibrary
- ___block_descriptor_56_e15_v24?0r^v8r^v16l
- ___ptpClock_copyPeerListForRegularPeer_block_invoke_5
- ___ptpClock_copyPeerListForRegularPeer_block_invoke_6
- ___ptpClock_enablePortsBasedOnTopology_block_invoke
- _kAPSNetworkClockPeerDictionaryKey_IsEnabled
- _kAPSNetworkClockPeerDictionaryKey_IsTightSyncGroupLeader
- _ptpClock_enablePortsBasedOnTopology
CStrings:
+ "%s signalled err=%d at <>:%d"
+ "Not invoking TTR: TTRKit unavailable"
+ "Not invoking TTR: TapToRadarService unavailable"
+ "Not invoking TTR: non-internal build"
+ "OSStatus ptpClock_SetOrUpdateLocalPeerInfo(APSNetworkClockRef, void *, CFDictionaryRef)"
+ "[%{ptr}] Promoted subHoseController [%{ptr}] to multicast, next SeqNum: %u"
+ "[%{ptr}] discontinuity, %s. lastEndPTSDequeuedForSBAR=%1.6f (%lld/%d), peekSBufPTS=%1.6f (%lld/%d), isBelowLowWaterLevel=%d, gap=%1.6f s (maxEnqueueGap %1.6f s)\n"
+ "[%{ptr}] holding sbuf across large discontinuity; lastEndPTSDequeuedForSBAR=%1.6f (%lld/%d), peekSBufPTS=%1.6f (%lld/%d), gap=%1.6f s (maxEnqueueGap %1.6f s), low-water timer rescheduled to synchronizerTime=%1.6f\n"
+ "enqueueing across gap within margin"
+ "holding sbuf"
- "%s%s%s signalled err=%d (%s) (%s) at %s:%d"
- "-108"
- "-6705"
- "-877"
- "-878"
- "-879"
- "-880"
- "APSAPAPExtensionLoudnessInfoUtils.c"
- "APSAudioFormatDescription.c"
- "APSAudioFormatDescriptionList.c"
- "APSSharedRingBuffer.c"
- "Could not allocate APSAudioFormatDescription"
- "Could not allocate APSAudioFormatDescriptionList"
- "Failed to create bufferMemObject"
- "Failed to create stateMemObject"
- "IsEnabled"
- "IsTightSyncGroupLeader"
- "Not invoking TTR on non-internal builds"
- "OSStatus ptpClock_SetOrUpdateLocalPeerInfo(APSNetworkClockRef, CFDictionaryRef)"
- "TapToRadarService does not exist. A radar cannot be started"
- "[%{ptr}] %'@ already %s"
- "[%{ptr}] Disabling clock port for peer %'@\n"
- "[%{ptr}] Enabling clock port for peer %'@\n"
- "[%{ptr}] Promoted subHoseController [%{ptr}] to multicast"
- "[%{ptr}] discontinuity, yielding until low water. lastEndPTSDequeuedForSBAR=%1.6f (%lld/%d), peekSBufPTS=%1.6f (%lld/%d), isBelowLowWaterLevel=%d\n"
- "anpi"
- "anri"
- "bufferMemory region maps to NULL"
- "bufferMemorySize is zero"
- "kCMBaseObjectError_AllocationFailed"
- "loudness key missing"
- "nan"
- "ptpClock_enableOnePortOrAll"
- "ptpClock_enablePortsBasedOnTopology"
- "ptpClock_hasPeerWithTightSyncUUID"
- "sample peak key missing"
- "stateMemObject maps to NULL"
- "stateMemoryLength < sizeof(RingState)"
- "true peak key missing"
- "void ptpClock_enableOnePortOrAll(APSNetworkClockRef, void *, CFDictionaryRef, CFStringRef, CFStringRef)"
```
