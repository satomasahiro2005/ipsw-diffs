## CoreCDPInternal

> `/System/Library/PrivateFrameworks/CoreCDPInternal.framework/CoreCDPInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8db84` | `0x8dbdc` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x567c` | `0x568c` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3900` | `0x3908` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1df0` | `0x1df8` | **`+0x8`** |

### Other Changes

```diff

-444.0.0.0.0
+445.0.0.0.0

-  Functions: 3157
-  Symbols:   4145
+  Functions: 3158
+  Symbols:   4146
Symbols:
+ -[CDPDStateMachine _handleSecureBackupEnablementDidEnable:error:circleJoinResult:completion:]
+ GCC_except_table121
+ ___block_descriptor_56_e8_32s40s48bs_e8_v12?0B8ls32l8s48l8s40l8
- GCC_except_table120
- ___block_descriptor_56_e8_32s40s48bs_e8_v12?0B8ls48l8s32l8s40l8
Functions:
~ -[CDPDStateMachine _enableSecureBackupWithJoinResult:completion:] : 412 -> 416
~ ___65-[CDPDStateMachine _enableSecureBackupWithJoinResult:completion:]_block_invoke : 304 -> 324
~ ___65-[CDPDStateMachine _enableSecureBackupWithJoinResult:completion:]_block_invoke.111 : 408 -> 24
+ -[CDPDStateMachine _handleSecureBackupEnablementDidEnable:error:circleJoinResult:completion:]
```
