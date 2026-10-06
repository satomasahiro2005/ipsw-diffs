## CoreAIRuntime

> `/System/Library/SubFrameworks/CoreAIRuntime.framework/CoreAIRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e5708` | `0x50ed5c` | **`+0x29654`** |
| `__TEXT.__eh_frame` | `0xd2e0` | `0x12248` | **`+0x4f68`** |
| `__TEXT.__unwind_info` | `0x5260` | `0x6378` | **`+0x1118`** |
| `__AUTH_CONST.__const` | `0x9708` | `0xa288` | **`+0xb80`** |
| `__TEXT.__swift5_capture` | `0x66c` | `0x11a4` | **`+0xb38`** |
| `__TEXT.__cstring` | `0xb5a0` | `0xbda1` | **`+0x801`** |
| `__DATA.__bss` | `0x8920` | `0x8ba0` | **`+0x280`** |
| `__AUTH.__data` | `0x2248` | `0x2400` | **`+0x1b8`** |
| `__TEXT.__const` | `0xe220` | `0xe090` | **`-0x190`** |
| `__TEXT.__swift5_typeref` | `0x309f` | `0x31bd` | **`+0x11e`** |
| `__TEXT.__constg_swiftt` | `0x33b0` | `0x34c0` | **`+0x110`** |
| `__TEXT.__swift5_fieldmd` | `0x3768` | `0x386c` | **`+0x104`** |
| `__AUTH_CONST.__auth_got` | `0x1408` | `0x14e0` | **`+0xd8`** |
| `__TEXT.__swift5_reflstr` | `0x2476` | `0x2526` | **`+0xb0`** |
| `__DATA.__data` | `0x2010` | `0x2068` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x80` | `0xa0` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x258` | `0x244` | **`-0x14`** |
| `__TEXT.__swift5_proto` | `0x6d8` | `0x6ec` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0xc0` | `0xd0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x3d8` | `0x3e4` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b18` | `0x1b20` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x3` | `0xb` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x6c` | `0x74` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x394` | `0x398` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0xb4` | `0xb8` | **`+0x4`** |
| `__TEXT.__swift5_types2` | `0x80` | `0x84` | **`+0x4`** |

### Other Changes

