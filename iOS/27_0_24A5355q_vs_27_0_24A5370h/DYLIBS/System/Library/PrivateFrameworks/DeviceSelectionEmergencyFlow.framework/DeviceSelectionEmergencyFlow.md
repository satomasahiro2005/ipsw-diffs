## DeviceSelectionEmergencyFlow

> `/System/Library/PrivateFrameworks/DeviceSelectionEmergencyFlow.framework/DeviceSelectionEmergencyFlow`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11e84` | `0x18f9c` | **`+0x7118`** |
| `__AUTH_CONST.__objc_const` | `0x3d8` | `0x1078` | **`+0xca0`** |
| `__AUTH_CONST.__const` | `0xa28` | `0x14a8` | **`+0xa80`** |
| `__TEXT.__const` | `0xa8c` | `0x1218` | **`+0x78c`** |
| `__DATA.__bss` | `0xc00` | `0x1290` | **`+0x690`** |
| `__TEXT.__eh_frame` | `0x1278` | `0x17bc` | **`+0x544`** |
| `__AUTH.__data` | `0x378` | `0x840` | **`+0x4c8`** |
| `__TEXT.__constg_swiftt` | `0x3ac` | `0x78c` | **`+0x3e0`** |
| `__TEXT.__unwind_info` | `0x6f8` | `0xac0` | **`+0x3c8`** |
| `__TEXT.__swift5_reflstr` | `0x321` | `0x6bc` | **`+0x39b`** |
| `__TEXT.__objc_methlist` | `—` | `0x374` | **`+0x374`** |
| `__TEXT.__swift5_fieldmd` | `0x304` | `0x624` | **`+0x320`** |
| `__TEXT.__swift5_typeref` | `0x391` | `0x5a0` | **`+0x20f`** |
| `__DATA_CONST.__objc_selrefs` | `0xc0` | `0x290` | **`+0x1d0`** |
| `__AUTH.__objc_data` | `—` | `0x190` | **`+0x190`** |
| `__DATA_CONST.__got` | `0x0` | `0x168` | **`+0x168`** |
| `__DATA.__data` | `0x170` | `0x2d0` | **`+0x160`** |
| `__AUTH_CONST.__auth_got` | `0x530` | `0x688` | **`+0x158`** |
| `__TEXT.__swift5_capture` | `0x114` | `0x264` | **`+0x150`** |
| `__TEXT.__cstring` | `0x3ad` | `0x4c2` | **`+0x115`** |
| `__DATA_CONST.__const` | `0xa0` | `0x198` | **`+0xf8`** |
| `__TEXT.__oslogstring` | `0x729` | `0x7e9` | **`+0xc0`** |
| `__TEXT.__dlopen_cstrs` | `—` | `0x60` | **`+0x60`** |
| `__TEXT.__swift_as_entry` | `0x68` | `0xc4` | **`+0x5c`** |
| `__TEXT.__swift5_proto` | `0x74` | `0xc8` | **`+0x54`** |
| `__TEXT.__swift_as_ret` | `0x68` | `0xbc` | **`+0x54`** |
| `__DATA_CONST.__objc_classlist` | `0x20` | `0x70` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x110` | `0x160` | **`+0x50`** |
| `__DATA.__objc_ivar` | `—` | `0x38` | **`+0x38`** |
| `__TEXT.__swift5_types` | `0x40` | `0x74` | **`+0x34`** |
| `__TEXT.__gcc_except_tab` | `—` | `0x30` | **`+0x30`** |
| `__DATA_CONST.__objc_superrefs` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x18` | `0x30` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__DATA_CONST.__objc_protolist` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x10` | `0x20` | **`+0x10`** |

### Other Changes

```diff

-3600.43.3.1.1
+3600.49.5.1.1

+  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

+  - /System/Library/PrivateFrameworks/SoftLinking.framework/SoftLinking

