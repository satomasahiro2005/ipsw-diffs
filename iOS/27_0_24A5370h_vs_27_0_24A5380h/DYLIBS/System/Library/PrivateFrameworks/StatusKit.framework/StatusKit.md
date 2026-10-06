## StatusKit

> `/System/Library/PrivateFrameworks/StatusKit.framework/StatusKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x48` | `0x460` | **`+0x418`** |
| `__DATA_DIRTY.__objc_data` | `0xd00` | `0x8e8` | **`-0x418`** |
| `__TEXT.__text` | `0x4583c` | `0x45974` | **`+0x138`** |
| `__TEXT.__oslogstring` | `0x5329` | `0x5419` | **`+0xf0`** |
| `__TEXT.__gcc_except_tab` | `0x884` | `0x8b8` | **`+0x34`** |
| `__TEXT.__cstring` | `0x1d3e` | `0x1d6e` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xa08` | `0x9e0` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0x11e0` | `0x1200` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x3a0` | `0x390` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0xae8` | `0xaf0` | **`+0x8`** |
| `__TEXT.__const` | `0x1920` | `0x1918` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1550` | `0x1558` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x7f6` | `0x7f0` | **`-0x6`** |
| `__TEXT.__swift_as_cont` | `0x174` | `0x170` | **`-0x4`** |

### Other Changes

```diff

-147.100.1.0.0
+149.100.1.0.0

-  Functions: 1704
-  Symbols:   3462
-  CStrings:  539
+  Functions: 1705
+  Symbols:   3458
+  CStrings:  541
Symbols:
+ _$s9StatusKit12SKAsyncQueueC4name14loggingEnabled9isolationACSS_SbScA_pSgYitcfcyyYacfU_yyYaXEfU_TQ0_
+ _$s9StatusKit12SKAsyncQueueC4name14loggingEnabled9isolationACSS_SbScA_pSgYitcfcyyYacfU_yyYaXEfU_TQ2_
+ _$s9StatusKit12SKAsyncQueueC4name14loggingEnabled9isolationACSS_SbScA_pSgYitcfcyyYacfU_yyYaXEfU_TY1_
+ _$s9StatusKit12SKAsyncQueueC4name14loggingEnabled9isolationACSS_SbScA_pSgYitcfcyyYacfU_yyYaXEfU_TY3_
+ _OUTLINED_FUNCTION_8
+ _OUTLINED_FUNCTION_9
+ ___block_descriptor_64_e8_32s40s48s56bs_e17_v16?0"NSError"8ls32l8s40l8s56l8s48l8
+ ___block_descriptor_72_e8_32s40s48s56bs64w_e17_v16?0"NSError"8ls32l8s56l8s40l8s48l8w64l8
+ ___block_descriptor_88_e8_32s40s48s56s64s72bs80w_e17_v16?0"NSError"8ls32l8w80l8s40l8s48l8s56l8s64l8s72l8
+ ___swift_closure_destructor.31Tm
+ _swift_task_localValuePop
+ _swift_task_localValuePush
- _$s15Synchronization5MutexVy9StatusKit21SKPresenceXPCListenerC5StateVGMR
- _$s15Synchronization5MutexVy9StatusKit21SKPresenceXPCListenerC5StateVGMd
- _$s9StatusKit12SKAsyncQueueC4name14loggingEnabled9isolationACSS_SbScA_pSgYitcfcyyYacfU_yyYaXEfU_TQ1_
- _$s9StatusKit12SKAsyncQueueC4name14loggingEnabled9isolationACSS_SbScA_pSgYitcfcyyYacfU_yyYaXEfU_TQ3_
- _$s9StatusKit12SKAsyncQueueC4name14loggingEnabled9isolationACSS_SbScA_pSgYitcfcyyYacfU_yyYaXEfU_TY0_
- _$s9StatusKit12SKAsyncQueueC4name14loggingEnabled9isolationACSS_SbScA_pSgYitcfcyyYacfU_yyYaXEfU_TY2_
- _$s9StatusKit12SKAsyncQueueC4name14loggingEnabled9isolationACSS_SbScA_pSgYitcfcyyYacfU_yyYaXEfU_TY4_
- _$ss9TaskLocalC9withValue_9operation9isolation4file4lineqd__x_qd__yYaKXEScA_pSgYiSSSutYaKlF
- _$ss9TaskLocalC9withValue_9operation9isolation4file4lineqd__x_qd__yYaKXEScA_pSgYiSSSutYaKlFTu
- ___block_descriptor_64_e8_32s40s48s56bs_e17_v16?0"NSError"8ls32l8s56l8s40l8s48l8
- ___block_descriptor_72_e8_32s40s48s56bs64w_e17_v16?0"NSError"8ls32l8w64l8s40l8s48l8s56l8
- ___block_descriptor_80_e8_32s40s48s56s64bs72w_e17_v16?0"NSError"8ls32l8s64l8s40l8s48l8w72l8s56l8
- ___block_descriptor_96_e8_32s40s48s56s64s72s80bs88w_e17_v16?0"NSError"8ls32l8w88l8s40l8s48l8s56l8s64l8s72l8s80l8
- ___swift_closure_destructor.32Tm
- _get_type_metadata 15Synchronization5MutexVy9StatusKit21SKPresenceXPCListenerC5StateVG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "Attempted to set persistent payload on channel %@ that is not equivalent to active channel: %@. Please use the rollToChannel API to change channels."
+ "Attempted to set persistent payload on channel that is not equivalent to active channel"
+ "Idle exit is enabled, skipping presenceDaemonDisconnected delegate callback and reconnect"
- "StatusKit/SKAsyncQueue.swift"
```