```diff

-3600.67.4.0.0
+3600.73.1.0.0

-  Functions: 7407
-  Symbols:   324
-  CStrings:  969
+  Functions: 7925
+  Symbols:   331
+  CStrings:  1013
Symbols:
+ _OBJC_CLASS_$_MTL4CommandQueueDescriptor
+ _OBJC_CLASS_$_MTLCommandQueueDescriptor
+ ___sincos_stret
+ _atan2
+ _cblas_cgemm$NEWLAPACK
+ _objc_retain_x4
+ _pthread_get_qos_class_np
+ _pthread_self
+ _sqrtf
+ _swift_retain_x10
- _madvise
- _objc_retain_x6
- _swift_retain_x11
CStrings:
+ " could not get input shape for meta output inference"
+ " has a dimension outside the ui32 range."
+ " has non-tensor meta inner type: "
+ " inferType called with non-meta output type: "
+ " is not a declared input of this function."
+ " is not a declared output of this function."
+ " is not allocated (return intent?)."
+ " is not allocated."
+ " is not an NDArray and cannot be serialized."
+ " must be resolved before type inference runs"
+ " out of range for operandIndices (count="
+ " requirements but expected "
+ "%{public}s"
+ "'acos' does not support scalar type Int128."
+ "'acos' does not support scalar type UInt128."
+ "'acosh' does not support scalar type Int128."
+ "'acosh' does not support scalar type UInt128."
+ "'asin' does not support scalar type Int128."
+ "'asin' does not support scalar type UInt128."
+ "'asinh' does not support scalar type Int128."
+ "'asinh' does not support scalar type UInt128."
+ "'atan' does not support scalar type Int128."
+ "'atan' does not support scalar type UInt128."
+ "'atanh' does not support scalar type Int128."
+ "'atanh' does not support scalar type UInt128."
+ "'cos' does not support scalar type Int128."
+ "'cos' does not support scalar type UInt128."
+ "'cosh' does not support scalar type Int128."
+ "'cosh' does not support scalar type UInt128."
+ "'erf' does not support scalar type Int128."
+ "'erf' does not support scalar type UInt128."
+ "'exp' does not support scalar type Int128."
+ "'exp' does not support scalar type UInt128."
+ "'log' does not support scalar type Int128."
+ "'log' does not support scalar type UInt128."
+ "'rsqrt' does not support scalar type Int128."
+ "'rsqrt' does not support scalar type UInt128."
+ "'silu' does not support scalar type Int128."
+ "'silu' does not support scalar type UInt128."
+ "'sin' does not support scalar type Int128."
+ "'sin' does not support scalar type UInt128."
+ "'sqrt' does not support scalar type Int128."
+ "'sqrt' does not support scalar type UInt128."
+ "'tan' does not support scalar type Int128."
+ "'tan' does not support scalar type UInt128."
+ "'tanh' does not support scalar type Int128."
+ "'tanh' does not support scalar type UInt128."
+ ") for gather axis dimension."
+ ": corrupt descriptor — negative shape dimension in "
+ "BLAS CGEMM received an empty buffer"
+ "CoreAIRuntime/BackportWrapper.swift"
+ "CoreAIRuntime/FastConv2DKernel+AccelerateBackend.swift"
+ "CoreAIRuntime/GetShapeKernel.swift"
+ "CoreAIRuntime/OwnedOperands.swift"
+ "CoreAIRuntime/TypeInferenceResult.swift"
+ "Expected first input to be a tensor type or tensor value."
+ "Expected first input to be a tensor type."
+ "InOut output at index "
+ "Intermediate metadata for "
+ "Loading function '"
+ "Output at index "
+ "OwnedOutputTypes returned "
+ "OwnedOutputs.setValue expected an ndArray value"
+ "Scale dimensions must be positive."
+ "Sub-byte reverse requires contiguous input and output."
+ "Type inference gave operand kind mismatched with expected output kind: inferred "
+ "Type inference must preserve rank: inferred "
+ "Unhandled ComputeStream.BackportHandle case — update this switch"
+ "com.apple.coreai"
+ "coreaix.copy_discarding_constraints"
+ "coreaix.copy_with_constraints"
+ "coreaix.view has non-tensor output"
+ "dilation values must be >= 1"
+ "inout output position "
+ "shape_1 and shape_2 must share the same scalar type, got "
+ "stride values must be >= 1"
+ "unknown ComputeStream.BackportHandle case"
+ "unknown ODIE.Intent case"
+ "unknown ODIE.OwnedAttribute case"
- "%s"
- "'pow' does not support scalar type Float4<E2M1FNSpec>."
- "'sigmoid' does not support scalar type Int16."
- "'sigmoid' does not support scalar type Int32."
- "'sigmoid' does not support scalar type Int64."
- "'sigmoid' does not support scalar type Int8."
- "'sigmoid' does not support scalar type UInt16."
- "'sigmoid' does not support scalar type UInt32."
- "'sigmoid' does not support scalar type UInt64."
- "'sigmoid' does not support scalar type UInt8."
- "'sinh' does not support scalar type Int16."
- "'sinh' does not support scalar type Int32."
- "'sinh' does not support scalar type Int64."
- "'sinh' does not support scalar type Int8."
- "'sinh' does not support scalar type UInt16."
- "'sinh' does not support scalar type UInt32."
- "'sinh' does not support scalar type UInt64."
- "'sinh' does not support scalar type UInt8."
- ", path has a file."
- "Destination buffer overflow during element copy"
- "Expected fill value to be a scalar (rank 0), but got rank "
- "Expected fill value to be a scalar, but got rank "
- "Expected fill value to be available during type inference (param intent)."
- "Expected shape parameter to be int32 type."
- "Failed to create directory at "
- "Failed to create directory: "
- "Failed to write buffer to path "
- "Source buffer overflow during element copy"
- "Type Float4<E2M1FNSpec> does not match scalar type "
- "Type Int128 does not match scalar type "
- "Type UInt128 does not match scalar type "
- "Unsupported intermediate."
- "coremlax.copy_discarding_constraints"
- "coremlax.copy_with_constraints"
- "coremlax.view has non-tensor output"
```
