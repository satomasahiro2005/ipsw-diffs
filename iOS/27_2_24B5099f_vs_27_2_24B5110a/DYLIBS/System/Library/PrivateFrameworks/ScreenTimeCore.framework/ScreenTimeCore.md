## ScreenTimeCore

> `/System/Library/PrivateFrameworks/ScreenTimeCore.framework/ScreenTimeCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10811c` | `0x108f00` | **`+0xde4`** |
| `__TEXT.__eh_frame` | `0x4960` | `0x4aac` | **`+0x14c`** |
| `__AUTH_CONST.__const` | `0x38b8` | `0x39c0` | **`+0x108`** |
| `__TEXT.__const` | `0x35a8` | `0x3618` | **`+0x70`** |
| `__TEXT.__cstring` | `0xa9cc` | `0xaa2c` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x1704` | `0x175e` | **`+0x5a`** |
| `__TEXT.__swift5_capture` | `0xbe4` | `0xc28` | **`+0x44`** |
| `__TEXT.__oslogstring` | `0xc85a` | `0xc82a` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x4290` | `0x42c0` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x9a80` | `0x9aa0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1f40` | `0x1f20` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0xe14` | `0xe30` | **`+0x1c`** |
| `__DATA.__data` | `0x2350` | `0x2360` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xa34` | `0xa44` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x278` | `0x284` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x18c` | `0x198` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x1c8` | `0x1d4` | **`+0xc`** |
| `__DATA_CONST.__got` | `0xef8` | `0xf00` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x2b8` | `0x2c0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xf8` | `0xfc` | **`+0x4`** |

### Other Changes

```diff

-655.1.12.0.0
+655.1.14.1.0

-  Functions: 6144
-  Symbols:   6905
-  CStrings:  2309
+  Functions: 6155
+  Symbols:   6907
+  CStrings:  2310
Symbols:
+ _STUserDefaultsKeyUpgradeEligibilityActiveWindowSeconds
+ ___87-[STManagementState saveExpressIntroductionSettingsDefaults:forUser:completionHandler:]_block_invoke_2
+ ___87-[STManagementState saveExpressIntroductionSettingsDefaults:forUser:completionHandler:]_block_invoke_3
+ ___87-[STManagementState saveExpressIntroductionSettingsDefaults:forUser:completionHandler:]_block_invoke_4
+ ___swift_closure_destructor.175Tm
+ ___swift_closure_destructor.47Tm
+ _symbolic So29STExpressIntroductionUserObjCC
+ _symbolic So41STExpressIntroductionSettingsDefaultsObjCC
+ _symbolic _____ 14ScreenTimeCore019ExpressIntroductionaB14SettingsLoaderO
- _OUTLINED_FUNCTION_11
- ___79-[STManagementState saveExpressIntroductionSettingsDefaults:completionHandler:]_block_invoke
- ___79-[STManagementState saveExpressIntroductionSettingsDefaults:completionHandler:]_block_invoke_2
- ___79-[STManagementState saveExpressIntroductionSettingsDefaults:completionHandler:]_block_invoke_3
- ___block_descriptor_40_e8_32bs_e5_v8?0ls32l8
- ___swift_closure_destructor.161Tm
- ___swift_closure_destructor.32Tm
CStrings:
+ "%s: Applying Express Introduction defaults to New Screen Time for user with DSID: %{private}s"
+ "UpgradeEligibilityActiveWindowSeconds"
+ "applyExpressIntroductionSettingsDefaults(_:forUser:)"
+ "nil (local user)"
- "%s: Applying Express Introduction defaults to New Screen Time"
- "Saving Express Introduction settings defaults for a remote user is not supported yet"
- "applyExpressIntroductionSettingsDefaults(_:)"
```
