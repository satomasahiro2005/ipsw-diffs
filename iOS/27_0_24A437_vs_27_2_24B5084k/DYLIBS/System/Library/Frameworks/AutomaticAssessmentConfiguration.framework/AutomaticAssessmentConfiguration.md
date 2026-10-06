## AutomaticAssessmentConfiguration

> `/System/Library/Frameworks/AutomaticAssessmentConfiguration.framework/AutomaticAssessmentConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8810` | `0x8874` | **`+0x64`** |
| `__AUTH_CONST.__objc_const` | `0x13a0` | `0x13d0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xa7c` | `0xa94` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x788` | `0x798` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x130` | `0x134` | **`+0x4`** |

### Other Changes

```diff

-56.2.1.0.0
+56.40.4.0.0

-  Functions: 301
-  Symbols:   521
+  Functions: 303
+  Symbols:   524
Symbols:
+ -[AEAssessmentConfiguration allowsForceQuitKeyboardShortcuts]
+ -[AEAssessmentConfiguration allowsLockdownMode]
+ -[AEAssessmentConfiguration allowsOnlyParticipantsToRun]
+ -[AEAssessmentConfiguration allowsPrivateRelay]
+ -[AEAssessmentConfiguration allowsVirtualMachine]
+ -[AEAssessmentConfiguration requiresReleaseOS]
+ -[AEAssessmentConfiguration setAllowsForceQuitKeyboardShortcuts:]
+ -[AEAssessmentConfiguration setAllowsLockdownMode:]
+ -[AEAssessmentConfiguration setAllowsOnlyParticipantsToRun:]
+ -[AEAssessmentConfiguration setAllowsPrivateRelay:]
+ -[AEAssessmentConfiguration setAllowsVirtualMachine:]
+ -[AEAssessmentConfiguration setRequiresReleaseOS:]
+ _OBJC_IVAR_$_AEAssessmentConfiguration._allowsForceQuitKeyboardShortcuts
+ _OBJC_IVAR_$_AEAssessmentConfiguration._allowsLockdownMode
+ _OBJC_IVAR_$_AEAssessmentConfiguration._allowsOnlyParticipantsToRun
+ _OBJC_IVAR_$_AEAssessmentConfiguration._allowsPrivateRelay
+ _OBJC_IVAR_$_AEAssessmentConfiguration._allowsVirtualMachine
+ _OBJC_IVAR_$_AEAssessmentConfiguration._requiresReleaseOS
- -[AEAssessmentConfiguration allowLockdownMode]
- -[AEAssessmentConfiguration allowOnlyParticipantsToRun]
- -[AEAssessmentConfiguration allowPrivateRelay]
- -[AEAssessmentConfiguration allowVirtualMachine]
- -[AEAssessmentConfiguration allowsForceQuit]
- -[AEAssessmentConfiguration setAllowLockdownMode:]
- -[AEAssessmentConfiguration setAllowOnlyParticipantsToRun:]
- -[AEAssessmentConfiguration setAllowPrivateRelay:]
- -[AEAssessmentConfiguration setAllowVirtualMachine:]
- -[AEAssessmentConfiguration setAllowsForceQuit:]
- _OBJC_IVAR_$_AEAssessmentConfiguration._allowLockdownMode
- _OBJC_IVAR_$_AEAssessmentConfiguration._allowOnlyParticipantsToRun
- _OBJC_IVAR_$_AEAssessmentConfiguration._allowPrivateRelay
- _OBJC_IVAR_$_AEAssessmentConfiguration._allowVirtualMachine
- _OBJC_IVAR_$_AEAssessmentConfiguration._allowsForceQuit
```
