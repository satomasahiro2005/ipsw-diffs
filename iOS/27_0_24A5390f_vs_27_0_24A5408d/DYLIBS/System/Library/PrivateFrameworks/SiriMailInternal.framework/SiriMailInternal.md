## SiriMailInternal

> `/System/Library/PrivateFrameworks/SiriMailInternal.framework/SiriMailInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfc830` | `0xfefa0` | **`+0x2770`** |
| `__TEXT.__eh_frame` | `0x6e78` | `0x70e0` | **`+0x268`** |
| `__TEXT.__const` | `0x8f78` | `0x90c8` | **`+0x150`** |
| `__TEXT.__unwind_info` | `0x2f00` | `0x2f88` | **`+0x88`** |
| `__AUTH_CONST.__auth_got` | `0x2448` | `0x2480` | **`+0x38`** |
| `__DATA.__bss` | `0x5fd0` | `0x6000` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x3870` | `0x3898` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x480` | `0x4a4` | **`+0x24`** |
| `__TEXT.__oslogstring` | `0x6f47` | `0x6f67` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x3ff0` | `0x400e` | **`+0x1e`** |
| `__TEXT.__swift_as_ret` | `0x474` | `0x490` | **`+0x1c`** |
| `__AUTH.__data` | `0x3288` | `0x32a0` | **`+0x18`** |
| `__DATA.__data` | `0x2490` | `0x24a8` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0xbb0` | `0xbc4` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x3b8` | `0x3c4` | **`+0xc`** |
| `__TEXT.__constg_swiftt` | `0x2590` | `0x2598` | **`+0x8`** |

### Other Changes

```diff

-3600.23.14.0.0
+3600.23.24.0.0

+  - /System/Library/PrivateFrameworks/ToolKit.framework/ToolKit

-  Functions: 5325
-  Symbols:   1633
-  CStrings:  571
+  Functions: 5377
+  Symbols:   1637
+  CStrings:  572
Symbols:
+ _OUTLINED_FUNCTION_203
+ _symbolic _____Sg 7ToolKit14TypeIdentifierO
+ _symbolic _____Sg 7ToolKit24EntityInstanceIdentifierO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10AppIntents10IntentFileV
CStrings:
+ "#ReplyMailSceneHostPlan confirmed via voice, sending reply now"
+ "#performSendViaIntent resolved SendMailIntent %{private}s"
- "#ReplyMailSceneHostPlan confirmed via voice, updating state to .sent and isConfirmed to true"
```
