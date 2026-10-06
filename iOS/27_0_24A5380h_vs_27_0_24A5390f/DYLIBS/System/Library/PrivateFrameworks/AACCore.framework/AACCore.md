## AACCore

> `/System/Library/PrivateFrameworks/AACCore.framework/AACCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xe10` | `—` | **`-0xe10`** |
| `__DATA_DIRTY.__objc_data` | `0x370` | `0x1180` | **`+0xe10`** |
| `__TEXT.__text` | `0x11f20` | `0x1201c` | **`+0xfc`** |
| `__TEXT.__cstring` | `0x1a29` | `0x1a7b` | **`+0x52`** |
| `__AUTH_CONST.__objc_const` | `0x47b0` | `0x47e0` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x1640` | `0x1660` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1a7c` | `0x1a94` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xcb0` | `0xcc0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x288` | `0x28c` | **`+0x4`** |

### Other Changes

```diff

-55.0.0.0.0
+56.0.0.0.0

-  Functions: 611
-  Symbols:   1490
-  CStrings:  223
+  Functions: 613
+  Symbols:   1493
+  CStrings:  224
Symbols:
+ -[AEAssessmentState allowsAccessibilityFullKeyboardAccess]
+ -[AEAssessmentState setAllowsAccessibilityFullKeyboardAccess:]
+ _OBJC_IVAR_$_AEAssessmentState._allowsAccessibilityFullKeyboardAccess
CStrings:
+ "<%@: %p { isEnabled = %@, mainIndividualConfiguration = %@, configurationsByApplicationDescriptor = %@, allowsAutoCorrection = %@, allowsSmartPunctuation = %@, allowsSpellCheck = %@, allowsPredictiveKeyboard = %@, allowsActivityContinuation = %@, allowsDictation = %@, allowsAccessibilityAlternativeInputMethods = %@, allowsAccessibilityBackgroundSounds = %@, allowsAccessibilityFullKeyboardAccess = %@, allowsAccessibilityHoverText = %@, allowsAccessibilityKeyboard = %@, allowsAccessibilityLiveCaptions = %@, allowsAccessibilityLiveSpeech = %@, allowsAccessibilityReader = %@, allowsAccessibilitySpeech = %@, allowsAccessibilitySpokenContent = %@, allowsAccessibilitySwitchControl = %@, allowsAccessibilityTypingFeedback = %@, allowsAccessibilityVoiceControl = %@, allowsAccessibilityVoiceOver = %@, allowsAccessibilityZoom = %@, allowsPasswordAutoFill = %@, allowsContinuousPathKeyboard = %@, allowsKeyboardShortcuts = %@, allowsKeyboardMathSolving = %@, allowsMathPaperSolving = %@, allowsScreenshots = %@, allowsEmojiKeyboard = %@, allowedAppleMenuItems = %@, allowedDirectoriesAndFiles = %@, allowsAutoFill = %@, allowsStructuralInput = %@, allowsDock = %@, allowsMenuBar = %@, allowedMenuBarItems = %@, allowsUserScriptExecution = %@, allowOnlyParticipantsToRun = %@, maxBluetoothDevicesAllowed = %@, allowedBluetoothDeviceNames = %@, allowedBluetoothProfiles = %@, allowLockdownMode = %@, allowPrivateRelay = %@, requiresManagedDevice = %@, requiresSIP = %@, requiresSingleUser = %@, requiresUserAccountType = %ld, _allowedCollaborationIDs = %@, _allowsAirPlay = %@, _allowsContentCapture = %@, _allowsDonatingClipboardHistoryToSpotlight = %@, _allowsNetworkAccess = %@, _allowsSharingServices = %@, _allowsSpotlight = %@}>"
+ "allowsAccessibilityFullKeyboardAccess"
- "<%@: %p { isEnabled = %@, mainIndividualConfiguration = %@, configurationsByApplicationDescriptor = %@, allowsAutoCorrection = %@, allowsSmartPunctuation = %@, allowsSpellCheck = %@, allowsPredictiveKeyboard = %@, allowsActivityContinuation = %@, allowsDictation = %@, allowsAccessibilityAlternativeInputMethods = %@, allowsAccessibilityBackgroundSounds = %@, allowsAccessibilityHoverText = %@, allowsAccessibilityKeyboard = %@, allowsAccessibilityLiveCaptions = %@, allowsAccessibilityLiveSpeech = %@, allowsAccessibilityReader = %@, allowsAccessibilitySpeech = %@, allowsAccessibilitySpokenContent = %@, allowsAccessibilitySwitchControl = %@, allowsAccessibilityTypingFeedback = %@, allowsAccessibilityVoiceControl = %@, allowsAccessibilityVoiceOver = %@, allowsAccessibilityZoom = %@, allowsPasswordAutoFill = %@, allowsContinuousPathKeyboard = %@, allowsKeyboardShortcuts = %@, allowsKeyboardMathSolving = %@, allowsMathPaperSolving = %@, allowsScreenshots = %@, allowsEmojiKeyboard = %@, allowedAppleMenuItems = %@, allowedDirectoriesAndFiles = %@, allowsAutoFill = %@, allowsStructuralInput = %@, allowsDock = %@, allowsMenuBar = %@, allowedMenuBarItems = %@, allowsUserScriptExecution = %@, allowOnlyParticipantsToRun = %@, maxBluetoothDevicesAllowed = %@, allowedBluetoothDeviceNames = %@, allowedBluetoothProfiles = %@, allowLockdownMode = %@, allowPrivateRelay = %@, requiresManagedDevice = %@, requiresSIP = %@, requiresSingleUser = %@, requiresUserAccountType = %ld, _allowedCollaborationIDs = %@, _allowsAirPlay = %@, _allowsContentCapture = %@, _allowsDonatingClipboardHistoryToSpotlight = %@, _allowsNetworkAccess = %@, _allowsSharingServices = %@, _allowsSpotlight = %@}>"
```
