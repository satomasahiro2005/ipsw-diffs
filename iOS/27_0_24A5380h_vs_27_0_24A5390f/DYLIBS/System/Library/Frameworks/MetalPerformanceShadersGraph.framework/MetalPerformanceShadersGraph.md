## MetalPerformanceShadersGraph

> `/System/Library/Frameworks/MetalPerformanceShadersGraph.framework/MetalPerformanceShadersGraph`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21a62f4` | `0x21a8134` | **`+0x1e40`** |
| `__TEXT.__cstring` | `0xef052` | `0xef21e` | **`+0x1cc`** |
| `__TEXT.__oslogstring` | `0x31b2` | `0x333a` | **`+0x188`** |
| `__TEXT.__gcc_except_tab` | `0x136d80` | `0x136eb0` | **`+0x130`** |
| `__AUTH_CONST.__const` | `0xa8ed0` | `0xa8f00` | **`+0x30`** |
| `__TEXT.__const` | `0x6cbe8` | `0x6cbb8` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x67080` | `0x670a8` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x14120` | `0x14100` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0x127d8` | `0x127f8` | **`+0x20`** |
| `__DATA.__data` | `0x76b8` | `0x76c8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x84ac` | `0x84bc` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x4660` | `0x4668` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x1628` | `0x1630` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x26c` | `0x270` | **`+0x4`** |

### Other Changes

```diff

-7.0.75.2.0
+7.0.76.1.0

