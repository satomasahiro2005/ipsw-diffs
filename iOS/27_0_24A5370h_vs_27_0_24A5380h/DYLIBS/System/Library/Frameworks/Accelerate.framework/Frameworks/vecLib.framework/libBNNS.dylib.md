## libBNNS.dylib

> `/System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libBNNS.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1137a2c` | `0x113f1d4` | **`+0x77a8`** |
| `__TEXT.__const` | `0x62a3c` | `0x6323c` | **`+0x800`** |
| `__TEXT.__gcc_except_tab` | `0x2e3e4` | `0x2e95c` | **`+0x578`** |
| `__AUTH_CONST.__const` | `0x3a830` | `0x3ad60` | **`+0x530`** |
| `__TEXT.__cstring` | `0x5f847` | `0x5fc50` | **`+0x409`** |
| `__TEXT.__unwind_info` | `0x1bda8` | `0x1c150` | **`+0x3a8`** |
| `__TEXT.__eh_frame` | `0xd9e8` | `0xdae0` | **`+0xf8`** |
| `__AUTH.__data` | `0x2220` | `0x2240` | **`+0x20`** |
| `__DATA.__data` | `0x2858` | `0x2878` | **`+0x20`** |
| `__DATA.__common` | `0x1098` | `0x10a0` | **`+0x8`** |

### Other Changes

```diff

-2211.0.0.0.1
+2212.0.4.0.0

-  Functions: 39318
+  Functions: 39486

-  CStrings:  8701
+  CStrings:  8722
CStrings:
+ " must be tensor of 1-bit unsigned integer values, but got "
+ " must be tensor of 4-bit unsigned integer or 4-bit signed integer or 8-bit unsigned integer or 8-bit signed integer or bfloat16 type or 16-bit float or 32-bit float values, but got "
+ "BasicNeuralNetworkSubroutines-2212.0.4~20"
+ "ConvertSDPAOp: failed to parse scale"
+ "ConvertSparseToDenseOp: expected 2 operands"
+ "ConvertSparseToDenseOp: expected exactly one result"
+ "ConvertSparseToDenseOp: failed to convert result type"
+ "ConvertSparseToDenseOp: mask must be constant"
+ "ConvertSparseToDenseOp: nonzero_data must be constant"
+ "Invalid attribute `scale` in property conversion: "
+ "StringRef llvm::getTypeName() [DesiredTypeName = mlir::bnns::ConvertSparseToDenseOp]"
+ "StringRef llvm::getTypeName() [DesiredTypeName = mlir::bnns::detail::SDPAOpGenericAdaptorBase::Properties]"
+ "bnns.sparse_to_dense"
+ "execute_affine_dequantize_conv_repack_op: unsupported tensor type combination"
+ "internal.rsqrt"
+ "matmul op requires input and output tensors of rank >= 2"
+ "scale_tensor"
+ "sdpa_dynamic_scale"
+ "sdpa_head_dim_fp"
+ "sdpa_head_dim_int"
+ "sdpa_query_shape"
+ "sparse_to_dense"
+ "sparse_to_dense: failed to parse output"
- "BasicNeuralNetworkSubroutines-2211.0.0.0.1~50"
- "ConvertSDPAOp: custom scale is not supported"
```
