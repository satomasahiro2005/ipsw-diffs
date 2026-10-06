## com.apple.driver.AppleARMPlatform

> `com.apple.driver.AppleARMPlatform`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0xd60` | **`+0xd60`** |
| `__TEXT_EXEC.__text` | `0x55234` | `0x5574c` | **`+0x518`** |
| `__DATA_CONST.__const` | `0x16af0` | `0x16b30` | **`+0x40`** |
| `__TEXT.__const` | `0x1ac0` | `0x1ae0` | **`+0x20`** |
| `__TEXT.__cstring` | `0xd21f` | `0xd238` | **`+0x19`** |

### Other Changes

```diff

-1145.0.0.0.0
+1150.0.0.0.0

-  CStrings:  1743
+  CStrings:  1747
Functions:
~ __ZN14MCPolicyMgrPMP20updateDataStreamSizeEPv : 348 -> 344
~ _OUTLINED_FUNCTION_0 : 1448 -> 1484
~ __ZNK14MCPolicyMgrPMP18printDSConfigArrayEv : 276 -> 312
~ __ZN14MCPolicyMgrPMP19update_stream_entryEjj : 420 -> 448
~ sub_fffffff0085b8198 -> sub_fffffff0085c5fe8 : 348 -> 356
~ __ZN11AppleARMCPU22_validateConfigurationEv : 2572 -> 2568
~ sub_fffffff0085bdba0 -> sub_fffffff0085cb9f4 : 540 -> 544
~ __ZN21AppleARMIICController12publishBelowEP15IORegistryEntry : 1812 -> 1820
~ __ZN17AppleARMIICDevice8copyLogsEPvPj : 448 -> 444
~ __ZN16VictimUserClient8addFreqsEPjP20IOSACVictimFrequency : 1416 -> 1436
~ __ZN16VictimUserClient11removeFreqsEPjP20IOSACVictimFrequency : 836 -> 828
~ sub_fffffff0085c22f0 -> sub_fffffff0085d0158 : 216 -> 240
~ __ZN10AppleARMIO17getIODeviceClocksEPjbj : 1124 -> 1136
~ sub_fffffff0085c44a0 -> sub_fffffff0085d232c : 128 -> 144
~ __ZN22AppleARMNORFlashDevice11writeRegionEjPKhyy : 916 -> 932
~ __ZN22AppleARMNORFlashDevice10writeBytesEjPKhyy : 836 -> 852
~ __ZN22AppleARMNORFlashDevice11eraseRegionEjyy : 948 -> 960
~ __ZN29AppleARMPerformanceController5startEP9IOService : 5292 -> 5328
~ __ZN29AppleARMPerformanceController13setPropertiesEP8OSObject : 468 -> 488
~ __ZN29AppleARMPerformanceController17publishStatisticsEv : 2700 -> 2872
~ __ZN29AppleARMPerformanceController31initVoltageAndPerformanceStatesEv : 6524 -> 6640
~ __ZN29AppleARMPerformanceController26startPerformanceControllerEv : 456 -> 500
~ sub_fffffff0085cd2c8 -> sub_fffffff0085db314 : 832 -> 836
~ sub_fffffff0085cd6b0 -> sub_fffffff0085db700 : 148 -> 144
~ sub_fffffff0085ce12c -> sub_fffffff0085dc178 : 72 -> 96
~ sub_fffffff0085ce174 -> sub_fffffff0085dc1d8 : 96 -> 124
~ __ZN29AppleARMPerformanceController17traceBufferEnableEv : 924 -> 944
~ __ZN29AppleARMPerformanceController19traceBufferAddEntryEjjjjj : 600 -> 592
~ sub_fffffff0085ce9b0 -> sub_fffffff0085dca3c : 96 -> 104
~ __ZN29AppleARMPerformanceController16_perfDivToStringEjjPc : 184 -> 204
~ sub_fffffff0085cf004 -> sub_fffffff0085dd0ac : 944 -> 952
~ sub_fffffff0085cf794 -> sub_fffffff0085dd844 : 168 -> 184
~ sub_fffffff0085cfd5c -> sub_fffffff0085dde1c : 256 -> 300
~ sub_fffffff0085cfe5c -> sub_fffffff0085ddf48 : 124 -> 152
~ __ZN29AppleARMPerformanceController27_mapVoltageLevelToPerfStateEjj : 108 -> 140
~ sub_fffffff0085d00e0 -> sub_fffffff0085de208 : 1844 -> 1768
~ sub_fffffff0085d0c60 -> sub_fffffff0085ded3c : 2872 -> 3064
~ sub_fffffff0085d1d0c -> sub_fffffff0085dfea8 : 160 -> 148
~ sub_fffffff0085d4ca8 -> sub_fffffff0085e2e38 : 332 -> 348
~ __ZN19AggressorUserClient23aggressorActionMultipleEjPKj : 284 -> 280
~ __ZN19AggressorUserClient17registerAggressorEPjP23IOSACAggressorFrequencyPA8_y : 448 -> 456
~ __ZN19AggressorUserClient11getFreqListEPjP23IOSACAggressorFrequency : 140 -> 148
~ __ZN19AggressorUserClient15getSafeFreqListEPjP23IOSACAggressorFrequency : 588 -> 648
~ __ZN22AppleARMSPMIController13logNewCommandEP19AppleARMSPMICommand : 968 -> 984
~ __ZN22AppleARMSPMIController16logFinishCommandEP19AppleARMSPMICommandi : 1264 -> 1280
~ __ZN14MCPolicyMgrPMPC1EjP9IOService : 2736 -> 2740
~ __ZN18AppleMemCacheEvent6createEP8MCClient14MCDataStreamIdj : 464 -> 468
~ _OUTLINED_FUNCTION_1_0 : 568 -> 572
~ sub_fffffff0085dd2d8 -> sub_fffffff0085eb4ec : 204 -> 220
~ sub_fffffff0085dd3a4 -> sub_fffffff0085eb5c8 : 204 -> 220
~ ____ZN23AppleMemCacheController9copyDSIDsE13MCPersistencePjj_block_invoke : 368 -> 364
~ __ZN23AppleMemCacheController13dataCollectorEv : 480 -> 492
~ sub_fffffff0085e1664 -> sub_fffffff0085ef8a0 : 676 -> 664
~ sub_fffffff0085e5008 -> sub_fffffff0085f3238 : 256 -> 300
~ __ZN26AppleARMSPIFlashController18_identifyNORDeviceEv : 2680 -> 2748
~ __ZN26AppleARMSPIFlashController16_programBytesSSTEPKhyy : 584 -> 576
~ sub_fffffff0085ec0d4 -> sub_fffffff0085fa36c : 288 -> 292
~ __ZN12MCDataStream13getStreamNameE14MCDataStreamId : 124 -> 132
~ sub_fffffff0085ee814 -> sub_fffffff0085fcab8 : 88 -> 84
~ __ZN17AppleARMBacklight38loadAndExportWhitepointCorrectionTableEv : 1564 -> 1584
~ __ZN17AppleARMBacklight19nits2CalibratedNitsEi : 272 -> 264
~ __ZN17AppleARMBacklight19calibratedNits2NitsEi : 276 -> 268
~ sub_fffffff008600edc -> sub_fffffff00860f180 : 140 -> 144
~ __ZN24MemCacheManagerInterface19setDataStreamConfigEP18MCDataStreamConfigj : 1120 -> 1144
~ __ZN24MemCacheManagerInterface21disableAllDataStreamsEv : 380 -> 392
~ __ZN24MemCacheManagerInterface24getQuotaGrpRequestedSizeEj : 156 -> 188
~ sub_fffffff008602684 -> sub_fffffff008610970 : 292 -> 296
~ sub_fffffff008605190 -> sub_fffffff008613480 : 128 -> 152
CStrings:
+ "12111112122212121121211111111111111111111111111121111111111111111111111111111111111111111111111111111111111111111111111111111111111212112121"
+ "ACPU"
+ "CVAVE"
+ "VCPU"
+ "uANE"
- "1211111212221212112121111111111111111111111121111111111111111111111111111111111111111111111111111111111111111111111111111111111212112121"
```
