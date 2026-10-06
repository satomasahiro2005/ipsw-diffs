## PeriodicSystemMetricsCore

> `/System/Library/PrivateFrameworks/PeriodicSystemMetricsCore.framework/PeriodicSystemMetricsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfdc4` | `0xfd70` | **`-0x54`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_selrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff
Symbols:
+ _OUTLINED_FUNCTION_11
+ __ZNKSt9type_infoeqB9fqe220106ERKS_
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__110__function12__value_funcIFN5apple4aiml12flatbuffers26OffsetIvEEmEED2B9fqe220106Ev
+ __ZNSt3__110__function12__value_funcIFvmPN14PSMHighCadence13LostPerfEntryEEED2B9fqe220106Ev
+ __ZNSt3__110__function12__value_funcIFvmPN14PSMHighCadence8QoSEntryEEED2B9fqe220106Ev
+ __ZNSt3__110__function12__value_funcIFvmPN16PSMMediumCadence17GpuPerfStateEntryEEED2B9fqe220106Ev
+ __ZNSt3__110__function12__value_funcIFvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEED2B9fqe220106Ev
+ __ZNSt3__110__function12__value_funcIFvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEED2B9fqe220106Ev
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIN5apple4aiml12flatbuffers26OffsetIvEEEENS_16allocator_traitsIS7_EEEENS_19__allocation_resultINT0_7pointerENSB_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__125__throw_bad_function_callB9fqe220106Ev
+ __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetIvEENS_9allocatorIS5_EEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetIvEENS_9allocatorIS5_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetIvEENS_9allocatorIS5_EEEC2B9fqe220106Em
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
- _OUTLINED_FUNCTION_13
- __ZNKSt9type_infoeqB9fqe220100ERKS_
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__110__function12__value_funcIFN5apple4aiml12flatbuffers26OffsetIvEEmEED2B9fqe220100Ev
- __ZNSt3__110__function12__value_funcIFvmPN14PSMHighCadence13LostPerfEntryEEED2B9fqe220100Ev
- __ZNSt3__110__function12__value_funcIFvmPN14PSMHighCadence8QoSEntryEEED2B9fqe220100Ev
- __ZNSt3__110__function12__value_funcIFvmPN16PSMMediumCadence17GpuPerfStateEntryEEED2B9fqe220100Ev
- __ZNSt3__110__function12__value_funcIFvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEED2B9fqe220100Ev
- __ZNSt3__110__function12__value_funcIFvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEED2B9fqe220100Ev
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIN5apple4aiml12flatbuffers26OffsetIvEEEENS_16allocator_traitsIS7_EEEENS_19__allocation_resultINT0_7pointerENSB_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__125__throw_bad_function_callB9fqe220100Ev
- __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetIvEENS_9allocatorIS5_EEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetIvEENS_9allocatorIS5_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetIvEENS_9allocatorIS5_EEEC2B9fqe220100Em
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
Functions:
~ __ZN5apple4aiml12flatbuffers217FlatBufferBuilder12CreateVectorINS1_6OffsetIvEEEENS4_INS1_6VectorIT_EEEEmRKNSt3__18functionIFS7_mEEE : 220 -> 216
~ -[PSMHighCadenceBuffer hash] : 380 -> 364
~ -[PSMHighCadenceBuffer isEqual:] : 708 -> 684
~ __ZN5apple4aiml12flatbuffers215vector_downward4fillEm : 88 -> 84
~ __ZN5apple4aiml12flatbuffers217FlatBufferBuilder12CreateVectorIvEENS1_6OffsetINS1_6VectorINS4_IT_EEEEEEPKS7_m : 136 -> 124
~ ____ioReportInit_block_invoke : 520 -> 516
~ -[PSMHighCadenceBuffer isEqual:].cold.1 : 140 -> 132
~ -[_PSMStateResidency initWithState:startingIndex:] : 232 -> 228
~ -[_PSMCLPCPackageStats _reset] : 272 -> 268
~ -[_PSMCLPCPackageStats bufferWithBuilder:] : 1072 -> 1068
```
