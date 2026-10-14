## HomeDeviceSetup

> `/System/Library/PrivateFrameworks/HomeDeviceSetup.framework/HomeDeviceSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72de0` | `0x7387c` | **`+0xa9c`** |
| `__TEXT.__cstring` | `0x1aac4` | `0x1ad64` | **`+0x2a0`** |
| `__AUTH_CONST.__cfstring` | `0x5600` | `0x5720` | **`+0x120`** |
| `__AUTH_CONST.__objc_const` | `0x78a8` | `0x79b0` | **`+0x108`** |
| `__TEXT.__objc_methlist` | `0x3494` | `0x3514` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x2e10` | `0x2e70` | **`+0x60`** |
| `__DATA.__objc_ivar` | `0xa4c` | `0xa64` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x19d8` | `0x19e8` | **`+0x10`** |
| `__TEXT.__const` | `0x488` | `0x478` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x81d` | `0x82d` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x18a0` | `0x18b0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x418` | `0x420` | **`+0x8`** |

### Other Changes

```diff

-405.10.34.1.1
+405.10.36.0.0

-  Functions: 3080
-  Symbols:   3348
-  CStrings:  3127
+  Functions: 3098
+  Symbols:   3367
+  CStrings:  3149
Symbols:
+ +[HDSDefaults forceTopCapBigAsset]
+ +[HDSDefaults forceTopCapNight]
+ +[HDSHPCommon productSupportsLightShow]
+ -[HDSSetupService lightShowOptedIn]
+ -[HDSSetupSession _runLightShowUserInput]
+ -[HDSSetupSession lightShowOptedIn:]
+ -[HDSSetupSession promptForLightShowOptInHandler]
+ -[HDSSetupSession setPromptForLightShowOptInHandler:]
+ GCC_except_table314
+ GCC_except_table377
+ GCC_except_table382
+ GCC_except_table432
+ _OBJC_IVAR_$_CLISetupInteractor._lightShowOptedIn
+ _OBJC_IVAR_$_HDSSetupService._lightShowOptedIn
+ _OBJC_IVAR_$_HDSSetupSession._isLightShowCapable
+ _OBJC_IVAR_$_HDSSetupSession._lightShowSelection
+ _OBJC_IVAR_$_HDSSetupSession._lightShowUserInputState
+ _OBJC_IVAR_$_HDSSetupSession._promptForLightShowOptInHandler
+ _OUTLINED_FUNCTION_80
+ ___36-[HDSSetupSession lightShowOptedIn:]_block_invoke
+ ___44-[CLISetupInteractor setCLIPromptsForStates]_block_invoke_22
+ _kDefaultsKey_ForceTopCapBigAsset
+ _kDefaultsKey_ForceTopCapNight
- GCC_except_table311
- GCC_except_table374
- GCC_except_table379
- GCC_except_table429
CStrings:
+ "-[CLISetupInteractor setCLIPromptsForStates]_block_invoke_22"
+ "-[HDSSetupSession _runLightShowUserInput]"
+ "-[HDSSetupSession lightShowOptedIn:]_block_invoke"
+ "AudioAccessory11,1"
+ "CLISetupInteractor: promptForLightShowHandler\n"
+ "CmdHomeDeviceSetupNoUI promptForLightShowHandler %s\n"
+ "HomePod Light Show capable: %s | %#m\n"
+ "Light Show capable: %s\n"
+ "Light Show user selection = %s\n"
+ "LightShow"
+ "LightShow Complete, user choice: %s\n"
+ "LightShowUserInput"
+ "LightShowUserInput asking user to opt in\n"
+ "LightShowUserInput skipping with no prompt handler\n"
+ "LightShowUserInput start\n"
+ "Oct  4 2026"
+ "forceTopCapBigAsset"
+ "forceTopCapNight"
+ "lightShow"
+ "lightShowState"
+ "ls_ca"
+ "ls_oi"
+ "setSetupUserInputConfig Light Show opted in set to cli arg %s\n"
- "Sep 30 2026"
```
