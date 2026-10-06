## PencilFeedback

> `/System/Library/PrivateFrameworks/PencilFeedback.framework/PencilFeedback`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7c48` | `0x7c98` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x4c4` | `0x4cc` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3b8` | `0x3c0` | **`+0x8`** |

### Other Changes

```diff

-9.0.0.0.0
+10.0.0.0.0
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt12out_of_rangeC1B9fqe220106EPKc
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorI12PFInputPointEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIfEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__120__throw_out_of_rangeB9fqe220106EPKc
+ __ZNSt3__16vectorI12PFInputPointNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_out_of_rangeB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt12out_of_rangeC1B9fqe220100EPKc
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorI12PFInputPointEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIfEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__120__throw_out_of_rangeB9fqe220100EPKc
- __ZNSt3__16vectorI12PFInputPointNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_out_of_rangeB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
Functions:
~ __ZL18__RenderWhiteNoisePvPjPK14AudioTimeStampjjP15AudioBufferList : 620 -> 632
~ -[PFPencilSoundManager updateGeneratorWithVelocity:force:tool:direction:altitudeNorm:roll:panH:panV:] : 868 -> 892
~ -[PFPencilSoundManager computeSmoothedVelocity] : 136 -> 156
~ -[PFPencilSoundManager computeSmoothedForce] : 84 -> 92
~ -[PFPencilSoundManager computeSmoothedDeltaRoll] : 244 -> 268
~ __ZNSt3__16vectorIfNS_9allocatorIfEEE6resizeEmRKf : 308 -> 300
```
