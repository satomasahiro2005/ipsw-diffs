## DisembarkUI

> `/System/Library/PrivateFrameworks/DisembarkUI.framework/DisembarkUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f3b8` | `0x20790` | **`+0x13d8`** |
| `__TEXT.__oslogstring` | `0xda5` | `0x109b` | **`+0x2f6`** |
| `__TEXT.__objc_methlist` | `0x2920` | `0x2a38` | **`+0x118`** |
| `__DATA_CONST.__const` | `0xf60` | `0x1070` | **`+0x110`** |
| `__AUTH_CONST.__objc_const` | `0x4ff8` | `0x50a8` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x1d54` | `0x1df4` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1a78` | `0x1b10` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x7f8` | `0x850` | **`+0x58`** |
| `__TEXT.__gcc_except_tab` | `0x25c` | `0x2a4` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x1620` | `0x1640` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x2c8` | `0x2d4` | **`+0xc`** |

### Other Changes

```diff

-282.0.0.0.0
+285.0.0.0.0

+  - /System/Library/PrivateFrameworks/PassKitCore.framework/PassKitCore

+  - /usr/lib/swift/libswiftAppleArchive.dylib
+  - /usr/lib/swift/libswiftCallKit.dylib

+  - /usr/lib/swift/libswiftCoreAudio_Private.dylib

