## AppleT6030

> `/System/Library/Extensions/AppleT6030.kext/AppleT6030`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0xea7c` | `0xebb0` | **`+0x134`** |
| `__TEXT.__cstring` | `0x5ecd` | `0x5f17` | **`+0x4a`** |

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

-  CStrings:  960
+  CStrings:  962
Functions:
~ __ZN28AppleH15PlatformErrorHandler5startEP9IOService : 4072 -> 4068
~ __ZN28AppleH15PlatformErrorHandler12_getMetadataERNS_10metadata_tEPKcjb : 1188 -> 1152
~ __ZN28AppleH15PlatformErrorHandler19_getNsApertureNamesEPKcPjjb : 480 -> 496
~ __ZN28AppleH15PlatformErrorHandler13_mapAperturesERKNS_10metadata_tEPNS_10aperture_tEj : 352 -> 380
~ __ZN28AppleH15PlatformErrorHandler23_amccGenerateEnableMaskEv : 276 -> 304
~ __ZN28AppleH15PlatformErrorHandler22_dcsGenerateEnableMaskEv : 244 -> 264
~ __ZN28AppleH15PlatformErrorHandler24_afxNiGenerateEnableMaskEv : 112 -> 108
~ __ZN28AppleH15PlatformErrorHandler17_amccEnableErrorsEb : 292 -> 328
~ __ZN28AppleH15PlatformErrorHandler16_dcsEnableErrorsEb : 228 -> 256
~ __ZN28AppleH15PlatformErrorHandler18_afxNiEnableErrorsEb : 276 -> 260
~ __ZN28AppleH15PlatformErrorHandler19_afcNsDisableErrorsEb : 124 -> 120
~ __ZN28AppleH15PlatformErrorHandler19_afiNsDisableErrorsEb : 124 -> 120
~ __ZN28AppleH15PlatformErrorHandler17_enableInterruptsEb : 104 -> 100
~ __ZN28AppleH15PlatformErrorHandler23amccNoPlaneFetchCeflLogEjPyPj : 368 -> 408
~ __ZN28AppleH15PlatformErrorHandler19_afrNsDisableErrorsEb : 124 -> 120
~ __ZN28AppleH15PlatformErrorHandler36_amccGenerateEnableMaskforInputTableEPNS_22AMCCNonPlaneDecoders_tE : 116 -> 136
~ __ZN28AppleH15PlatformErrorHandler13_amccDumpRegsEj : 588 -> 596
~ __ZN28AppleH15PlatformErrorHandler21_amccDecodeInterruptsEiPv : 596 -> 620
~ __ZN28AppleH15PlatformErrorHandler34_amccDecodeInterruptsForInputTableEPNS_22AMCCNonPlaneDecoders_tEjPb : 356 -> 380
~ __ZN28AppleH15PlatformErrorHandler18_dcsDecodeMCUErrorEjjjRjPKNS_12DCSDecoder_tE : 696 -> 708
~ __ZN28AppleH15PlatformErrorHandler20_dcsDecodeInterruptsEiPv : 792 -> 808
~ __ZN28AppleH15PlatformErrorHandler20_ioaDecodeInterruptsEiPv : 220 -> 216
~ __ZN28AppleH15PlatformErrorHandler23_sepDecodeMonInterruptsEiPv : 452 -> 468
~ __ZN26AppleH15MemCacheController5startEP9IOService : 4948 -> 4952
~ __ZN26AppleH15MemCacheController13_mapAperturesEPNS_15amcc_aperture_tEj : 504 -> 524
~ __ZN26AppleH15MemCacheController31_mccRestoreAMCPerfCounterConfigEv : 220 -> 216
~ ____ZN26AppleH15MemCacheController20callPlatformFunctionEPK8OSSymbolbPvS3_S3_S3__block_invoke : 148 -> 156
~ __ZN26AppleH15MemCacheController25_mccSampleAllPerfCountersEb : 176 -> 180
~ __ZN26AppleH15MemCacheController28_mccSelectDynamicDRAMCFGModeEj : 428 -> 424
~ __ZN26AppleH15MemCacheController15_enablePerfCtrlEPNS_17AMCCCounterConfigEjb : 912 -> 932
~ __ZN26AppleH15MemCacheController21_mccSamplePerfCounterEPNS_17AMCCCounterConfigEjPy : 176 -> 172
~ __ZN26AppleH15MemCacheController14_readPerfValueEPNS_17AMCCCounterConfigEj : 356 -> 380
~ __ZN26AppleH15MemCacheController15getAllDSIDQuotaEPjPy : 376 -> 388
~ __ZN28AppleH15PlatformErrorHandler23_amccNonPlaneDecodeXCTTEjjRjPKNS_21AMCCNonPlaneDecoder_tEPKNS_10xCTTInfo_tE : 376 -> 368
CStrings:
+ "%s::%s: DRAMECC: CEFL: AMCC%u Valid = 0x%08x\n"
+ "121111121222121211212111111111111111111111111111211111111111111111111111111111111111111111111111111111111111111111111111111111111112121121211121121121121121121121121121121121121121121121121121122211111122222222222222222222222222222222222222222222222222222222222222222122222112222111111211122"
+ "amccNoPlaneFetchCeflLog"
- "12111112122212121121211111111111111111111111211111111111111111111111111111111111111111111111111111111111111111111111111111111112121121211121121121121121121121121121121121121121121121121121122211111122222222222222222222222222222222222222222222222222222222222222222122222112222111111211122"
```
