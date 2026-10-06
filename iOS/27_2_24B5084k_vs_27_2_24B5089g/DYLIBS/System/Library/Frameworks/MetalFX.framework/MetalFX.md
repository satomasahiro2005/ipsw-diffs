## MetalFX

> `/System/Library/Frameworks/MetalFX.framework/MetalFX`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `—` | `0x8a0` | **`+0x8a0`** |
| `__TEXT.__text` | `0x7f5f4` | `0x7fe2c` | **`+0x838`** |
| `__DATA.__data` | `0x8a0` | `0xc0` | **`-0x7e0`** |
| `__AUTH.__objc_data` | `0x1e0` | `—` | **`-0x1e0`** |
| `__DATA_DIRTY.__objc_data` | `0xc80` | `0xe60` | **`+0x1e0`** |
| `__AUTH_CONST.__objc_const` | `0xefd0` | `0xf198` | **`+0x1c8`** |
| `__TEXT.__objc_methlist` | `0x55f4` | `0x56dc` | **`+0xe8`** |
| `__TEXT.__gcc_except_tab` | `0xc170` | `0xc248` | **`+0xd8`** |
| `__TEXT.__unwind_info` | `0x1750` | `0x17a8` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x13e8` | `0x1408` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0xb8` | `0xc8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x10c8` | `0x10d0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x2b8` | `0x2c0` | **`+0x8`** |

### Other Changes

```diff

-40.8.0.0.0
+40.9.0.0.0

-  Functions: 1893
-  Symbols:   3631
+  Functions: 1902
+  Symbols:   3657
Symbols:
+ -[_M4FXTemporalScalingEffectBBR _didCreateComputeCommandEncoder:forEncode:]
+ -[_M4FXTemporalScalingEffectBBR _didCreateRenderCommandEncoder:forEncode:]
+ -[_M4FXTemporalScalingEffectBBR setTracingDelegate:]
+ -[_M4FXTemporalScalingEffectBBR tracingDelegate]
+ -[_MFXTemporalScalingEffectBBR _didCreateBlitCommandEncoder:forEncode:]
+ -[_MFXTemporalScalingEffectBBR _didCreateComputeCommandEncoder:forEncode:]
+ -[_MFXTemporalScalingEffectBBR _didCreateRenderCommandEncoder:forEncode:]
+ -[_MFXTemporalScalingEffectBBR setTracingDelegate:]
+ -[_MFXTemporalScalingEffectBBR tracingDelegate]
+ _OBJC_CLASS_$_MTL4PipelineOptions
+ _OBJC_IVAR_$__M4FXTemporalScalingEffectBBR._tracingDelegate
+ _OBJC_IVAR_$__MFXTemporalScalingEffectBBR._tracingDelegate
+ __OBJC_$_PROP_LIST_MTL4FXEffectTracing
+ __OBJC_$_PROP_LIST_MTLFXEffectTracing
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MTL4FXEffectTracing
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MTLFXEffectTracing
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MTL4FXEffectTracing
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MTLFXEffectTracing
+ __OBJC_$_PROTOCOL_REFS_MTL4FXEffectTracing
+ __OBJC_$_PROTOCOL_REFS_MTLFXEffectTracing
+ __OBJC_CLASS_PROTOCOLS_$__MTL4FXEffect
+ __OBJC_CLASS_PROTOCOLS_$__MTLFXEffect
+ __OBJC_LABEL_PROTOCOL_$_MTL4FXEffectTracing
+ __OBJC_LABEL_PROTOCOL_$_MTLFXEffectTracing
+ __OBJC_PROTOCOL_$_MTL4FXEffectTracing
+ __OBJC_PROTOCOL_$_MTLFXEffectTracing
+ __ZN10MFXDevice321createComputePipelineEPU21objcproto10MTLLibrary11objc_objectP8NSStringP25MTLFunctionConstantValuesj
+ __ZN10MFXDevice421createComputePipelineEPU21objcproto10MTLLibrary11objc_objectP8NSStringP25MTLFunctionConstantValuesj
- __ZN10MFXDevice321createComputePipelineEPU21objcproto10MTLLibrary11objc_objectP8NSStringP25MTLFunctionConstantValues
- __ZN10MFXDevice421createComputePipelineEPU21objcproto10MTLLibrary11objc_objectP8NSStringP25MTLFunctionConstantValues
```
