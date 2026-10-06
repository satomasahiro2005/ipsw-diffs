## AACClient

> `/System/Library/Frameworks/AutomaticAssessmentConfiguration.framework/Frameworks/AACClient.framework/AACClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22894` | `0x22b4c` | **`+0x2b8`** |
| `__AUTH_CONST.__objc_const` | `0x32e8` | `0x3360` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0x1408` | `0x1440` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x101b` | `0x104b` | **`+0x30`** |
| `__AUTH.__objc_data` | `0xc60` | `0xc80` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x7f8` | `0x810` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x1918` | `0x1930` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x410` | `0x420` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xbf8` | `0xc04` | **`+0xc`** |
| `__DATA.__data` | `0x13f0` | `0x13f8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xa38` | `0xa40` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xf4` | `0xf8` | **`+0x4`** |

### Other Changes

```diff

-56.2.1.0.0
+56.40.4.0.0

-  Functions: 1435
-  Symbols:   959
+  Functions: 1447
+  Symbols:   962
Symbols:
+ -[AECAssessmentConfigurationWrapper allowsForceQuitKeyboardShortcuts]
+ -[AECAssessmentConfigurationWrapper allowsLockdownMode]
+ -[AECAssessmentConfigurationWrapper allowsOnlyParticipantsToRun]
+ -[AECAssessmentConfigurationWrapper allowsPrivateRelay]
+ -[AECAssessmentConfigurationWrapper allowsVirtualMachine]
+ -[AECAssessmentConfigurationWrapper requiresReleaseOS]
+ -[AECAssessmentConfigurationWrapper setAllowsForceQuitKeyboardShortcuts:]
+ -[AECAssessmentConfigurationWrapper setAllowsLockdownMode:]
+ -[AECAssessmentConfigurationWrapper setAllowsOnlyParticipantsToRun:]
+ -[AECAssessmentConfigurationWrapper setAllowsPrivateRelay:]
+ -[AECAssessmentConfigurationWrapper setAllowsVirtualMachine:]
+ -[AECAssessmentConfigurationWrapper setRequiresReleaseOS:]
+ _OBJC_IVAR_$_AECAssessmentConfigurationWrapper._allowsForceQuitKeyboardShortcuts
+ _OBJC_IVAR_$_AECAssessmentConfigurationWrapper._allowsLockdownMode
+ _OBJC_IVAR_$_AECAssessmentConfigurationWrapper._allowsOnlyParticipantsToRun
+ _OBJC_IVAR_$_AECAssessmentConfigurationWrapper._allowsPrivateRelay
+ _OBJC_IVAR_$_AECAssessmentConfigurationWrapper._allowsVirtualMachine
+ _OBJC_IVAR_$_AECAssessmentConfigurationWrapper._requiresReleaseOS
+ _keypath_get.115Tm
+ _keypath_get.57Tm
+ _keypath_set.114Tm
+ _keypath_set.58Tm
- -[AECAssessmentConfigurationWrapper allowLockdownMode]
- -[AECAssessmentConfigurationWrapper allowOnlyParticipantsToRun]
- -[AECAssessmentConfigurationWrapper allowPrivateRelay]
- -[AECAssessmentConfigurationWrapper allowVirtualMachine]
- -[AECAssessmentConfigurationWrapper allowsForceQuit]
- -[AECAssessmentConfigurationWrapper setAllowLockdownMode:]
- -[AECAssessmentConfigurationWrapper setAllowOnlyParticipantsToRun:]
- -[AECAssessmentConfigurationWrapper setAllowPrivateRelay:]
- -[AECAssessmentConfigurationWrapper setAllowVirtualMachine:]
- -[AECAssessmentConfigurationWrapper setAllowsForceQuit:]
- _OBJC_IVAR_$_AECAssessmentConfigurationWrapper._allowLockdownMode
- _OBJC_IVAR_$_AECAssessmentConfigurationWrapper._allowOnlyParticipantsToRun
- _OBJC_IVAR_$_AECAssessmentConfigurationWrapper._allowPrivateRelay
- _OBJC_IVAR_$_AECAssessmentConfigurationWrapper._allowVirtualMachine
- _OBJC_IVAR_$_AECAssessmentConfigurationWrapper._allowsForceQuit
- _keypath_get.114Tm
- _keypath_get.56Tm
- _keypath_set.113Tm
- _keypath_set.57Tm
```
