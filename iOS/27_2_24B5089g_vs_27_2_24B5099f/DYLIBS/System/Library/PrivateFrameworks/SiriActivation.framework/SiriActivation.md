## SiriActivation

> `/System/Library/PrivateFrameworks/SiriActivation.framework/SiriActivation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x762dc` | `0x76d6c` | **`+0xa90`** |
| `__TEXT.__cstring` | `0xcf62` | `0xd0d2` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x9ae4` | `0x9bc3` | **`+0xdf`** |
| `__TEXT.__objc_methlist` | `0x7254` | `0x72dc` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0x35f8` | `0x3658` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x18c0` | `0x1910` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1f10` | `0x1f60` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0xb5f8` | `0xb640` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0xcec` | `0xd00` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0xbe8` | `0xbf0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x748` | `0x750` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x2d8` | `0x2e0` | **`+0x8`** |

### Other Changes

```diff

-3605.24.1.0.0
+3605.30.1.0.0

-  Functions: 2971
-  Symbols:   4743
-  CStrings:  1856
+  Functions: 2988
+  Symbols:   4764
+  CStrings:  1867
Symbols:
+ -[SASActivationRequest isAutoPromptRequest]
+ -[SASHeater _replacePreheatBlock:]
+ -[SASHeater _scheduleBlockAfterTimeInterval:]
+ -[SASHeater init]
+ -[SASHeater preheatQueue]
+ -[SASHeater prepareForUseAfterTimeInterval:buttonDownTimestamp:]
+ -[SASHeater setPreheatQueue:]
+ -[SASMyriadController _goodnessScoreContextWithTimerFiring:alarmFiring:]
+ -[SASMyriadController _primeMTAlarmManagerState]
+ -[SASMyriadController _primeMTTimerManagerState]
+ -[SASMyriadController _runOnMyriadWorkQueueWithSelf:]
+ -[SASSignalServer prewarmFromButtonIdentifier:longPressInterval:buttonDownTimestamp:]
+ -[SiriActivationService prewarmFromButtonIdentifier:longPressInterval:buttonDownTimestamp:]
+ GCC_except_table106
+ GCC_except_table112
+ GCC_except_table163
+ GCC_except_table33
+ GCC_except_table38
+ GCC_except_table43
+ GCC_except_table44
+ GCC_except_table49
+ GCC_except_table56
+ GCC_except_table84
+ _OBJC_IVAR_$_SASHeater._lock
+ _OBJC_IVAR_$_SASHeater._preheatBlock
+ _OBJC_IVAR_$_SASHeater._preheatQueue
+ ___45-[SASHeater _scheduleBlockAfterTimeInterval:]_block_invoke
+ ___45-[SASHeater _scheduleBlockAfterTimeInterval:]_block_invoke_2
+ ___48-[SASMyriadController _primeMTAlarmManagerState]_block_invoke
+ ___48-[SASMyriadController _primeMTAlarmManagerState]_block_invoke_2
+ ___48-[SASMyriadController _primeMTTimerManagerState]_block_invoke
+ ___48-[SASMyriadController _primeMTTimerManagerState]_block_invoke_2
+ ___53-[SASMyriadController _runOnMyriadWorkQueueWithSelf:]_block_invoke
+ ___block_descriptor_40_e8_32s_e29_v16?0"SASMyriadController"8ls32l8
+ ___block_descriptor_40_e8_32w_e17_v16?0"NSArray"8lw32l8
+ _dispatch_block_cancel
- -[SASHeater preheatTimer]
- -[SASHeater setPreheatTimer:]
- GCC_except_table105
- GCC_except_table110
- GCC_except_table162
- GCC_except_table26
- GCC_except_table31
- GCC_except_table34
- GCC_except_table39
- GCC_except_table40
- GCC_except_table47
- GCC_except_table83
- _OBJC_IVAR_$_SASHeater._preheatTimer
- ___31-[SASHeater _cancelPreparation]_block_invoke
- ___44-[SASHeater prepareForUseAfterTimeInterval:]_block_invoke
CStrings:
+ "%s #myriad priming MTAlarmManager: %lu alarm(s)"
+ "%s #myriad priming MTTimerManager: %lu timer(s)"
+ "%s #myriad unenumerated siriContext type: %@, resolved speechRequestOptions generically"
+ "%s Scheduling preheat for %fs from now"
+ "-[SASHeater prepareForUseAfterTimeInterval:buttonDownTimestamp:]"
+ "-[SASMyriadController _primeMTAlarmManagerState]_block_invoke_2"
+ "-[SASMyriadController _primeMTTimerManagerState]_block_invoke_2"
+ "-[SASSignalServer prewarmFromButtonIdentifier:longPressInterval:buttonDownTimestamp:]"
+ "-[SiriActivationService prewarmFromButtonIdentifier:longPressInterval:buttonDownTimestamp:]"
+ "com.apple.siri.SASHeater.preheat"
+ "v16@?0@\"NSArray\"8"
+ "v16@?0@\"SASMyriadController\"8"
- "-[SiriActivationService prewarmFromButtonIdentifier:longPressInterval:]"
```
