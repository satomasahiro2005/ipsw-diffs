## SiriFindMy

> `/System/Library/PrivateFrameworks/SiriFindMy.framework/SiriFindMy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1863f0` | `0x1816d0` | **`-0x4d20`** |
| `__TEXT.__eh_frame` | `0xb69c` | `0xb25c` | **`-0x440`** |
| `__DATA.__bss` | `0x18e00` | `0x18a80` | **`-0x380`** |
| `__TEXT.__oslogstring` | `0x7405` | `0x70d5` | **`-0x330`** |
| `__TEXT.__const` | `0x14428` | `0x141a8` | **`-0x280`** |
| `__AUTH_CONST.__const` | `0xe6d8` | `0xe520` | **`-0x1b8`** |
| `__TEXT.__unwind_info` | `0x6878` | `0x67c0` | **`-0xb8`** |
| `__TEXT.__swift5_reflstr` | `0x3b28` | `0x3a98` | **`-0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x4ee4` | `0x4e70` | **`-0x74`** |
| `__TEXT.__cstring` | `0x2823` | `0x27c3` | **`-0x60`** |
| `__TEXT.__swift_as_ret` | `0x960` | `0x90c` | **`-0x54`** |
| `__TEXT.__swift5_capture` | `0x1d34` | `0x1ce4` | **`-0x50`** |
| `__TEXT.__swift_as_cont` | `0xb5c` | `0xb1c` | **`-0x40`** |
| `__TEXT.__constg_swiftt` | `0x5bac` | `0x5b74` | **`-0x38`** |
| `__TEXT.__swift_as_entry` | `0x5c8` | `0x590` | **`-0x38`** |
| `__DATA.__data` | `0x5168` | `0x5138` | **`-0x30`** |
| `__TEXT.__swift5_assocty` | `0xb78` | `0xb58` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0xe60` | `0xe44` | **`-0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x26f0` | `0x26d8` | **`-0x18`** |
| `__TEXT.__swift5_typeref` | `0x7aea` | `0x7ad6` | **`-0x14`** |
| `__TEXT.__swift5_types` | `0x5f8` | `0x5f0` | **`-0x8`** |

### Other Changes

```diff

-3600.12.3.0.0
+3600.18.2.0.0

-  Functions: 10649
-  Symbols:   3042
-  CStrings:  800
+  Functions: 10591
+  Symbols:   3038
+  CStrings:  787
Symbols:
- _associated conformance 10SiriFindMy0B15FriendFlowErrorOSHAASQ
- _symbolic _____ 10SiriFindMy0B15FriendFlowErrorO
- _symbolic _____ 10SiriFindMy0B6FriendO21ConfirmIntentStrategyV
- _type_layout_string 10SiriFindMy0B6FriendO21ConfirmIntentStrategyV
CStrings:
- "FindFriend.ConfirmIntentStrategy parsing confirmation response"
- "FindFriend.ConfirmIntentStrategy unable to parse dialog act"
- "FindFriend.ConfirmIntentStrategy user confirmed task, returning ConfirmIntentAnswer with confirmed confirmation response"
- "FindFriend.ConfirmIntentStrategy user did NOT confirm task, returning ConfirmIntentAnswer with rejected confirmation response"
- "FindFriend.ConfirmIntentStrategy.actionForInput() called"
- "FindFriend.ConfirmIntentStrategy.makeFlowCancelledResponse() called"
- "FindFriend.ConfirmIntentStrategy.makePromptForConfirmation() called"
- "FindFriend.ConfirmIntentStrategy: friend is nil"
- "FindMyFriend#UtteranceRewriteConfirmation"
- "SiriFindMyCommon#GenericCancellation"
- "Unsupported input type, cancelling"
- "User accepted confirmation, handling"
- "User rejected, cancelled, or gave unclear response - cancelling"
```
