## HMFoundation

> `/System/Library/PrivateFrameworks/HMFoundation.framework/HMFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x966cc` | `0x97cbc` | **`+0x15f0`** |
| `__AUTH_CONST.__objc_const` | `0xe4c8` | `0xe638` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x7ec5` | `0x801d` | **`+0x158`** |
| `__TEXT.__eh_frame` | `0x3130` | `0x3278` | **`+0x148`** |
| `__TEXT.__objc_methlist` | `0x78d4` | `0x7944` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x1568` | `0x15c8` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x3180` | `0x31e0` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x1b30` | `0x1b80` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x22e8` | `0x2338` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x1040` | `0x1090` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x64c` | `0x670` | **`+0x24`** |
| `__AUTH.__data` | `0x2f0` | `0x310` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0xdf0` | `0xe10` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1954` | `0x1970` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x1330` | `0x1348` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x30e8` | `0x3100` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x468` | `0x478` | **`+0x10`** |
| `__TEXT.__const` | `0x3018` | `0x3028` | **`+0x10`** |
| `__DATA.__data` | `0x27c4` | `0x27cc` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x380` | `0x388` | **`+0x8`** |
| `__DATA_DIRTY.__objc_ivar` | `0x59c` | `0x5a4` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x230` | `0x228` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x198` | `0x19c` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x1c0` | `0x1c4` | **`+0x4`** |

### Other Changes

```diff

-1479.0.0.1.0
+1484.2.0.0.0

-  Functions: 3640
-  Symbols:   5463
-  CStrings:  1411
+  Functions: 3657
+  Symbols:   5487
+  CStrings:  1415
Symbols:
+ -[HMFCoalescingTimer __fire]
+ -[HMFCoalescingTimer debounceInterval]
+ -[HMFCoalescingTimer initWithDebounceInterval:maximumInterval:options:]
+ -[HMFCoalescingTimer maximumInterval]
+ -[HMFCoalescingTimer nextFireInterval]
+ -[HMFCoalescingTimer resume]
+ -[HMFCoalescingTimer suspend]
+ -[HMFTimer nextFireInterval]
+ GCC_except_table41
+ GCC_except_table44
+ _HMFQualityOfServiceClassToString
+ _OBJC_CLASS_$_HMFCoalescingTimer
+ _OBJC_METACLASS_$_HMFCoalescingTimer
+ __DATA__TtCO12HMFoundation3HMF16AsyncSerialQueue
+ __IVARS__TtCO12HMFoundation3HMF16AsyncSerialQueue
+ __METACLASS_DATA__TtCO12HMFoundation3HMF16AsyncSerialQueue
+ __OBJC_$_INSTANCE_METHODS_HMFCoalescingTimer
+ __OBJC_$_INSTANCE_VARIABLES_HMFCoalescingTimer
+ __OBJC_$_PROP_LIST_HMFCoalescingTimer
+ __OBJC_CLASS_RO_$_HMFCoalescingTimer
+ __OBJC_METACLASS_RO_$_HMFCoalescingTimer
+ ___block_descriptor_56_e8_32s40s48s_e41_B32?0"<HMFMessageRegistration>"8Q16^B24ls32l8s40l8s48l8
+ _swift_release_x26
+ _swift_task_localValuePop
+ _swift_task_localValuePush
+ _swift_updateClassMetadata2
+ _symbolic ShySOG
+ _symbolic _____ 12HMFoundation3HMFO16AsyncSerialQueueC
- GCC_except_table18
- _get_type_metadata 15Synchronization5MutexVy12HMFoundation3HMFO11ManualClockC5State33_465D37F0B3FF74F1DA60984A81E9136ELLVG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _symbolic _____ 12HMFoundation3HMFO16AsyncSerialQueueV
CStrings:
+ "[%{public}@] [HMFCoalescingTimer] The debounce interval, %f, must be greater than 0"
+ "[%{public}@] [HMFCoalescingTimer] The maximum interval, %f, must be 0 or > the debounce interval, %f"
+ "[HMFCoalescingTimer] The debounce interval, %f, must be greater than 0"
+ "[HMFCoalescingTimer] The maximum interval, %f, must be 0 or > the debounce interval, %f"
```
