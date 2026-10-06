## BiometricKitUI

> `/System/Library/PrivateFrameworks/BiometricKitUI.framework/BiometricKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6ef80` | `0x6ec9c` | **`-0x2e4`** |
| `__TEXT.__oslogstring` | `0x61e3` | `0x6253` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x10700` | `0x106a0` | **`-0x60`** |
| `__TEXT.__objc_methlist` | `0x72d0` | `0x72a0` | **`-0x30`** |
| `__TEXT.__gcc_except_tab` | `0xd5c` | `0xd34` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x4898` | `0x4880` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0x9f8` | `0x9f0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1a80` | `0x1a78` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-676.0.0.0.0
+678.0.0.0.0

-  Functions: 2857
-  Symbols:   4575
+  Functions: 2852
+  Symbols:   4567
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorI12InstanceInfoEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorI12InstanceInfoNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
- -[BKUIPeriocularEnableSplashViewController maxCellHeight]
- -[BKUIPeriocularEnableSplashViewController setMaxCellHeight:]
- -[BKUIPeriocularEnableSplashViewController setTraitChangeRegistration:]
- -[BKUIPeriocularEnableSplashViewController traitChangeRegistration]
- GCC_except_table9
- _OBJC_IVAR_$_BKUIPeriocularEnableSplashViewController._maxCellHeight
- _OBJC_IVAR_$_BKUIPeriocularEnableSplashViewController._traitChangeRegistration
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorI12InstanceInfoEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorI12InstanceInfoNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- ___55-[BKUIPeriocularEnableSplashViewController viewDidLoad]_block_invoke
CStrings:
+ "BKUIPearl: navigateToMidFlowPeriocularSplash aborted; container is no longer in a window (enrollment likely cancelled)."
- "+"
```
