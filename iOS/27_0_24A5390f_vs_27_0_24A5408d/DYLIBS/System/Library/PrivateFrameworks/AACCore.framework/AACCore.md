## AACCore

> `/System/Library/PrivateFrameworks/AACCore.framework/AACCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1201c` | `0x1254c` | **`+0x530`** |
| `__TEXT.__cstring` | `0x1a7b` | `0x1b91` | **`+0x116`** |
| `__AUTH_CONST.__objc_const` | `0x47e0` | `0x4888` | **`+0xa8`** |
| `__AUTH_CONST.__cfstring` | `0x1660` | `0x1700` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x1a94` | `0x1afc` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0xcc0` | `0xd08` | **`+0x48`** |
| `__DATA.__objc_ivar` | `0x28c` | `0x2a0` | **`+0x14`** |
| `__DATA_CONST.__objc_catlist` | `0x38` | `0x30` | **`-0x8`** |

### Other Changes

```diff

-56.0.0.0.0
+56.0.3.0.0

-  Functions: 613
-  Symbols:   1493
-  CStrings:  224
+  Functions: 623
+  Symbols:   1505
+  CStrings:  229
Symbols:
+ -[AEAssessmentApplicationDescriptor executablePath]
+ -[AEAssessmentApplicationDescriptor initWithExecutablePath:teamIdentifier:requiresSignatureValidation:]
+ -[AEAssessmentState _allowsAccessibilityIntelligence]
+ -[AEAssessmentState _allowsVisualIntelligence]
+ -[AEAssessmentState allowVirtualMachine]
+ -[AEAssessmentState allowsForceQuit]
+ -[AEAssessmentState setAllowVirtualMachine:]
+ -[AEAssessmentState setAllowsForceQuit:]
+ -[AEAssessmentState set_allowsAccessibilityIntelligence:]
+ -[AEAssessmentState set_allowsVisualIntelligence:]
+ -[AEPreferences useDeviceConfigurationProvider]
+ _OBJC_IVAR_$_AEAssessmentApplicationDescriptor._executablePath
+ _OBJC_IVAR_$_AEAssessmentState.__allowsAccessibilityIntelligence
+ _OBJC_IVAR_$_AEAssessmentState.__allowsVisualIntelligence
+ _OBJC_IVAR_$_AEAssessmentState._allowVirtualMachine
+ _OBJC_IVAR_$_AEAssessmentState._allowsForceQuit
- -[NSData(AEAdditions) ae_hexString]
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSData_$_AEAdditions
- __OBJC_$_CATEGORY_NSData_$_AEAdditions
- __OBJC_$_PROP_LIST_NSData_$_AEAdditions
CStrings:
+ "<%@: %p { bundleIdentifier = %@, teamIdentifier = %@, requiresSignatureValidation = %@, pid = %@, executablePath = %@ }>"
+ "<%@: %p { isEnabled = %@, mainIndividualConfiguration = %@, configurationsByApplicationDescriptor = %@, allowsAutoCorrection = %@, allowsSmartPunctuation = %@, allowsSpellCheck = %@, allowsPredictiveKeyboard = %@, allowsActivityContinuation = %@, allowsDictation = %@, allowsAccessibilityAlternativeInputMethods = %@, allowsAccessibilityBackgroundSounds = %@, allowsAccessibilityFullKeyboardAccess = %@, allowsAccessibilityHoverText = %@, allowsAccessibilityKeyboard = %@, allowsAccessibilityLiveCaptions = %@, allowsAccessibilityLiveSpeech = %@, allowsAccessibilityReader = %@, allowsAccessibilitySpeech = %@, allowsAccessibilitySpokenContent = %@, allowsAccessibilitySwitchControl = %@, allowsAccessibilityTypingFeedback = %@, allowsAccessibilityVoiceControl = %@, allowsAccessibilityVoiceOver = %@, allowsAccessibilityZoom = %@, allowsPasswordAutoFill = %@, allowsContinuousPathKeyboard = %@, allowsKeyboardShortcuts = %@, allowsKeyboardMathSolving = %@, allowsMathPaperSolving = %@, allowsScreenshots = %@, allowsEmojiKeyboard = %@, allowedAppleMenuItems = %@, allowedDirectoriesAndFiles = %@, allowsAutoFill = %@, allowsStructuralInput = %@, allowsDock = %@, allowsMenuBar = %@, allowedMenuBarItems = %@, allowsUserScriptExecution = %@, allowOnlyParticipantsToRun = %@, allowsForceQuit = %@, maxBluetoothDevicesAllowed = %@, allowedBluetoothDeviceNames = %@, allowedBluetoothProfiles = %@, allowLockdownMode = %@, allowPrivateRelay = %@, allowVirtualMachine = %@, requiresManagedDevice = %@, requiresSIP = %@, requiresSingleUser = %@, requiresUserAccountType = %ld, _allowedCollaborationIDs = %@, _allowsAccessibilityIntelligence = %@, _allowsAirPlay = %@, _allowsContentCapture = %@, _allowsDonatingClipboardHistoryToSpotlight = %@, _allowsNetworkAccess = %@, _allowsSharingServices = %@, _allowsSpotlight = %@, _allowsVisualIntelligence = %@}>"
+ "UseDeviceConfigurationProvider"
+ "_allowsAccessibilityIntelligence"
+ "_allowsVisualIntelligence"
+ "allowVirtualMachine"
+ "allowsForceQuit"
+ "executablePath"
- "%02x"
- "<%@: %p { bundleIdentifier = %@, teamIdentifier = %@, requiresSignatureValidation = %@, pid = %@ }>"
- "<%@: %p { isEnabled = %@, mainIndividualConfiguration = %@, configurationsByApplicationDescriptor = %@, allowsAutoCorrection = %@, allowsSmartPunctuation = %@, allowsSpellCheck = %@, allowsPredictiveKeyboard = %@, allowsActivityContinuation = %@, allowsDictation = %@, allowsAccessibilityAlternativeInputMethods = %@, allowsAccessibilityBackgroundSounds = %@, allowsAccessibilityFullKeyboardAccess = %@, allowsAccessibilityHoverText = %@, allowsAccessibilityKeyboard = %@, allowsAccessibilityLiveCaptions = %@, allowsAccessibilityLiveSpeech = %@, allowsAccessibilityReader = %@, allowsAccessibilitySpeech = %@, allowsAccessibilitySpokenContent = %@, allowsAccessibilitySwitchControl = %@, allowsAccessibilityTypingFeedback = %@, allowsAccessibilityVoiceControl = %@, allowsAccessibilityVoiceOver = %@, allowsAccessibilityZoom = %@, allowsPasswordAutoFill = %@, allowsContinuousPathKeyboard = %@, allowsKeyboardShortcuts = %@, allowsKeyboardMathSolving = %@, allowsMathPaperSolving = %@, allowsScreenshots = %@, allowsEmojiKeyboard = %@, allowedAppleMenuItems = %@, allowedDirectoriesAndFiles = %@, allowsAutoFill = %@, allowsStructuralInput = %@, allowsDock = %@, allowsMenuBar = %@, allowedMenuBarItems = %@, allowsUserScriptExecution = %@, allowOnlyParticipantsToRun = %@, maxBluetoothDevicesAllowed = %@, allowedBluetoothDeviceNames = %@, allowedBluetoothProfiles = %@, allowLockdownMode = %@, allowPrivateRelay = %@, requiresManagedDevice = %@, requiresSIP = %@, requiresSingleUser = %@, requiresUserAccountType = %ld, _allowedCollaborationIDs = %@, _allowsAirPlay = %@, _allowsContentCapture = %@, _allowsDonatingClipboardHistoryToSpotlight = %@, _allowsNetworkAccess = %@, _allowsSharingServices = %@, _allowsSpotlight = %@}>"
```