-  Functions: 104703
-  Symbols:   140263
-  CStrings:  20945
+  Functions: 104711
+  Symbols:   140272
+  CStrings:  20952
Symbols:
+ -[MPSGraphExecutable leadingDevice]
+ GCC_except_table538
+ GCC_except_table630
+ GCC_except_table635
+ GCC_except_table651
+ _$s28MetalPerformanceShadersGraph22MPSGraphDelegateKernelC16coreAI_inferTypeyy13CoreAIRuntime12OperandTypesV_AE0K15InferenceResultVAE16ExecutionContextVtKFSbSiXEfU0_
+ _$s28MetalPerformanceShadersGraph23reorderInputsAndOutputs6inputs7outputs12stateIndices13outputIsInOutSayxG09reorderedF0_AG0qH0tAG_AGSaySo8NSNumberCGSgSbSiXEtlFSo18MPSGraphShapedTypeC_Tg504$s28abc18Graph27undoReorderfg46Outputs09reorderedG00jI012stateIndices13outputnop32SayxG04origG0_AG0qI0tAG_AGSaySo8R23CGSgSaySbGtlFSbSiXEfU2_ShySiGTf1nnnc_n
+ _$s28MetalPerformanceShadersGraph27undoReorderInputsAndOutputs09reorderedG00jI012stateIndices13outputIsInOutSayxG04origG0_AG0qI0tAG_AGSaySo8NSNumberCGSgSaySbGtlF
+ _$s28MetalPerformanceShadersGraph27undoReorderInputsAndOutputs09reorderedG00jI012stateIndices13outputIsInOutSayxG04origG0_AG0qI0tAG_AGSaySo8NSNumberCGSgSaySbGtlFSbSiXEfU2_TA
+ _$s28MetalPerformanceShadersGraph27undoReorderInputsAndOutputs09reorderedG00jI012stateIndices13outputIsInOutSayxG04origG0_AG0qI0tAG_AGSaySo8NSNumberCGSgSaySbGtlFSo18MPSGraphShapedTypeC_Tg5
+ _OBJC_IVAR_$_MPSGraphExecutable._storedModulesFailedToMaterializeCount
+ __ZN4llvm10TypeSwitchIPN4mlir9OperationEbE4CaseIN6AICode12QuantizeOpV1ERZNS1_3mps15shouldSegmentOpES3_RNS1_13TypeConverterEE4$_13EERS4_OT0_
+ __ZN4llvm10TypeSwitchIPN4mlir9OperationEbE4CaseIN6AICode12QuantizeOpV2ERZNS1_3mps15shouldSegmentOpES3_RNS1_13TypeConverterEE4$_13EERS4_OT0_
+ __ZN4llvm10TypeSwitchIPN4mlir9OperationEbE4CaseIN6AICode14DequantizeOpV1ERZNS1_3mps15shouldSegmentOpES3_RNS1_13TypeConverterEE4$_12EERS4_OT0_
+ __ZN4llvm10TypeSwitchIPN4mlir9OperationEbE4CaseIN6AICode14DequantizeOpV2ERZNS1_3mps15shouldSegmentOpES3_RNS1_13TypeConverterEE4$_12EERS4_OT0_
+ __ZN4llvm12function_refIFN4mlir10WalkResultEPNS1_9OperationEEE11callback_fnIZNS1_6detail4walkILNS1_9WalkOrderE1ENS1_15ForwardIteratorERZZZ35-[MPSGraphExecutable leadingDevice]ENK4$_74clENS1_8ModuleOpEENKUlRNS1_6RegionEE_clESF_EUlNS1_9placement10RegionCallEE_SI_S2_EENSt3__19enable_ifIXaantsr4llvm9is_one_ofIT2_S4_PSE_PNS1_5BlockEEE5valuesr3std7is_sameIT3_S2_EE5valueESR_E4typeES4_OT1_EUlS4_E_EES2_lS4_
+ __ZN4llvm6any_ofIN4mlir14ValueTypeRangeINS1_11ResultRangeEEEZNS1_3mps15shouldSegmentOpEPNS1_9OperationERNS1_13TypeConverterEE4$_17EEbOT_T0_
+ __ZN4llvm6any_ofIN4mlir14ValueTypeRangeINS1_12OperandRangeEEEZNS1_3mps15shouldSegmentOpEPNS1_9OperationERNS1_13TypeConverterEE4$_17EEbOT_T0_
+ __ZN4llvm6any_ofINS_14iterator_rangeIN4mlir17ValueUserIteratorINS2_11ResultRange11UseIteratorENS2_9OpOperandEEEEEZNS2_3mps15shouldSegmentOpEPNS2_9OperationERNS2_13TypeConverterEE3$_6EEbOT_T0_
+ __ZN4mlir3mps12_GLOBAL__N_131enclosingFuncHasAllStaticInputsEPNS_9OperationE
+ __ZNK4mlir3mps12_GLOBAL__N_121ReorderDequantPermute19matchAndRewriteImplENS0_9PermuteOpERNS_15PatternRewriterE
+ __ZNK4mlir3mps12_GLOBAL__N_123ReorderDequantTranspose19matchAndRewriteImplENS0_11TransposeOpERNS_15PatternRewriterE
+ __ZNK4mlir3mps12_GLOBAL__N_125MPSToMemrefSliceConverter18handleDynamicSliceENS_5ValueENS0_7SliceOpERNS_15PatternRewriterEN4llvm8ArrayRefIxEEjRKNS7_11SmallVectorIxLj6EEESD_jjj
+ __ZNSt3__110unique_ptrIN4mlir3mps12MPSResourcesENS_14default_deleteIS3_EEEaSB9foe220106EOS6_
+ __ZNSt3__18__invokeB9fon220106IJRZN4mlir3mps15shouldSegmentOpEPNS1_9OperationERNS1_13TypeConverterEE3$_5NS1_4TypeEEEENS_20__invoke_result_implIvJDpT_EE4typeEDpOSB_
+ __ZZN4mlir3mps15shouldSegmentOpEPNS_9OperationERNS_13TypeConverterEENK3$_1clIRZNS0_15shouldSegmentOpES2_S4_E4$_10EEbNS_5ValueES9_S9_OT_
+ __ZZN4mlir3mps15shouldSegmentOpEPNS_9OperationERNS_13TypeConverterEENK3$_8clENS_5ValueE
+ __ZZN4mlir3mps15shouldSegmentOpEPNS_9OperationERNS_13TypeConverterEENK4$_14clENS_5ValueE
+ __ZZNK4mlir3mps12_GLOBAL__N_121ReorderDequantPermute19matchAndRewriteImplENS0_9PermuteOpERNS_15PatternRewriterEENKUlNS_5ValueEE0_clES6_
+ __ZZNK4mlir3mps12_GLOBAL__N_121ReorderDequantPermute19matchAndRewriteImplENS0_9PermuteOpERNS_15PatternRewriterEENKUlNS_5ValueEE_clES6_
+ ____ZN3GPUL20aneConstantsDisabledEv_block_invoke
- GCC_except_table595
- GCC_except_table628
- GCC_except_table639
- GCC_except_table679
- _$s28MetalPerformanceShadersGraph23reorderInputsAndOutputs6inputs7outputs12stateIndices13outputIsInOutSayxG09reorderedF0_AG0qH0tAG_AGSaySo8NSNumberCGSgSbSiXEtlFSo18MPSGraphShapedTypeC_Tg504$s28abc18Graph27undoReorderfg83Outputs33_6D50CC86E2CCE881D418F1204106A462LL09reorderedG00qI012stateIndices13outputnop32SayxG04origG0_AH0xI0tAH_AHSaySo8R23CGSgSaySbGtlFSbSiXEfU2_ShySiGTf1nnnc_n
- __ZN4llvm10TypeSwitchIPN4mlir9OperationEbE4CaseIN6AICode12QuantizeOpV1ERZNS1_3mps15shouldSegmentOpES3_RNS1_13TypeConverterEE4$_12EERS4_OT0_
- __ZN4llvm10TypeSwitchIPN4mlir9OperationEbE4CaseIN6AICode12QuantizeOpV2ERZNS1_3mps15shouldSegmentOpES3_RNS1_13TypeConverterEE4$_12EERS4_OT0_
- __ZN4llvm10TypeSwitchIPN4mlir9OperationEbE4CaseIN6AICode14DequantizeOpV1ERZNS1_3mps15shouldSegmentOpES3_RNS1_13TypeConverterEE4$_11EERS4_OT0_
- __ZN4llvm10TypeSwitchIPN4mlir9OperationEbE4CaseIN6AICode14DequantizeOpV2ERZNS1_3mps15shouldSegmentOpES3_RNS1_13TypeConverterEE4$_11EERS4_OT0_
- __ZN4llvm6any_ofIN4mlir14ValueTypeRangeINS1_11ResultRangeEEEZNS1_3mps15shouldSegmentOpEPNS1_9OperationERNS1_13TypeConverterEE4$_14EEbOT_T0_
- __ZN4llvm6any_ofIN4mlir14ValueTypeRangeINS1_12OperandRangeEEEZNS1_3mps15shouldSegmentOpEPNS1_9OperationERNS1_13TypeConverterEE4$_14EEbOT_T0_
- __ZN4llvm6any_ofINS_14iterator_rangeIN4mlir17ValueUserIteratorINS2_11ResultRange11UseIteratorENS2_9OpOperandEEEEEZNS2_3mps15shouldSegmentOpEPNS2_9OperationERNS2_13TypeConverterEE3$_5EEbOT_T0_
- __ZN4mlir12RewriterBase18replaceOpWithNewOpINS_7mps_spi27ScaledDotProductAttentionOpEJRNS_5ValueES5_S5_S5_S5_EEET_PNS_9OperationEDpOT0_
- __ZN4mlir9OpBuilder6createINS_7mps_spi27ScaledDotProductAttentionOpEJNS_5ValueERS4_S5_S4_S4_EEET_NS_8LocationEDpOT0_
- __ZN4mlir9OpBuilder6createINS_7mps_spi27ScaledDotProductAttentionOpEJRNS_5ValueES4_S4_S4_S5_EEET_NS_8LocationEDpOT0_
- __ZNK4mlir3mps12_GLOBAL__N_121ReorderDequantPermute15matchAndRewriteENS0_9PermuteOpERNS_15PatternRewriterE
- __ZNK4mlir3mps12_GLOBAL__N_123ReorderDequantTranspose15matchAndRewriteENS0_11TransposeOpERNS_15PatternRewriterE
- __ZZN4mlir3mps15shouldSegmentOpEPNS_9OperationERNS_13TypeConverterEENK3$_1clIRZNS0_15shouldSegmentOpES2_S4_E3$_9EEbNS_5ValueES9_S9_OT_
- __ZZN4mlir3mps15shouldSegmentOpEPNS_9OperationERNS_13TypeConverterEENK3$_7clENS_5ValueE
- __ZZN4mlir3mps15shouldSegmentOpEPNS_9OperationERNS_13TypeConverterEENK4$_13clENS_5ValueE
- __ZZNK4mlir3mps12_GLOBAL__N_121ReorderDequantPermute15matchAndRewriteENS0_9PermuteOpERNS_15PatternRewriterEENKUlNS_5ValueEE0_clES6_
- __ZZNK4mlir3mps12_GLOBAL__N_121ReorderDequantPermute15matchAndRewriteENS0_9PermuteOpERNS_15PatternRewriterEENKUlNS_5ValueEE_clES6_
CStrings:
+ "%s:%u: ANE compile failed!"
+ "%s:%u: Error = %@"
+ "%s:%u: Full compile with ANE as preferred device failed. Falling back to full compile on GPU."
+ "%s:%u: Specialized module(s) in package failed to materialize (%llu failure(s)); triggering full on-device recompile from original module."
+ "%s:%u: getANERequest: self=%p, entryFunction=%@, procedureIndex=%@, machoInputsIndices=%@, machoOutputsIndices=%@"
+ "7.0.76.1"
+ "slice has a dynamic view in an all-static graph: its shape operands did not resolve to static values, so no runtime shape function exists to resolve it"
+ "strided_slice has a dynamic view in an all-static graph: its shape operands did not resolve to static values, so no runtime shape function exists to resolve it"
+ "strided_slice_update has a dynamic view in an all-static graph: its index/shape operands did not resolve to static values, so no runtime shape function exists to resolve it"
- "7.0.75.2"
- "ANE compile failed!"
```
