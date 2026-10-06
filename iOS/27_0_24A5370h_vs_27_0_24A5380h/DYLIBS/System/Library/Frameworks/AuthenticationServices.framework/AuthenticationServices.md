## AuthenticationServices

> `/System/Library/Frameworks/AuthenticationServices.framework/AuthenticationServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x143894` | `0x143f5c` | **`+0x6c8`** |
| `__AUTH.__objc_data` | `0x3d08` | `0x3ac8` | **`-0x240`** |
| `__DATA_DIRTY.__objc_data` | `0x2d0` | `0x510` | **`+0x240`** |
| `__DATA.__data` | `0x3940` | `0x39a0` | **`+0x60`** |
| `__TEXT.__cstring` | `0xb578` | `0xb5d8` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x80ec` | `0x813c` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x4580` | `0x45c0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x4ce8` | `0x4d18` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1a38` | `0x1a60` | **`+0x28`** |
| `__DATA_DIRTY.__data` | `—` | `0x28` | **`+0x28`** |
| `__AUTH.__data` | `0x18f0` | `0x18d0` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0x10370` | `0x10390` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x5d90` | `0x5db0` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x34eb` | `0x34db` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x10a8` | `0x10b0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x358` | `0x360` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x700` | `0x704` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0x12bc` | `0x12c0` | **`+0x4`** |

### Other Changes

```diff

-625.1.20.10.3
+625.1.22.10.3

-  Functions: 8196
-  Symbols:   6564
-  CStrings:  1352
+  Functions: 8210
+  Symbols:   6575
+  CStrings:  1354
Symbols:
+ -[ASCredentialRequestButton accessibilityLabel]
+ -[ASCredentialRequestButton accessibilityTraits]
+ -[ASCredentialRequestButton isAccessibilityElement]
+ -[ASCredentialRequestConfirmButtonSubPane _evaluatePolicy:reason:reply:]
+ -[ASCredentialRequestConfirmButtonSubPane _performBiometricValidationAllowingPasscodeFallback:reply:]
+ -[ASCredentialRequestConfirmButtonSubPane _shouldUseInlineBiometricsView]
+ _OBJC_IVAR_$_ASCredentialRequestConfirmButtonSubPane._selectedLoginChoice
+ _UIAccessibilityTraitNotEnabled
+ ___72-[ASCredentialRequestConfirmButtonSubPane _evaluatePolicy:reason:reply:]_block_invoke
+ ___72-[ASCredentialRequestConfirmButtonSubPane _evaluatePolicy:reason:reply:]_block_invoke_2
+ ___75-[ASCredentialRequestConfirmButtonSubPane _authorizationButtonBioSelected:]_block_invoke
+ ___75-[ASCredentialRequestConfirmButtonSubPane _authorizationButtonBioSelected:]_block_invoke_2
+ ___86-[_ASAgentCredentialExchangeListener continueExportWithCredentials:completionHandler:]_block_invoke_2
+ ___block_descriptor_41_e8_32s_e22_v20?0B8"LAContext"12ls32l8
+ _visibilityForLoginChoiceKind
- GCC_except_table31
- GCC_except_table33
- ___71-[ASCredentialRequestConfirmButtonSubPane _performCompanionValidation:]_block_invoke
- ___71-[ASCredentialRequestConfirmButtonSubPane _performCompanionValidation:]_block_invoke_2
CStrings:
+ "-[_ASAgentCredentialExchangeListener continueExportWithCredentials:completionHandler:]_block_invoke_2"
+ "An export is currently in progress. Please try again in a few minutes."
+ "Authentication in ASAuthorizationController credential picker failed with error: %{public}@"
+ "Export in progress"
+ "\xf1"
- "-[_ASAgentCredentialExchangeListener continueExportWithCredentials:completionHandler:]_block_invoke"
- "Companion authentication in ASAuthorizationController credential picker failed with error: %{public}@"
- "\xe1"
```
