## com.apple.driver.AppleT8140

> `com.apple.driver.AppleT8140`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x360` | **`+0x360`** |
| `__TEXT_EXEC.__text` | `0x854c` | `0x860c` | **`+0xc0`** |

### Other Changes

```text
Functions:
~ __ZN29AppleH17PPlatformErrorHandler5startEP9IOService : 3376 -> 3384
~ __ZN29AppleH17PPlatformErrorHandler12_getMetadataERNS_10metadata_tEPKcjb : 1184 -> 1168
~ __ZN29AppleH17PPlatformErrorHandler19_getNsApertureNamesEPKcPjj : 416 -> 424
~ __ZN29AppleH17PPlatformErrorHandler13_mapAperturesERKNS_10metadata_tEPNS_10aperture_tEj : 352 -> 380
~ __ZN29AppleH17PPlatformErrorHandler24_initDSIDTimeoutReporterEv : 484 -> 476
~ sub_fffffff009748ae4 -> sub_fffffff00979f0b8 : 192 -> 216
~ sub_fffffff009748ba4 -> sub_fffffff00979f190 : 332 -> 360
~ sub_fffffff009748d00 -> sub_fffffff00979f308 : 96 -> 104
~ sub_fffffff009748d60 -> sub_fffffff00979f370 : 300 -> 276
~ sub_fffffff009748e8c -> sub_fffffff00979f484 : 228 -> 260
~ sub_fffffff009748f70 -> sub_fffffff00979f588 : 484 -> 480
~ sub_fffffff009749154 -> sub_fffffff00979f768 : 120 -> 116
~ sub_fffffff009749250 -> sub_fffffff00979f860 : 104 -> 100
~ __ZN29AppleH17PPlatformErrorHandler25_afxSocNiDecodeInterruptsEiPv : 692 -> 688
~ __ZN29AppleH17PPlatformErrorHandler25_afxPioGwDecodeInterruptsEiPv : 852 -> 860
~ __ZN29AppleH17PPlatformErrorHandler27_amccPlaneHandleDSIDTimeoutEjjjRjPKNS_18AMCCPlaneDecoder_tE : 364 -> 392
~ __ZN29AppleH17PPlatformErrorHandler21_amccDecodeInterruptsEiPv : 528 -> 548
~ __ZN29AppleH17PPlatformErrorHandler18_dcsDecodeMCUErrorEjjjRjPKNS_12DCSDecoder_tE : 1068 -> 1076
~ __ZN29AppleH17PPlatformErrorHandler20_dcsDecodeInterruptsEi : 744 -> 780
~ __ZN29AppleH17PPlatformErrorHandler15_dcsGetPTDRangeEPKcj : 524 -> 528
~ __ZN29AppleH17PPlatformErrorHandler23_sepDecodeMonInterruptsEiPv : 496 -> 512
```
