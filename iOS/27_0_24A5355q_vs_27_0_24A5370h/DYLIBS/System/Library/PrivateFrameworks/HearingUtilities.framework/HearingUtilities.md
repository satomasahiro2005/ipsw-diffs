## HearingUtilities

> `/System/Library/PrivateFrameworks/HearingUtilities.framework/HearingUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xadc2c` | `0xb6570` | **`+0x8944`** |
| `__TEXT.__oslogstring` | `0xcaf3` | `0xeee3` | **`+0x23f0`** |
| `__AUTH_CONST.__objc_const` | `0xb720` | `0xbdb0` | **`+0x690`** |
| `__TEXT.__objc_methlist` | `0x8c04` | `0x919c` | **`+0x598`** |
| `__DATA_CONST.__objc_selrefs` | `0x5228` | `0x54f8` | **`+0x2d0`** |
| `__TEXT.__cstring` | `0x5dad` | `0x6046` | **`+0x299`** |
| `__TEXT.__unwind_info` | `0x29f8` | `0x2c38` | **`+0x240`** |
| `__DATA_CONST.__const` | `0x35a0` | `0x36e8` | **`+0x148`** |
| `__TEXT.__gcc_except_tab` | `0x2740` | `0x2858` | **`+0x118`** |
| `__AUTH.__objc_data` | `0x1280` | `0x1320` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x5c60` | `0x5d00` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x1578` | `0x1618` | **`+0xa0`** |
| `__DATA.__objc_ivar` | `0x990` | `0x9ec` | **`+0x5c`** |
| `__DATA_CONST.__got` | `0x738` | `0x760` | **`+0x28`** |
| `__AUTH_CONST.__objc_intobj` | `0xa38` | `0xa50` | **`+0x18`** |
| `__DATA.__bss` | `0x840` | `0x850` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x208` | `0x218` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x190` | `0x1a0` | **`+0x10`** |
| `__TEXT.__const` | `0x7d4` | `0x7e4` | **`+0x10`** |

### Other Changes

