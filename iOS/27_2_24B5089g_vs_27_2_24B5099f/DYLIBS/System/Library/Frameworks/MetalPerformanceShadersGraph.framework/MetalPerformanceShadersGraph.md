## MetalPerformanceShadersGraph

> `/System/Library/Frameworks/MetalPerformanceShadersGraph.framework/MetalPerformanceShadersGraph`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21dbad0` | `0x21dc91c` | **`+0xe4c`** |
| `__TEXT.__const` | `0x6de08` | `0x6dea8` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0xa9ba0` | `0xa9c30` | **`+0x90`** |
| `__TEXT.__cstring` | `0xf1b00` | `0xf1b82` | **`+0x82`** |
| `__TEXT.__gcc_except_tab` | `0x137fa0` | `0x138010` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x14cc0` | `0x14d20` | **`+0x60`** |
| `__DATA_CONST.__objc_arraydata` | `0x1ad8` | `0x1b20` | **`+0x48`** |
| `__AUTH_CONST.__objc_dictobj` | `0x618` | `0x640` | **`+0x28`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x2430` | `0x2448` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x67648` | `0x67660` | **`+0x18`** |
| `__DATA.__data` | `0x77d0` | `0x77e0` | **`+0x10`** |

### Other Changes

```diff

-7.1.4.0.0
+7.1.5.0.0

-  Functions: 105298
-  Symbols:   141132
-  CStrings:  21156
+  Functions: 105307
+  Symbols:   141150
+  CStrings:  21161
Symbols:
+ GCC_except_table506
+ GCC_except_table507
+ GCC_except_table525
+ GCC_except_table624
+ GCC_except_table627
+ GCC_except_table628
+ GCC_except_table654
+ GCC_except_table666
+ GCC_except_table720
+ __ZN4llvm7support6detail30stream_operator_format_adapterIN4mlir8LocationEE6formatERNS_11raw_ostreamENS_9StringRefE
+ __ZN4llvm7support6detail30stream_operator_format_adapterIN4mlir8LocationEED0Ev
+ __ZN4llvm7support6detail30stream_operator_format_adapterIN4mlir8LocationEED1Ev
+ __ZN4llvm7support6detail30stream_operator_format_adapterIRN4mlir10DiagnosticEE6formatERNS_11raw_ostreamENS_9StringRefE
+ __ZN4llvm7support6detail30stream_operator_format_adapterIRN4mlir10DiagnosticEED0Ev
+ __ZN4llvm7support6detail30stream_operator_format_adapterIRN4mlir10DiagnosticEED1Ev
+ __ZN4mlir7mps_spi27ScaledDotProductAttentionOp15writePropertiesERNS_21DialectBytecodeWriterE
+ __ZN4mlir7mps_spi27ScaledDotProductAttentionOp19verifyInherentAttrsENS_13OperationNameERNS_13NamedAttrListEN4llvm12function_refIFNS_18InFlightDiagnosticEvEEE
+ __ZN4mlir7mps_spi27ScaledDotProductAttentionOp27getReducedPrecisionFastMathEv
+ __ZN4mlir7mps_spi27ScaledDotProductAttentionOp5buildERNS_9OpBuilderERNS_14OperationStateENS_5ValueES6_S6_S6_S6_NS_8BoolAttrENS_11IntegerAttrES6_S8_
+ __ZN4mlir9OpBuilder6createINS_7mps_spi27ScaledDotProductAttentionOpEJRNS_5ValueES5_S5_S5_S5_NS_8BoolAttrENS_11IntegerAttrES5_S7_EEET_NS_8LocationEDpOT0_
+ __ZNK4llvm19formatv_object_base3strEv
+ __ZNO4mlir18InFlightDiagnosticlsIRA88_KcEEOS0_OT_
+ __ZTIN4llvm7support6detail30stream_operator_format_adapterIN4mlir8LocationEEE
+ __ZTIN4llvm7support6detail30stream_operator_format_adapterIRN4mlir10DiagnosticEEE
+ __ZTSN4llvm7support6detail30stream_operator_format_adapterIN4mlir8LocationEEE
+ __ZTSN4llvm7support6detail30stream_operator_format_adapterIRN4mlir10DiagnosticEEE
+ __ZTVN4llvm7support6detail30stream_operator_format_adapterIN4mlir8LocationEEE
+ __ZTVN4llvm7support6detail30stream_operator_format_adapterIRN4mlir10DiagnosticEEE
- GCC_except_table538
- GCC_except_table570
- GCC_except_table577
- GCC_except_table645
- GCC_except_table650
- GCC_except_table661
- GCC_except_table664
- __ZN4mlir7mps_spi27ScaledDotProductAttentionOp5buildERNS_9OpBuilderERNS_14OperationStateENS_5ValueES6_S6_S6_S6_NS_8BoolAttrENS_11IntegerAttrES6_
- __ZN4mlir9OpBuilder6createINS_7mps_spi27ScaledDotProductAttentionOpEJRNS_5ValueES5_S5_S5_S5_NS_8BoolAttrENS_11IntegerAttrES5_EEET_NS_8LocationEDpOT0_
- __ZZZN23ScopedDiagnosticHandlerC1EPN4mlir11MLIRContextEbENKUlRNS0_10DiagnosticEE_clES4_ENKUlRN4llvm11raw_ostreamEE_clES8_
CStrings:
+ "1.0.13"
+ "7.1.5"
+ "Invalid attribute `reduced_precision_fast_math` in property conversion: "
+ "reduced_precision_fast_math"
+ "{0}: {1}"
+ "{0}: {1}: {2}"
- "7.1.4"
```
