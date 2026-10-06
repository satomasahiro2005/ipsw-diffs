## IOKit

> `/System/Library/Frameworks/IOKit.framework/Versions/A/IOKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa2680` | `0xa2770` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x22b8` | `0x2288` | **`-0x30`** |
| `__AUTH_CONST.__auth_got` | `0x10b0` | `0x10b8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-100284.0.0.0.0
+100287.0.0.0.0

-  Functions: 3568
-  Symbols:   3954
+  Functions: 3570
+  Symbols:   3955
Symbols:
+ __IOHIDServiceCreateVirtualNoInit
+ _objc_storeWeak
- ___IOHIDServiceCreateVirtualNoInit
Functions:
~ _IODispatchCalloutFromCFMessage : 456 -> 460
~ _OUTLINED_FUNCTION_5 : 20 -> 12
~ _OUTLINED_FUNCTION_5 : 44 -> 20
~ _OUTLINED_FUNCTION_5 : 16 -> 44
~ _OUTLINED_FUNCTION_5 : 24 -> 16
~ _OUTLINED_FUNCTION_5 : 48 -> 24
~ _OUTLINED_FUNCTION_5 : 32 -> 48
~ _OUTLINED_FUNCTION_5 : 36 -> 32
~ _OUTLINED_FUNCTION_5 : 16 -> 36
~ _OUTLINED_FUNCTION_5 : 32 -> 16
~ _OUTLINED_FUNCTION_5 : 24 -> 32
~ _OUTLINED_FUNCTION_5 : 32 -> 24
+ _OUTLINED_FUNCTION_5
~ _IOCFUnserializeBinary : 2036 -> 2016
~ _OUTLINED_FUNCTION_1 : 16 -> 28
~ __IOHIDObjectRetainCount : 380 -> 376
~ _IOHIDEventSystemClientCreateWithType : 944 -> 928
~ _OUTLINED_FUNCTION_0 : 28 -> 12
~ _iohideventsystem_server : 156 -> 160
~ _OUTLINED_FUNCTION_2 : 24 -> 16
~ __IOHIDServiceClientCopyUsageProp : 456 -> 452
~ _iohideventsystem_client_server : 156 -> 160
~ __IOHIDServiceRemoveConnection : 420 -> 332
~ -[HIDEventService dealloc] : 72 -> 88
~ __IOHIDServiceReleasePrivate : 580 -> 596
~ _OUTLINED_FUNCTION_3 : 12 -> 24
~ _OUTLINED_FUNCTION_12 : 12 -> 28
~ _OUTLINED_FUNCTION_12 : 28 -> 12
- _OUTLINED_FUNCTION_12
~ __IOHIDServiceUnscheduleAsync : 876 -> 892
~ _IOCFUnserializeparse : 3544 -> 3540
~ _getTag : 1108 -> 1088
~ _getString : 476 -> 480
~ __IOHIDServiceCopyEventCounts : 316 -> 308
~ ___OSKextInitialize : 1220 -> 1204
~ _OSKextParseVersionString : 968 -> 984
- ___IOHIDServiceCreateVirtualNoInit
~ ___IOHIDServiceInit : 4324 -> 4320
~ _IOPMCopyDeviceRestartPreventers : 304 -> 300
~ _DoIdrefScan : 476 -> 492
~ _idRefDictionaryForObject : 184 -> 180
~ _DoCFSerialize : 1664 -> 1668
~ _DoCFSerializeString : 304 -> 320
~ _getCFEncodedData : 400 -> 396
~ _OUTLINED_FUNCTION_10 : 32 -> 12
~ _OUTLINED_FUNCTION_10 : 28 -> 32
+ _OUTLINED_FUNCTION_10
~ ___IOHIDEventPopulateDigitizerLegacyData : 520 -> 504
~ ___IOHIDEventPopulateDigitizerCurrentData : 560 -> 544
~ _DoCFSerializeSet : 228 -> 240
~ _mergeDictIntoMutable : 284 -> 272
~ _setPreferencesForSrc : 856 -> 828
~ _IOPMCopyPreferencesOnFile : 180 -> 188
~ _getSystemProvidedPreferences : 1696 -> 1688
~ _comparePrefsToDefaults : 344 -> 336
~ _IOPMRemoveIrrelevantProperties : 860 -> 848
~ _IOPMCopyUPSShutdownLevels : 588 -> 584
~ _NXEventSystemInfo : 408 -> 404
~ _NXGetClickSpace : 268 -> 264
~ _fat_iterator_find_fat_arch : 364 -> 376
~ _macho_find_symbol : 764 -> 720
~ _macho_scan_load_commands : 404 -> 408
~ ___macho_sect_in_lc : 284 -> 324
~ _macho_remove_linkedit : 344 -> 352
~ _macho_trim_linkedit : 684 -> 696
~ _IOHIDDeviceSetValueMultipleWithCallback : 512 -> 492
~ ___IOHIDDeviceCopyMatchingInputElements : 552 -> 548
~ ___IOHIDPropertySaveToKeyWithSpecialKeys : 276 -> 284
~ ___IOHIDPropertyLoadFromKeyWithSpecialKeys : 224 -> 228
~ _IOHIDEventGetIntegerMultiple : 92 -> 108
~ _IOHIDEventGetIntegerMultipleWithOptions : 104 -> 112
~ _IOHIDEventGetFloatMultiple : 92 -> 108
~ _IOHIDEventGetFloatMultipleWithOptions : 104 -> 112
~ _IOHIDEventGetDoubleMultiple : 92 -> 108
~ _IOHIDEventGetDoubleMultipleWithOptions : 104 -> 112
~ _IOHIDEventGetUInt64Multiple : 92 -> 108
~ _IOHIDEventGetUInt64MultipleWithOptions : 104 -> 112
~ _IOHIDEventSetIntegerMultiple : 92 -> 108
~ _IOHIDEventSetIntegerMultipleWithOptions : 104 -> 112
~ _IOHIDEventSetFloatMultiple : 92 -> 108
~ _IOHIDEventSetFloatMultipleWithOptions : 104 -> 112
~ _IOHIDEventSetDoubleMultiple : 92 -> 108
~ _IOHIDEventSetDoubleMultipleWithOptions : 104 -> 112
~ _IOHIDEventSetUInt64Multiple : 92 -> 108
~ _IOHIDEventSetUInt64MultipleWithOptions : 104 -> 112
~ ___IOHIDEventTypeDescriptorVendorDefined : 568 -> 564
~ ___IOHIDEventTypeDescriptorUnicode : 388 -> 384
~ ___IOHIDEventTypeDescriptorForceStageEvent : 332 -> 328
~ ___IOHIDEventTypeDescriptorHeartRateEvent : 240 -> 236
~ ___IOEthernetControllerCFMachPortCallBack : 228 -> 224
~ _OSKextGetExecutableURL : 752 -> 756
~ _OSKextCopyAllRequestedIdentifiers : 500 -> 496
~ ___OSKextResolveDependencies : 2796 -> 2776
~ ___OSKextReadSymbolReferences : 924 -> 928
~ _OSKextFindLinkDependencies : 2208 -> 2236
~ ___OSKextValidate : 1424 -> 1420
~ ___absPathOnVolume : 124 -> 120
~ _saveBackTrace : 340 -> 336
~ __copyAssertionsByProcess : 420 -> 412
~ _IODPCreateStringWithLinkTrainingData : 540 -> 552
~ _IOAVCreateStringWithVideoColorData : 228 -> 224
~ _iohideventsystem_server_routine : 64 -> 68
~ _iohideventsystem_client_server_routine : 64 -> 68
~ __ZN9DisplayID8checksumEPKvm : 40 -> 56
~ _IOAVHDMIAudioClockRegenerationDataForLink : 232 -> 236
~ _IOAVAudioGetChannelAllocation : 120 -> 124
~ _IOAVContentProtectionTypeString : 44 -> 40
~ _IOAVVideoTimingGetSyncRateRounded : 24 -> 32
~ __ZL32__IOAVGetStandardVideoTimingData23IOAVVideoTimingStandardjjibP19IOAVVideoTimingData22IOAVVideoBlankingStyle : 276 -> 300
~ __ZL32__IOAVGetCEAVideoShortIDWithDataPK19IOAVVideoTimingDatab : 252 -> 256
~ _IOAVVideoTimingGetITSource : 72 -> 84
~ _IOAVDSCCapabilitiesGetMaxSlicesPerLine : 52 -> 48
~ _IODPDriveSettingsEqual : 72 -> 84
~ _IODPConstrainedDriveSettings : 84 -> 76
~ _IODPConstrainDriveSettings : 132 -> 124
~ __getNextInQueueMemInternal : 464 -> 460
~ __getPrevInQueueMemInternal : 432 -> 428
~ _IOHIDDeviceCopyDescription : 544 -> 540
~ ___IOHIDEventEventCopyDebugDescWithIndentLevel : 1100 -> 1096
+ __IOHIDServiceCreateVirtualNoInit
~ __IOHIDServiceCopyServiceInfoForClient : 600 -> 608
~ __IOHIDServiceRemoveConnection.cold.2 : 128 -> 148
+ __IOHIDServiceRemoveConnection.cold.3
~ _IOHIDServiceClientConformsTo : 72 -> 76
~ __IOHIDEventSystemConnectionCopyEventCounts : 148 -> 140
~ _IOAVPropertyListCreateWithCFProperties : 1188 -> 1164
CStrings:
+ "OSKEXT_BUILD_DATE 00:23:36 Jun 11 2026"
- "OSKEXT_BUILD_DATE 09:48:24 May 24 2026"
```
