## CalendarFoundation

> `/System/Library/PrivateFrameworks/CalendarFoundation.framework/CalendarFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5e750` | `0x62a30` | **`+0x42e0`** |
| `__AUTH_CONST.__const` | `0xe28` | `0x1058` | **`+0x230`** |
| `__TEXT.__eh_frame` | `—` | `0x130` | **`+0x130`** |
| `__TEXT.__swift5_capture` | `0x38` | `0xfc` | **`+0xc4`** |
| `__TEXT.__unwind_info` | `0x1b70` | `0x1c28` | **`+0xb8`** |
| `__AUTH_CONST.__objc_const` | `0x7918` | `0x79b0` | **`+0x98`** |
| `__TEXT.__swift5_typeref` | `0x172` | `0x1f8` | **`+0x86`** |
| `__AUTH_CONST.__auth_got` | `0xbb0` | `0xc28` | **`+0x78`** |
| `__DATA_CONST.__const` | `0x1710` | `0x1788` | **`+0x78`** |
| `__AUTH.__objc_data` | `0x1278` | `0x12c8` | **`+0x50`** |
| `__TEXT.__cstring` | `0x6572` | `0x65b2` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x5d44` | `0x5d7c` | **`+0x38`** |
| `__TEXT.__const` | `0x564` | `0x594` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x38ac` | `0x38d5` | **`+0x29`** |
| `__DATA_CONST.__objc_selrefs` | `0x4180` | `0x41a8` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x8d8` | `0x8f0` | **`+0x18`** |
| `__DATA.__data` | `0xb40` | `0xb48` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x350` | `0x358` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `—` | `0x8` | **`+0x8`** |

### Other Changes

```diff

-1634.0.0.0.0
+1636.0.0.0.0

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 2619
-  Symbols:   4403
-  CStrings:  1557
+  Functions: 2679
+  Symbols:   4443
+  CStrings:  1560
Symbols:
+ +[CalBlockListFilter filterUnblockedResults:usingBlockList:emailForResult:phoneForResult:completionQueue:completion:]
+ _OBJC_CLASS_$_CalBlockListFilter
+ _OBJC_CLASS_$_NSMutableIndexSet
+ _OBJC_METACLASS_$_CalBlockListFilter
+ __OBJC_$_CLASS_METHODS_CalBlockListFilter
+ __OBJC_CLASS_RO_$_CalBlockListFilter
+ __OBJC_METACLASS_RO_$_CalBlockListFilter
+ ___117+[CalBlockListFilter filterUnblockedResults:usingBlockList:emailForResult:phoneForResult:completionQueue:completion:]_block_invoke
+ ___117+[CalBlockListFilter filterUnblockedResults:usingBlockList:emailForResult:phoneForResult:completionQueue:completion:]_block_invoke_2
+ ___117+[CalBlockListFilter filterUnblockedResults:usingBlockList:emailForResult:phoneForResult:completionQueue:completion:]_block_invoke_3
+ ___117+[CalBlockListFilter filterUnblockedResults:usingBlockList:emailForResult:phoneForResult:completionQueue:completion:]_block_invoke_4
+ ___117+[CalBlockListFilter filterUnblockedResults:usingBlockList:emailForResult:phoneForResult:completionQueue:completion:]_block_invoke_5
+ ___block_descriptor_48_e8_32s40s_e12_v24?0Q8^B16ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e47_v32?0"NSIndexSet"8"NSIndexSet"16"NSError"24ls32l8s40l8s48l8s56l8
+ ___block_descriptor_80_e8_32s40s48s56s64bs72bs_e15_v32?08Q16^B24ls64l8s32l8s40l8s72l8s48l8s56l8
+ ___swift_async_cont_functlets
+ ___swift_async_entry_functlets
+ ___swift_async_ret_functlets
+ _swift_release_x22
+ _swift_release_x25
+ _swift_retain_x24
+ _swift_retain_x25
+ _swift_retain_x28
+ _swift_retain_x8
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_switch
+ _swift_unknownObjectRelease
+ _symbolic SaySSGSg
+ _symbolic ScA_pSg
+ _symbolic ScPSg
+ _symbolic Shy_____G 20LiveCommunicationKit6HandleV
+ _symbolic So17OS_dispatch_queueC
+ _symbolic _____ 18CommunicationTrust9BlockListC
+ _symbolic _____SgAB______pSgIeghnng_ 10Foundation8IndexSetV s5ErrorP
+ _symbolic ______p s5ErrorP
+ _symbolic ______pSg s5ErrorP
+ _symbolic _____y_____G s11_SetStorageC 20LiveCommunicationKit6HandleV
+ _symbolic ytIeAgHr_
CStrings:
+ "Failed to look up blocked handles %@"
+ "v24@?0Q8^B16"
+ "v32@?0@\"NSIndexSet\"8@\"NSIndexSet\"16@\"NSError\"24"
```
