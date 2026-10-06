## com.apple.driver.AppleSART

> `com.apple.driver.AppleSART`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x273c` | `0x2884` | **`+0x148`** |

### Other Changes

```text
Functions:
~ sub_fffffff0094e7460 -> sub_fffffff009564070 : 72 -> 76
~ sub_fffffff0094e74b0 -> sub_fffffff0095640c4 : 52 -> 56
~ sub_fffffff0094e74e4 -> sub_fffffff0095640fc : 52 -> 56
~ sub_fffffff0094e7528 -> sub_fffffff009564144 : 68 -> 72
~ sub_fffffff0094e7594 -> sub_fffffff0095641b4 : 72 -> 76
~ sub_fffffff0094e75dc -> sub_fffffff009564200 : 104 -> 108
~ sub_fffffff0094e7658 -> sub_fffffff009564280 : 88 -> 92
~ sub_fffffff0094e76b0 -> sub_fffffff0095642dc : 88 -> 92
~ _panic : 876 -> 880
~ _OUTLINED_FUNCTION_1 : 140 -> 144
~ __ZN22IOCoastGuardSARTMapper13iovmMapMemoryEP18IOMemoryDescriptoryyjPK21IODMAMapSpecificationP12IODMACommandPK16IODMAMapPageListPySA_ : 636 -> 640
~ __ZN22IOCoastGuardSARTMapper15iovmUnmapMemoryEP18IOMemoryDescriptorP12IODMACommandyy : 460 -> 472
~ sub_fffffff0094e7f8c -> sub_fffffff009564bd4 : 80 -> 84
~ sub_fffffff0094e8014 -> sub_fffffff009564c60 : 72 -> 76
~ sub_fffffff0094e8064 -> sub_fffffff009564cb4 : 52 -> 56
~ sub_fffffff0094e8098 -> sub_fffffff009564cec : 52 -> 56
~ sub_fffffff0094e80dc -> sub_fffffff009564d34 : 68 -> 72
~ sub_fffffff0094e8148 -> sub_fffffff009564da4 : 72 -> 76
~ sub_fffffff0094e8190 -> sub_fffffff009564df0 : 104 -> 108
~ sub_fffffff0094e820c -> sub_fffffff009564e70 : 88 -> 92
~ sub_fffffff0094e8264 -> sub_fffffff009564ecc : 88 -> 92
~ __ZN16AppleSARTMarconi5startEP9IOService : 992 -> 996
~ _OUTLINED_FUNCTION_1_0 : 56 -> 60
~ sub_fffffff0094e86d4 -> sub_fffffff009565348 : 76 -> 80
~ sub_fffffff0094e8728 -> sub_fffffff0095653a0 : 80 -> 84
~ sub_fffffff0094e87e4 -> sub_fffffff009565460 : 72 -> 76
~ sub_fffffff0094e8834 -> sub_fffffff0095654b4 : 60 -> 64
~ sub_fffffff0094e8870 -> sub_fffffff0095654f4 : 60 -> 64
~ sub_fffffff0094e88bc -> sub_fffffff009565544 : 68 -> 72
~ sub_fffffff0094e8928 -> sub_fffffff0095655b4 : 72 -> 76
~ sub_fffffff0094e8970 -> sub_fffffff009565600 : 112 -> 116
~ sub_fffffff0094e89f4 -> sub_fffffff009565688 : 96 -> 100
~ sub_fffffff0094e8a54 -> sub_fffffff0095656ec : 96 -> 100
~ _OUTLINED_FUNCTION_0_1 : 308 -> 312
~ __ZN12IOSARTMapper10_setActiveEb : 352 -> 356
~ sub_fffffff0094e8dc4 -> sub_fffffff009565a68 : 120 -> 124
~ __ZN12IOSARTMapper10_addRegionEmjb : 332 -> 336
~ __ZN12IOSARTMapper13_removeRegionEi : 220 -> 224
~ sub_fffffff0094e9084 -> sub_fffffff009565d34 : 388 -> 392
~ __ZN12IOSARTMapper15iovmUnmapMemoryEP18IOMemoryDescriptorP12IODMACommandyy : 232 -> 236
~ sub_fffffff0094e92f0 -> sub_fffffff009565fa8 : 132 -> 136
~ sub_fffffff0094e9388 -> sub_fffffff009566044 : 80 -> 84
~ _OUTLINED_FUNCTION_0 : 52 -> 56
~ __ZN22IOCoastGuardSARTMapper5startEP9IOService.cold.2 : 52 -> 56
~ __ZN12IOSARTMapper5startEP9IOService.cold.2 : 52 -> 56
~ __ZN12IOSARTMapper5startEP9IOService.cold.3 : 52 -> 56
~ __ZN22IOCoastGuardSARTMapper20callPlatformFunctionEPK8OSSymbolbPvS3_S3_S3_.cold.1 : 52 -> 56
~ __ZN22IOCoastGuardSARTMapper13iovmMapMemoryEP18IOMemoryDescriptoryyjPK21IODMAMapSpecificationP12IODMACommandPK16IODMAMapPageListPySA_.cold.1 : 52 -> 56
~ __ZN22IOCoastGuardSARTMapper15iovmUnmapMemoryEP18IOMemoryDescriptorP12IODMACommandyy.cold.1 : 52 -> 56
~ __ZN16AppleSARTMarconi5startEP9IOService.cold.1 : 40 -> 44
~ __ZN16AppleSARTMarconi5startEP9IOService.cold.2 : 40 -> 44
~ __ZN16AppleSARTMarconi5startEP9IOService.cold.3 : 40 -> 44
~ __ZN16AppleSARTMarconi5startEP9IOService.cold.4 : 40 -> 44
~ __ZN16AppleSARTMarconi5startEP9IOService.cold.5 : 40 -> 44
~ __ZN16AppleSARTMarconi5startEP9IOService.cold.6 : 40 -> 44
~ __ZN16AppleSARTMarconi5startEP9IOService.cold.7 : 40 -> 44
~ sub_fffffff0094e9760 -> sub_fffffff009566458 : 40 -> 44
~ __ZN16AppleSARTMarconi5startEP9IOService.cold.9 : 40 -> 44
~ __ZN16AppleSARTMarconi15_makeRegionBaseEy.cold.1 : 52 -> 56
~ __ZN16AppleSARTMarconi15_makeRegionBaseEy.cold.2 : 52 -> 56
~ __ZN12IOSARTMapper10_addRegionEmjb.cold.3 : 52 -> 56
~ __ZN12IOSARTMapper10_addRegionEmjb.cold.4 : 52 -> 56
~ __ZN9os_detail21panic_trapping_policy4trapEPKc : 48 -> 52
~ __ZN12IOSARTMapper5startEP9IOService.cold.1 : 52 -> 56
~ sub_fffffff0094e98e4 -> sub_fffffff0095665fc : 52 -> 56
~ sub_fffffff0094e9918 -> sub_fffffff009566634 : 52 -> 56
~ __ZN12IOSARTMapper10_setActiveEb.cold.1 : 52 -> 56
~ __ZN12IOSARTMapper10_setActiveEb.cold.2 : 16 -> 20
~ __ZN9os_detail21panic_trapping_policy4trapEPKc : 16 -> 20
~ __ZN12IOSARTMapper10_addRegionEmjb.cold.1 : 52 -> 56
~ __ZN12IOSARTMapper10_addRegionEmjb.cold.2 : 52 -> 56
~ sub_fffffff0094e9a08 -> sub_fffffff00956673c : 52 -> 56
~ sub_fffffff0094e9a3c -> sub_fffffff009566774 : 52 -> 56
~ __ZN12IOSARTMapper10_addRegionEmjb.cold.6 : 16 -> 20
~ __ZN12IOSARTMapper13_removeRegionEi.cold.6 : 24 -> 28
~ _OUTLINED_FUNCTION_3 : 52 -> 56
~ sub_fffffff0094e9acc -> sub_fffffff009566814 : 52 -> 56
~ __ZN12IOSARTMapper15iovmUnmapMemoryEP18IOMemoryDescriptorP12IODMACommandyy.cold.1 : 52 -> 56
~ __ZN12IOSARTMapper10iovmInsertEjyyyy.cold.2 : 52 -> 56
~ sub_fffffff0094e9b68 -> sub_fffffff0095668bc : 52 -> 56
```
