## AGXMetalG17P

> `/System/Library/Extensions/AGXMetalG17P.bundle/AGXMetalG17P`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8d1dbc` | `0x8d3af0` | **`+0x1d34`** |
| `__TEXT.__gcc_except_tab` | `0x13890` | `0x13848` | **`-0x48`** |
| `__AUTH_CONST.__cfstring` | `0x47c0` | `0x47a0` | **`-0x20`** |
| `__DATA.__bss` | `0x3fa0` | `0x3f80` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x77f0` | `0x77d8` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x55e0` | `0x55f0` | **`+0x10`** |
| `__TEXT.__cstring` | `0xce56` | `0xce4d` | **`-0x9`** |
| `__AUTH_CONST.__auth_got` | `0xaf0` | `0xaf8` | **`+0x8`** |

### Other Changes

```diff

-360.31.1.0.0
+360.32.0.0.0

-  Functions: 8912
-  Symbols:   14613
-  CStrings:  1862
+  Functions: 8913
+  Symbols:   14608
+  CStrings:  1861
Symbols:
+ GCC_except_table2406
+ GCC_except_table2413
+ GCC_except_table2423
+ GCC_except_table2424
+ GCC_except_table2430
+ GCC_except_table2454
+ GCC_except_table2472
+ GCC_except_table2556
+ GCC_except_table2632
+ GCC_except_table2636
+ GCC_except_table2651
+ GCC_except_table2665
+ GCC_except_table2675
+ GCC_except_table2679
+ GCC_except_table2681
+ GCC_except_table2872
+ GCC_except_table2875
+ GCC_except_table2881
+ GCC_except_table2895
+ GCC_except_table2901
+ GCC_except_table2906
+ GCC_except_table2909
+ GCC_except_table2916
+ GCC_except_table2920
+ GCC_except_table2953
+ GCC_except_table2962
+ GCC_except_table2967
+ _MTLDataTypeGetSize
+ __ZGVZN3AGX6DeviceINS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEE40findOrCreateUberBlitPipelineWithFallbackERNS_18UberBlitProgramKeyEPNS1_13CommandBufferEE26forceMslBlitSpecialization
+ __ZGVZN3AGX8BlitUtil17requireLegacyBlitILb1EEEbPNS_6HAL2006DeviceEP19AGXG17FamilyTextureE16disableMSLBlitEV
+ __ZN3AGX6DeviceINS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEE23decrementUberShaderUsesExxx
+ __ZN3AGX6DeviceINS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEE40findOrCreateUberBlitPipelineWithFallbackERNS_18UberBlitProgramKeyEPNS1_13CommandBufferE
+ __ZZN3AGX6DeviceINS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEE40findOrCreateUberBlitPipelineWithFallbackERNS_18UberBlitProgramKeyEPNS1_13CommandBufferEE26forceMslBlitSpecialization
+ __ZZN3AGX8BlitUtil17requireLegacyBlitILb1EEEbPNS_6HAL2006DeviceEP19AGXG17FamilyTextureE16disableMSLBlitEV
+ ____ZN3AGX6DeviceINS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEE13setupDeferredEP18AGXG17FamilyDevice_block_invoke_5
+ ____ZN3AGX6DeviceINS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEE40findOrCreateUberBlitPipelineWithFallbackERNS_18UberBlitProgramKeyEPNS1_13CommandBufferE_block_invoke
- GCC_except_table2388
- GCC_except_table2395
- GCC_except_table2414
- GCC_except_table2415
- GCC_except_table2421
- GCC_except_table2451
- GCC_except_table2469
- GCC_except_table2553
- GCC_except_table2631
- GCC_except_table2635
- GCC_except_table2650
- GCC_except_table2660
- GCC_except_table2673
- GCC_except_table2678
- GCC_except_table2680
- GCC_except_table2683
- GCC_except_table2870
- GCC_except_table2873
- GCC_except_table2880
- GCC_except_table2894
- GCC_except_table2900
- GCC_except_table2905
- GCC_except_table2908
- GCC_except_table2915
- GCC_except_table2919
- GCC_except_table2952
- GCC_except_table2961
- GCC_except_table2966
- GCC_except_table2974
- __ZGVZL28areDriverUberShadersDisabledvE19disableUberVariants
- __ZGVZN3AGX6DeviceINS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEE40findOrCreateUberBlitPipelineWithFallbackERNS_18UberBlitProgramKeyEE26forceMslBlitSpecialization
- __ZGVZN3AGX8BlitUtil17requireLegacyBlitILb1EEEbP19AGXG17FamilyTextureE16disableMSLBlitEV
- __ZGVZN3AGX8BlitUtil17requireLegacyBlitILb1EEEbP19AGXG17FamilyTextureE21disableMSLBlitFeature
- __ZL28areDriverUberShadersDisabledv
- __ZN3AGX6DeviceINS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEE40findOrCreateUberBlitPipelineWithFallbackERNS_18UberBlitProgramKeyE
- __ZN3AGX8BlitUtil17requireLegacyBlitILb1EEEbP19AGXG17FamilyTexture
- __ZZL28areDriverUberShadersDisabledvE19disableUberVariants
- __ZZN3AGX6DeviceINS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEE40findOrCreateUberBlitPipelineWithFallbackERNS_18UberBlitProgramKeyEE26forceMslBlitSpecialization
- __ZZN3AGX8BlitUtil17requireLegacyBlitILb1EEEbP19AGXG17FamilyTextureE16disableMSLBlitEV
- __ZZN3AGX8BlitUtil17requireLegacyBlitILb1EEEbP19AGXG17FamilyTextureE21disableMSLBlitFeature
- ____ZN3AGX6DeviceINS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEE40findOrCreateUberBlitPipelineWithFallbackERNS_18UberBlitProgramKeyE_block_invoke
CStrings:
- "metal_rt"
```
