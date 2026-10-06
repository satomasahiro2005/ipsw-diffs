## PowerlogCore

> `/System/Library/PrivateFrameworks/PowerlogCore.framework/PowerlogCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x64e00` | `0x666e0` | **`+0x18e0`** |
| `__TEXT.__text` | `0xe5320` | `0xe6808` | **`+0x14e8`** |
| `__DATA_CONST.__objc_arraydata` | `0x40178` | `0x41040` | **`+0xec8`** |
| `__TEXT.__cstring` | `0x3e989` | `0x3f5fd` | **`+0xc74`** |
| `__AUTH_CONST.__objc_dictobj` | `0xf438` | `0xf618` | **`+0x1e0`** |
| `__DATA_CONST.__const` | `0x2500` | `0x2580` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x9698` | `0x96e0` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x2460` | `0x24a0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x880f` | `0x884a` | **`+0x3b`** |
| `__DATA_CONST.__objc_selrefs` | `0x58f0` | `0x5920` | **`+0x30`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x1158` | `0x1170` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xd98` | `0xda8` | **`+0x10`** |
| `__AUTH_CONST.__objc_doubleobj` | `0x1390` | `0x13a0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3090` | `0x3098` | **`+0x8`** |

### Other Changes

```diff

-3468.0.0.502.1
+3486.0.21.502.1

-  Functions: 4908
-  Symbols:   7208
-  CStrings:  14214
+  Functions: 4920
+  Symbols:   7227
+  CStrings:  14419
Symbols:
+ +[PLIOKitOperatorComposition enrichSnapshot:withPackSnapshot:withBankSnapshot:withChargerSnapshot:]
+ +[PLIOKitOperatorComposition enrichedSmartBatterySnapshotFromIOEntry:]
+ +[PLIOKitOperatorComposition enrichedSnapshotFromChargerService:]
+ +[PLIOKitOperatorComposition enrichedSnapshotFromPackService:]
+ +[PLIOKitOperatorComposition firstMatchingServiceSnapshotForClass:matcher:]
+ +[PLIOKitOperatorComposition legacyRescuedSnapshot:]
+ _IORegistryEntryGetParentEntry
+ _IOServiceGetMatchingServices
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em
+ __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEE15__init_buf_ptrsB9fqe220106Ev
+ __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEEC2B9fqe220106Ej
+ __ZNSt3__116__pad_and_outputB9fqe220106IcNS_11char_traitsIcEEEENS_19ostreambuf_iteratorIT_T0_EES6_PKS4_S8_S8_RNS_8ios_baseES4_
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIlEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220106Ev
+ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220106Ev
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__124__put_character_sequenceB9fqe220106IcNS_11char_traitsIcEEEERNS_13basic_ostreamIT_T0_EES7_PKS4_m
+ __ZNSt3__16vectorIlNS_9allocatorIlEEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIlNS_9allocatorIlEEE16__init_with_sizeB9fqe220106IPKlS6_EEvT_T0_m
+ __ZNSt3__16vectorIlNS_9allocatorIlEEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ ___62+[PLIOKitOperatorComposition enrichedSnapshotFromPackService:]_block_invoke
+ ___62+[PLIOKitOperatorComposition enrichedSnapshotFromPackService:]_block_invoke_2
+ ___65+[PLIOKitOperatorComposition enrichedSnapshotFromChargerService:]_block_invoke
+ ___70+[PLIOKitOperatorComposition enrichedSmartBatterySnapshotFromIOEntry:]_block_invoke
+ ___70+[PLIOKitOperatorComposition enrichedSmartBatterySnapshotFromIOEntry:]_block_invoke_2
+ ___70+[PLIOKitOperatorComposition enrichedSmartBatterySnapshotFromIOEntry:]_block_invoke_3
+ ___block_descriptor_32_e25_B20?0"NSDictionary"8I16l
+ ___block_descriptor_36_e25_B20?0"NSDictionary"8I16l
+ ___block_descriptor_40_e25_B20?0"NSDictionary"8I16l
+ ___block_descriptor_44_e25_B20?0"NSDictionary"8I16l
+ _mergeMissingKeys
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220100Em
- __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEE15__init_buf_ptrsB9fqe220100Ev
- __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEEC2B9fqe220100Ej
- __ZNSt3__116__pad_and_outputB9fqe220100IcNS_11char_traitsIcEEEENS_19ostreambuf_iteratorIT_T0_EES6_PKS4_S8_S8_RNS_8ios_baseES4_
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIlEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220100Ev
- __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220100Ev
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__124__put_character_sequenceB9fqe220100IcNS_11char_traitsIcEEEERNS_13basic_ostreamIT_T0_EES7_PKS4_m
- __ZNSt3__16vectorIlNS_9allocatorIlEEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorIlNS_9allocatorIlEEE16__init_with_sizeB9fqe220100IPKlS6_EEvT_T0_m
- __ZNSt3__16vectorIlNS_9allocatorIlEEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
CStrings:
+ "1006037"
+ "A2DPNAKPercentage"
+ "A2DPReTxPercentage"
+ "A2DPTxBFPercentage"
+ "AllowPolicyRun"
+ "AppleChargerData"
+ "AppleSmartBatteryBank"
+ "AppleSmartBatteryPack"
+ "B20@?0@\"NSDictionary\"8I16"
+ "BDC_Daily_Charger"
+ "BDC_OBC_Charger"
+ "BDC_OBC_Pack"
+ "BDC_SBC_Pack"
+ "BankID"
+ "BatteryData"
+ "BatteryPackCount"
+ "BrownoutRiskEngaged"
+ "BrownoutRiskPu_Battery0"
+ "BrownoutRiskPu_Battery1"
+ "BrownoutRiskSysCap_Battery0"
+ "BrownoutRiskSysCap_Battery1"
+ "CM-ASSETCREATION"
+ "CM-ASSETDOWNLOAD"
+ "CM-EXPORT"
+ "CM-IMAGEQUEUE"
+ "ChargerConfiguration"
+ "ChargerData"
+ "ChargerIndex"
+ "ClientGrantedBudget"
+ "ClientRequestedBudget"
+ "ControlSnapshot"
+ "CoreMedia"
+ "CoreMedia_CM-ASSETCREATION_2_2"
+ "CoreMedia_CM-ASSETDOWNLOAD_2_2"
+ "CoreMedia_CM-EXPORT_2_2"
+ "CoreMedia_CM-IMAGEQUEUE_2_2"
+ "CoreMotion"
+ "DroopCE"
+ "DroopIS"
+ "ELNAHPActiveDuration"
+ "ELNATotalDuration"
+ "EMLSRDisableCount2G"
+ "EMLSRDisableCount5G"
+ "EMLSRDisableCount6G"
+ "EMLSREmlModeEnableDuration2G"
+ "EMLSREmlModeEnableDuration5G"
+ "EMLSREmlModeEnableDuration6G"
+ "EMLSREnableCount2G"
+ "EMLSREnableCount5G"
+ "EMLSREnableCount6G"
+ "EMLSRMainPhyActiveDuration2G"
+ "EMLSRMainPhyActiveDuration5G"
+ "EMLSRMainPhyActiveDuration6G"
+ "EMLSRMainPhyOfflineDuration2G"
+ "EMLSRMainPhyOfflineDuration5G"
+ "EMLSRMainPhyOfflineDuration6G"
+ "EMLSRSwitchEnabledDuration2G"
+ "EMLSRSwitchEnabledDuration5G"
+ "EMLSRSwitchEnabledDuration6G"
+ "Gauge10s_Battery0"
+ "Gauge10s_Battery1"
+ "Gauge1s_Battery0"
+ "Gauge1s_Battery1"
+ "HFPNAKPercentage"
+ "HFPReTxPercentage"
+ "HFPTxBFPercentage"
+ "IBat_Battery0"
+ "IBat_Battery1"
+ "IOService"
+ "KioskMode"
+ "LPEMData"
+ "LaneCE_0"
+ "LaneCE_1"
+ "LaneCE_2"
+ "LaneCE_3"
+ "LaneCE_4"
+ "LaneCE_5"
+ "LaneCE_6"
+ "LaneCE_7"
+ "LastDisengagedCritDroopTS"
+ "LastDisengagedPolicyTS"
+ "LastEngagedCritDroopTS"
+ "LastEngagedPolicyTS"
+ "LifetimeData"
+ "MainCoreRxRxPercentage"
+ "OperationMode"
+ "OverrideFlags"
+ "PMU100ms_Battery0"
+ "PMU100ms_Battery1"
+ "PMU10ms_Battery0"
+ "PMU10ms_Battery1"
+ "PMU10s_Battery0"
+ "PMU10s_Battery1"
+ "PMU1s_Battery0"
+ "PMU1s_Battery1"
+ "PNFC"
+ "PPMParametersHF"
+ "PeakPowerPressureLevel"
+ "PowerTelemetryData"
+ "RemainingCapacity_Battery0"
+ "RemainingCapacity_Battery1"
+ "SDTP"
+ "SDtC"
+ "SDtL"
+ "ScanCoreLeScanOffloadingPercentage"
+ "ScanCoreLeScanPercentage"
+ "SecondaryPICE"
+ "SecondaryPIIS"
+ "ServoCE_0"
+ "ServoCE_1"
+ "ServoCE_2"
+ "ServoCE_3"
+ "ServoCE_4"
+ "ServoCE_5"
+ "ServoCE_6"
+ "SnapshotTimestamp"
+ "SystemCapabilitySource_Battery0"
+ "SystemCapabilitySource_Battery1"
+ "SystemLoadFraction"
+ "SystemStressLevel"
+ "Trial activation skipped: DRConfig unavailable after delay"
+ "VddMon_Battery0"
+ "VddMon_Battery1"
+ "assetDownloadSessionDuration"
+ "assetLoadedFromCacheKB"
+ "baseband_100ms"
+ "baseband_1sec"
+ "baseband_Insta"
+ "bdS0"
+ "bfo0"
+ "bfo1"
+ "camera_100ms"
+ "camera_1sec"
+ "camera_Insta"
+ "clpc_100ms"
+ "clpc_1sec"
+ "clpc_Insta"
+ "display2_100ms"
+ "display2_1sec"
+ "display2_Insta"
+ "display_100ms"
+ "display_1sec"
+ "display_Insta"
+ "downloadedBytes"
+ "estimatedFileByteCount"
+ "exportSessionDuration"
+ "f_100ms"
+ "f_1sec"
+ "f_Insta"
+ "gpu_100ms"
+ "gpu_1sec"
+ "gpu_Insta"
+ "haptics_100ms"
+ "haptics_1sec"
+ "haptics_Insta"
+ "inductive_100ms"
+ "inductive_1sec"
+ "inductive_Insta"
+ "ioport_100ms"
+ "ioport_1sec"
+ "ioport_Insta"
+ "m_100ms"
+ "m_1sec"
+ "m_Insta"
+ "nand_100ms"
+ "nand_1sec"
+ "nand_Insta"
+ "nfc_100ms"
+ "nfc_1sec"
+ "nfc_Insta"
+ "numFramesDisplayed"
+ "numFramesRendered"
+ "pr_100ms"
+ "pr_1sec"
+ "pr_Insta"
+ "pv_100ms"
+ "pv_1sec"
+ "pv_Insta"
+ "rtmu_100ms"
+ "rtmu_1sec"
+ "rtmu_Insta"
+ "se_100ms"
+ "se_1sec"
+ "se_Insta"
+ "sne_100ms"
+ "sne_1sec"
+ "sne_Insta"
+ "speaker_100ms"
+ "speaker_1sec"
+ "speaker_Insta"
+ "strobe_100ms"
+ "strobe_1sec"
+ "strobe_Insta"
+ "t_100ms"
+ "t_1sec"
+ "t_Insta"
+ "telephony_100ms"
+ "telephony_1sec"
+ "telephony_Insta"
+ "uwb_100ms"
+ "uwb_1sec"
+ "uwb_Insta"
+ "waterejection_100ms"
+ "waterejection_1sec"
+ "waterejection_Insta"
+ "wifi_100ms"
+ "wifi_1sec"
+ "wifi_Insta"
+ "zSPs"
- "Bds0"
- "Bfo0"
- "Bfo1"
- "assetloadedfromCacheKB"
```
