## MTLCompiler

> `/System/Library/PrivateFrameworks/MTLCompiler.framework/Versions/32024/MTLCompiler`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb7430` | `0xb7a58` | **`+0x628`** |
| `__TEXT.__gcc_except_tab` | `0xa51c` | `0xa548` | **`+0x2c`** |
| `__TEXT.__unwind_info` | `0x2f38` | `0x2f58` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x10e8` | `0x10f8` | **`+0x10`** |
| `__TEXT.__const` | `0x1278` | `0x1288` | **`+0x10`** |
| `__TEXT.__cstring` | `0x96db` | `0x96e7` | **`+0xc`** |

### Other Changes

```diff

-382.5.0.0.0
+382.5.3.0.0

-  Functions: 2137
-  Symbols:   3429
-  CStrings:  1638
+  Functions: 2144
+  Symbols:   3438
+  CStrings:  1639
Symbols:
+ __ZN4llvm10AllocaInst25getDeferredStaticSizeCallEv
+ __ZN4llvm11Instruction10moveBeforeEPS0_
+ __ZN4llvm12DenseMapBaseINS_13SmallDenseMapIPNS_8CallInstENS_6detail13DenseSetEmptyELj4ENS_12DenseMapInfoIS3_vEENS4_12DenseSetPairIS3_EEEES3_S5_S7_S9_E11try_emplaceIJRS5_EEENSt3__14pairINS_16DenseMapIteratorIS3_S5_S7_S9_Lb0EEEbEERKS3_DpOT_
+ __ZN4llvm12DenseMapBaseINS_13SmallDenseMapIPNS_8CallInstENS_6detail13DenseSetEmptyELj4ENS_12DenseMapInfoIS3_vEENS4_12DenseSetPairIS3_EEEES3_S5_S7_S9_E18moveFromOldBucketsEPS9_SC_
+ __ZN4llvm12DenseMapBaseINS_13SmallDenseMapIPNS_8CallInstENS_6detail13DenseSetEmptyELj4ENS_12DenseMapInfoIS3_vEENS4_12DenseSetPairIS3_EEEES3_S5_S7_S9_E20InsertIntoBucketImplIS3_EEPS9_RKS3_RKT_SD_
+ __ZN4llvm13SmallDenseMapIPNS_8CallInstENS_6detail13DenseSetEmptyELj4ENS_12DenseMapInfoIS2_vEENS3_12DenseSetPairIS2_EEE4growEj
+ __ZN4llvm14SmallSetVectorIPNS_8CallInstELj4EED2Ev
+ __ZN4llvm9SetVectorIPNS_8CallInstENS_11SmallVectorIS2_Lj4EEENS_13SmallDenseSetIS2_Lj4ENS_12DenseMapInfoIS2_vEEEEE6insertERKS2_
+ __ZNK4llvm12DenseMapBaseINS_13SmallDenseMapIPNS_8CallInstENS_6detail13DenseSetEmptyELj4ENS_12DenseMapInfoIS3_vEENS4_12DenseSetPairIS3_EEEES3_S5_S7_S9_E15LookupBucketForIS3_EEbRKT_RPKS9_
CStrings:
+ "stride0_i32"
```
