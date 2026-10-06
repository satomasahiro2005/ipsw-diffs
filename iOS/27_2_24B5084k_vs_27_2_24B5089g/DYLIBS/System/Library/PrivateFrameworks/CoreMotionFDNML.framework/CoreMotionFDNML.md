## CoreMotionFDNML

> `/System/Library/PrivateFrameworks/CoreMotionFDNML.framework/CoreMotionFDNML`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cd14` | `0x1c9b4` | **`-0x360`** |
| `__AUTH_CONST.__auth_got` | `0x848` | `0x7f8` | **`-0x50`** |
| `__TEXT.__gcc_except_tab` | `0xfc8` | `0x100c` | **`+0x44`** |
| `__DATA.__data` | `0x270` | `0x238` | **`-0x38`** |
| `__AUTH_CONST.__const` | `0xbc0` | `0xb90` | **`-0x30`** |
| `__TEXT.__const` | `0x11f8` | `0x11d8` | **`-0x20`** |
| `__TEXT.__eh_frame` | `0x1ca0` | `0x1c80` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0x32c` | `0x318` | **`-0x14`** |
| `__DATA.__bss` | `0x1390` | `0x1380` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x248` | `0x240` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x12d0` | `0x12c8` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-26.0.0.0.0
+27.0.0.0.0

-  Functions: 909
-  Symbols:   581
-  CStrings:  52
+  Functions: 902
+  Symbols:   577
+  CStrings:  53
Symbols:
+ GCC_except_table15
+ GCC_except_table26
+ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE16__init_with_sizeB9fqe220106IPKS6_SB_EEvT_T0_m
+ ___block_descriptor_72_ea8_40c79_ZTSNSt3__18functionIFvNS_10shared_ptrIKN6motion2fm20ModelManagerResponseEEEEEE_e58_v16?0"_TtC15CoreMotionFDNML25CMFoundationModelResponse"8l
- _OBJC_CLASS_$_OS_dispatch_queue
- ___block_descriptor_72_ea8_32s40c79_ZTSNSt3__18functionIFvNS_10shared_ptrIKN6motion2fm20ModelManagerResponseEEEEEE_e58_v16?0"_TtC15CoreMotionFDNML25CMFoundationModelResponse"8l
- _block_copy_helper
- _block_descriptor
- _block_destroy_helper
- _swift_retain_x2
- _symbolic Say_____G 8Dispatch0A13WorkItemFlagsV
- _symbolic Say_____G So17OS_dispatch_queueC8DispatchE10AttributesV
CStrings:
+ "com.apple.coremotion.crashdetection"
+ "com.apple.fm.motionanomalyfm.adapter"
- "com.apple.coremotion.foundationmodel.client.release"
```
