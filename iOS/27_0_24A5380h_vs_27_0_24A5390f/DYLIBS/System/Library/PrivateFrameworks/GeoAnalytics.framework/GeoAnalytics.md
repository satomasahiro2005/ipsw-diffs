## GeoAnalytics

> `/System/Library/PrivateFrameworks/GeoAnalytics.framework/GeoAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x92dc4` | `0x94754` | **`+0x1990`** |
| `__AUTH_CONST.__objc_const` | `0x2960` | `0x2e88` | **`+0x528`** |
| `__TEXT.__gcc_except_tab` | `0xae0` | `0x680` | **`-0x460`** |
| `__TEXT.__objc_methlist` | `0x237c` | `0x2504` | **`+0x188`** |
| `__DATA.__data` | `0x310` | `0x490` | **`+0x180`** |
| `__AUTH.__objc_data` | `0x50` | `0x140` | **`+0xf0`** |
| `__DATA_CONST.__objc_selrefs` | `0x4090` | `0x4130` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0xfe8` | `0x1078` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x1035` | `0x10be` | **`+0x89`** |
| `__TEXT.__cstring` | `0xe3b4` | `0xe42a` | **`+0x76`** |
| `__AUTH_CONST.__cfstring` | `0x13ce0` | `0x13d40` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x2ed8` | `0x2ef8` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x1b0` | `0x1d0` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x40` | `0x60` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x4e8` | `0x500` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0xf8` | `0x110` | **`+0x18`** |
| `__DATA.__bss` | `0x110` | `0x120` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x698` | `0x6a8` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x98` | `0xa0` | **`+0x8`** |

### Other Changes

```diff

-2075.30.6.12.3
+2075.30.6.12.8

