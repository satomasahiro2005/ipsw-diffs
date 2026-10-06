## ScreenTimeSettingsUI

> `/System/Library/PrivateFrameworks/ScreenTimeSettingsUI.framework/ScreenTimeSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x124bdc` | `0x124f50` | **`+0x374`** |
| `__TEXT.__oslogstring` | `0x5eb3` | `0x5f53` | **`+0xa0`** |
| `__TEXT.__cstring` | `0xd2e5` | `0xd355` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x26a8` | `0x26f8` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0xb180` | `0xb1c0` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x25e18` | `0x25e48` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x3cc0` | `0x3ce8` | **`+0x28`** |
| `__TEXT.__const` | `0x3d24` | `0x3d44` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xc4bc` | `0xc4dc` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x6dd0` | `0x6de8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0xcfc` | `0xd00` | **`+0x4`** |

### Other Changes

```diff

-637.0.102.0.0
+640.0.100.0.0

-  Functions: 6222
-  Symbols:   8407
-  CStrings:  2134
+  Functions: 6231
+  Symbols:   8414
+  CStrings:  2138
Symbols:
+ -[STCommunicationSafetyViewModelCoordinator _resolveUserInContext:error:]
+ -[STCommunicationSafetyViewModelCoordinator didAttemptUserLoad]
+ -[STCommunicationSafetyViewModelCoordinator setDidAttemptUserLoad:]
+ _OBJC_IVAR_$_STCommunicationSafetyViewModelCoordinator._didAttemptUserLoad
+ ___88-[STChildSetupController initExpressSetupWithDSID:childAge:childName:completionHandler:]_block_invoke_2
+ ___block_descriptor_80_e8_32s40s48s56s64s72bs_e17_v16?0"NSError"8ls72l8s32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_88_e8_32s40s48s56s64s72s80bs_e5_v8?0ls32l8s80l8s40l8s48l8s56l8s64l8s72l8
CStrings:
+ "Communication Safety persist dropped — user record unavailable for DSID %{public}@."
+ "Communication Safety persist: user could not be resolved."
+ "Communication Safety save dropped — user record unavailable for DSID %{public}@."
+ "Communication Safety save: user could not be resolved."
+ "Express Parental Controls failed to enable Screen Time. Error: %{public}@"
- "Communication Safety View Model has no userObjectID. Nothing will be saved."
```
