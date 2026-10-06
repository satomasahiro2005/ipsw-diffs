## libLLVM.dylib

> `/System/Library/PrivateFrameworks/GPUCompiler.framework/Versions/32023/Libraries/libLLVM.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20296ac` | `0x202f09c` | **`+0x59f0`** |
| `__AUTH_CONST.__const` | `0x66660` | `0x66750` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x2d410` | `0x2d468` | **`+0x58`** |
| `__TEXT.__const` | `0x4191200` | `0x4191230` | **`+0x30`** |
| `__TEXT.__cstring` | `0x11940a` | `0x11942b` | **`+0x21`** |
| `__DATA_CONST.__const` | `0x273418` | `0x273420` | **`+0x8`** |

### Other Changes

```diff

-32023.921.0.0.0
+32023.921.4.0.0

-  Functions: 72766
-  Symbols:   21893
-  CStrings:  43511
+  Functions: 72829
+  Symbols:   21900
+  CStrings:  43512
Symbols:
+ __ZN4llvm17DivergenceTracker24markControlDependentPhisEPKNS_11InstructionEPNS_10BasicBlockENSt3__18functionIFvPKNS_5ValueEEEE
+ __ZNK4llvm19TargetTransformInfo21getCopyLikeDstSrcLocsEPKNS_11InstructionE
+ __ZNK4llvm19TargetTransformInfo21isIgnorableMemLikeDefEPKNS_11InstructionE
+ __ZNK4llvm19TargetTransformInfo23getSafeMemLikeAccessLocEPKNS_11InstructionE
+ __ZNK4llvm19TargetTransformInfo26getSafeStoreLikeStoredValsEPNS_11InstructionE
+ __ZNK4llvm19TargetTransformInfo27isRewritableMemLikeMiscInstEPKNS_11InstructionE
+ __ZNK4llvm19TargetTransformInfo30rewriteMemLikeWithAddressSpaceEPNS_11InstructionEj
CStrings:
+ "32023.921.4"
+ "Apple LLVM version 32023.921.4"
+ "LLVM version 32023.921.4"
+ "llvm-mc (based on LLVM 32023.921.4)"
+ "tensor_element_addrspace"
- "32023.921"
- "Apple LLVM version 32023.921"
- "LLVM version 32023.921"
- "llvm-mc (based on LLVM 32023.921)"
```
