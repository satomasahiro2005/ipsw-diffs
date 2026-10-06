## Feedback Assistant iOS

> `/Applications/Feedback Assistant iOS.app/Feedback Assistant iOS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x76e88` | `0x74a40` | **`-0x2448`** |
| `__TEXT.__objc_methname` | `0xf71f` | `0xf27f` | **`-0x4a0`** |
| `__TEXT.__oslogstring` | `0x2734` | `0x22e4` | **`-0x450`** |
| `__TEXT.__objc_stubs` | `0xad40` | `0xa940` | **`-0x400`** |
| `__DATA.__objc_const` | `0xc900` | `0xc6c0` | **`-0x240`** |
| `__DATA_CONST.__cfstring` | `0x2420` | `0x21e0` | **`-0x240`** |
| `__TEXT.__objc_methlist` | `0x52ac` | `0x50d4` | **`-0x1d8`** |
| `__TEXT.__cstring` | `0x41b2` | `0x4032` | **`-0x180`** |
| `__DATA.__objc_selrefs` | `0x3e00` | `0x3cc8` | **`-0x138`** |
| `__TEXT.__unwind_info` | `0x1d38` | `0x1c80` | **`-0xb8`** |
| `__DATA_CONST.__const` | `0x32b8` | `0x3228` | **`-0x90`** |
| `__TEXT.__gcc_except_tab` | `0x580` | `0x528` | **`-0x58`** |
| `__TEXT.__objc_methtype` | `0x3dc5` | `0x3d75` | **`-0x50`** |
| `__DATA.__objc_data` | `0x3978` | `0x3930` | **`-0x48`** |
| `__DATA.__objc_ivar` | `0x26c` | `0x248` | **`-0x24`** |
| `__DATA.__bss` | `0x1bf0` | `0x1bd0` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x2250` | `0x2230` | **`-0x20`** |
| `__TEXT.__objc_classname` | `0x1122` | `0x1102` | **`-0x20`** |
| `__DATA_CONST.__objc_intobj` | `0x48` | `0x30` | **`-0x18`** |
| `__DATA_CONST.__auth_got` | `0x1138` | `0x1128` | **`-0x10`** |
| `__DATA_CONST.__got` | `0xc28` | `0xc18` | **`-0x10`** |
| `__TEXT.__const` | `0x2174` | `0x2164` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x280` | `0x278` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xf0` | `0xe8` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x1ac4` | `0x1acc` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-639.0.0.0.0
+641.0.0.0.0

+  - /System/Library/PrivateFrameworks/AppProtection.framework/AppProtection

