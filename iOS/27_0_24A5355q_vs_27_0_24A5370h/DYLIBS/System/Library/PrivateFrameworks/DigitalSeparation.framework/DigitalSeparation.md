## DigitalSeparation

> `/System/Library/PrivateFrameworks/DigitalSeparation.framework/DigitalSeparation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x364d0` | `0x3a5b0` | **`+0x40e0`** |
| `__AUTH_CONST.__const` | `0x9f8` | `0xe88` | **`+0x490`** |
| `__TEXT.__const` | `0x6f8` | `0xaf8` | **`+0x400`** |
| `__TEXT.__eh_frame` | `0x9b0` | `0xd10` | **`+0x360`** |
| `__DATA.__bss` | `0x4f8` | `0x828` | **`+0x330`** |
| `__TEXT.__swift5_typeref` | `0x316` | `0x50e` | **`+0x1f8`** |
| `__TEXT.__unwind_info` | `0xc70` | `0xdd8` | **`+0x168`** |
| `__TEXT.__swift5_fieldmd` | `0x180` | `0x2c4` | **`+0x144`** |
| `__TEXT.__cstring` | `0x1757` | `0x1887` | **`+0x130`** |
| `__TEXT.__constg_swiftt` | `0x178` | `0x280` | **`+0x108`** |
| `__TEXT.__swift5_reflstr` | `0x127` | `0x213` | **`+0xec`** |
| `__AUTH_CONST.__auth_got` | `0x820` | `0x908` | **`+0xe8`** |
| `__DATA.__data` | `0x720` | `0x7a8` | **`+0x88`** |
| `__DATA_CONST.__got` | `0x4b0` | `0x530` | **`+0x80`** |
| `__AUTH.__objc_data` | `0x540` | `0x5b0` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0x15c` | `0x1c8` | **`+0x6c`** |
| `__AUTH_CONST.__objc_const` | `0x4e40` | `0x4e88` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x2694` | `0x26c4` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `—` | `0x30` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x60` | `0x90` | **`+0x30`** |
| `__AUTH.__data` | `0xe8` | `0x110` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0x30` | `0x54` | **`+0x24`** |
| `__TEXT.__swift_as_ret` | `0x44` | `0x68` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0x1528` | `0x1548` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1f8c` | `0x1fac` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x40` | `0x5c` | **`+0x1c`** |
| `__TEXT.__swift5_types` | `0x20` | `0x38` | **`+0x18`** |
| `__TEXT.__swift5_protos` | `0x10` | `0x1c` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0xf0` | `0xf8` | **`+0x8`** |

### Other Changes

```diff

-654.0.0.0.0
+653.0.1.0.0

+  - /System/Library/Frameworks/Network.framework/Network

-  Functions: 1126
-  Symbols:   1767
-  CStrings:  456
+  Functions: 1242
+  Symbols:   1815
+  CStrings:  464
Symbols:
+ _AnalyticsSendEvent
+ _OBJC_CLASS_$_CTQuickSwitchInfo
+ _OBJC_CLASS_$_CTQuickSwitchNumberSharingInfo
+ _OBJC_CLASS_$_DSSafetyCheckEnteredAnalyticsReporter
+ _OBJC_CLASS_$_OS_dispatch_queue
+ _OBJC_METACLASS_$_DSSafetyCheckEnteredAnalyticsReporter
+ __DATA_DSSafetyCheckEnteredAnalyticsReporter
+ __INSTANCE_METHODS_DSSafetyCheckEnteredAnalyticsReporter
+ __METACLASS_DATA_DSSafetyCheckEnteredAnalyticsReporter
+ ___swift_instantiateConcreteTypeFromMangledNameAbstractV2
+ ___swift_memcpy120_8
+ ___swift_memcpy16_8
+ __swift_stdlib_bridgeErrorToNSError
+ _associated conformance 17DigitalSeparation18ConnectivityStatusOSHAASQ
+ _associated conformance 17DigitalSeparation23QuickSwitchDeviceStatusOSHAASQ
+ _swift_beginAccess
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_weakDestroy
+ _swift_weakInit
+ _swift_weakLoadStrong
+ _symbolic $s17DigitalSeparation16AnalyticsSendingP
+ _symbolic $s17DigitalSeparation20QuickSwitchProvidingP
+ _symbolic $s17DigitalSeparation21ConnectivityProvidingP
+ _symbolic $sSY
+ _symbolic SS_So8NSObjectCt
+ _symbolic SaySo30CTQuickSwitchNumberSharingInfoCG
+ _symbolic Say_____G So17OS_dispatch_queueC8DispatchE10AttributesV
+ _symbolic ScCySaySo30CTQuickSwitchNumberSharingInfoCG______pG s5ErrorP
+ _symbolic ScCySo17CTQuickSwitchInfoC______pG s5ErrorP
+ _symbolic ScCy__________G 7Network6NWPathV s5NeverO
+ _symbolic So17OS_dispatch_queueC
+ _symbolic So19CoreTelephonyClientC
+ _symbolic So8NSNumberC
+ _symbolic _____ 17DigitalSeparation18ConnectivityStatusO
+ _symbolic _____ 17DigitalSeparation22DefaultAnalyticsSenderV
+ _symbolic _____ 17DigitalSeparation23QuickSwitchDataProviderV
+ _symbolic _____ 17DigitalSeparation23QuickSwitchDeviceStatusO
+ _symbolic _____ 17DigitalSeparation24ConnectivityDataProviderV
+ _symbolic _____ 17DigitalSeparation26DSDeviceAnalyticsStoreCoreV
+ _symbolic _____ 7Network13NWPathMonitorC
+ _symbolic ______p 17DigitalSeparation16AnalyticsSendingP
+ _symbolic ______p 17DigitalSeparation20QuickSwitchProvidingP
+ _symbolic ______p 17DigitalSeparation21ConnectivityProvidingP
+ _symbolic _____ySSSo8NSObjectCG s18_DictionaryStorageC
+ _symbolic _____ySS_So8NSObjectCtG s23_ContiguousArrayStorageC
+ _type_layout_string 17DigitalSeparation23QuickSwitchDataProviderV
+ _type_layout_string 17DigitalSeparation24ConnectivityDataProviderV
+ _type_layout_string 17DigitalSeparation26DSDeviceAnalyticsStoreCoreV
CStrings:
+ "DSDeviceAnalyticsStore"
+ "DigitalSeparation/DSSafetyCheckEnteredAnalyticsReporter.swift"
+ "Failed to get Quick Switch role: %@"
+ "com.DigitalSeparation.coreTelephonyQueue"
+ "com.DigitalSeparation.networkMonitorQueue"
+ "com.apple.DigitalSeparation.SafetyCheckEntered"
+ "getConnectivityStatus()"
+ "quickSwitchStatus"
```
