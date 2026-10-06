## libODIECompiler.dylib

> `/System/Library/SubFrameworks/CoreAICompiler.framework/Frameworks/libODIECompiler.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc65004` | `0xc65650` | **`+0x64c`** |
| `__TEXT.__cstring` | `0xab996` | `0xaba47` | **`+0xb1`** |

### Other Changes

```diff

-3605.5.4.0.0
+3605.6.4.0.0

-  Functions: 74696
-  Symbols:   83177
-  CStrings:  11455
+  Functions: 74699
+  Symbols:   83180
+  CStrings:  11459
Symbols:
+ __ZN4llvm15SmallVectorImplIPN4mlir9OperationEE6appendINS1_17ValueUserIteratorINS1_16ValueUseIteratorINS1_9OpOperandEEES8_EEvEEvT_SB_
+ __ZN4mlir10DiagnosticlsINS_16RankedTensorTypeEEENSt3__19enable_ifIXaantsr3std14is_convertibleIT_N4llvm9StringRefEEE5valuesr3std16is_constructibleINS_18DiagnosticArgumentES5_EE5valueERS0_E4typeEOS5_
+ __ZN4mlir12matchPatternINS_6detail18constant_op_binderINS_19DenseFPElementsAttrEEEEEbNS_5ValueERKT_
CStrings:
+ "3605.6.4"
+ "offset1 must be statically shaped, but got "
+ "offset2 must be statically shaped, but got "
+ "per-axis quantization requires a constant axis"
+ "scale must be statically shaped, but got "
- "3605.5.4"
```