-  Functions: 2753
-  Symbols:   1108
-  CStrings:  3630
+  Functions: 2694
+  Symbols:   1104
+  CStrings:  3517
Symbols:
+ _OBJC_CLASS_$_APApplication
+ _OBJC_CLASS_$_APGuard
+ _OBJC_CLASS_$_APSettingsManager
- _OBJC_CLASS_$_LAContext
- _OBJC_CLASS_$_NSDate
- _OBJC_CLASS_$_NSTimer
- _OBJC_CLASS_$_UIBlurEffect
- _OBJC_CLASS_$_UIVisualEffectView
- _objc_sync_enter
- _objc_sync_exit
CStrings:
+ "AppProtection authentication checkpoint failed: [%{public}@]"
+ "AppProtection authentication checkpoint passed"
+ "AppProtection lock status is not changeable; deferring legacy biometric lock migration"
+ "FBA already locked by AppProtection; clearing legacy biometric lock preference"
+ "Failed to enable AppProtection lock during migration: [%{public}@]"
+ "Migrated legacy biometric lock preference to AppProtection lock"
+ "TB,N,V_didAttemptBiometricLockMigration"
+ "_didAttemptBiometricLockMigration"
+ "applicationWithBundleIdentifier:"
+ "canChangeLockedStatusOfSubject:"
+ "didAttemptBiometricLockMigration"
+ "initiateAuthenticationWithShieldingForSubject:completion:"
+ "isLocked"
+ "migrateLegacyBiometricLockToAppProtection"
+ "setDidAttemptBiometricLockMigration:"
+ "setHoverStyle:"
+ "setSubject:isLocked:error:"
+ "sharedGuard"
+ "sharedManager"
- "@\"LAContext\""
- "@\"NSTimer\""
- "@\"UIVisualEffectView\""
- "After %lu minutes"
- "Already evaluating biometrics"
- "Application is active and logged in. Biometric state [%lu]"
- "Biometric callback"
- "Biometric evaluation began with context [%@]"
- "Biometric evaluation completed"
- "Biometric evaluation pending. Will perform evaluation"
- "Biometric unlock cancelled by system – likely that user went home."
- "Biometric unlock cancelled by user - likely that user pressed Cancel (suspending)."
- "Biometric unlock failed - not authenticated"
- "Biometric unlock failed - unknown error."
- "Biometric unlock succeeded"
- "Biometric unlock unavailable - biometry is in lockout."
- "Biometrics Evaluation stuck evaluating. Will lock out"
- "Biometrics Evaluation stuck in cancelled state. Will lock out"
- "Biometrics Evaluation stuck in state [%lu]"
- "Biometrics authentication enabled"
- "Biometrics authentication has not timed out"
- "Biometrics authentication is not enabled"
- "Biometrics disabled. Will not save bio timer"
- "Biometrics evaluation callback"
- "Biometrics evaluation completed in background"
- "Biometrics evaluation happened while app was in background - Retrying"
- "Biometrics evaluation timer fired. Current state [%lu], Active? [%i]"
- "Biometrics handler context does not match last used context. Ignoring result"
- "Biometrics stuck - locking out"
- "Did add blur view"
- "FACE_ID_NOT_ENROLLED"
- "FACE_ID_NOT_ENROLLED_MESSAGE"
- "FACE_ID_PREFERENCE"
- "FACE_ID_PROMPT"
- "FACE_ID_REQUIRE"
- "Not Authenticated. Will not save bio timer"
- "Plurals"
- "Saving biometrics date [%@]"
- "SupportsBiometricsLock"
- "T@\"LAContext\",&,N,V_lastUsedLAContext"
- "T@\"NSTimer\",&,V_biometricsWatchDog"
- "T@\"UILabel\",W,N,V_requireTouchIDCellLabel"
- "T@\"UILabel\",W,N,V_touchIDTimeoutLabel"
- "T@\"UILabel\",W,N,V_useTouchIDSwitchCellLabel"
- "T@\"UISwitch\",W,N,V_touchIDSwitch"
- "T@\"UITableViewCell\",W,N,V_touchIDCell"
- "T@\"UIVisualEffectView\",&,N,V_blurView"
- "TB,N,V_hideTouchID"
- "TOUCH_ID_NOT_ENROLLED"
- "TOUCH_ID_NOT_ENROLLED_MESSAGE"
- "TOUCH_ID_PREFERENCE"
- "TOUCH_ID_PROMPT"
- "TOUCH_ID_REQUIRE"
- "TQ,R,V_biometricsState"
- "TimeoutCell"
- "Timer Fired, Authenticated, blurView visible? [%i]"
- "TouchIDEnableRequestShown"
- "TouchIDLastRequested"
- "TouchIDPreferenceCell"
- "TouchIDTimeoutDuration"
- "Will add blur view"
- "Will remove blur view"
- "_biometricsState"
- "_biometricsWatchDog"
- "_blurView"
- "_evaluationPolicy"
- "_hideTouchID"
- "_invalidateWatchDogTimer"
- "_lastUsedLAContext"
- "_logOutForBiometricsAuthFailure"
- "_performBiometricsEvaluationWithContext:"
- "_requireTouchIDCellLabel"
- "_startBiometricsTimer"
- "_touchIDCell"
- "_touchIDDidTimeout"
- "_touchIDSwitch"
- "_touchIDTimeoutLabel"
- "_useTouchIDSwitchCellLabel"
- "addBlurView"
- "bio"
- "biometricsState"
- "biometricsWatchDog"
- "blurView"
- "canEvaluatePolicy:error:"
- "cellConfiguration"
- "context [%@] last context used [%@]"
- "date"
- "dateWithTimeIntervalSince1970:"
- "deviceSupportsFaceID"
- "dictionary"
- "did remove blur view"
- "didToggleTouchID:"
- "effectWithStyle:"
- "evaluatePolicy:localizedReason:reply:"
- "handleInteractiveLoginResultWithLoginManager:pendingUI:startupFailures:skipBiometrics:"
- "hideTouchID"
- "iFBAPreferencesTimeoutViewController"
- "initWithEffect:"
- "invalidate"
- "lastUsedLAContext"
- "newLAContext"
- "not logged in, removing blur view"
- "performBiometricAuthenticationIfNeeded"
- "q24@0:8q16"
- "removeBlurView"
- "requireTouchIDCellLabel"
- "rowForTimeout:"
- "saveBiometricsDate"
- "scheduledTimerWithTimeInterval:repeats:block:"
- "setBiometricsState:"
- "setBiometricsWatchDog:"
- "setBlurView:"
- "setHideTouchID:"
- "setLastUsedLAContext:"
- "setOn:"
- "setRequireTouchIDCellLabel:"
- "setTouchIDCell:"
- "setTouchIDSwitch:"
- "setTouchIDTimeoutLabel:"
- "setUseTouchIDSwitchCellLabel:"
- "supportsBiometricsLock"
- "suspendReturningToLastApp:"
- "timeIntervalSinceDate:"
- "timeoutForRow:"
- "touchIDCell"
- "touchIDSwitch"
- "touchIDTimeoutLabel"
- "useTouchIDSwitchCellLabel"
- "v16@?0@\"NSTimer\"8"
- "v44@0:8@16Q24Q32B40"
- "will perform biometric evaluation if needed"
- "\xd1"
```
