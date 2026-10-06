## ClarityBoard

> `/System/Library/CoreServices/ClarityBoard.app/ClarityBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x285cec` | `0x28866c` | **`+0x2980`** |
| `__TEXT.__objc_methname` | `0x11035` | `0x11645` | **`+0x610`** |
| `__TEXT.__oslogstring` | `0x6892` | `0x6c5d` | **`+0x3cb`** |
| `__TEXT.__objc_stubs` | `0xb3c0` | `0xb740` | **`+0x380`** |
| `__DATA.__objc_const` | `0x9880` | `0x9bc8` | **`+0x348`** |
| `__TEXT.__objc_methlist` | `0x5174` | `0x534c` | **`+0x1d8`** |
| `__DATA.__data` | `0x7e58` | `0x8008` | **`+0x1b0`** |
| `__TEXT.__const` | `0x272a8` | `0x27458` | **`+0x1b0`** |
| `__DATA_CONST.__const` | `0x190f0` | `0x19260` | **`+0x170`** |
| `__DATA.__objc_selrefs` | `0x3cc0` | `0x3dc8` | **`+0x108`** |
| `__DATA.__objc_data` | `0x43e0` | `0x44c8` | **`+0xe8`** |
| `__TEXT.__objc_methtype` | `0x3fea` | `0x40c3` | **`+0xd9`** |
| `__TEXT.__constg_swiftt` | `0x3ca8` | `0x3d80` | **`+0xd8`** |
| `__TEXT.__unwind_info` | `0x3ba8` | `0x3c68` | **`+0xc0`** |
| `__TEXT.__swift5_reflstr` | `0x2f18` | `0x2fc8` | **`+0xb0`** |
| `__TEXT.__objc_classname` | `0x169f` | `0x1744` | **`+0xa5`** |
| `__TEXT.__cstring` | `0x320b` | `0x32ae` | **`+0xa3`** |
| `__DATA.__bss` | `0x5f20` | `0x5fb0` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x23f0` | `0x2468` | **`+0x78`** |
| `__TEXT.__swift5_typeref` | `0xf6e6` | `0xf75c` | **`+0x76`** |
| `__DATA_CONST.__cfstring` | `0x1d00` | `0x1d40` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x3128` | `0x30f0` | **`-0x38`** |
| `__TEXT.__auth_stubs` | `0x4200` | `0x4230` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1530` | `0x1550` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x358` | `0x374` | **`+0x1c`** |
| `__DATA_CONST.__auth_got` | `0x2110` | `0x2128` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x1130` | `0x1148` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x348` | `0x360` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0xc68` | `0xc80` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x2f0` | `0x2fc` | **`+0xc`** |
| `__DATA_CONST.__objc_protolist` | `0x2d8` | `0x2e0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xf0` | `0xf8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x2d4` | `0x2d8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-158.0.0.0.0
+161.0.0.0.0

+  - /System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices

-  Functions: 5480
-  Symbols:   2131
-  CStrings:  4044
+  Functions: 5552
+  Symbols:   2139
+  CStrings:  4112
Symbols:
+ _AFIsLinwoodEnabledAndAvailable
+ _AFSystemAssistantExperienceAvailabilityDidChangeNotificationName
+ _AVSystemController_EffectiveVolumeNotificationParameter_ActiveAudioCategory
+ _AVSystemController_EffectiveVolumeNotificationParameter_Category
+ _OBJC_CLASS_$_BKSHIDUISensorMode
+ _OBJC_METACLASS_$_SiriPresentationViewController
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
CStrings:
+ "$__lazy_storage_$_mirroredDisplayProfileController"
+ "@\"<CLBLegacySiriPresentationViewControllerDelegate>\""
+ "@\"CLBProximityDetectionManager\""
+ "@48@0:8@16@24@32@40"
+ "Assistant Island enablement changed. isEnabled: %i"
+ "CLBAssistantIslandWorkspaceEnablementDidChangeNotification"
+ "CLBLegacySiriPresentationViewController"
+ "CLBLegacySiriPresentationViewControllerDelegate"
+ "CLBProximityDetectionManager"
+ "CLBProximityDetectionManager: foreground scene expects face contact"
+ "Cannot install legacy Siri keyboard deferring rule yet. Siri view controller is not in a window scene."
+ "Display system interface orientation changed from %s to %s. Display: %@"
+ "Effective volume changed: %f, reason: %@, active category: %@"
+ "Evaluating display preferences for %s. isActiveDisplay: %{bool}d, isBacklightOn: %{bool}d, shouldTurnOnDisplay: %{bool}d"
+ "Foreground scene expects face contact. Requesting HID proximity LowPowerActive mode."
+ "Found top level scene with no display identity: %@"
+ "Ignoring effective volume change for non-active category. Notification category: %@, active category: %@, volume: %f"
+ "Ignoring tap on app icon: %s, because we already have a current app: %s"
+ "No foreground scene expects face contact. Releasing HID proximity assertion."
+ "Removing legacy Siri keyboard deferring rule."
+ "Someone tried to call _frontMostAppOrientation before our display configurations were ready."
+ "T@\"<BSInvalidatable>\",&,N,V_legacySiriDeferringRule"
+ "T@\"<CLBLegacySiriPresentationViewControllerDelegate>\",W,N,V_appearanceDelegate"
+ "T@\"CLBProximityDetectionManager\",&,N,V_proximityDetectionManager"
+ "T@\"FBScene\",&,N,V_legacySiriScene"
+ "TB,N,V_hasForegroundSceneThatExpectsFaceContact"
+ "T{UIEdgeInsets=dddd},N,V_presentingSafeAreaInsets"
+ "Unexpectedly created new Siri scene without tearing down the earlier one."
+ "Unexpectedly missing keyboard host component for scene: %@"
+ "_TtC12ClarityBoard17BacklightObserver"
+ "_addLegacySiriDeferringRuleIfNeeded"
+ "_appearanceDelegate"
+ "_applyLegacySiriKeyboardPadding"
+ "_assistantAvailabilityDidChange:"
+ "_assistantIslandEnablementDidChange:"
+ "_cleanUpLegacySiriScene"
+ "_createAssistantIslandWorkspaceIfNeeded"
+ "_frontMostAppOrientation"
+ "_hasForegroundSceneThatExpectsFaceContact"
+ "_isEnabled"
+ "_legacySiriDeferringRule"
+ "_legacySiriScene"
+ "_presentingSafeAreaInsets"
+ "_proximityDetectionManager"
+ "_removeLegacySiriDeferringRuleIfNeeded"
+ "_sensorModeAssertion"
+ "_startTrackingEnablement"
+ "_updateLegacySiriSceneProperties"
+ "addDeferringRuleWithWindowScene:scene:reason:sceneViewController:"
+ "appearanceDelegate"
+ "applyInsetsToSceneSettings:scene:safeAreaInsets:bottomInset:sceneInterfaceOrientation:shouldPadForBackButton:isFullScreenNonClarityUIApp:"
+ "backlightObserver"
+ "buildModeForReason:builder:"
+ "hasForegroundSceneThatExpectsFaceContact"
+ "legacySiriDeferringRule"
+ "legacySiriPresentationViewControllerIsAppearing:"
+ "legacySiriScene"
+ "presentingSafeAreaInsets"
+ "proximityDetectionManager"
+ "proximityDetectionModes"
+ "requestUISensorMode:"
+ "setAppearanceDelegate:"
+ "setDigitizerEnabled:"
+ "setHasForegroundSceneThatExpectsFaceContact:"
+ "setLegacySiriDeferringRule:"
+ "setLegacySiriScene:"
+ "setPresentingSafeAreaInsets:"
+ "setProximityDetectionManager:"
+ "setProximityDetectionMode:"
+ "updateWithForegroundApplicationScenes:"
+ "v16@?0@\"BKSMutableHIDUISensorMode\"8"
+ "v24@0:8@\"CLBLegacySiriPresentationViewController\"16"
+ "v88@0:8@16@24{UIEdgeInsets=dddd}32d64q72B80B84"
+ "viewIsAppearing:"
- "Effective volume changed: %f. Reason: %@"
- "System interface orientation changed from %s to %s."
- "Updated rotation animation duration to %f."
- "hasSurfaceType2Display"
- "mirroredDisplayProfileController"
- "systemInterfaceOrientation"
```
