## MechTouchId

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/MechanismPlugins/MechTouchId.bundle/MechTouchId`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3244` | `0x3d18` | **`+0xad4`** |
| `__TEXT.__objc_stubs` | `0xe80` | `0x1080` | **`+0x200`** |
| `__TEXT.__objc_methname` | `0xde2` | `0xfa3` | **`+0x1c1`** |
| `__TEXT.__oslogstring` | `0x271` | `0x33b` | **`+0xca`** |
| `__DATA_CONST.__const` | `0x1b8` | `0x260` | **`+0xa8`** |
| `__DATA.__objc_selrefs` | `0x4c8` | `0x550` | **`+0x88`** |
| `__DATA.__objc_const` | `0x380` | `0x3e0` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x180` | `0x1d0` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x2fc` | `0x334` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x148` | `0x170` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x23d` | `0x261` | **`+0x24`** |
| `__DATA_CONST.__cfstring` | `0x1a0` | `0x1c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x10c` | `0x127` | **`+0x1b`** |
| `__TEXT.__gcc_except_tab` | `0xe0` | `0xf4` | **`+0x14`** |
| `__TEXT.__auth_stubs` | `0x2b0` | `0x2c0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x20` | `0x2c` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x168` | `0x170` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-2319.0.46.0.0
+2319.0.63.0.0

-  Functions: 45
-  Symbols:   101
-  CStrings:  239
+  Functions: 56
+  Symbols:   112
+  CStrings:  267
Symbols:
+ _LACErrorCodeDoublePressRequired
+ _LACErrorSubcodeLostFocus
+ _LACEventParamCredentialPresent
+ _LACEventPushButton
+ _LACPolicyOptionSkipDoublePress
+ _LACResultPushButtonPressed
+ _OBJC_CLASS_$_LACACMHelper
+ _OBJC_CLASS_$_LACMutableEvaluationEventValuePushButtonStatus
+ _OBJC_CLASS_$_NSDate
+ ___kCFBooleanFalse
+ __os_log_error_impl
+ _objc_alloc
- _objc_retain_x4
CStrings:
+ "%{public}@ cached match expired while waiting for the double press"
+ "%{public}@ failed to query push button credential: %{public}@"
+ "%{public}@ state changed to %d"
+ "%{public}@ will not restart in biolockout"
+ "@\"NSDate\""
+ "@\"NSDictionary\""
+ "@\"NSUUID\""
+ "Double press is required."
+ "_expireMatchThatStartedAt:"
+ "_hasDoublePressPrecondition"
+ "_matchIdentityUUID"
+ "_matchResult"
+ "_runWithHints:eventHandler:"
+ "_scheduleMatchExpirationWithResult:identityUUID:"
+ "_startedMatching"
+ "acmContext"
+ "biolockout"
+ "canRecoverFromError:"
+ "checkCredentialValid"
+ "companionStateChanged:newState:"
+ "date"
+ "error:hasCode:subcode:"
+ "initWithACMContext:"
+ "isCredentialOfTypeSet:error:"
+ "isLastRestartAttempt"
+ "preCompanion"
+ "prepareForRestart"
+ "runWithHints:eventHandler:reply:"
+ "setIsCredentialPresent:"
- "_runWithHints"
```
