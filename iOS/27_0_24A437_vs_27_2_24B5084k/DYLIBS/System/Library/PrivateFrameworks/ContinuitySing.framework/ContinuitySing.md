## ContinuitySing

> `/System/Library/PrivateFrameworks/ContinuitySing.framework/ContinuitySing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5de2c` | `0x5e570` | **`+0x744`** |
| `__TEXT.__cstring` | `0x61b9` | `0x62f9` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0x7320` | `0x7408` | **`+0xe8`** |
| `__AUTH_CONST.__const` | `0x1400` | `0x1478` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0x3389` | `0x33f9` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x3694` | `0x36fc` | **`+0x68`** |
| `__AUTH.__objc_data` | `0x2118` | `0x2168` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x344` | `0x374` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x2af8` | `0x2b20` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x2f00` | `0x2f20` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xb98` | `0xbb8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1888` | `0x18a0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xd70` | `0xd78` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x484` | `0x48c` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x2d0` | `0x2d8` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x9f6` | `0x9fa` | **`+0x4`** |

### Other Changes

```diff

-764.22.13.0.0
+764.40.4.122.1

-  Functions: 1915
-  Symbols:   3041
-  CStrings:  946
+  Functions: 1931
+  Symbols:   3055
+  CStrings:  953
Symbols:
+ +[CSDismissOnboardingMessage messageID]
+ -[CSRemoteRequestClient dismissOnboardingHandler]
+ -[CSRemoteRequestClient setDismissOnboardingHandler:]
+ -[CSShieldManager _notifyDismissOnboarding]
+ -[CSShieldViewController _handleRemoteDismissOnboardingRequest]
+ -[CSShieldViewController shieldManagerDidReceiveDismissOnboardingRequest:]
+ GCC_except_table151
+ GCC_except_table157
+ GCC_except_table38
+ GCC_except_table45
+ GCC_except_table49
+ GCC_except_table65
+ GCC_except_table80
+ GCC_except_table83
+ _OBJC_CLASS_$_CSDismissOnboardingMessage
+ _OBJC_IVAR_$_CSRemoteRequestClient._dismissOnboardingHandler
+ _OBJC_IVAR_$_CSShieldViewController._onboardingFlowNavigationController
+ _OBJC_METACLASS_$_CSDismissOnboardingMessage
+ __OBJC_$_CLASS_METHODS_CSDismissOnboardingMessage
+ __OBJC_CLASS_RO_$_CSDismissOnboardingMessage
+ __OBJC_METACLASS_RO_$_CSDismissOnboardingMessage
+ ___43-[CSShieldManager _notifyDismissOnboarding]_block_invoke
+ ___62-[CSShieldManager _bootstrapRequestClientIfNeededAndAvailable]_block_invoke_6
+ _swift_isEscapingClosureAtFileLocation
+ _symbolic Ig_
- GCC_except_table149
- GCC_except_table15
- GCC_except_table155
- GCC_except_table24
- GCC_except_table30
- GCC_except_table44
- GCC_except_table48
- GCC_except_table64
- GCC_except_table79
- GCC_except_table81
- ___119-[CSRemoteRequestClient initWithRemoteDisplayIdentifier:participantInfo:disconnectHandler:connectionCompletionHandler:]_block_invoke_4
CStrings:
+ "%s: %@ Dismissing onboarding card for remote request"
+ "%s: Received continuity sing dismiss onboarding message %@"
+ "-[CSRemoteRequestClient initWithRemoteDisplayIdentifier:participantInfo:disconnectHandler:connectionCompletionHandler:]_block_invoke_2"
+ "-[CSRemoteRequestClient initWithRemoteDisplayIdentifier:participantInfo:disconnectHandler:connectionCompletionHandler:]_block_invoke_3"
+ "-[CSShieldViewController _handleRemoteDismissOnboardingRequest]"
+ "-[CSShieldViewController shieldManagerDidReceiveDismissOnboardingRequest:]"
+ "com.apple.ContinuitySing.dismissOnboarding"
+ "\xf0\xe1"
- "-[CSRemoteRequestClient initWithRemoteDisplayIdentifier:participantInfo:disconnectHandler:connectionCompletionHandler:]_block_invoke_4"
```
