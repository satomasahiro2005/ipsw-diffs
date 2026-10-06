## AskTo

> `/System/Library/PrivateFrameworks/AskTo.framework/AskTo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6bb4` | `0x613c` | **`-0xa78`** |
| `__TEXT.__eh_frame` | `0x5d4` | `0x524` | **`-0xb0`** |
| `__TEXT.__cstring` | `0x162` | `0x112` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x2c0` | `0x298` | **`-0x28`** |
| `__TEXT.__oslogstring` | `0x1dd` | `0x1bd` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x408` | `0x3f0` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0xa0` | `0x8c` | **`-0x14`** |
| `__TEXT.__swift_as_cont` | `0x8c` | `0x80` | **`-0xc`** |
| `__AUTH_CONST.__const` | `0x290` | `0x288` | **`-0x8`** |
| `__AUTH_CONST.__objc_const` | `0x2a0` | `0x298` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x58` | `0x50` | **`-0x8`** |
| `__TEXT.__const` | `0x3b0` | `0x3a8` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x168` | `0x160` | **`-0x8`** |

### Other Changes

```diff

-93.0.0.0.0
+96.0.0.0.0

-  Functions: 187
+  Functions: 180

-  CStrings:  16
+  CStrings:  14
Symbols:
+ __OBJC_$_INSTANCE_METHODS__TtC5AskTo16ATDispatchCenter(AskTo)
+ ___swift_closure_destructor.26Tm
- __INSTANCE_METHODS__TtC5AskTo16ATDispatchCenter
- ___swift_closure_destructor.23Tm
CStrings:
+ "%s developer sandbox was set and mock responses were available, not proceeding with question staging"
+ "_stageQuestionInMessages(_:recipientGroup:)"
- "%s called. action: %ld"
- "%s developer sandbox was set and mock responses were available, not proceeding with question send"
- "_send(_:to:destinationsNotSupportingLegacyAskViaMessages:)"
- "acknowledgmentAlertButtonTapped(question:action:reply:)"
```