-  Functions: 1484
-  Symbols:   2971
-  CStrings:  2726
+  Functions: 1544
+  Symbols:   3089
+  CStrings:  2735
Symbols:
+ -[GEOAPFinderSession .cxx_destruct]
+ -[GEOAPFinderSession _clearTimer]
+ -[GEOAPFinderSession _handleExpiration]
+ -[GEOAPFinderSession _isValidSession:]
+ -[GEOAPFinderSession _updateSessionData]
+ -[GEOAPFinderSession currentSessionID]
+ -[GEOAPFinderSession dealloc]
+ -[GEOAPFinderSession finderSessionDataChanged]
+ -[GEOAPFinderSession initWithMonitor:]
+ -[GEOAPFinderSession initWithMonitor:timeProvider:sessionDataProvider:]
+ -[GEOAPFinderSession isValidSession:]
+ -[GEOAPFinderSessionDataProvider .cxx_destruct]
+ -[GEOAPFinderSessionDataProvider deregisterForChange:]
+ -[GEOAPFinderSessionDataProvider finderSessionData]
+ -[GEOAPFinderSessionDataProvider registerForChange:onQueue:]
+ -[GEOAPFinderSessionDataProvider sessionDuration]
+ -[GEOAPFinderSessionDataProvider valueChangedForGEOConfigKey:]
+ -[GEOAPFinderSessionTimeProvider dateNow]
+ -[GEOAPFinderSessionTimeProvider now]
+ -[GEOAPStateFactory actionButtonDetails]
+ -[GEOAPStateFactory applicationIdentifierShort]
+ -[GEOAPStateFactory carPlay]
+ -[GEOAPStateFactory curatedCollection]
+ -[GEOAPStateFactory deviceConnection]
+ -[GEOAPStateFactory deviceIdentifierHardwareClass]
+ -[GEOAPStateFactory deviceLocale]
+ -[GEOAPStateFactory deviceSettings_DailySettings]
+ -[GEOAPStateFactory deviceSettings_Long]
+ -[GEOAPStateFactory deviceSettings_Short]
+ -[GEOAPStateFactory extension]
+ -[GEOAPStateFactory lookAroundSummary]
+ -[GEOAPStateFactory lookAroundView]
+ -[GEOAPStateFactory mapLaunch]
+ -[GEOAPStateFactory mapRestore]
+ -[GEOAPStateFactory mapSettingsShort]
+ -[GEOAPStateFactory mapSettings]
+ -[GEOAPStateFactory mapUI]
+ -[GEOAPStateFactory mapViewLocation]
+ -[GEOAPStateFactory mapView]
+ -[GEOAPStateFactory mapsServer]
+ -[GEOAPStateFactory mapsUser]
+ -[GEOAPStateFactory market]
+ -[GEOAPStateFactory muninResourceLog]
+ -[GEOAPStateFactory offline]
+ -[GEOAPStateFactory pairedDeviceLong]
+ -[GEOAPStateFactory pairedDevice]
+ -[GEOAPStateFactory photoSubmissionDetails]
+ -[GEOAPStateFactory ratingPhotoSubmissionDetails]
+ -[GEOAPStateFactory ratingSubmissionDetails]
+ -[GEOAPStateFactory route]
+ -[GEOAPStateFactory suggestions]
+ -[GEOAPStateFactory tapEvent]
+ -[GEOAPStateFactory tileSet]
+ -[GEOAPStateFactory ugc]
+ GCC_except_table1086
+ GCC_except_table111
+ GCC_except_table1111
+ GCC_except_table1113
+ GCC_except_table113
+ GCC_except_table1131
+ GCC_except_table1135
+ GCC_except_table1137
+ GCC_except_table119
+ GCC_except_table121
+ GCC_except_table123
+ GCC_except_table129
+ GCC_except_table1350
+ GCC_except_table1388
+ GCC_except_table160
+ GCC_except_table161
+ GCC_except_table31
+ GCC_except_table5
+ GCC_except_table51
+ GCC_except_table551
+ GCC_except_table555
+ GCC_except_table557
+ GCC_except_table559
+ GCC_except_table561
+ GCC_except_table564
+ GCC_except_table567
+ GCC_except_table570
+ GCC_except_table572
+ GCC_except_table573
+ GCC_except_table575
+ GCC_except_table582
+ GCC_except_table585
+ GCC_except_table588
+ GCC_except_table634
+ GCC_except_table636
+ GCC_except_table641
+ GCC_except_table655
+ GCC_except_table660
+ GCC_except_table661
+ GCC_except_table670
+ GCC_except_table79
+ GCC_except_table81
+ GCC_except_table969
+ GCC_except_table974
+ GCC_except_table976
+ _GEOGetGEOAPFinderSessionAnalyticsLog
+ _GEOGetGEOAPFinderSessionAnalyticsLog.log
+ _GEOGetGEOAPFinderSessionAnalyticsLog.onceToken
+ _GeoUserSessionConfig_ACSNFinderSessionData
+ _OBJC_CLASS_$_GEOAPFinderSession
+ _OBJC_CLASS_$_GEOAPFinderSessionDataProvider
+ _OBJC_CLASS_$_GEOAPFinderSessionTimeProvider
+ _OBJC_CLASS_$_GEOAPSessionData
+ _OBJC_IVAR_$_GEOAPFinderSession._monitor
+ _OBJC_IVAR_$_GEOAPFinderSession._q
+ _OBJC_IVAR_$_GEOAPFinderSession._sessionData
+ _OBJC_IVAR_$_GEOAPFinderSession._sessionDataProvider
+ _OBJC_IVAR_$_GEOAPFinderSession._timeProvider
+ _OBJC_IVAR_$_GEOAPFinderSession._timer
+ _OBJC_IVAR_$_GEOAPFinderSessionDataProvider._delegate
+ _OBJC_IVAR_$_GEOAPStateFactory._runningInMaps
+ _OBJC_METACLASS_$_GEOAPFinderSession
+ _OBJC_METACLASS_$_GEOAPFinderSessionDataProvider
+ _OBJC_METACLASS_$_GEOAPFinderSessionTimeProvider
+ __GEOConfigAddDelegateListenerForKey
+ __OBJC_$_INSTANCE_METHODS_GEOAPFinderSession
+ __OBJC_$_INSTANCE_METHODS_GEOAPFinderSessionDataProvider
+ __OBJC_$_INSTANCE_METHODS_GEOAPFinderSessionTimeProvider
+ __OBJC_$_INSTANCE_VARIABLES_GEOAPFinderSession
+ __OBJC_$_INSTANCE_VARIABLES_GEOAPFinderSessionDataProvider
+ __OBJC_$_PROP_LIST_GEOAPFinderSession
+ __OBJC_$_PROP_LIST_GEOAPFinderSessionDataProvider
+ __OBJC_$_PROP_LIST_GEOAPFinderSessionDataProviding
+ __OBJC_$_PROP_LIST_GEOAPFinderSessionTimeProvider
+ __OBJC_$_PROP_LIST_GEOAPTimeProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_GEOAPFinderSessionDataDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_GEOAPFinderSessionDataProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_GEOAPTimeProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_GEOConfigChangeListenerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_GEOAPFinderSessionDataDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_GEOAPFinderSessionDataProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_GEOAPTimeProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_GEOConfigChangeListenerDelegate
+ __OBJC_$_PROTOCOL_REFS_GEOAPFinderSessionDataDelegate
+ __OBJC_$_PROTOCOL_REFS_GEOAPFinderSessionDataProviding
+ __OBJC_$_PROTOCOL_REFS_GEOAPTimeProviding
+ __OBJC_$_PROTOCOL_REFS_GEOConfigChangeListenerDelegate
+ __OBJC_CLASS_PROTOCOLS_$_GEOAPFinderSession
+ __OBJC_CLASS_PROTOCOLS_$_GEOAPFinderSessionDataProvider
+ __OBJC_CLASS_PROTOCOLS_$_GEOAPFinderSessionTimeProvider
+ __OBJC_CLASS_RO_$_GEOAPFinderSession
+ __OBJC_CLASS_RO_$_GEOAPFinderSessionDataProvider
+ __OBJC_CLASS_RO_$_GEOAPFinderSessionTimeProvider
+ __OBJC_LABEL_PROTOCOL_$_GEOAPFinderSessionDataDelegate
+ __OBJC_LABEL_PROTOCOL_$_GEOAPFinderSessionDataProviding
+ __OBJC_LABEL_PROTOCOL_$_GEOAPTimeProviding
+ __OBJC_LABEL_PROTOCOL_$_GEOConfigChangeListenerDelegate
+ __OBJC_METACLASS_RO_$_GEOAPFinderSession
+ __OBJC_METACLASS_RO_$_GEOAPFinderSessionDataProvider
+ __OBJC_METACLASS_RO_$_GEOAPFinderSessionTimeProvider
+ __OBJC_PROTOCOL_$_GEOAPFinderSessionDataDelegate
+ __OBJC_PROTOCOL_$_GEOAPFinderSessionDataProviding
+ __OBJC_PROTOCOL_$_GEOAPTimeProviding
+ __OBJC_PROTOCOL_$_GEOConfigChangeListenerDelegate
+ ___37-[GEOAPFinderSession isValidSession:]_block_invoke
+ ___38-[GEOAPFinderSession currentSessionID]_block_invoke
+ ___71-[GEOAPFinderSession initWithMonitor:timeProvider:sessionDataProvider:]_block_invoke
+ ___71-[GEOAPFinderSession initWithMonitor:timeProvider:sessionDataProvider:]_block_invoke_2
+ ___GEOGetGEOAPFinderSessionAnalyticsLog_block_invoke
+ ___block_descriptor_56_e8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
+ _createStateWithType
+ _dispatch_assert_queue$V2
+ _objc_storeWeak
- GCC_except_table1026
- GCC_except_table1051
- GCC_except_table1053
- GCC_except_table1071
- GCC_except_table1075
- GCC_except_table1077
- GCC_except_table127
- GCC_except_table128
- GCC_except_table1290
- GCC_except_table1328
- GCC_except_table19
- GCC_except_table26
- GCC_except_table46
- GCC_except_table48
- GCC_except_table491
- GCC_except_table495
- GCC_except_table497
- GCC_except_table499
- GCC_except_table501
- GCC_except_table504
- GCC_except_table507
- GCC_except_table510
- GCC_except_table512
- GCC_except_table513
- GCC_except_table515
- GCC_except_table522
- GCC_except_table525
- GCC_except_table528
- GCC_except_table574
- GCC_except_table576
- GCC_except_table581
- GCC_except_table595
- GCC_except_table600
- GCC_except_table601
- GCC_except_table610
- GCC_except_table78
- GCC_except_table8
- GCC_except_table80
- GCC_except_table86
- GCC_except_table88
- GCC_except_table90
- GCC_except_table909
- GCC_except_table914
- GCC_except_table916
- GCC_except_table96
- __ZN6gloria6TileId10FromLatLngERKdS2_RKh
- __ZNK6gloria6TileId16GetEncodedTileIdEv
- __ZNK6gloria6TileId6ToBBOXEv
- ___block_descriptor_56_e8_32s40s48r_e5_v8?0ls32l8r48l8s40l8
CStrings:
+ "GEOAPFinderSession"
+ "TAP_DICTATION_ADD_STOP"
+ "TAP_SATELLITE_MODE_OFF"
+ "TAP_SATELLITE_MODE_ON"
+ "com.apple.geoapfindersession"
+ "session has expired"
+ "unexpected state : _sessionData has already rotated"
+ "unexpected state : should have _sessionData"
+ "updating timer state"
```
