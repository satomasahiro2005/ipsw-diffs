## ODIE

> `/System/Library/PrivateFrameworks/ODIE.framework/ODIE`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f5190` | `0x3decb0` | **`-0x164e0`** |
| `__TEXT.__eh_frame` | `0x19600` | `0x19960` | **`+0x360`** |
| `__TEXT.__cstring` | `0xb36e` | `0xb17e` | **`-0x1f0`** |
| `__TEXT.__const` | `0x112f4` | `0x11494` | **`+0x1a0`** |
| `__TEXT.__unwind_info` | `0x8070` | `0x8178` | **`+0x108`** |
| `__AUTH_CONST.__const` | `0xd460` | `0xd540` | **`+0xe0`** |
| `__DATA_DIRTY.__data` | `0x2718` | `0x2678` | **`-0xa0`** |
| `__AUTH.__data` | `0x7c0` | `0x848` | **`+0x88`** |
| `__DATA.__bss` | `0xc480` | `0xc500` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x3a98` | `0x3b14` | **`+0x7c`** |
| `__TEXT.__swift5_reflstr` | `0x2bde` | `0x2c31` | **`+0x53`** |
| `__TEXT.__swift5_fieldmd` | `0x47d0` | `0x4810` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x4394` | `0x43c8` | **`+0x34`** |
| `__TEXT.__swift5_capture` | `0x9e4` | `0x9b4` | **`-0x30`** |
| `__DATA.__data` | `0x251c` | `0x2534` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x320` | `0x334` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x1300` | `0x1310` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x62` | `0x6a` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x190` | `0x198` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x9c4` | `0x9c8` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x5a4` | `0x5a8` | **`+0x4`** |

### Other Changes

```diff

-3600.67.4.0.0
+3600.73.1.0.0

-  Functions: 10475
-  Symbols:   301
-  CStrings:  1004
+  Functions: 10433
+  Symbols:   302
+  CStrings:  995
Symbols:
+ _objc_retain_x9
+ _swift_release_x12
- _madvise
CStrings:
+ " enable-encoding-functions=false"
+ " has a dimension outside the ui32 range."
+ " is not allocated (return intent?)."
+ " is not allocated."
+ " out of range for operandIndices (count="
+ "%{public}s"
+ "Encoding functions are no longer supported in the ODIE framework. Please transition your application to the CoreAI framework to continue using this feature."
+ "Expected first input to be a tensor type or tensor value."
+ "Expected output to have shape ["
+ "No operand bound for dynamic inout output at index "
+ "ODIE/OwnedOperands.swift"
+ "ODIE/Procedure+Binding.swift"
+ "ODIE/TypeInferenceResult.swift"
+ "Output at index "
+ "coreai.get_shape: corrupt descriptor — negative shape dimension."
+ "coreaix.constexpr_lut_to_dense"
+ "coreaix.constexpr_sparse_to_dense"
+ "coreaix.copy_discarding_constraints"
+ "coreaix.copy_with_constraints"
+ "coreaix.dequantize"
+ "coreaix.quantize"
+ "coreaix.view has non-tensor output"
+ "default"
+ "inout output position "
- " enable-encoding-functions="
- "%s"
- "ODIE/MemberFunction+Binding.swift"
- "Type BFloat16 does not match scalar type "
- "Type Bool does not match scalar type "
- "Type Complex<Double> does not match scalar type "
- "Type Complex<Float16> does not match scalar type "
- "Type Complex<Float> does not match scalar type "
- "Type Double does not match scalar type "
- "Type Float does not match scalar type "
- "Type Float16 does not match scalar type "
- "Type Float4<E2M1FNSpec> does not match scalar type "
- "Type Float8<E4M3FNSpec> does not match scalar type "
- "Type Float8<E5M2Spec> does not match scalar type "
- "Type Float8<E8M0FNSpec> does not match scalar type "
- "Type Int128 does not match scalar type "
- "Type Int16 does not match scalar type "
- "Type Int32 does not match scalar type "
- "Type Int64 does not match scalar type "
- "Type Int8 does not match scalar type "
- "Type UInt128 does not match scalar type "
- "Type UInt16 does not match scalar type "
- "Type UInt32 does not match scalar type "
- "Type UInt64 does not match scalar type "
- "Type UInt8 does not match scalar type "
- "coreai.get_shape expects the output to have shape ["
- "coremlax.constexpr_lut_to_dense"
- "coremlax.constexpr_sparse_to_dense"
- "coremlax.copy_discarding_constraints"
- "coremlax.copy_with_constraints"
- "coremlax.dequantize"
- "coremlax.quantize"
- "coremlax.view has non-tensor output"
```