```diff

-527.0.0.0.0
+530.0.0.0.0

-  Functions: 3933
-  Symbols:   6181
-  CStrings:  1894
+  Functions: 4064
+  Symbols:   6360
+  CStrings:  2060
Symbols:
+ -[AXHearingAidDevice isMFiDeviceProtocol]
+ -[AXHearingAidDevice leftMicrophoneInputGain]
+ -[AXHearingAidDevice leftVolumeInputGain]
+ -[AXHearingAidDevice rightMicrophoneInputGain]
+ -[AXHearingAidDevice rightVolumeInputGain]
+ -[AXHearingAidDevice setLeftMicrophoneInputGain:]
+ -[AXHearingAidDevice setLeftVolumeInputGain:]
+ -[AXHearingAidDevice setRightMicrophoneInputGain:]
+ -[AXHearingAidDevice setRightVolumeInputGain:]
+ -[AXHearingAidDeviceController addPeripheral:toDevice:]
+ -[AXHearingAidDeviceController hearingAidForLEAudioPeripheral:]
+ -[AXHearingAidDeviceController isLEAudioServiceInServiceUUIDs:]
+ -[AXHearingAidDeviceController processConnectedIdentifiers:andLocations:]
+ -[AXHearingAidDeviceController setupCentralManagerForLEAudio]
+ -[AXHearingAidLEAudioDevice .cxx_destruct]
+ -[AXHearingAidLEAudioDevice _initCharacteristicsForPeripheral:]
+ -[AXHearingAidLEAudioDevice _init]
+ -[AXHearingAidLEAudioDevice addPeripheral:]
+ -[AXHearingAidLEAudioDevice addPeripheral:asLeft:]
+ -[AXHearingAidLEAudioDevice availablePropertiesForPeripheral:]
+ -[AXHearingAidLEAudioDevice connect]
+ -[AXHearingAidLEAudioDevice connectionDidChange]
+ -[AXHearingAidLEAudioDevice dealloc]
+ -[AXHearingAidLEAudioDevice delayWriteProperty:forPeripheral:]
+ -[AXHearingAidLEAudioDevice deviceProtocol]
+ -[AXHearingAidLEAudioDevice didAddPeripheral:]
+ -[AXHearingAidLEAudioDevice didLoadOptionalBasicProperties]
+ -[AXHearingAidLEAudioDevice didLoadPersistentProperties]
+ -[AXHearingAidLEAudioDevice disconnectAndUnpair:]
+ -[AXHearingAidLEAudioDevice discoveringServiceUUIDs]
+ -[AXHearingAidLEAudioDevice earForPeripheral:]
+ -[AXHearingAidLEAudioDevice initWithHearingAidDevice:]
+ -[AXHearingAidLEAudioDevice initWithLeftDevice:andRightDevice:]
+ -[AXHearingAidLEAudioDevice isLeftEventHandlerSet]
+ -[AXHearingAidLEAudioDevice isRightEventHandlerSet]
+ -[AXHearingAidLEAudioDevice isValidProperty:]
+ -[AXHearingAidLEAudioDevice leftMicrophoneInputData]
+ -[AXHearingAidLEAudioDevice leftMicrophoneInputGain]
+ -[AXHearingAidLEAudioDevice leftVolumeInputData]
+ -[AXHearingAidLEAudioDevice leftVolumeInputGain]
+ -[AXHearingAidLEAudioDevice loadProperties:forPeripheral:withRetryPeriod:]
+ -[AXHearingAidLEAudioDevice loadRequiredProperties]
+ -[AXHearingAidLEAudioDevice peripheral:characteristicForUUID:]
+ -[AXHearingAidLEAudioDevice processBTActivePresetUpdate:forEar:]
+ -[AXHearingAidLEAudioDevice processBTMicrophoneInputDiscovered:forEar:]
+ -[AXHearingAidLEAudioDevice processBTMicrophoneInputGainUpdate:forInputDescription:forEar:]
+ -[AXHearingAidLEAudioDevice processBTMicrophoneInputMuteUpdate:forInputDescription:forEar:]
+ -[AXHearingAidLEAudioDevice processBTMicrophoneInputStatusUpdate:forInputDescription:forEar:]
+ -[AXHearingAidLEAudioDevice processBTPresetsUpdate:activePreset:forEar:]
+ -[AXHearingAidLEAudioDevice processBTVolumeInputDiscovered:forEar:]
+ -[AXHearingAidLEAudioDevice processBTVolumeInputGainUpdate:forInputDescription:forEar:]
+ -[AXHearingAidLEAudioDevice processBTVolumeInputMuteUpdate:forInputDescription:forEar:]
+ -[AXHearingAidLEAudioDevice processBTVolumeInputStatusUpdate:forInputDescription:forEar:]
+ -[AXHearingAidLEAudioDevice processBTVolumeUpdate:forEar:]
+ -[AXHearingAidLEAudioDevice processLEA3Event:forPeripheral:]
+ -[AXHearingAidLEAudioDevice rightMicrophoneInputData]
+ -[AXHearingAidLEAudioDevice rightMicrophoneInputGain]
+ -[AXHearingAidLEAudioDevice rightVolumeInputData]
+ -[AXHearingAidLEAudioDevice rightVolumeInputGain]
+ -[AXHearingAidLEAudioDevice sessionDidUpdateLocations:]
+ -[AXHearingAidLEAudioDevice sessionDidUpdateValue:forProperty:]
+ -[AXHearingAidLEAudioDevice setIsLeftEventHandlerSet:]
+ -[AXHearingAidLEAudioDevice setIsRightEventHandlerSet:]
+ -[AXHearingAidLEAudioDevice setLeftMicrophoneInputData:]
+ -[AXHearingAidLEAudioDevice setLeftMicrophoneInputGain:]
+ -[AXHearingAidLEAudioDevice setLeftVolumeInputData:]
+ -[AXHearingAidLEAudioDevice setLeftVolumeInputGain:]
+ -[AXHearingAidLEAudioDevice setNotify:forPeripheral:]
+ -[AXHearingAidLEAudioDevice setRightMicrophoneInputData:]
+ -[AXHearingAidLEAudioDevice setRightMicrophoneInputGain:]
+ -[AXHearingAidLEAudioDevice setRightVolumeInputData:]
+ -[AXHearingAidLEAudioDevice setRightVolumeInputGain:]
+ -[AXHearingAidLEAudioDevice setValue:forProperty:]
+ -[AXHearingAidLEAudioDevice setupBasicPropertiesLoaded]
+ -[AXHearingAidLEAudioDevice setupLoadingProperties]
+ -[AXHearingAidLEAudioDevice setupUpdatesHandlerForLEAudioPeripheral:]
+ -[AXHearingAidLEAudioDevice updateName]
+ -[AXHearingAidLEAudioDevice writeValueForProperty:]
+ -[AXRemoteHearingAidDevice leftMicrophoneInputGainValueForInputDescription:]
+ -[AXRemoteHearingAidDevice leftMicrophoneInputGain]
+ -[AXRemoteHearingAidDevice leftVolumeInputGainValueForInputDescription:]
+ -[AXRemoteHearingAidDevice leftVolumeInputGain]
+ -[AXRemoteHearingAidDevice rightMicrophoneInputGainValueForInputDescription:]
+ -[AXRemoteHearingAidDevice rightMicrophoneInputGain]
+ -[AXRemoteHearingAidDevice rightVolumeInputGainValueForInputDescription:]
+ -[AXRemoteHearingAidDevice rightVolumeInputGain]
+ -[AXRemoteHearingAidDevice setLeftMicrophoneInputGain:]
+ -[AXRemoteHearingAidDevice setLeftMicrophoneInputGainValue:forInputDescription:]
+ -[AXRemoteHearingAidDevice setLeftVolumeInputGain:]
+ -[AXRemoteHearingAidDevice setLeftVolumeInputGainValue:forInputDescription:]
+ -[AXRemoteHearingAidDevice setRightMicrophoneInputGain:]
+ -[AXRemoteHearingAidDevice setRightMicrophoneInputGainValue:forInputDescription:]
+ -[AXRemoteHearingAidDevice setRightVolumeInputGain:]
+ -[AXRemoteHearingAidDevice setRightVolumeInputGainValue:forInputDescription:]
+ -[HUAudioInputData description]
+ -[HUAudioInputData initWithType:unit:min:max:]
+ -[HUAudioInputData max]
+ -[HUAudioInputData min]
+ -[HUAudioInputData mute]
+ -[HUAudioInputData rawValue]
+ -[HUAudioInputData setMute:]
+ -[HUAudioInputData setRawValue:]
+ -[HUAudioInputData setStatus:]
+ -[HUAudioInputData setValue:]
+ -[HUAudioInputData status]
+ -[HUAudioInputData type]
+ -[HUAudioInputData unit]
+ -[HUAudioInputData value]
+ GCC_except_table1017
+ GCC_except_table1024
+ GCC_except_table1029
+ GCC_except_table1033
+ GCC_except_table1041
+ GCC_except_table1049
+ GCC_except_table1052
+ GCC_except_table1059
+ GCC_except_table1066
+ GCC_except_table1075
+ GCC_except_table1079
+ GCC_except_table1086
+ GCC_except_table1117
+ GCC_except_table1125
+ GCC_except_table1127
+ GCC_except_table1132
+ GCC_except_table1136
+ GCC_except_table1138
+ GCC_except_table1142
+ GCC_except_table1144
+ GCC_except_table1166
+ GCC_except_table1167
+ GCC_except_table1188
+ GCC_except_table1192
+ GCC_except_table1251
+ GCC_except_table1269
+ GCC_except_table1273
+ GCC_except_table138
+ GCC_except_table1433
+ GCC_except_table1441
+ GCC_except_table1464
+ GCC_except_table1500
+ GCC_except_table1506
+ GCC_except_table151
+ GCC_except_table153
+ GCC_except_table1539
+ GCC_except_table1547
+ GCC_except_table1548
+ GCC_except_table1554
+ GCC_except_table1555
+ GCC_except_table1556
+ GCC_except_table1570
+ GCC_except_table159
+ GCC_except_table161
+ GCC_except_table1622
+ GCC_except_table1647
+ GCC_except_table1655
+ GCC_except_table1663
+ GCC_except_table1667
+ GCC_except_table1672
+ GCC_except_table1687
+ GCC_except_table1789
+ GCC_except_table1808
+ GCC_except_table1833
+ GCC_except_table1903
+ GCC_except_table1918
+ GCC_except_table1936
+ GCC_except_table1944
+ GCC_except_table1945
+ GCC_except_table1949
+ GCC_except_table1956
+ GCC_except_table1962
+ GCC_except_table1965
+ GCC_except_table2009
+ GCC_except_table2077
+ GCC_except_table2080
+ GCC_except_table2087
+ GCC_except_table2101
+ GCC_except_table2102
+ GCC_except_table2103
+ GCC_except_table2104
+ GCC_except_table2105
+ GCC_except_table2106
+ GCC_except_table2107
+ GCC_except_table2108
+ GCC_except_table2109
+ GCC_except_table2110
+ GCC_except_table2113
+ GCC_except_table2115
+ GCC_except_table2117
+ GCC_except_table2120
+ GCC_except_table2123
+ GCC_except_table2132
+ GCC_except_table2141
+ GCC_except_table2143
+ GCC_except_table2145
+ GCC_except_table2147
+ GCC_except_table2167
+ GCC_except_table2168
+ GCC_except_table2169
+ GCC_except_table2180
+ GCC_except_table2182
+ GCC_except_table2185
+ GCC_except_table2189
+ GCC_except_table2205
+ GCC_except_table2206
+ GCC_except_table2213
+ GCC_except_table2227
+ GCC_except_table2235
+ GCC_except_table224
+ GCC_except_table225
+ GCC_except_table2250
+ GCC_except_table2252
+ GCC_except_table226
+ GCC_except_table227
+ GCC_except_table2427
+ GCC_except_table2440
+ GCC_except_table2467
+ GCC_except_table2583
+ GCC_except_table2609
+ GCC_except_table2670
+ GCC_except_table2672
+ GCC_except_table2673
+ GCC_except_table2678
+ GCC_except_table2679
+ GCC_except_table2680
+ GCC_except_table2681
+ GCC_except_table2682
+ GCC_except_table2686
+ GCC_except_table2725
+ GCC_except_table2730
+ GCC_except_table2737
+ GCC_except_table2745
+ GCC_except_table2750
+ GCC_except_table2752
+ GCC_except_table2761
+ GCC_except_table2765
+ GCC_except_table2860
+ GCC_except_table2882
+ GCC_except_table290
+ GCC_except_table2914
+ GCC_except_table2942
+ GCC_except_table3079
+ GCC_except_table3108
+ GCC_except_table3129
+ GCC_except_table3130
+ GCC_except_table3138
+ GCC_except_table3147
+ GCC_except_table3156
+ GCC_except_table3159
+ GCC_except_table3161
+ GCC_except_table3311
+ GCC_except_table3312
+ GCC_except_table3313
+ GCC_except_table3330
+ GCC_except_table3336
+ GCC_except_table3342
+ GCC_except_table3345
+ GCC_except_table3357
+ GCC_except_table3365
+ GCC_except_table3372
+ GCC_except_table3375
+ GCC_except_table3383
+ GCC_except_table3385
+ GCC_except_table3395
+ GCC_except_table3398
+ GCC_except_table3407
+ GCC_except_table3409
+ GCC_except_table3411
+ GCC_except_table3436
+ GCC_except_table3499
+ GCC_except_table3505
+ GCC_except_table3509
+ GCC_except_table3578
+ GCC_except_table3580
+ GCC_except_table3623
+ GCC_except_table3660
+ GCC_except_table368
+ GCC_except_table3735
+ GCC_except_table3753
+ GCC_except_table3756
+ GCC_except_table3766
+ GCC_except_table405
+ GCC_except_table429
+ GCC_except_table574
+ GCC_except_table577
+ GCC_except_table578
+ GCC_except_table586
+ GCC_except_table590
+ GCC_except_table602
+ GCC_except_table615
+ GCC_except_table834
+ GCC_except_table887
+ GCC_except_table902
+ GCC_except_table910
+ GCC_except_table921
+ GCC_except_table924
+ GCC_except_table926
+ GCC_except_table944
+ GCC_except_table951
+ GCC_except_table983
+ _AXLEAudioServiceUUIDString
+ _CBConnectPeripheralOptionDetectAndLaunchLEAudioServices
+ _OBJC_CLASS_$_AXHearingAidLEAudioDevice
+ _OBJC_CLASS_$_CBLEAudioPeripheralInputGainDiscoveredEvent
+ _OBJC_CLASS_$_HUAudioInputData
+ _OBJC_IVAR_$_AXHearingAidDevice.leftMicrophoneInputGain
+ _OBJC_IVAR_$_AXHearingAidDevice.leftVolumeInputGain
+ _OBJC_IVAR_$_AXHearingAidDevice.rightMicrophoneInputGain
+ _OBJC_IVAR_$_AXHearingAidDevice.rightVolumeInputGain
+ _OBJC_IVAR_$_AXHearingAidDeviceController._leAudioSessionInfo
+ _OBJC_IVAR_$_AXHearingAidLEAudioDevice._isLeftEventHandlerSet
+ _OBJC_IVAR_$_AXHearingAidLEAudioDevice._isRightEventHandlerSet
+ _OBJC_IVAR_$_AXHearingAidLEAudioDevice._leftMicrophoneInputData
+ _OBJC_IVAR_$_AXHearingAidLEAudioDevice._leftVolumeInputData
+ _OBJC_IVAR_$_AXHearingAidLEAudioDevice._rightMicrophoneInputData
+ _OBJC_IVAR_$_AXHearingAidLEAudioDevice._rightVolumeInputData
+ _OBJC_IVAR_$_AXRemoteHearingAidDevice._leftMicrophoneInputGain
+ _OBJC_IVAR_$_AXRemoteHearingAidDevice._leftVolumeInputGain
+ _OBJC_IVAR_$_AXRemoteHearingAidDevice._rightMicrophoneInputGain
+ _OBJC_IVAR_$_AXRemoteHearingAidDevice._rightVolumeInputGain
+ _OBJC_IVAR_$_HUAudioInputData._max
+ _OBJC_IVAR_$_HUAudioInputData._min
+ _OBJC_IVAR_$_HUAudioInputData._mute
+ _OBJC_IVAR_$_HUAudioInputData._rawValue
+ _OBJC_IVAR_$_HUAudioInputData._status
+ _OBJC_IVAR_$_HUAudioInputData._type
+ _OBJC_IVAR_$_HUAudioInputData._unit
+ _OBJC_IVAR_$_HUAudioInputData._value
+ _OBJC_METACLASS_$_AXHearingAidLEAudioDevice
+ _OBJC_METACLASS_$_HUAudioInputData
+ __OBJC_$_INSTANCE_METHODS_AXHearingAidLEAudioDevice
+ __OBJC_$_INSTANCE_METHODS_HUAudioInputData
+ __OBJC_$_INSTANCE_VARIABLES_AXHearingAidLEAudioDevice
+ __OBJC_$_INSTANCE_VARIABLES_HUAudioInputData
+ __OBJC_$_PROP_LIST_AXHearingAidLEAudioDevice
+ __OBJC_$_PROP_LIST_HUAudioInputData
+ __OBJC_CLASS_RO_$_AXHearingAidLEAudioDevice
+ __OBJC_CLASS_RO_$_HUAudioInputData
+ __OBJC_METACLASS_RO_$_AXHearingAidLEAudioDevice
+ __OBJC_METACLASS_RO_$_HUAudioInputData
+ ___38-[HANanoSettings pairedWatchDidChange]_block_invoke
+ ___48-[AXHearingAidLEAudioDevice leftVolumeInputGain]_block_invoke
+ ___49-[AXHearingAidLEAudioDevice rightVolumeInputGain]_block_invoke
+ ___52-[AXHearingAidLEAudioDevice discoveringServiceUUIDs]_block_invoke
+ ___52-[AXHearingAidLEAudioDevice leftMicrophoneInputGain]_block_invoke
+ ___52-[AXHearingAidLEAudioDevice setLeftVolumeInputGain:]_block_invoke
+ ___53-[AXHearingAidLEAudioDevice rightMicrophoneInputGain]_block_invoke
+ ___53-[AXHearingAidLEAudioDevice setRightVolumeInputGain:]_block_invoke
+ ___55-[AXHearingAidLEAudioDevice sessionDidUpdateLocations:]_block_invoke
+ ___56-[AXHearingAidLEAudioDevice setLeftMicrophoneInputGain:]_block_invoke
+ ___57-[AXHearingAidLEAudioDevice setRightMicrophoneInputGain:]_block_invoke
+ ___61-[AXHearingAidDeviceController setupCentralManagerForLEAudio]_block_invoke
+ ___62-[AXHearingAidLEAudioDevice delayWriteProperty:forPeripheral:]_block_invoke
+ ___63-[AXHearingAidDeviceController isLEAudioServiceInServiceUUIDs:]_block_invoke
+ ___69-[AXHearingAidLEAudioDevice setupUpdatesHandlerForLEAudioPeripheral:]_block_invoke
+ ___73-[AXHearingAidDeviceController processConnectedIdentifiers:andLocations:]_block_invoke
+ ___block_descriptor_40_e8_32s_e33_v32?0"NSUUID"8"NSNumber"16^B24ls32l8
+ ___block_descriptor_40_e8_32s_e43_v32?0"NSString"8"HUAudioInputData"16^B24ls32l8
+ ___block_descriptor_48_e8_32s40r_e23_v32?0"CBUUID"8Q16^B24ls32l8r40l8
+ ___block_descriptor_48_e8_32s40r_e35_v32?0"NSString"8"NSNumber"16^B24ls32l8r40l8
+ ___block_descriptor_48_e8_32s40s_e43_v32?0"NSString"8"HUAudioInputData"16^B24ls32l8s40l8
+ ___block_descriptor_48_e8_32s40w_e31_v16?0"CBLEAudioSessionEvent"8ls32l8w40l8
+ ___block_descriptor_48_e8_32s40w_e57_v24?0"CBPeripheral"8"CBLEAudioPeripheralUpdateEvent"16ls32l8w40l8
+ ___block_descriptor_49_e8_32s40s_e25_v32?0"NSNumber"816^B24ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48s56r_e23_v32?0"CBUUID"8Q16^B24ls32l8s40l8r56l8s48l8
+ ___block_descriptor_80_e8_32s40s48s56s64s72s_e26_v32?0"CBService"8Q16^B24ls32l8s40l8s48l8s56l8s64l8s72l8
- GCC_except_table1023
- GCC_except_table1028
- GCC_except_table1032
- GCC_except_table1034
- GCC_except_table1038
- GCC_except_table1040
- GCC_except_table1084
- GCC_except_table1147
- GCC_except_table1165
- GCC_except_table1169
- GCC_except_table129
- GCC_except_table130
- GCC_except_table131
- GCC_except_table132
- GCC_except_table1329
- GCC_except_table1337
- GCC_except_table1359
- GCC_except_table1395
- GCC_except_table1401
- GCC_except_table1434
- GCC_except_table1437
- GCC_except_table1442
- GCC_except_table1443
- GCC_except_table1449
- GCC_except_table1450
- GCC_except_table1451
- GCC_except_table1465
- GCC_except_table1517
- GCC_except_table1550
- GCC_except_table1558
- GCC_except_table1562
- GCC_except_table1567
- GCC_except_table1582
- GCC_except_table1684
- GCC_except_table1703
- GCC_except_table1728
- GCC_except_table1734
- GCC_except_table1798
- GCC_except_table1813
- GCC_except_table1831
- GCC_except_table1840
- GCC_except_table1844
- GCC_except_table1851
- GCC_except_table1857
- GCC_except_table1860
- GCC_except_table1891
- GCC_except_table1897
- GCC_except_table1904
- GCC_except_table195
- GCC_except_table1972
- GCC_except_table1975
- GCC_except_table1982
- GCC_except_table1997
- GCC_except_table1998
- GCC_except_table1999
- GCC_except_table2000
- GCC_except_table2001
- GCC_except_table2003
- GCC_except_table2004
- GCC_except_table2005
- GCC_except_table2008
- GCC_except_table2010
- GCC_except_table2012
- GCC_except_table2014
- GCC_except_table2017
- GCC_except_table2026
- GCC_except_table2031
- GCC_except_table2033
- GCC_except_table2035
- GCC_except_table2037
- GCC_except_table2039
- GCC_except_table2041
- GCC_except_table2061
- GCC_except_table2062
- GCC_except_table2063
- GCC_except_table2076
- GCC_except_table2092
- GCC_except_table2093
- GCC_except_table2100
- GCC_except_table2114
- GCC_except_table2122
- GCC_except_table2306
- GCC_except_table2311
- GCC_except_table2338
- GCC_except_table2454
- GCC_except_table2480
- GCC_except_table2487
- GCC_except_table2541
- GCC_except_table2543
- GCC_except_table2544
- GCC_except_table2549
- GCC_except_table2550
- GCC_except_table2551
- GCC_except_table2552
- GCC_except_table2553
- GCC_except_table2557
- GCC_except_table2596
- GCC_except_table2601
- GCC_except_table2608
- GCC_except_table2621
- GCC_except_table2623
- GCC_except_table2632
- GCC_except_table2636
- GCC_except_table273
- GCC_except_table2731
- GCC_except_table2753
- GCC_except_table2785
- GCC_except_table2813
- GCC_except_table2950
- GCC_except_table2979
- GCC_except_table3000
- GCC_except_table3001
- GCC_except_table3009
- GCC_except_table3018
- GCC_except_table3027
- GCC_except_table3030
- GCC_except_table3032
- GCC_except_table3085
- GCC_except_table310
- GCC_except_table3110
- GCC_except_table3180
- GCC_except_table3181
- GCC_except_table3182
- GCC_except_table3199
- GCC_except_table3205
- GCC_except_table3211
- GCC_except_table3226
- GCC_except_table3234
- GCC_except_table3244
- GCC_except_table3252
- GCC_except_table3254
- GCC_except_table3264
- GCC_except_table3267
- GCC_except_table3276
- GCC_except_table3278
- GCC_except_table3280
- GCC_except_table3305
- GCC_except_table334
- GCC_except_table3368
- GCC_except_table3374
- GCC_except_table3378
- GCC_except_table3447
- GCC_except_table3449
- GCC_except_table3492
- GCC_except_table3529
- GCC_except_table3604
- GCC_except_table3622
- GCC_except_table3625
- GCC_except_table3635
- GCC_except_table479
- GCC_except_table482
- GCC_except_table483
- GCC_except_table491
- GCC_except_table495
- GCC_except_table507
- GCC_except_table520
- GCC_except_table730
- GCC_except_table783
- GCC_except_table798
- GCC_except_table806
- GCC_except_table809
- GCC_except_table817
- GCC_except_table820
- GCC_except_table822
- GCC_except_table825
- GCC_except_table840
- GCC_except_table844
- GCC_except_table847
- GCC_except_table851
- GCC_except_table879
- GCC_except_table909
- GCC_except_table917
- GCC_except_table920
- GCC_except_table925
- GCC_except_table937
- GCC_except_table945
- GCC_except_table958
- GCC_except_table959
- GCC_except_table962
- GCC_except_table971
- GCC_except_table975
- GCC_except_table982
- GCC_except_table984
- ___36-[AXHearingAidDeviceController init]_block_invoke_2
- ___block_descriptor_56_e8_32s40s48r_e23_v32?0"CBUUID"8Q16^B24ls32l8r48l8s40l8
- ___block_descriptor_72_e8_32s40s48s56s64s_e26_v32?0"CBService"8Q16^B24ls32l8s40l8s48l8s56l8s64l8
CStrings:
+ "1854"
+ "AudioInputData: Can't init, received invalid range: min %ld, max: %ld"
+ "AudioInputData: value %.2f, raw value %@, min %ld, max: %ld, unit %ld"
+ "BackCenter"
+ "BackLeft"
+ "BackRight"
+ "BottomFrontCenter"
+ "BottomFrontLeft"
+ "BottomFrontRight"
+ "CentralManager LEA 3: session connected peripherals %@"
+ "Empty"
+ "FrontCenter"
+ "FrontLeft"
+ "FrontLeftOfCenter"
+ "FrontLeftWide"
+ "FrontRight"
+ "FrontRightOfCenter"
+ "FrontRightWide"
+ "HearingAidDevice peripheral: didDiscoverServices, detected LEA 3 service for %@"
+ "HearingAidDevice: connectToPeripheral error, no peripherals"
+ "HearingAidDevice: setValue, MicrophoneInputGain %@"
+ "HearingAidDevice: setValue, VolumeInputGain %@"
+ "HearingAidDevice: valueForProperty, Reading MicrophoneInput %@"
+ "HearingAidDevice: valueForProperty, Reading VolumeInput %@"
+ "HearingAidDeviceController LEA 3: Merged into LEA 3 device\n%@"
+ "HearingAidDeviceController LEA 3: session added the second peripheral %@ to %@"
+ "HearingAidDeviceController LEA 3: session setup"
+ "HearingAidDeviceController LEA 3: session update - ID %@, state %@"
+ "HearingAidDeviceController LEA 3: session update - event %@ error %@"
+ "HearingAidDeviceController LEA 3: session update - eventType %@, connectedIdentifiers %@, locations %@"
+ "HearingAidDeviceController: Replaced MFi with LEA 3 device\n%@"
+ "HearingAidDeviceController: Scanning LEA 3"
+ "HearingAidDeviceController: hearingAidForLEAudioPeripheral %@ failed, found device with wrong protocol\n%@"
+ "HearingAidLEA3Device LEA 3: peripheral is unknown - %@"
+ "HearingAidLEA3Device LEA 3: peripheral setup update handler fail, device has no such peripheral - %@"
+ "HearingAidLEA3Device LEA 3: sessionDidUpdateLocations, session location %@ %@ %s"
+ "HearingAidLEA3Device LEA 3: sessionDidUpdateLocations, session location for unknown peripheral identifier %@"
+ "HearingAidLEA3Device LEA 3: sessionDidUpdateLocations, session unknown location %@ for %@"
+ "HearingAidLEA3Device LEA 3: sessionDidUpdateValue %@ for property %@, wrong format error, device %@"
+ "HearingAidLEA3Device LEA 3: sessionDidUpdateValue for volume %@"
+ "HearingAidLEA3Device LEA 3: setup update handler for peripheral %@,\ndevice: %@"
+ "HearingAidLEA3Device LEA 3: setupLoadingProperties for %@"
+ "HearingAidLEA3Device addPeripheral: %@, didAdd: %d\n%@"
+ "HearingAidLEA3Device peripheral LEA 3: LeftPrograms %@"
+ "HearingAidLEA3Device peripheral LEA 3: MicrophoneInputGain error %@"
+ "HearingAidLEA3Device peripheral LEA 3: Received Microphone InputDescription \"%@\", %@"
+ "HearingAidLEA3Device peripheral LEA 3: Received MicrophoneInputDiscovered with empty includedServiceDescription"
+ "HearingAidLEA3Device peripheral LEA 3: Received MicrophoneInputDiscovered with invalid event data %@"
+ "HearingAidLEA3Device peripheral LEA 3: Received MicrophoneInputGainUpdate, bur never got MicrophoneInputDiscovered for Left"
+ "HearingAidLEA3Device peripheral LEA 3: Received MicrophoneInputGainUpdate, bur never got MicrophoneInputDiscovered for Right"
+ "HearingAidLEA3Device peripheral LEA 3: Received Volume InputDescription \"%@\", %@"
+ "HearingAidLEA3Device peripheral LEA 3: Received VolumeInputDiscovered with empty includedServiceDescription"
+ "HearingAidLEA3Device peripheral LEA 3: Received VolumeInputDiscovered with invalid event data %@"
+ "HearingAidLEA3Device peripheral LEA 3: Received VolumeInputGainUpdate, bur never got VolumeInputDiscovered for Left"
+ "HearingAidLEA3Device peripheral LEA 3: Received VolumeInputGainUpdate, bur never got VolumeInputDiscovered for Right"
+ "HearingAidLEA3Device peripheral LEA 3: RightPrograms %@"
+ "HearingAidLEA3Device peripheral LEA 3: leftSelectedProgram %@"
+ "HearingAidLEA3Device peripheral LEA 3: preset available %d"
+ "HearingAidLEA3Device peripheral LEA 3: preset index: %d"
+ "HearingAidLEA3Device peripheral LEA 3: preset name: %s"
+ "HearingAidLEA3Device peripheral LEA 3: preset writable: %d"
+ "HearingAidLEA3Device peripheral LEA 3: received peripheral update for MicrophoneInput %@f"
+ "HearingAidLEA3Device peripheral LEA 3: received peripheral update for VolumeInput %@"
+ "HearingAidLEA3Device peripheral LEA 3: rightSelectedProgram %@"
+ "HearingAidLEA3Device peripheral LEA 3: set MicrophoneInputGain %@ adjusted %@ for %@ to peripheral: %@ %@"
+ "HearingAidLEA3Device peripheral LEA 3: set VolumeInputGain %@ adjusted %@ for %@ to peripheral: %@ %@"
+ "HearingAidLEA3Device peripheral LEA 3: set VolumeInputGain error %@"
+ "HearingAidLEA3Device peripheral LEA 3: setActivePreset %@"
+ "HearingAidLEA3Device peripheral LEA 3: setActivePreset error %@"
+ "HearingAidLEA3Device peripheral LEA 3: setVolume %@ adjusted %@"
+ "HearingAidLEA3Device peripheral LEA 3: setVolume error %@"
+ "HearingAidLEA3Device peripheral LEA 3: update %@ %@, HA features %@"
+ "HearingAidLEA3Device peripheral LEA 3: update %@ %@, MicrophoneInputDiscovered"
+ "HearingAidLEA3Device peripheral LEA 3: update %@ %@, MicrophoneInputGainValue %@"
+ "HearingAidLEA3Device peripheral LEA 3: update %@ %@, MicrophoneInputMuteValue %@"
+ "HearingAidLEA3Device peripheral LEA 3: update %@ %@, MicrophoneInputStatusValue %@"
+ "HearingAidLEA3Device peripheral LEA 3: update %@ %@, VolumeInputDiscovered"
+ "HearingAidLEA3Device peripheral LEA 3: update %@ %@, VolumeInputGainValue %@"
+ "HearingAidLEA3Device peripheral LEA 3: update %@ %@, VolumeInputMuteValue %@"
+ "HearingAidLEA3Device peripheral LEA 3: update %@ %@, VolumeInputStatusValue %@"
+ "HearingAidLEA3Device peripheral LEA 3: update %@ %@, active preset %@"
+ "HearingAidLEA3Device peripheral LEA 3: update %@ %@, name preset at index: %@"
+ "HearingAidLEA3Device peripheral LEA 3: update %@ %@, presets %@, active preset index %@"
+ "HearingAidLEA3Device peripheral LEA 3: update %@ %@, volume %@"
+ "HearingAidLEA3Device peripheral LEA 3: updateHandler %@, event type: %@, event: %@\ndevice: %@"
+ "HearingAidLEA3Device: Connect to %@"
+ "HearingAidLEA3Device: Created from Left and Right device\n%@"
+ "HearingAidLEA3Device: Created from MFi device\n%@"
+ "HearingAidLEA3Device: addPeripheral %@ %@ didAdd: %d to device:\n%@"
+ "HearingAidLEA3Device: availablePropertiesForPeripheral SKIP for %@"
+ "HearingAidLEA3Device: characteristicForUUID SKIP for %@"
+ "HearingAidLEA3Device: connectionDidChange, isConnecting %d %@"
+ "HearingAidLEA3Device: delayWriteProperty %@ ear %@ peripheral %@ device name %@"
+ "HearingAidLEA3Device: didLoadPersistentProperties %d %@, Left %@, Right %@"
+ "HearingAidLEA3Device: disconnectAndUnpair(%d) from \n%@"
+ "HearingAidLEA3Device: disconnectAndUnpair(%d), SKIP disconnecting/unpairing from %@ %@\n%@"
+ "HearingAidLEA3Device: loadProperties SKIP for %@ %@"
+ "HearingAidLEA3Device: loadRequiredProperties SKIP for %@"
+ "HearingAidLEA3Device: set LeftMicrophoneInputGain value %.2f, %ld"
+ "HearingAidLEA3Device: set LeftVolumeInputGain value %.2f, %ld"
+ "HearingAidLEA3Device: set MicrophoneInputGain value %.2f, %ld"
+ "HearingAidLEA3Device: set RightVolumeInputGain value %.2f, %ld"
+ "HearingAidLEA3Device: setNotify %d SKIP for peripheral: %@ in device %p,\nservices %@"
+ "HearingAidLEA3Device: setValue, %@ %@ %@"
+ "HearingAidLEA3Device: updateName, (paired: %d %d) name: %p %@, left: %@, right: %@"
+ "HearingAidLEA3Device: updated name %@"
+ "HearingAidLEA3Device: updated name %@, saving persistent representation - %@"
+ "HearingAidLEA3Device: writeValueForProperty SKIP for %@"
+ "LEA 3"
+ "LEA 3: session DeviceIdentifier - %@"
+ "LEA 3: session connected, will send delayed connected message if needed"
+ "LEA 3: session device %@"
+ "LEA 3: session device already has both peripherals %@"
+ "LEA 3: session device is not found"
+ "LEA 3: session left %@ connection requested %d"
+ "LEA 3: session no connected identifiers"
+ "LEA 3: session no peripherals for identifiers %@"
+ "LEA 3: session not all peripherals retrieved for identifiers %@"
+ "LEA 3: session peripheral1 %@\n found device %@"
+ "LEA 3: session peripheral2 %@\n found device %@"
+ "LEA 3: session right %@ connection requested %d"
+ "LEA 3: session update - ID %@, new state %@"
+ "LEA 3: session update - connected, connectedIdentifiers %@, locations %@"
+ "LEA 3: session update - fail, paired hearing device has wrong protocol"
+ "LEA 3: session update - mic gain %@, paired HearingDevice: %@"
+ "LEA 3: session update - mic mute %@"
+ "LEA 3: session update - peripheral ready, connectedIdentifiers %@"
+ "LEA 3: session update - unknown event %@"
+ "LEA 3: session update - volume %@, paired HearingDevice: %@"
+ "LEA 3: session update - volume mute %@"
+ "LEA 3: session update - volume offset %@"
+ "LEA 3: session updating persistent representation - %@"
+ "LeftSurround"
+ "LiveListenController: Route changed, selected route: LL = %d, HA = %d"
+ "LiveListenController: Starting Live Listen result: Is Listening (%d), error %@"
+ "LiveListenController: Stopping Live Listen result: Is Listening (%d), error %@"
+ "LowFrequencyEffects1"
+ "LowFrequencyEffects2"
+ "Microphone Input Gain"
+ "NearbyHearingAidController: Ignoring peer's Hearing Device BT paired and Connection properties for %@, isLocal device: %d"
+ "NearbyHearingAidController: Removed peer's Hearing Device BT paired and Connection properties for %@, isLocal device: %d"
+ "NearbyHearingAidController: Writing peer's Hearing Device properties for %@, isLocal device: %d"
+ "NotAllowed"
+ "RemoteDevice: setValue for property MicrophoneInput: %@ for %@"
+ "RemoteDevice: setValue for property VolumeInput: %@ for %@"
+ "RightSurround"
+ "SideLeft"
+ "SideRight"
+ "TopBackCenter"
+ "TopBackLeft"
+ "TopBackRight"
+ "TopCenter"
+ "TopFrontCenter"
+ "TopFrontLeft"
+ "TopFrontRight"
+ "TopSideLeft"
+ "TopSideRight"
+ "Volume Input Gain"
+ "[PairedHA-trace] AXHAController callback FIRED listener=%p processingPairDeviceUUID=%@"
+ "[PairedHA-trace] AXHAController registering pairedHearingAids update block listener=%p settingsInstance=%p"
+ "[PairedHA-trace] AXHearingAidDeviceController callback FIRED listener=%p"
+ "[PairedHA-trace] AXHearingAidDeviceController dispatched pairedHearingAidsDidChange on bluetoothCentralQueue listener=%p"
+ "[PairedHA-trace] AXHearingAidDeviceController registering pairedHearingAids update block listener=%p settingsInstance=%p (registration is delayed 0.1s on bluetoothCentralQueue)"
+ "[PairedHA-trace] setPairedHearingAids ENTER process=%{public}@ pid=%d settingsInstance=%p valueIsNil=%d count=%lu"
+ "[PairedHA-trace] setPairedHearingAids returned from setValue:forPreferenceKey: settingsInstance=%p"
+ "processBTVolumeInputDiscovered %@ for inputDescription %@ for Ear: %@"
+ "processBTVolumeInputGainUpdate %@ for inputDescription %@ for Ear: %@"
+ "v16@?0@\"CBLEAudioSessionEvent\"8"
+ "v24@?0@\"CBPeripheral\"8@\"CBLEAudioPeripheralUpdateEvent\"16"
+ "v32@?0@\"NSString\"8@\"HUAudioInputData\"16^B24"
+ "v32@?0@\"NSUUID\"8@\"NSNumber\"16^B24"
+ "\xd12\x89($d$\"\""
+ "\xf0T;)Q"
+ "\xf0\x91"
- "LiveListenController: Is Listening (%d) %@ - %lf, %lf"
- "LiveListenController: Is Listening (%d) with error %@"
- "LiveListenController: audioRoutesDidChange, Live Listen route selected: %d, Hearing Aids route selected: %d"
- "NearbyHearingAidController: Writing Hearing Aids properties, updating controller: %@"
- "PairedHearingUUIDsPreference"
- "\xd12\x89($dB\""
- "\xf0Q"
- "\xf0\x8b)Q"
```
