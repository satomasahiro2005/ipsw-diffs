## AppleH15MCD

> `/System/Library/Extensions/AppleH15MCD.kext/AppleH15MCD`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x13184` | `0x133cc` | **`+0x248`** |
| `__TEXT.__cstring` | `0x88e3` | `0x8a1d` | **`+0x13a`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`

### Other Changes

```diff

-125.0.0.0.0
+126.0.0.0.0

-  CStrings:  1415
+  CStrings:  1421
Functions:
~ __ZN28AppleH15PlatformErrorHandler30_amccNoPlaneDecodeUeflOverflowEjjRjPKNS_21AMCCNonPlaneDecoder_tE : 308 -> 352
~ __ZN28AppleH15PlatformErrorHandler5startEP9IOService : 5256 -> 5252
~ __ZN28AppleH15PlatformErrorHandler15eccEventHandlerEP8OSObjectP22IOInterruptEventSourcei : 1024 -> 900
~ __ZN28AppleH15PlatformErrorHandler30amccNoPlaneDelayedFetchUeflLogEP8OSObjectP22IOInterruptEventSourcei : 392 -> 544
~ __ZN28AppleH15PlatformErrorHandler12_getMetadataERNS_10metadata_tEPKcjb : 1188 -> 1152
~ __ZN28AppleH15PlatformErrorHandler19_getNsApertureNamesEPKcPjjb : 480 -> 496
~ __ZN28AppleH15PlatformErrorHandler13_mapAperturesERKNS_10metadata_tEPNS_10aperture_tEj : 352 -> 380
~ __ZN28AppleH15PlatformErrorHandler23_amccGenerateEnableMaskEv : 288 -> 316
~ __ZN28AppleH15PlatformErrorHandler22_dcsGenerateEnableMaskEv : 244 -> 264
~ __ZN28AppleH15PlatformErrorHandler24_afxNiGenerateEnableMaskEv : 112 -> 108
~ __ZN28AppleH15PlatformErrorHandler26_d2dAfcGenerateDisableMaskEv : 144 -> 156
~ __ZN28AppleH15PlatformErrorHandler26_d2dAfiGenerateDisableMaskEv : 156 -> 168
~ __ZN28AppleH15PlatformErrorHandler26_d2dAfrGenerateDisableMaskEv : 180 -> 188
~ __ZN28AppleH15PlatformErrorHandler17_amccEnableErrorsEb : 292 -> 328
~ __ZN28AppleH15PlatformErrorHandler16_dcsEnableErrorsEb : 388 -> 408
~ __ZN28AppleH15PlatformErrorHandler18_afxNiEnableErrorsEb : 292 -> 284
~ __ZN28AppleH15PlatformErrorHandler19_afcNsDisableErrorsEb : 124 -> 120
~ __ZN28AppleH15PlatformErrorHandler19_afiNsDisableErrorsEb : 124 -> 120
~ __ZN28AppleH15PlatformErrorHandler20_d2dAfrDisableErrorsEv : 216 -> 192
~ __ZN28AppleH15PlatformErrorHandler17_enableInterruptsEb : 104 -> 100
~ __ZN28AppleH15PlatformErrorHandler23amccNoPlaneFetchCeflLogEjPyPj : 368 -> 408
~ __ZN28AppleH15PlatformErrorHandler19_afrNsDisableErrorsEb : 124 -> 120
~ __ZN28AppleH15PlatformErrorHandler31_amccNoPlaneDecodeCeflReportLogEjNS_12EFLErrorTypeE : 196 -> 240
~ __ZN28AppleH15PlatformErrorHandler36_amccGenerateEnableMaskforInputTableEPNS_22AMCCNonPlaneDecoders_tE : 156 -> 176
~ __ZN28AppleH15PlatformErrorHandler13_amccDumpRegsEj : 588 -> 596
~ __ZN28AppleH15PlatformErrorHandler21_amccDecodeInterruptsEiPv : 596 -> 620
~ __ZN28AppleH15PlatformErrorHandler34_amccDecodeInterruptsForInputTableEPNS_22AMCCNonPlaneDecoders_tEjPb : 356 -> 380
~ __ZN28AppleH15PlatformErrorHandler18_dcsDecodeMCUErrorEjjjRjPKNS_12DCSDecoder_tE : 724 -> 736
~ __ZN28AppleH15PlatformErrorHandler20_dcsDecodeInterruptsEiPv : 804 -> 840
~ __ZN28AppleH15PlatformErrorHandler23_gibIoaDecodeInterruptsEiPv : 240 -> 248
~ __ZN28AppleH15PlatformErrorHandler23_gibD2dDecodeInterruptsEiPv : 236 -> 248
~ __ZN28AppleH15PlatformErrorHandler24_gibAmccDecodeInterruptsEiPv : 236 -> 248
~ __ZN28AppleH15PlatformErrorHandler20_ioaDecodeInterruptsEiPv : 304 -> 300
~ __ZN28AppleH15PlatformErrorHandler23_sepDecodeMonInterruptsEiPv : 448 -> 464
~ __ZN28AppleH15PlatformErrorHandler21_sramDecodeInterruptsEiPv : 340 -> 320
~ __ZN26AppleH15MemCacheController5startEP9IOService : 4956 -> 4960
~ __ZN26AppleH15MemCacheController13_mapAperturesEPNS_15amcc_aperture_tEj : 504 -> 524
~ __ZN26AppleH15MemCacheController17_initMemHashParamEP9IOService : 2416 -> 2424
~ __ZN26AppleH15MemCacheController31_mccRestoreAMCPerfCounterConfigEv : 220 -> 216
~ ____ZN26AppleH15MemCacheController20callPlatformFunctionEPK8OSSymbolbPvS3_S3_S3__block_invoke : 148 -> 156
~ __ZN26AppleH15MemCacheController25_mccSampleAllPerfCountersEb : 176 -> 180
~ __ZN26AppleH15MemCacheController28_mccSelectDynamicDRAMCFGModeEj : 428 -> 424
~ __ZN26AppleH15MemCacheController21getDCSODTSReadingsMR4Ev : 636 -> 616
~ __ZN26AppleH15MemCacheController15_enablePerfCtrlEPNS_17AMCCCounterConfigEjb : 912 -> 932
~ __ZN26AppleH15MemCacheController21_mccSamplePerfCounterEPNS_17AMCCCounterConfigEjPy : 176 -> 172
~ __ZN26AppleH15MemCacheController14_readPerfValueEPNS_17AMCCCounterConfigEj : 356 -> 380
~ __ZN26AppleH15MemCacheController15getAllDSIDQuotaEPjPy : 376 -> 388
~ __ZN26AppleH15MemCacheController15getHashingTableEPNS_13DcsHashingRegEPNS_14DcsHashingUnitEj : 304 -> 372
~ __ZN26AppleH15MemCacheController22getPhysicalAddrFromECSEjjjPjPy : 448 -> 452
~ __ZN26AppleH15MemCacheController22writeErrorInjectionRegEjjPj : 108 -> 124
~ __ZN26AppleH15MemCacheController16getHashBitValuesEPjyPNS_14DcsHashingUnitEj : 152 -> 148
~ __ZN26AppleH15MemCacheController15restoreDropBitsEPyPNS_14DcsHashingUnitEPjj : 308 -> 340
~ __ZN26AppleH15MemCacheController17setErrorInjectionEPNS_8errorInjE : 252 -> 268
~ __ZN28AppleH15PlatformErrorHandler23_amccNonPlaneDecodeXCTTEjjRjPKNS_21AMCCNonPlaneDecoder_tEPKNS_10xCTTInfo_tE : 376 -> 368
CStrings:
+ "%s::%s: DRAMECC: AMCC CE count exceeded[%u/%u]: PA 0x%llx, ceCount %u (log0 = 0x%08x, log1 = 0x%08x, log2 = 0x%08x)\n"
+ "%s::%s: DRAMECC: AMCC UE[%u/%u]: PA 0x%llx, req: %s, AFID 0x%x (log0 = 0x%08x, log1 = 0x%08x, log2 = 0x%08x)\n"
+ "%s::%s: DRAMECC: CEFL occupancy threshold interrupt for AMCC %d cefl_log[0][0] is 0x%08x cefl_log[0][1] is 0x%08x cefl_log[0][2] is 0x%08x cefl_log[23][0] is 0x%08x cefl_log[23][1] is 0x%08x cefl_log[23][2] is 0x%08x\n"
+ "%s::%s: DRAMECC: CEFL overflow interrupt for AMCC %d cefl_log[0][0] is 0x%08x cefl_log[0][1] is 0x%08x cefl_log[0][2] is 0x%08xcefl_log[31][0] is 0x%08x cefl_log[31][1] is 0x%08x cefl_log[31][2] is 0x%08x\n"
+ "%s::%s: DRAMECC: CEFL, valid = 0x%08x\n"
+ "%s::%s: DRAMECC: CEFL: AMCC%u Valid = 0x%08x\n"
+ "%s::%s: DRAMECC: No errors\n"
+ "%s::%s: DRAMECC: UEFL Int, valid = 0x%08x, overflow = 0x%08x\n"
+ "12111112122212121121211111111111111111111111111121111111111111111111111111111111111111111111111111111111111111111111111111111111111212112121112112112112112112112112112112112112112112112112112112221111112222222222222222222222222222222222222222222222222222222222222222212222211222211111121112222"
+ "ACC"
+ "_amccNoPlaneDecodeCeflReportLog"
+ "_amccNoPlaneDecodeUeflOverflow"
+ "amccNoPlaneFetchCeflLog"
+ "non-ACC"
- "%s::%s: CEFL occupancy threshold interrupt for AMCC %d cefl_log[0][0] is 0x%08x cefl_log[0][1] is 0x%08x cefl_log[0][2] is 0x%08x cefl_log[23][0] is 0x%08x cefl_log[23][1] is 0x%08x cefl_log[23][2] is 0x%08x\n"
- "%s::%s: CEFL overflow interrupt for AMCC %d cefl_log[0][0] is 0x%08x cefl_log[0][1] is 0x%08x cefl_log[0][2] is 0x%08xcefl_log[31][0] is 0x%08x cefl_log[31][1] is 0x%08x cefl_log[31][2] is 0x%08x\n"
- "%s::%s: eccEventHandler: Logging pa 0x%llx ce_count 0x%u ecc_flags 0x%x: AFID 0x%x Status=%u\n\n"
- "%s::%s: ecc_log_memory_error, UE\n"
- "%s::%s: log0 = 0x%08x, log1 = 0x%08x, log2= 0x%08x\n"
- "%s::%s: no errors\n"
- "1211111212221212112121111111111111111111111121111111111111111111111111111111111111111111111111111111111111111111111111111111111212112121112112112112112112112112112112112112112112112112112112221111112222222222222222222222222222222222222222222222222222222222222222212222211222211111121112222"
- "dram-ecc"
```