-  Functions: 950
-  Symbols:   1883
-  CStrings:  359
+  Functions: 988
+  Symbols:   1932
+  CStrings:  378
Symbols:
+ -[DKAccountProvider _validateWalrusForSignOutWithCompletion:]
+ -[DKAccountProvider authenticateForSignOutWithPresentingViewController:completion:]
+ -[DKAccountProvider authenticatedWipeToken]
+ -[DKAccountProvider didValidateWalrusSignOut]
+ -[DKAccountProvider setAuthenticatedWipeToken:]
+ -[DKAccountProvider setDidValidateWalrusSignOut:]
+ -[DKConfiguration .cxx_destruct]
+ -[DKConfiguration preEraseStep]
+ -[DKConfiguration setPreEraseStep:]
+ -[DKEraseFlow _authenticateSignOutIfNeededWithCompletion:]
+ -[DKEraseFlow _erase]
+ -[DKEraseFlow _presentPreEraseStep]
+ -[DKEraseFlow _presentUnknownFailureAlertThenEndFlowForCancellationWithReason:]
+ -[DKEraseFlow _runPreEraseStep]
+ -[DKEraseFlow _signOutIfNeededWithCompletion:]
+ -[DKFindMyProvider _authenticateDisableWithPresentingViewController:keepAlertVisible:completion:]
+ -[DKFindMyProvider _disableInContextWithWipeToken:completion:]
+ -[DKFindMyProvider _handleAuthenticateDisableResultWithCancel:wipeToken:completion:]
+ -[DKFindMyProvider authenticateFindMyDisableWithPresentingViewController:completion:]
+ -[DKFindMyProvider commitFindMyDisableWithWipeToken:completion:]
+ -[DKFindMyProvider disableFindMyDeviceWithWipeToken:presentingViewController:completion:]
+ GCC_except_table33
+ GCC_except_table39
+ GCC_except_table49
+ GCC_except_table59
+ GCC_except_table93
+ _OBJC_IVAR_$_DKAccountProvider._authenticatedWipeToken
+ _OBJC_IVAR_$_DKAccountProvider._didValidateWalrusSignOut
+ _OBJC_IVAR_$_DKConfiguration._preEraseStep
+ ___21-[DKEraseFlow _erase]_block_invoke
+ ___31-[DKEraseFlow _runPreEraseStep]_block_invoke
+ ___35-[DKEraseFlow _presentPreEraseStep]_block_invoke
+ ___35-[DKEraseFlow _presentPreEraseStep]_block_invoke_2
+ ___46-[DKEraseFlow _signOutIfNeededWithCompletion:]_block_invoke
+ ___46-[DKEraseFlow _signOutIfNeededWithCompletion:]_block_invoke_2
+ ___58-[DKEraseFlow _authenticateSignOutIfNeededWithCompletion:]_block_invoke
+ ___58-[DKEraseFlow _authenticateSignOutIfNeededWithCompletion:]_block_invoke_2
+ ___61-[DKAccountProvider _validateWalrusForSignOutWithCompletion:]_block_invoke
+ ___62-[DKFindMyProvider _disableInContextWithWipeToken:completion:]_block_invoke
+ ___79-[DKEraseFlow _presentUnknownFailureAlertThenEndFlowForCancellationWithReason:]_block_invoke
+ ___83-[DKAccountProvider authenticateForSignOutWithPresentingViewController:completion:]_block_invoke
+ ___83-[DKAccountProvider authenticateForSignOutWithPresentingViewController:completion:]_block_invoke_2
+ ___85-[DKFindMyProvider authenticateFindMyDisableWithPresentingViewController:completion:]_block_invoke
+ ___97-[DKFindMyProvider _authenticateDisableWithPresentingViewController:keepAlertVisible:completion:]_block_invoke
+ ___block_descriptor_40_e8_32w_e8_v12?0B8lw32l8
+ ___block_descriptor_41_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_48_e8_32bs40w_e21_v20?0B8"NSString"12lw40l8s32l8
+ ___block_descriptor_48_e8_32s40bs_e21_v20?0B8"NSString"12ls32l8s40l8
+ ___block_descriptor_48_e8_32s40bs_e21_v20?0B8"NSString"12ls40l8s32l8
+ ___block_descriptor_49_e8_32s40bs_e5_v8?0ls32l8s40l8
+ __swift_FORCE_LOAD_$_swiftAppleArchive
+ __swift_FORCE_LOAD_$_swiftAppleArchive_$_DisembarkUI
+ __swift_FORCE_LOAD_$_swiftCallKit
+ __swift_FORCE_LOAD_$_swiftCallKit_$_DisembarkUI
+ __swift_FORCE_LOAD_$_swiftCoreAudio_Private
+ __swift_FORCE_LOAD_$_swiftCoreAudio_Private_$_DisembarkUI
- -[DKEraseFlow _signOutAndEraseDevice]
- GCC_except_table31
- GCC_except_table47
- GCC_except_table57
- ___37-[DKEraseFlow _signOutAndEraseDevice]_block_invoke
- ___37-[DKEraseFlow _signOutAndEraseDevice]_block_invoke_2
- ___88-[DKAccountProvider signOutFlowController:performWalrusValidationForAccount:completion:]_block_invoke
CStrings:
+ "-[DKEraseFlow _authenticateSignOutIfNeededWithCompletion:]"
+ "-[DKEraseFlow _signOutIfNeededWithCompletion:]"
+ "-[DKFindMyProvider commitFindMyDisableWithWipeToken:completion:]"
+ "Authenticating Find My disable..."
+ "Authenticating sign out of primary Apple account..."
+ "Committing Find My disable with wipe token..."
+ "Failed to authenticate sign out of primary Apple account: %@"
+ "Find My disable authenticated; returning wipe token to caller for commit."
+ "Find My disable authentication canceled; aborting."
+ "Find My disable authentication did not return a wipe token; treating as failure."
+ "Find My not enabled; nothing to commit."
+ "Find My not enabled; skipping disable authentication."
+ "No pre-erase step configured; advancing to erase."
+ "Pre-Erase Step"
+ "Pre-erase step completed; proceeding to erase"
+ "Pre-erase step did not complete; ending flow without erasing"
+ "Running pre-erase step before erase..."
+ "Sign-out authentication did not succeed; ending flow without erasing"
+ "a"
+ "wipeToken"
- "-[DKEraseFlow _signOutAndEraseDevice]"
```
