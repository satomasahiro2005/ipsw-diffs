## EXBrightHIDPlugin

> `/System/Library/HIDPlugins/ServiceFilters/EXBrightHIDPlugin.plugin/EXBrightHIDPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28b0` | `0x28a0` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2285.0.0.502.1
+2300.0.0.502.1

-  Symbols:   249
+  Symbols:   98
Symbols:
+ radr://5614542
- 
- +[EXBrightHIDPlugin matchService:options:score:]
- -[EXBrightHIDPlugin .cxx_destruct]
- -[EXBrightHIDPlugin activate]
- -[EXBrightHIDPlugin cancel]
- -[EXBrightHIDPlugin description]
- -[EXBrightHIDPlugin fetchFDRBundlesFromDisk]
- -[EXBrightHIDPlugin filterEvent:]
- -[EXBrightHIDPlugin filterEventMatching:event:forClient:]
- -[EXBrightHIDPlugin forwardFDRBundles]
- -[EXBrightHIDPlugin initWithService:]
- -[EXBrightHIDPlugin propertyForKey:client:]
- -[EXBrightHIDPlugin setCancelHandler:]
- -[EXBrightHIDPlugin setDispatchQueue:]
- -[EXBrightHIDPlugin setProperty:forKey:client:]
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleEmbeddedLightSensor_EXBright_all/install/TempContent/Objects/EXBright.build/EXBrightHIDPlugin.build/DerivedSources/
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleEmbeddedLightSensor_EXBright_all/install/TempContent/Objects/EXBright.build/EXBrightHIDPlugin.build/Objects-normal/arm64e/EXBrightHIDPlugin.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleEmbeddedLightSensor_EXBright_all/install/TempContent/Objects/EXBright.build/EXBrightHIDPlugin.build/Objects-normal/arm64e/EXBrightHIDPlugin.swiftmodule
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleEmbeddedLightSensor_EXBright_all/install/TempContent/Objects/EXBright.build/EXBrightHIDPlugin.build/Objects-normal/arm64e/EXBrightHIDPlugin_vers.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleEmbeddedLightSensor_EXBright_all/install/TempContent/Objects/EXBright.build/EXBrightHIDPlugin.build/Objects-normal/arm64e/ExclaveFDRProxy.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AppleEmbeddedLightSensor_EXBright_all/EXBright/EXBrightHIDPlugin/
- EXBrightHIDPlugin.m
- EXBrightHIDPlugin_vers.c
- ExclaveFDRProxy.swift
- OBJC_IVAR_$_EXBrightHIDPlugin._activated
- OBJC_IVAR_$_EXBrightHIDPlugin._cancelHandler
- OBJC_IVAR_$_EXBrightHIDPlugin._didRunForwardFDRBundles
- OBJC_IVAR_$_EXBrightHIDPlugin._logHandle
- OBJC_IVAR_$_EXBrightHIDPlugin._queue
- OBJC_IVAR_$_EXBrightHIDPlugin._service
- _$s10Foundation4DataV13_copyContents12initializingAC8IteratorV_SitSrys5UInt8VG_tF
- _$s10Foundation4DataV15_RepresentationOWOe
- _$s10Foundation4DataV15_RepresentationOWOy
- _$s10Foundation4DataV36_unconditionallyBridgeFromObjectiveCyACSo6NSDataCSgFZ
- _$s10Foundation4DataV8IteratorVMa
- _$s16ExclaveFDRDecode0aB21RawDataStoreKitClientC08transfercD03ctxyAA019EXFDRDecodeTransfercD3CtxV_tKFTj
- _$s16ExclaveFDRDecode0aB21RawDataStoreKitClientC10conclaveIDACSS_tKcfc
- _$s16ExclaveFDRDecode0aB21RawDataStoreKitClientCMa
- _$s16ExclaveFDRDecode17EXFDRDecodeClientO01kabD8EXBrightyA2CmFWC
- _$s16ExclaveFDRDecode17EXFDRDecodeClientOMa
- _$s16ExclaveFDRDecode29EXFDRDecodeTransferRawDataCtxV4data0H6Length06clientA0ACSays5UInt8VG_s6UInt32VAA0C6ClientOtcfC
- _$s16ExclaveFDRDecode29EXFDRDecodeTransferRawDataCtxVMa
- _$s17EXBrightHIDPlugin23sendBundlesToFDRStorage11osLogHandle03fdrD0SbSo03OS_G4_logC_10Foundation4DataVtF
- _$s17EXBrightHIDPlugin3TagC2fn4nameS2S_tFZ
- _$s17EXBrightHIDPlugin3TagC2fn4nameS2S_tFZTf4nd_n
- _$s17EXBrightHIDPlugin3TagCACycfC
- _$s17EXBrightHIDPlugin3TagCACycfCTq
- _$s17EXBrightHIDPlugin3TagCACycfc
- _$s17EXBrightHIDPlugin3TagCMF
- _$s17EXBrightHIDPlugin3TagCMa
- _$s17EXBrightHIDPlugin3TagCMf
- _$s17EXBrightHIDPlugin3TagCMm
- _$s17EXBrightHIDPlugin3TagCMn
- _$s17EXBrightHIDPlugin3TagCN
- _$s17EXBrightHIDPlugin3TagCfD
- _$s17EXBrightHIDPlugin3TagCfd
- _$s17EXBrightHIDPluginMXM
- _$s2os18OSLogInterpolationV06appendC0_7privacy10attributesys5Error_pyXA_AA0B7PrivacyVSStFfA1_
- _$s2os32getNullTerminatedUTF8PointerImpl_21storingStringOwnersInSVSS_SpyypGSgztF
- _$s2os6LoggerV9logObjectSo03OS_a1_C0Cvg
- _$s2os6LoggerVMa
- _$s2os6LoggerVyACSo03OS_A4_logCcfC
- _$sBoWV
- _$sSS14_fromSubstringySSSshFZ
- _$sSS21_builtinStringLiteral17utf8CodeUnitCount7isASCIISSBp_BwBi1_tcfC
- _$sSS5index5afterSS5IndexVAD_tF
- _$sSS6appendyySSF
- _$sSS8UTF8ViewV13_foreignCountSiyF
- _$sSSySJSS5IndexVcig
- _$sSSySsSnySS5IndexVGcig
- _$sSa6append10contentsOfyqd__n_t7ElementQyd__RszSTRd__lFs5UInt8V_SayAFGTgq5
- _$sSaySayxGqd__c7ElementQyd__RszSTRd__lufCs5UInt8V_10Foundation4DataVTt0g5
- _$sSlsE5split9maxSplits25omittingEmptySubsequences14whereSeparatorSay11SubSequenceQzGSi_S2b7ElementQzKXEtKFSS_Tg5
- _$sSlsSQ7ElementRpzrlE5split9separator9maxSplits25omittingEmptySubsequencesSay11SubSequenceQzGAB_SiSbtFSbABXEfU_SS_TG5TA
- _$sSo13os_log_type_ta0A0E5errorABvgZ
- _$sSo13os_log_type_ta0A0E7defaultABvgZ
- _$sSo8NSObjectCSgMR
- _$sSo8NSObjectCSgMd
- _$sSo8NSObjectCSgWOh
- _$sSsN
- _$ss11_StringGutsV16_deconstructUTF87scratchyXlSg5owner_xSi6lengthSb11usesScratchSb15allocatedMemorytSwSg_ts8_PointerRzlFSV_Tgq5
- _$ss11_StringGutsV16_foreignCopyUTF84intoSiSgSrys5UInt8VG_tF
- _$ss11_StringGutsV23_allocateForDeconstructyXl5owner_SVSi6lengthtyF
- _$ss11_StringGutsV23_allocateForDeconstructyXl5owner_SVSi6lengthtyFTv_r
- _$ss11_StringGutsVN
- _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFSs_Tg5
- _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFs5UInt8V_Tgq5
- _$ss13_StringObjectV10sharedUTF8SRys5UInt8VGvg
- _$ss20__StaticArrayStorageCN
- _$ss22_ContiguousArrayBufferV19_uninitializedCount15minimumCapacityAByxGSi_SitcfCs5UInt8V_Tt1gq5
- _$ss23_ContiguousArrayStorageCMn
- _$ss23_ContiguousArrayStorageCySsGMR
- _$ss23_ContiguousArrayStorageCySsGMd
- _$ss23_ContiguousArrayStorageCys5UInt8VGMR
- _$ss23_ContiguousArrayStorageCys5UInt8VGMd
- _$ss27_stringCompareWithSmolCheck__9expectingSbs11_StringGutsV_ADs01_G16ComparisonResultOtF
- _$ss32_copyCollectionToContiguousArrayys0dE0Vy7ElementQzGxSlRzlFSS8UTF8ViewV_Tgq5
- _$ss5UInt8VMn
- _$sypWOc
- _OUTLINED_FUNCTION_0
- _OUTLINED_FUNCTION_1
- _OUTLINED_FUNCTION_2
- __DATA__TtC17EXBrightHIDPlugin3Tag
- __METACLASS_DATA__TtC17EXBrightHIDPlugin3Tag
- __OBJC_$_CLASS_METHODS_EXBrightHIDPlugin
- __OBJC_$_INSTANCE_METHODS_EXBrightHIDPlugin
- __OBJC_$_INSTANCE_VARIABLES_EXBrightHIDPlugin
- __OBJC_$_PROP_LIST_EXBrightHIDPlugin
- __OBJC_$_PROP_LIST_NSObject
- __OBJC_$_PROTOCOL_CLASS_METHODS_HIDServiceFilter
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_HIDServiceFilter
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSObject
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HIDServiceFilter
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSObject
- __OBJC_$_PROTOCOL_METHOD_TYPES_HIDServiceFilter
- __OBJC_$_PROTOCOL_METHOD_TYPES_NSObject
- __OBJC_$_PROTOCOL_REFS_HIDServiceFilter
- __OBJC_CLASS_PROTOCOLS_$_EXBrightHIDPlugin
- __OBJC_CLASS_RO_$_EXBrightHIDPlugin
- __OBJC_LABEL_PROTOCOL_$_HIDServiceFilter
- __OBJC_LABEL_PROTOCOL_$_NSObject
- __OBJC_METACLASS_RO_$_EXBrightHIDPlugin
- __OBJC_PROTOCOL_$_HIDServiceFilter
- __OBJC_PROTOCOL_$_NSObject
- ___27-[EXBrightHIDPlugin cancel]_block_invoke
- ___38-[EXBrightHIDPlugin setDispatchQueue:]_block_invoke
- ___block_descriptor_40_e8_32s_e5_v8?0ls32l8
- ___swift_destroy_boxed_opaque_existential_0
- ___swift_instantiateConcreteTypeFromMangledNameV2
- ___swift_reflection_version
- __swift_FORCE_LOAD_$_swiftCoreFoundation_$_EXBrightHIDPlugin
- __swift_FORCE_LOAD_$_swiftDispatch_$_EXBrightHIDPlugin
- __swift_FORCE_LOAD_$_swiftFoundation_$_EXBrightHIDPlugin
- __swift_FORCE_LOAD_$_swiftObjectiveC_$_EXBrightHIDPlugin
- __swift_FORCE_LOAD_$_swiftXPC_$_EXBrightHIDPlugin
- __swift_FORCE_LOAD_$_swift_Builtin_float_$_EXBrightHIDPlugin
- __swift_FORCE_LOAD_$_swiftos_$_EXBrightHIDPlugin
- __swift_stdlib_malloc_size
- _objc_msgSend$conformsToUsagePage:usage:
- _objc_msgSend$countByEnumeratingWithState:objects:count:
- _objc_msgSend$description
- _objc_msgSend$fetchFDRBundlesFromDisk
- _objc_msgSend$forwardFDRBundles
- _objc_msgSend$initWithObjectsAndKeys:
- _objc_msgSend$isEqualToString:
- _objc_msgSend$numberWithBool:
- _objc_msgSend$objectForKeyedSubscript:
- _objc_msgSend$setObject:forKeyedSubscript:
- _symbolic So8NSObjectCSg
- _symbolic _____ 17EXBrightHIDPlugin3TagC
- _symbolic _____ySsG s23_ContiguousArrayStorageC
- _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
Functions:
~ -[EXBrightHIDPlugin fetchFDRBundlesFromDisk] -> sub_1838 : 1636 -> 1624
~ _$ss11_StringGutsV16_deconstructUTF87scratchyXlSg5owner_xSi6lengthSb11usesScratchSb15allocatedMemorytSwSg_ts8_PointerRzlFSV_Tgq5 -> sub_2e8c : 280 -> 276
```
