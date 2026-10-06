## SiriActivationFoundation

> `/System/Library/PrivateFrameworks/SiriActivationFoundation.framework/SiriActivationFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38678` | `0x3ad7c` | **`+0x2704`** |
| `__AUTH_CONST.__const` | `0x2a60` | `0x2c08` | **`+0x1a8`** |
| `__TEXT.__eh_frame` | `0x1570` | `0x16d0` | **`+0x160`** |
| `__TEXT.__const` | `0x1f6c` | `0x204c` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x10d0` | `0x1190` | **`+0xc0`** |
| `__AUTH_CONST.__auth_got` | `0x898` | `0x950` | **`+0xb8`** |
| `__AUTH_CONST.__objc_const` | `0x5928` | `0x59e0` | **`+0xb8`** |
| `__DATA.__data` | `0x1298` | `0x1338` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x438b` | `0x442b` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x1586` | `0x1622` | **`+0x9c`** |
| `__TEXT.__constg_swiftt` | `0xbd0` | `0xc58` | **`+0x88`** |
| `__TEXT.__swift5_capture` | `0x864` | `0x8e8` | **`+0x84`** |
| `__DATA.__bss` | `0x1320` | `0x13a0` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x3ac0` | `0x3b20` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x868` | `0x8a8` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x6d8` | `0x718` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x6d4` | `0x714` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x27bc` | `0x27ec` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x10b0` | `0x10d0` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0xe8` | `0xfc` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x3e0` | `0x3f0` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0xdc` | `0xe8` | **`+0xc`** |
| `__DATA.__common` | `0x20` | `0x28` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x380` | `0x388` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x350` | `0x354` | **`+0x4`** |
| `__TEXT.__swift5_proto` | `0xd0` | `0xd4` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x94` | `0x98` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xbc` | `0xc0` | **`+0x4`** |

### Other Changes

```diff

-3600.49.31.1.6
+3600.55.10.0.0

-  Functions: 1855
-  Symbols:   2061
-  CStrings:  597
+  Functions: 1907
+  Symbols:   2086
+  CStrings:  602
Symbols:
+ -[SAFContextOverride deviceIsThermallyBlockedForSystemState:]
+ -[SAFContextOverride deviceIsThermallyBlocked]
+ -[SAFContextOverride overrideDeviceIsThermallyBlocked:]
+ -[SAFContextOverride setDeviceIsThermallyBlocked:]
+ _OBJC_IVAR_$_SAFContextOverride._deviceIsThermallyBlocked
+ __IVARS__TtC24SiriActivationFoundation23BroadcastingAsyncStream
+ ___unnamed_1
+ _swift_bridgeObjectRetain_n
+ _swift_defaultActor_deallocate
+ _swift_defaultActor_destroy
+ _swift_defaultActor_initialize
+ _swift_task_deinitOnExecutor
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
+ _symbolic BD
+ _symbolic SDy__________yx_GG 10Foundation4UUIDV ScS12ContinuationV
+ _symbolic _____ 24SiriActivationFoundation23BroadcastingAsyncStreamC
+ _symbolic ___________y______Gt 10Foundation4UUIDV ScS12ContinuationV 014SiriActivationA00D12AvailabilityO6StatusO
+ _symbolic _____y_____G 24SiriActivationFoundation23BroadcastingAsyncStreamC AA0A12AvailabilityO6StatusO
+ _symbolic _____y__________y______GG s18_DictionaryStorageC 10Foundation4UUIDV ScS12ContinuationV 014SiriActivationC00F12AvailabilityO6StatusO
+ _symbolic _____yxGSgXw 24SiriActivationFoundation23BroadcastingAsyncStreamC
+ _symbolic _____yxGSgXwz_x_lXX 24SiriActivationFoundation23BroadcastingAsyncStreamC
+ _symbolic _____yx__G ScS12ContinuationV15BufferingPolicyO
+ _symbolic ytSg
+ _symbolic ytSgIeAgHr_
CStrings:
+ "SAFRequestSourceMicButton"
+ "SAFRequestSourcePullDownGesture"
+ "SiriActivationFoundation/BroadcastingAsyncStream.swift"
+ "deviceIsThermallyBlocked"
+ "key value "
```