+  - /System/Library/PrivateFrameworks/WirelessProximity.framework/WirelessProximity
+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 548
-  Symbols:   332
-  CStrings:  63
+  Functions: 930
+  Symbols:   536
+  CStrings:  74
Symbols:
+ -[WiProxAdapterBase .cxx_destruct]
+ -[WiProxAdapterBase activationCompletionHandler]
+ -[WiProxAdapterBase bluetoothStateChangedHandler]
+ -[WiProxAdapterBase heySiriDidUpdateState:]
+ -[WiProxAdapterBase initWithQueueLabel:]
+ -[WiProxAdapterBase invalidate]
+ -[WiProxAdapterBase performOnQueue:]
+ -[WiProxAdapterBase setActivationCompletionHandler:]
+ -[WiProxAdapterBase setBluetoothStateChangedHandler:]
+ -[WiProxAdapterBase stopOperationWithHeySiri:]
+ -[WiProxAdvertiserAdapter heySiri:failedToStartAdvertisingWithError:]
+ -[WiProxAdvertiserAdapter heySiriStartedAdvertising:]
+ -[WiProxAdvertiserAdapter init]
+ -[WiProxAdvertiserAdapter startAdvertisingWithPhash:snr:random:confidence:additionalInfo:]
+ -[WiProxAdvertiserAdapter stopAdvertising]
+ -[WiProxAdvertiserAdapter stopOperationWithHeySiri:]
+ -[WiProxDeviceInfo .cxx_destruct]
+ -[WiProxDeviceInfo deviceAddress]
+ -[WiProxDeviceInfo deviceUUID]
+ -[WiProxDeviceInfo heySiriConfidence]
+ -[WiProxDeviceInfo heySiriDeviceClass]
+ -[WiProxDeviceInfo heySiriDeviceGroup]
+ -[WiProxDeviceInfo heySiriPerceptualHash]
+ -[WiProxDeviceInfo heySiriProductType]
+ -[WiProxDeviceInfo heySiriRandom]
+ -[WiProxDeviceInfo heySiriSNR]
+ -[WiProxDeviceInfo initWithDeviceUUID:deviceAddress:heySiriPerceptualHash:heySiriSNR:heySiriConfidence:heySiriDeviceGroup:heySiriDeviceClass:heySiriRandom:heySiriProductType:]
+ -[WiProxDiscoveryAdapter .cxx_destruct]
+ -[WiProxDiscoveryAdapter deviceFoundBlock]
+ -[WiProxDiscoveryAdapter heySiri:failedToStartScanningWithError:]
+ -[WiProxDiscoveryAdapter heySiri:foundDevice:withInfo:]
+ -[WiProxDiscoveryAdapter heySiriStartedScanning:]
+ -[WiProxDiscoveryAdapter init]
+ -[WiProxDiscoveryAdapter setDeviceFoundBlock:]
+ -[WiProxDiscoveryAdapter startScanning]
+ -[WiProxDiscoveryAdapter stopOperationWithHeySiri:]
+ -[WiProxDiscoveryAdapter stopScanning]
+ GCC_except_table27
+ _CBCentralManagerOptionShowPowerAlertKey
+ _CFPreferencesCopyValue
+ _MobileGestalt_get_current_device
+ _MobileGestalt_get_internalBuild
+ _OBJC_CLASS_$_CBCentralManager
+ _OBJC_CLASS_$_NSData
+ _OBJC_CLASS_$_NSMutableDictionary
+ _OBJC_CLASS_$_NSObject
+ _OBJC_CLASS_$_WPHeySiri
+ _OBJC_CLASS_$_WiProxAdapterBase
+ _OBJC_CLASS_$_WiProxAdvertiserAdapter
+ _OBJC_CLASS_$_WiProxDeviceInfo
+ _OBJC_CLASS_$_WiProxDiscoveryAdapter
+ _OBJC_IVAR_$_WiProxAdapterBase._activationCompletionHandler
+ _OBJC_IVAR_$_WiProxAdapterBase._bluetoothStateChangedHandler
+ _OBJC_IVAR_$_WiProxAdapterBase._heySiri
+ _OBJC_IVAR_$_WiProxAdapterBase._queue
+ _OBJC_IVAR_$_WiProxDeviceInfo._deviceAddress
+ _OBJC_IVAR_$_WiProxDeviceInfo._deviceUUID
+ _OBJC_IVAR_$_WiProxDeviceInfo._heySiriConfidence
+ _OBJC_IVAR_$_WiProxDeviceInfo._heySiriDeviceClass
+ _OBJC_IVAR_$_WiProxDeviceInfo._heySiriDeviceGroup
+ _OBJC_IVAR_$_WiProxDeviceInfo._heySiriPerceptualHash
+ _OBJC_IVAR_$_WiProxDeviceInfo._heySiriProductType
+ _OBJC_IVAR_$_WiProxDeviceInfo._heySiriRandom
+ _OBJC_IVAR_$_WiProxDeviceInfo._heySiriSNR
+ _OBJC_IVAR_$_WiProxDiscoveryAdapter._deviceFoundBlock
+ _OBJC_METACLASS_$_NSObject
+ _OBJC_METACLASS_$_WiProxAdapterBase
+ _OBJC_METACLASS_$_WiProxAdvertiserAdapter
+ _OBJC_METACLASS_$_WiProxDeviceInfo
+ _OBJC_METACLASS_$_WiProxDiscoveryAdapter
+ _WPHeySiriKeyDeviceAddress
+ _WPHeySiriKeyManufacturerData
+ _WirelessProximityLibraryCore.frameworkLibrary
+ __Block_object_dispose
+ __DATA__TtC28DeviceSelectionEmergencyFlow13CBV2Discovery
+ __DATA__TtC28DeviceSelectionEmergencyFlow14CBV2Advertiser
+ __DATA__TtC28DeviceSelectionEmergencyFlow15WiProxDiscovery
+ __DATA__TtC28DeviceSelectionEmergencyFlow16WiProxAdvertiser
+ __DATA__TtC28DeviceSelectionEmergencyFlow31CBv2EmergencyBluetoothTransport
+ __DATA__TtC28DeviceSelectionEmergencyFlow33WiProxEmergencyBluetoothTransport
+ __IVARS__TtC28DeviceSelectionEmergencyFlow13CBV2Discovery
+ __IVARS__TtC28DeviceSelectionEmergencyFlow14CBV2Advertiser
+ __IVARS__TtC28DeviceSelectionEmergencyFlow15WiProxDiscovery
+ __IVARS__TtC28DeviceSelectionEmergencyFlow16WiProxAdvertiser
+ __IVARS__TtC28DeviceSelectionEmergencyFlow31CBv2EmergencyBluetoothTransport
+ __IVARS__TtC28DeviceSelectionEmergencyFlow33WiProxEmergencyBluetoothTransport
+ __METACLASS_DATA__TtC28DeviceSelectionEmergencyFlow13CBV2Discovery
+ __METACLASS_DATA__TtC28DeviceSelectionEmergencyFlow14CBV2Advertiser
+ __METACLASS_DATA__TtC28DeviceSelectionEmergencyFlow15WiProxDiscovery
+ __METACLASS_DATA__TtC28DeviceSelectionEmergencyFlow16WiProxAdvertiser
+ __METACLASS_DATA__TtC28DeviceSelectionEmergencyFlow31CBv2EmergencyBluetoothTransport
+ __METACLASS_DATA__TtC28DeviceSelectionEmergencyFlow33WiProxEmergencyBluetoothTransport
+ __NSConcreteGlobalBlock
+ __OBJC_$_INSTANCE_METHODS_WiProxAdapterBase
+ __OBJC_$_INSTANCE_METHODS_WiProxAdvertiserAdapter
+ __OBJC_$_INSTANCE_METHODS_WiProxDeviceInfo
+ __OBJC_$_INSTANCE_METHODS_WiProxDiscoveryAdapter
+ __OBJC_$_INSTANCE_VARIABLES_WiProxAdapterBase
+ __OBJC_$_INSTANCE_VARIABLES_WiProxDeviceInfo
+ __OBJC_$_INSTANCE_VARIABLES_WiProxDiscoveryAdapter
+ __OBJC_$_PROP_LIST_NSObject
+ __OBJC_$_PROP_LIST_WiProxAdapterBase
+ __OBJC_$_PROP_LIST_WiProxDeviceInfo
+ __OBJC_$_PROP_LIST_WiProxDiscoveryAdapter
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSObject
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSObject
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_WPHeySiriProtocol
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_WPHeySiriProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSObject
+ __OBJC_$_PROTOCOL_METHOD_TYPES_WPHeySiriProtocol
+ __OBJC_$_PROTOCOL_REFS_WPHeySiriProtocol
+ __OBJC_CLASS_PROTOCOLS_$_WiProxAdapterBase
+ __OBJC_CLASS_RO_$_WiProxAdapterBase
+ __OBJC_CLASS_RO_$_WiProxAdvertiserAdapter
+ __OBJC_CLASS_RO_$_WiProxDeviceInfo
+ __OBJC_CLASS_RO_$_WiProxDiscoveryAdapter
+ __OBJC_LABEL_PROTOCOL_$_NSObject
+ __OBJC_LABEL_PROTOCOL_$_WPHeySiriProtocol
+ __OBJC_METACLASS_RO_$_WiProxAdapterBase
+ __OBJC_METACLASS_RO_$_WiProxAdvertiserAdapter
+ __OBJC_METACLASS_RO_$_WiProxDeviceInfo
+ __OBJC_METACLASS_RO_$_WiProxDiscoveryAdapter
+ __OBJC_PROTOCOL_$_NSObject
+ __OBJC_PROTOCOL_$_WPHeySiriProtocol
+ __Unwind_Resume
+ ___31-[WiProxAdapterBase invalidate]_block_invoke
+ ___36-[WiProxAdapterBase performOnQueue:]_block_invoke
+ ___38-[WiProxDiscoveryAdapter stopScanning]_block_invoke
+ ___39-[WiProxDiscoveryAdapter startScanning]_block_invoke
+ ___42-[WiProxAdvertiserAdapter stopAdvertising]_block_invoke
+ ___90-[WiProxAdvertiserAdapter startAdvertisingWithPhash:snr:random:confidence:additionalInfo:]_block_invoke
+ ___WirelessProximityLibraryCore_block_invoke
+ ___block_descriptor_32_e19_v16?0"WPHeySiri"8l
+ ___block_descriptor_40_e5_v8?0l
+ ___block_descriptor_40_e8_32r_e5_v8?0lr32l8
+ ___block_descriptor_40_e8_32s_e19_v16?0"WPHeySiri"8ls32l8
+ ___block_descriptor_40_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_48_e8_32s40bs_e5_v8?0ls32l8s40l8
+ ___block_literal_global
+ ___getWPHeySiriAdvertisingDataSymbolLoc_block_invoke
+ ___objc_personality_v0
+ ___stack_chk_fail
+ ___stack_chk_guard
+ ___swift_allocate_boxed_opaque_existential_1
+ ___swift_closure_destructorTm
+ ___swift_memcpy4_4
+ ___swift_memcpy8_2
+ ___swift_project_boxed_opaque_existential_0
+ __sl_dlopen
+ _abort_report_np
+ _associated conformance 28DeviceSelectionEmergencyFlow0C23BluetoothTransportErrorOSHAASQ
+ _associated conformance 28DeviceSelectionEmergencyFlow11BLEPriorityOSHAASQ
+ _associated conformance 28DeviceSelectionEmergencyFlow17AdvertisePriorityOSHAASQ
+ _audit_stringWirelessProximity
+ _dispatch_async
+ _dispatch_queue_create
+ _dlerror
+ _dlsym
+ _free
+ _getWPHeySiriAdvertisingDataSymbolLoc.ptr
+ _kCFPreferencesCurrentHost
+ _objc_alloc
+ _objc_claimAutoreleasedReturnValue
+ _objc_msgSendSuper2
+ _objc_release_x27
+ _objc_retainAutorelease
+ _objc_retain_x2
+ _objc_retain_x23
+ _objc_retain_x25
+ _objc_retain_x26
+ _objc_retain_x28
+ _objc_retain_x3
+ _objc_retain_x6
+ _objc_retain_x8
+ _objc_setProperty_nonatomic_copy
+ _objc_storeStrong
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithTake
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getSingletonMetadata
+ _swift_initStackObject
+ _swift_projectBox
+ _swift_release_x1
+ _swift_retain_x1
+ _swift_storeEnumTagSinglePayloadGeneric
+ _swift_task_addCancellationHandler
+ _swift_task_isCurrentExecutor
+ _swift_task_removeCancellationHandler
+ _swift_task_reportUnexpectedExecutor
+ _swift_updateClassMetadata2
+ _swift_weakDestroy
+ _swift_weakInit
+ _swift_weakLoadStrong
+ _symbolic $s28DeviceSelectionEmergencyFlow013BLEDiscoveredA0P
+ _symbolic $s28DeviceSelectionEmergencyFlow04SiriC10AdvertiserP
+ _symbolic $s28DeviceSelectionEmergencyFlow0C18BluetoothTransportP
+ _symbolic $s28DeviceSelectionEmergencyFlow12BLEDiscoveryP
+ _symbolic $sSY
+ _symbolic ScCyyt______pGSg s5ErrorP
+ _symbolic Scsy___________pG 28DeviceSelectionEmergencyFlow6RecordO s5ErrorP
+ _symbolic So16CBCentralManagerC
+ _symbolic So22WiProxDiscoveryAdapterC
+ _symbolic So23WiProxAdvertiserAdapterC
+ _symbolic _____ 10Foundation4UUIDV
+ _symbolic _____ 28DeviceSelectionEmergencyFlow014CBV2DiscoveredA033_D99C9F674C2403F0DA3183E319809E1FLLV
+ _symbolic _____ 28DeviceSelectionEmergencyFlow016WiProxDiscoveredA033_586BCC0765FA9DED129BEF32164C8C5BLLV
+ _symbolic _____ 28DeviceSelectionEmergencyFlow04CBv2C18BluetoothTransportC
+ _symbolic _____ 28DeviceSelectionEmergencyFlow06WiProxC18BluetoothTransportC
+ _symbolic _____ 28DeviceSelectionEmergencyFlow0C11PreferencesO
+ _symbolic _____ 28DeviceSelectionEmergencyFlow0C23BluetoothTransportErrorO
+ _symbolic _____ 28DeviceSelectionEmergencyFlow11BLEPriorityO
+ _symbolic _____ 28DeviceSelectionEmergencyFlow13CBV2DiscoveryC
+ _symbolic _____ 28DeviceSelectionEmergencyFlow14CBV2AdvertiserC
+ _symbolic _____ 28DeviceSelectionEmergencyFlow15WiProxDiscoveryC
+ _symbolic _____ 28DeviceSelectionEmergencyFlow16WiProxAdvertiserC
+ _symbolic _____ 28DeviceSelectionEmergencyFlow17AdvertisePriorityO
+ _symbolic _____ So14BluetoothStateV
+ _symbolic _____ So16os_unfair_lock_sV
+ _symbolic _____ s5UInt8V
+ _symbolic _____ s6UInt16V
+ _symbolic _____ s6UInt32V
+ _symbolic _____Ieghy_ So14BluetoothStateV
+ _symbolic _____Sg 10Foundation4DataV
+ _symbolic _____SgXw 28DeviceSelectionEmergencyFlow04CBv2C18BluetoothTransportC
+ _symbolic _____SgXw 28DeviceSelectionEmergencyFlow13CBV2DiscoveryC
+ _symbolic _____SgXw 28DeviceSelectionEmergencyFlow14CBV2AdvertiserC
+ _symbolic _____SgXw 28DeviceSelectionEmergencyFlow15WiProxDiscoveryC
+ _symbolic _____SgXw 28DeviceSelectionEmergencyFlow16WiProxAdvertiserC
+ _symbolic ______p 28DeviceSelectionEmergencyFlow12BLEDiscoveryP
+ _symbolic ______pIeghn_ 28DeviceSelectionEmergencyFlow013BLEDiscoveredA0P
+ _symbolic ______pyYbKc 28DeviceSelectionEmergencyFlow0C18BluetoothTransportP
+ _symbolic ______pytIeghnr_ 28DeviceSelectionEmergencyFlow013BLEDiscoveredA0P
+ _symbolic _____ySS_yptG s23_ContiguousArrayStorageC
+ _symbolic _____y___________p_G Scs12ContinuationV 28DeviceSelectionEmergencyFlow6RecordO s5ErrorP
+ _symbolic _____y___________p_G Scs8IteratorV 28DeviceSelectionEmergencyFlow6RecordO s5ErrorP
+ _symbolic _____y___________p__G Scs12ContinuationV11YieldResultO 28DeviceSelectionEmergencyFlow6RecordO s5ErrorP
+ _symbolic _____y___________p__G Scs12ContinuationV15BufferingPolicyO 28DeviceSelectionEmergencyFlow6RecordO s5ErrorP
+ _symbolic _____ytIeghnr_ So14BluetoothStateV
+ _symbolic _____yy_____YbcSgG 2os21OSAllocatedUnfairLockV So14BluetoothStateV
+ _symbolic _____yy_____YbcSg_____G s13ManagedBufferCsRi__rlE So14BluetoothStateV So16os_unfair_lock_sV
+ _symbolic _____yy______pYbcSgG 2os21OSAllocatedUnfairLockV 28DeviceSelectionEmergencyFlow013BLEDiscoveredE0P
+ _symbolic _____yy______pYbcSg_____G s13ManagedBufferCsRi__rlE 28DeviceSelectionEmergencyFlow013BLEDiscoveredC0P So16os_unfair_lock_sV
+ _symbolic x
+ _symbolic y_____cSg So14BluetoothStateV
+ _type_layout_string 28DeviceSelectionEmergencyFlow014CBV2DiscoveredA033_D99C9F674C2403F0DA3183E319809E1FLLV
+ _type_layout_string So16os_unfair_lock_sV
- _OUTLINED_FUNCTION_52
- _OUTLINED_FUNCTION_53
- _OUTLINED_FUNCTION_54
- _OUTLINED_FUNCTION_55
- _OUTLINED_FUNCTION_56
- _OUTLINED_FUNCTION_57
- _OUTLINED_FUNCTION_58
- _OUTLINED_FUNCTION_59
- _OUTLINED_FUNCTION_60
- _OUTLINED_FUNCTION_61
- _OUTLINED_FUNCTION_62
- _OUTLINED_FUNCTION_63
- _OUTLINED_FUNCTION_64
- _OUTLINED_FUNCTION_65
- _OUTLINED_FUNCTION_66
- _OUTLINED_FUNCTION_67
- _OUTLINED_FUNCTION_68
- _OUTLINED_FUNCTION_69
- _OUTLINED_FUNCTION_70
- _OUTLINED_FUNCTION_71
- _OUTLINED_FUNCTION_72
- ___swift_closure_destructor.35Tm
- ___swift_project_boxed_opaque_existential_1Tm
- _objc_release_x28
- _objc_retain_x24
- _swift_retain_x22
- _swift_task_future_wait_throwing
- _swift_unknownObjectWeakDestroy
- _swift_unknownObjectWeakInit
- _swift_unknownObjectWeakLoadStrong
- _symbolic Scsy_____Sg______pG 28DeviceSelectionEmergencyFlow6RecordO s5ErrorP
- _symbolic So11CBDiscoveryCyc
- _symbolic So12CBAdvertiserCSgXw
- _symbolic So12CBAdvertiserCSgXwz_Xx
- _symbolic So12CBAdvertiserCyc
- _symbolic _____ So14CBManagerStateV
- _symbolic _____ s15ContinuousClockV7InstantV
- _symbolic _____Sg So14CBManagerStateV
- _symbolic _____yScsy_____Sg______pGABG s23AsyncCompactMapSequenceV 28DeviceSelectionEmergencyFlow6RecordO s5ErrorP
- _symbolic _____yScsy_____Sg______pGAB_G s23AsyncCompactMapSequenceV8IteratorV 28DeviceSelectionEmergencyFlow6RecordO s5ErrorP
- _symbolic _____y_____Sg______p_G Scs12ContinuationV 28DeviceSelectionEmergencyFlow6RecordO s5ErrorP
- _symbolic _____y_____Sg______p_G Scs8IteratorV 28DeviceSelectionEmergencyFlow6RecordO s5ErrorP
- _symbolic _____y_____Sg______p__G Scs12ContinuationV11YieldResultO 28DeviceSelectionEmergencyFlow6RecordO s5ErrorP
- _symbolic _____y_____Sg______p__G Scs12ContinuationV15BufferingPolicyO 28DeviceSelectionEmergencyFlow6RecordO s5ErrorP
CStrings:
+ "#wiprox activateAdvertiser — stub, no-op"
+ "#wiprox invalidateAdvertiser — stub, no-op"
+ "#wiprox scan(cycle: %ld) — stub, returning nil"
+ "#wiprox setRecord — stub, no-op (priority: %s)"
+ "CBv2 Advertiser Bluetooth state changed: %s."
+ "Cycle %ld: Advertising p:%hu, s:%hhu, tb:%hhu, c:%hhu priority:%s"
+ "Cycle %ld: Bluetooth state changed: %s."
+ "Cycle %ld: received unknown record ph:%hu, s:%hhu"
+ "DeviceSelectionEmergencyFlow/WiProxDiscovery.swift"
+ "Emergency Call Test Mode"
+ "Emergency dial decision: internalBuild=%{bool}d, testModeDefault=%{bool}d, testMode=%{bool}d"
+ "WPHeySiriAdvertisingData"
+ "activate(priority:)"
+ "com.apple.assistant"
+ "com.apple.emergencyflow.wiprox.advertiser"
+ "com.apple.emergencyflow.wiprox.discovery"
+ "enable_wiprox"
+ "softlink:r:path:/System/Library/PrivateFrameworks/WirelessProximity.framework/WirelessProximity"
+ "v16@?0@\"WPHeySiri\"8"
+ "v8@?0"
- "Cycle %ld: %s BLE Remaining discovery time: %s"
- "Cycle %ld: Advertising p:%hu, s:%hhu, tb:%hhu, c:%hhu"
- "Cycle %ld: BLE Discovery startup duration: %s"
- "Cycle %ld: Bluetooth state changed to: %s."
- "Cycle %ld: Finished Discovery Wait"
- "Cycle %ld: Received unknown record, ignoring ph:%hu, s:%hhu"
- "Cycle %ld: Starting Discovery Wait for: %s"
- "Emergency Advertisement"
- "dial_emergency"
```
