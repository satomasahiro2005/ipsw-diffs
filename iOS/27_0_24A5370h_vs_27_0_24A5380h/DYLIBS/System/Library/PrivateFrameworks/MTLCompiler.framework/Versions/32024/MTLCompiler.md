## MTLCompiler

> `/System/Library/PrivateFrameworks/MTLCompiler.framework/Versions/32024/MTLCompiler`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb6340` | `0xb745c` | **`+0x111c`** |
| `__TEXT.__gcc_except_tab` | `0xa414` | `0xa51c` | **`+0x108`** |
| `__TEXT.__cstring` | `0x9622` | `0x96db` | **`+0xb9`** |
| `__TEXT.__unwind_info` | `0x2ef0` | `0x2f38` | **`+0x48`** |

### Other Changes

```diff

-381.0.0.0.0
+382.4.0.0.0

-  Functions: 2125
-  Symbols:   3418
-  CStrings:  1628
+  Functions: 2137
+  Symbols:   3429
+  CStrings:  1638
Symbols:
+ GCC_except_table114
+ __Z19getOrInsertFunctionIJRA24_KcRPN4llvm4TypeES5_RPNS3_11PointerTypeEEEPNS3_8FunctionERNS3_6ModuleEDpOT_
+ __Z19getOrInsertFunctionIJRA27_KcRPN4llvm4TypeEPNS3_11PointerTypeES6_S6_S6_EEPNS3_8FunctionERNS3_6ModuleEDpOT_
+ __Z19getOrInsertFunctionIJRA28_KcRPN4llvm4TypeEPNS3_11PointerTypeES6_S6_S6_S6_S6_EEPNS3_8FunctionERNS3_6ModuleEDpOT_
+ __Z19getOrInsertFunctionIJRA35_KcRPN4llvm4TypeEPNS3_11PointerTypeES8_S6_S6_S6_S6_S6_S6_EEPNS3_8FunctionERNS3_6ModuleEDpOT_
+ __ZN12MTLIRBuilder16CreateAtomicLoadEPN4llvm5ValueE
+ __ZN12MTLIRBuilder20CreateAtomicFetchAddEPN4llvm5ValueES2_
+ __ZN12MTLIRBuilder27CreateAtomicCompareExchangeEPN4llvm5ValueES2_S2_
+ __ZN21MemoryIndirectionPass23createBVHResidencyCheckERN4llvm9IRBuilderINS0_14ConstantFolderENS0_24IRBuilderDefaultInserterEEEPNS0_5ValueES7_
+ __ZN21MemoryIndirectionPass24loadBVHResidencyTablePtrERN4llvm9IRBuilderINS0_14ConstantFolderENS0_24IRBuilderDefaultInserterEEE
+ __ZN4llvm11SmallVectorIPNS_4TypeELj8EEC2ESt16initializer_listIS2_E
+ __ZN4llvm6Module19getOrInsertFunctionIJPNS_11PointerTypeEPNS_4TypeES5_S5_S5_S5_EEENS_14FunctionCalleeENS_9StringRefENS_13AttributeListES5_DpT_
+ __ZN4llvm6Module19getOrInsertFunctionIJPNS_11PointerTypeES3_PNS_4TypeES5_S5_S5_S5_S5_EEENS_14FunctionCalleeENS_9StringRefENS_13AttributeListES5_DpT_
+ __ZN4llvm6Module19getOrInsertFunctionIJPNS_4TypeEPNS_11PointerTypeEEEENS_14FunctionCalleeENS_9StringRefENS_13AttributeListES3_DpT_
- GCC_except_table104
- __Z19getOrInsertFunctionIJRA24_KcRPN4llvm4TypeES5_EEPNS3_8FunctionERNS3_6ModuleEDpOT_
- __ZN21MemoryIndirectionPass23createBVHResidencyCheckERN4llvm9IRBuilderINS0_14ConstantFolderENS0_24IRBuilderDefaultInserterEEEPNS0_5ValueE
CStrings:
+ "air.atomic.global.cmpxchg.weak.i32"
+ "air.atomic.global.load.i32"
+ "air.block_read_depth"
+ "air.block_read_texture"
+ "cursorSlot"
+ "cursorTablePtr"
+ "cursorUpdateBlock"
+ "pastEnd"
+ "windowEnd"
+ "windowSetupBlock"
```
