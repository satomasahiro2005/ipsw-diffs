## WiFiPolicy

> `/System/Library/PrivateFrameworks/WiFiPolicy.framework/WiFiPolicy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe2dbc` | `0xe3c94` | **`+0xed8`** |
| `__AUTH_CONST.__objc_const` | `0x25980` | `0x25bf0` | **`+0x270`** |
| `__TEXT.__objc_methlist` | `0x13d18` | `0x13e88` | **`+0x170`** |
| `__DATA_CONST.__objc_selrefs` | `0xaf20` | `0xb080` | **`+0x160`** |
| `__TEXT.__cstring` | `0x25d4b` | `0x25deb` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x20de0` | `0x20e40` | **`+0x60`** |
| `__DATA.__objc_ivar` | `0x2568` | `0x259c` | **`+0x34`** |
| `__DATA_CONST.__objc_arraydata` | `0x1510` | `0x1530` | **`+0x20`** |
| `__TEXT.__const` | `0x868` | `0x888` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x29e8` | `0x2a00` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xbb8` | `0xbc0` | **`+0x8`** |
| `__DATA.__bss` | `0x48` | `0x49` | **`+0x1`** |

### Other Changes

```diff

-1070.62.0.0.0
+1072.4.0.0.0

-  Functions: 7206
-  Symbols:   11986
-  CStrings:  5323
+  Functions: 7242
+  Symbols:   12038
+  CStrings:  5327
Symbols:
+ +[WiFiUsagePrivacyFilter isInternalOrSeedInstall]
+ -[WiFiUsageMonitor updateCellularWRMScore:forInterface:]
+ -[WiFiUsageNetworkDetails previousJoinDate]
+ -[WiFiUsageNetworkDetails setPreviousJoinDate:]
+ -[WiFiUsageNetworkSession cellularWRMScoreDidChange:]
+ -[WiFiUsageSession bssidAtSessionStart]
+ -[WiFiUsageSession cellDataIndicatorAtSessionStart]
+ -[WiFiUsageSession cellularWRMScoreDidChange:]
+ -[WiFiUsageSession hasCellDataIndicatorAtSessionStart]
+ -[WiFiUsageSession hasCellularStateAtSessionStart]
+ -[WiFiUsageSession iRatScoreAtSessionStart]
+ -[WiFiUsageSession iRatScoreBadCount]
+ -[WiFiUsageSession iRatScoreFairCount]
+ -[WiFiUsageSession iRatScoreGoodCount]
+ -[WiFiUsageSession iRatScoreUnknownCount]
+ -[WiFiUsageSession iRatScoreUnusableCount]
+ -[WiFiUsageSession latestCellularWRMScore]
+ -[WiFiUsageSession latestLqaScore]
+ -[WiFiUsageSession resetJoinSideCaptures]
+ -[WiFiUsageSession setBssidAtSessionStart:]
+ -[WiFiUsageSession setCellDataIndicatorAtSessionStart:]
+ -[WiFiUsageSession setHasCellDataIndicatorAtSessionStart:]
+ -[WiFiUsageSession setHasCellularStateAtSessionStart:]
+ -[WiFiUsageSession setIRatScoreAtSessionStart:]
+ -[WiFiUsageSession setIRatScoreBadCount:]
+ -[WiFiUsageSession setIRatScoreFairCount:]
+ -[WiFiUsageSession setIRatScoreGoodCount:]
+ -[WiFiUsageSession setIRatScoreUnknownCount:]
+ -[WiFiUsageSession setIRatScoreUnusableCount:]
+ -[WiFiUsageSession setLatestCellularWRMScore:]
+ -[WiFiUsageSession setLatestLqaScore:]
+ GCC_except_table285
+ GCC_except_table64
+ GCC_except_table65
+ _OBJC_IVAR_$_WiFiUsageNetworkDetails._previousJoinDate
+ _OBJC_IVAR_$_WiFiUsageSession._bssidAtSessionStart
+ _OBJC_IVAR_$_WiFiUsageSession._cellDataIndicatorAtSessionStart
+ _OBJC_IVAR_$_WiFiUsageSession._hasCellDataIndicatorAtSessionStart
+ _OBJC_IVAR_$_WiFiUsageSession._hasCellularStateAtSessionStart
+ _OBJC_IVAR_$_WiFiUsageSession._iRatScoreAtSessionStart
+ _OBJC_IVAR_$_WiFiUsageSession._iRatScoreBadCount
+ _OBJC_IVAR_$_WiFiUsageSession._iRatScoreFairCount
+ _OBJC_IVAR_$_WiFiUsageSession._iRatScoreGoodCount
+ _OBJC_IVAR_$_WiFiUsageSession._iRatScoreUnknownCount
+ _OBJC_IVAR_$_WiFiUsageSession._iRatScoreUnusableCount
+ _OBJC_IVAR_$_WiFiUsageSession._latestCellularWRMScore
+ _OBJC_IVAR_$_WiFiUsageSession._latestLqaScore
+ _WiFiUsageConnectionQualityRecordApnsPartialConnectivityBucket
+ _WiFiUsageConnectionQualityRecordConvertCellDataIndicatorToGEORAT
+ _WiFiUsageConnectionQualityRecordConvertLqaScoreToGEO
+ _WiFiUsageConnectionQualityRecordRssiMedianFromLQM
+ ___56-[WiFiUsageMonitor updateCellularWRMScore:forInterface:]_block_invoke
+ __isSeedInstall
+ _kPerformanceNetAttachPartialConnectivityDetections
- GCC_except_table283
- GCC_except_table62
CStrings:
+ "-[WiFiUsageMonitor updateCellularWRMScore:forInterface:]_block_invoke"
+ "HotSpot_LPEMLSR_LpscTotalIcfCount"
+ "HotSpot_LPEMLSR_MainTotalIcfCount"
+ "delta_HOTSPOT_EMLSR_LPSC_TOTAL_ICF_COUNT"
+ "delta_HOTSPOT_EMLSR_MAIN_TOTAL_ICF_COUNT"
- "%s Rejected due to [WiFiUsagePrivacyFilter isInternalInstall]\n"
```
