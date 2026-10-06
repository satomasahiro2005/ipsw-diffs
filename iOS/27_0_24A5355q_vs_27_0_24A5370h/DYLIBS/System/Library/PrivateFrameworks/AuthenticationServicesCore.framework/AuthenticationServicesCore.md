## AuthenticationServicesCore

> `/System/Library/PrivateFrameworks/AuthenticationServicesCore.framework/AuthenticationServicesCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc78cc` | `0xc8558` | **`+0xc8c`** |
| `__TEXT.__cstring` | `0x3be1` | `0x3cc1` | **`+0xe0`** |
| `__TEXT.__eh_frame` | `0x45b0` | `0x4688` | **`+0xd8`** |
| `__AUTH_CONST.__const` | `0x6508` | `0x6588` | **`+0x80`** |
| `__TEXT.__const` | `0xcc98` | `0xcd08` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0x5fc` | `0x648` | **`+0x4c`** |
| `__TEXT.__objc_methlist` | `0x3b0c` | `0x3b4c` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x7e68` | `0x7ea0` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x3508` | `0x3538` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x2020` | `0x2040` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1e88` | `0x1ea8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x13f8` | `0x1400` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x1d08` | `0x1d10` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x2630` | `0x2638` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xbc` | `0xc4` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x2531` | `0x2537` | **`+0x6`** |
| `__DATA.__objc_ivar` | `0x434` | `0x438` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0xe0` | `0xe4` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xa8` | `0xac` | **`+0x4`** |

### Other Changes

```diff

-625.1.18.10.4
+625.1.20.10.3

-  Functions: 4983
-  Symbols:   3388
-  CStrings:  779
+  Functions: 4997
+  Symbols:   3395
+  CStrings:  785
Symbols:
+ -[ASAgentAutoFillListener credentialProviderInformationForAnyRecentAutoFillOfUsername:password:hostApplicationBundleIdentifier:completionHandler:]
+ -[ASCCredentialRequestContext proxyShouldIgnoreSilentRequestRequirements]
+ -[ASCCredentialRequestContext setProxyShouldIgnoreSilentRequestRequirements:]
+ _OBJC_IVAR_$_ASCCredentialRequestContext._proxyShouldIgnoreSilentRequestRequirements
+ ___146-[ASAgentAutoFillListener credentialProviderInformationForAnyRecentAutoFillOfUsername:password:hostApplicationBundleIdentifier:completionHandler:]_block_invoke
+ ___swift_closure_destructor.63Tm
+ _swift_retain_x27
+ _symbolic _____ 10ObjectiveC8ObjCBoolV
- ___swift_closure_destructor.62Tm
CStrings:
+ "conditionalMediation"
+ "extension:largeBlob"
+ "proxyShouldIgnoreSilentRequestRequirements"
+ "signalAllAcceptedCredentials"
+ "signalCurrentUserDetails"
+ "signalUnknownCredential"
```
