## PasscodeAndBiometricsSettings

> `/System/Library/PrivateFrameworks/PasscodeAndBiometricsSettings.framework/PasscodeAndBiometricsSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3be54` | `0x3b340` | **`-0xb14`** |
| `__TEXT.__oslogstring` | `0x5195` | `0x50d5` | **`-0xc0`** |
| `__TEXT.__dlopen_cstrs` | `0x3ed` | `0x333` | **`-0xba`** |
| `__AUTH_CONST.__objc_const` | `0x2110` | `0x2098` | **`-0x78`** |
| `__AUTH_CONST.__objc_intobj` | `0x1c8` | `0x150` | **`-0x78`** |
| `__AUTH_CONST.__cfstring` | `0x2e20` | `0x2e80` | **`+0x60`** |
| `__DATA.__data` | `0x984` | `0x924` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x1098` | `0x1048` | **`-0x50`** |
| `__TEXT.__gcc_except_tab` | `0x900` | `0x8c8` | **`-0x38`** |
| `__TEXT.__cstring` | `0x3648` | `0x3678` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0xaa8` | `0xa88` | **`-0x20`** |
| `__DATA.__bss` | `0xa90` | `0xa70` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x210c` | `0x20ec` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0xa58` | `0xa68` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1df8` | `0x1de8` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0xe8` | `0xe0` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x98` | `0x90` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1090` | `0x1088` | **`-0x8`** |

### Other Changes

```diff

-29.0.0.0.0
+32.0.0.0.0

-  Functions: 1323
-  Symbols:   1836
-  CStrings:  884
+  Functions: 1310
+  Symbols:   1828
+  CStrings:  881
Symbols:
+ -[PABSPasscodeLockController _extractAndSyncKeychainFromPasscodeChange:]
+ -[PABSPasscodeLockController _extractCredentialAndSyncKeychain:]
+ -[PABSPasscodeLockController _handleKeychainSyncCompletion:presentingController:passcodeChangeController:completion:]
+ -[PABSPasscodeLockController _startPasscodeChangeServiceWithController:title:passcodePrompt:]
+ -[PABSPasscodeLockController _syncKeychainWithPasscode:promise:]
+ GCC_except_table116
+ GCC_except_table118
+ GCC_except_table120
+ GCC_except_table129
+ GCC_except_table149
+ GCC_except_table46
+ GCC_except_table49
+ GCC_except_table54
+ GCC_except_table65
+ GCC_except_table73
+ GCC_except_table78
+ GCC_except_table79
+ GCC_except_table85
+ ___117-[PABSPasscodeLockController _handleKeychainSyncCompletion:presentingController:passcodeChangeController:completion:]_block_invoke
+ ___64-[PABSPasscodeLockController _extractCredentialAndSyncKeychain:]_block_invoke
+ ___64-[PABSPasscodeLockController _syncKeychainWithPasscode:promise:]_block_invoke
+ ___64-[PABSPasscodeLockController _syncKeychainWithPasscode:promise:]_block_invoke_2
+ ___72-[PABSPasscodeLockController _extractAndSyncKeychainFromPasscodeChange:]_block_invoke
+ ___93-[PABSPasscodeLockController _startPasscodeChangeServiceWithController:title:passcodePrompt:]_block_invoke
+ ___block_descriptor_48_e8_32s40s_e28_v24?0"NSData"8"NSError"16ls32l8s40l8
+ ___block_descriptor_48_e8_32s40w_e19_v16?0"NAPromise"8lw40l8s32l8
+ _memset_s
+ _objc_retain_x5
- -[PABSPearlPasscodeController authContext]
- -[PABSPearlPasscodeController event:params:reply:]
- -[PABSPearlPasscodeController setAuthContext:]
- -[PABSTouchIDPasscodeController authContext]
- -[PABSTouchIDPasscodeController event:params:reply:]
- -[PABSTouchIDPasscodeController setAuthContext:]
- GCC_except_table113
- GCC_except_table115
- GCC_except_table117
- GCC_except_table126
- GCC_except_table146
- GCC_except_table51
- GCC_except_table55
- GCC_except_table69
- GCC_except_table77
- GCC_except_table82
- GCC_except_table84
- _LocalAuthenticationLibraryCore.frameworkLibrary
- _OBJC_IVAR_$_PABSPearlPasscodeController._authContext
- _OBJC_IVAR_$_PABSTouchIDPasscodeController._authContext
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_LAUIDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_LAUIDelegate
- __OBJC_LABEL_PROTOCOL_$_LAUIDelegate
- __OBJC_PROTOCOL_$_LAUIDelegate
- ___132-[PABSPasscodeLockController showLocalAuthenticationPasscodeChangeFlowFromPresentingController:title:passcodePrompt:withCompletion:]_block_invoke
- ___132-[PABSPasscodeLockController showLocalAuthenticationPasscodeChangeFlowFromPresentingController:title:passcodePrompt:withCompletion:]_block_invoke_2
- ___132-[PABSPasscodeLockController showLocalAuthenticationPasscodeChangeFlowFromPresentingController:title:passcodePrompt:withCompletion:]_block_invoke_3
- ___50-[PABSPearlPasscodeController event:params:reply:]_block_invoke
- ___52-[PABSTouchIDPasscodeController event:params:reply:]_block_invoke
- ___LocalAuthenticationLibraryCore_block_invoke
- ___block_descriptor_32_e26_"NAFuture"16?0"NSData"8l
- ___block_descriptor_40_e8_32w_e28_"NAFuture"16?0"NSString"8lw32l8
- ___block_descriptor_48_e8_32s40s_e19_v16?0"NAPromise"8ls32l8s40l8
- ___getLAContextClass_block_invoke
- _audit_stringLocalAuthentication
- _getLAContextClass.softClass
CStrings:
+ "%@: Adding: cachedShowPassbookRow [1]"
+ "NO_ACCOUNT_ALERT_MESSAGE_FACE_ID"
+ "NO_ACCOUNT_ALERT_MESSAGE_OPTIC_ID"
+ "NO_ACCOUNT_ALERT_MESSAGE_TOUCH_ID"
+ "com.apple.pabs"
+ "configurePeriocularEnabled: %@"
+ "v24@?0@\"NSData\"8@\"NSError\"16"
- "%@: Adding: cachedShowPassbookRow [1] isWalletVisible [1]"
- "@\"NAFuture\"16@?0@\"NSData\"8"
- "@\"NAFuture\"16@?0@\"NSString\"8"
- "LAContext"
- "LAContextClass evaluatePolicy failed: %@"
- "LAUIDelegate [LAEventParamActive]: Failed to extract passcode - %@"
- "NO_ACCOUNT_ALERT_MESSAGE"
- "Received event: LAUIDelegate [LAEventParamActive]"
- "Touch ID: authContext = nil - No passcode object"
- "softlink:r:path:/System/Library/Frameworks/LocalAuthentication.framework/LocalAuthentication"
```
