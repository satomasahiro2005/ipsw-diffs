## HomeDeviceSetup

> `/System/Library/PrivateFrameworks/HomeDeviceSetup.framework/HomeDeviceSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x73114` | `0x726a4` | **`-0xa70`** |
| `__TEXT.__cstring` | `0x1ad54` | `0x1aa54` | **`-0x300`** |
| `__AUTH_CONST.__objc_const` | `0x78c0` | `0x77d0` | **`-0xf0`** |
| `__AUTH_CONST.__cfstring` | `0x5640` | `0x5580` | **`-0xc0`** |
| `__TEXT.__objc_methlist` | `0x3474` | `0x342c` | **`-0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x2dc8` | `0x2d98` | **`-0x30`** |
| `__DATA.__objc_ivar` | `0xa64` | `0xa48` | **`-0x1c`** |
| `__AUTH.__data` | `0x338` | `0x328` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x82d` | `0x81d` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x1980` | `0x1978` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1870` | `0x1868` | **`-0x8`** |

### Other Changes

```diff

-405.0.1.0.0
+405.0.3.0.0

-  Functions: 3092
-  Symbols:   3347
-  CStrings:  3140
+  Functions: 3075
+  Symbols:   3325
+  CStrings:  3118
Symbols:
+ GCC_except_table310
+ GCC_except_table369
+ GCC_except_table421
- +[HDSDefaults forceSiriV2]
- -[HDSSetupSession _runSiriV2UserInput]
- -[HDSSetupSession _shouldShowPersonalRequestsForSiriV2]
- -[HDSSetupSession promptForSiriV2OptInHandler]
- -[HDSSetupSession setPromptForSiriV2OptInHandler:]
- -[HDSSetupSession siriV2OptedIn:]
- GCC_except_table313
- GCC_except_table373
- GCC_except_table425
- _OBJC_IVAR_$_CLISetupInteractor._siriV2OptedIn
- _OBJC_IVAR_$_HDSSetupSession._companionSiriV2Capable
- _OBJC_IVAR_$_HDSSetupSession._companionSiriV2Enabled
- _OBJC_IVAR_$_HDSSetupSession._isSiriV2Capable
- _OBJC_IVAR_$_HDSSetupSession._promptForSiriV2OptInHandler
- _OBJC_IVAR_$_HDSSetupSession._siriV2Selection
- _OBJC_IVAR_$_HDSSetupSession._siriV2UserInputState
- _OUTLINED_FUNCTION_80
- _OUTLINED_FUNCTION_81
- ___33-[HDSSetupSession siriV2OptedIn:]_block_invoke
- ___44-[CLISetupInteractor setCLIPromptsForStates]_block_invoke_22
- _initAFIsLinwoodCapableIgnoringUserSetting
- _initAFIsLinwoodEnabledAndAvailable
- _kDefaultsKey_ForceSiriV2
- _softLinkAFIsLinwoodCapableIgnoringUserSetting
- _softLinkAFIsLinwoodEnabledAndAvailable
CStrings:
- "-[CLISetupInteractor setCLIPromptsForStates]_block_invoke_22"
- "-[HDSSetupSession _runSiriV2UserInput]"
- "-[HDSSetupSession _shouldShowPersonalRequestsForSiriV2]"
- "AFIsLinwoodCapableIgnoringUserSetting"
- "AFIsLinwoodEnabledAndAvailable"
- "CLISetupInteractor: promptForSiriV2Handler\n"
- "CmdHomeDeviceSetupNoUI promptForSiriV2Handler %s\n"
- "Companion SiriV2 capable: %s, enabled: %s\n"
- "HomePod SiriV2 capable: %s | %#m\n"
- "PersonalRequests SiriV2 gating: companionCapable=%s companionEnabled=%s homePodCapable=%s siriV2Selection=%d result=%s\n"
- "SiriV2"
- "SiriV2 Complete, user choice: %s\n"
- "SiriV2UserInput"
- "SiriV2UserInput asking user to opt in\n"
- "SiriV2UserInput skipping with no prompt handler\n"
- "SiriV2UserInput start\n"
- "forceSiriV2"
- "setSetupUserInputConfig SiriV2 opted in set to cli arg %s\n"
- "siriV2"
- "siriv2"
- "sv2_ca"
- "sv2_oi"
```
