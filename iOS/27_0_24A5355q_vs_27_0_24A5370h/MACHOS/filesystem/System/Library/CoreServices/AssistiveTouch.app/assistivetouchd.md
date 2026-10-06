## assistivetouchd

> `/System/Library/CoreServices/AssistiveTouch.app/assistivetouchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15fa50` | `0x15e3c0` | **`-0x1690`** |
| `__TEXT.__cstring` | `0xd651` | `0xddfe` | **`+0x7ad`** |
| `__TEXT.__objc_methname` | `0x36f40` | `0x376e0` | **`+0x7a0`** |
| `__TEXT.__objc_stubs` | `0x2b1a0` | `0x2b660` | **`+0x4c0`** |
| `__TEXT.__oslogstring` | `0x6844` | `0x6c4f` | **`+0x40b`** |
| `__DATA.__bss` | `0x5080` | `0x4cb0` | **`-0x3d0`** |
| `__TEXT.__const` | `0x4960` | `0x45a0` | **`-0x3c0`** |
| `__DATA_CONST.__const` | `0x6d58` | `0x6a20` | **`-0x338`** |
| `__DATA.__objc_const` | `0x1c088` | `0x1c368` | **`+0x2e0`** |
| `__TEXT.__objc_methlist` | `0x1513c` | `0x1537c` | **`+0x240`** |
| `__DATA.__objc_selrefs` | `0xc158` | `0xc2b8` | **`+0x160`** |
| `__TEXT.__unwind_info` | `0x6058` | `0x5f08` | **`-0x150`** |
| `__DATA.__data` | `0x4060` | `0x41a0` | **`+0x140`** |
| `__DATA.__objc_data` | `0x5ec0` | `0x5ff8` | **`+0x138`** |
| `__TEXT.__swift5_capture` | `0x87c` | `0x754` | **`-0x128`** |
| `__TEXT.__swift5_reflstr` | `0xe8f` | `0xf7f` | **`+0xf0`** |
| `__TEXT.__eh_frame` | `0x4730` | `0x4810` | **`+0xe0`** |
| `__TEXT.__objc_classname` | `0x298c` | `0x2a44` | **`+0xb8`** |
| `__DATA_CONST.__cfstring` | `0x9dc0` | `0x9e60` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x1cb8` | `0x1c1c` | **`-0x9c`** |
| `__TEXT.__objc_methtype` | `0x754b` | `0x75ba` | **`+0x6f`** |
| `__DATA_CONST.__auth_ptr` | `0xb18` | `0xb68` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x3fe0` | `0x4030` | **`+0x50`** |
| `__TEXT.__swift5_proto` | `0x2b0` | `0x260` | **`-0x50`** |
| `__TEXT.__swift5_types` | `0x17c` | `0x12c` | **`-0x50`** |
| `__TEXT.__swift_as_entry` | `0x41c` | `0x3d8` | **`-0x44`** |
| `__TEXT.__swift5_assocty` | `0x2e8` | `0x2b8` | **`-0x30`** |
| `__DATA_CONST.__auth_got` | `0x2000` | `0x2028` | **`+0x28`** |
| `__TEXT.__swift5_builtin` | `0x208` | `0x1e0` | **`-0x28`** |
| `__TEXT.__swift_as_cont` | `0x32c` | `0x304` | **`-0x28`** |
| `__TEXT.__swift_as_ret` | `0x170` | `0x150` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x1af0` | `0x1b08` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0xf54` | `0xf64` | **`+0x10`** |
| `__DATA.__common` | `0xb0` | `0xb8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x730` | `0x738` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x1561` | `0x1568` | **`+0x7`** |

### Same-size Content Changes

- `__DATA.__objc_ivar`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-1494.0.0.0.0
+1497.0.0.0.0

+  - /System/Library/PrivateFrameworks/WorkflowKit.framework/WorkflowKit

-  Functions: 9247
-  Symbols:   2265
-  CStrings:  11769
+  Functions: 9167
+  Symbols:   2274
+  CStrings:  11874
Symbols:
+ _$s28AccessibilitySharedUISupport0A15FloatingUIStateC10setVisible_8animatedySb_SbtF
+ _$s7SwiftUI4PathVN
+ _$sSdN
+ _$sSds7CVarArgsWP
+ _$sSo8NSObjectC10ObjectiveCE2eeoiySbAB_ABtFZ
+ __AXSLoadAuxiliaryBundlesWithName
+ _kAXScreenChangePopup
+ _swift_allocBox
+ _swift_deletedAsyncMethodErrorTu
+ _swift_makeBoxUnique
+ _swift_retain_x8
- _$s7SwiftUI19UIHostingControllerC8rootViewxvgTj
- _swift_isaMask
CStrings:
+ "*** Menu dismissed; saving menu-origin element for custom-action restore: %{public}@"
+ "*** Screen will change; saving element before change: %{public}@ (popup=%d)"
+ "<nil>"
+ "AXSCATAvoidanceRegionDidChangeNotification"
+ "Active display change candidate=%{public}@ (settledActive=%{public}@ prevForegroundActive=%{BOOL}d); commit in %.2fs or when prev leaves foreground"
+ "Active display change flicker cancelled (settledActive=%{public}@)"
+ "Active display change settled to same display; ignoring (display=%{public}@)"
+ "Active display changed (prev=%{public}@ new=%{public}@). Reset gaze enrollment (wasEnrolled=%{BOOL}d)."
+ "Calibration debounce fired but target is no longer active (target=%{public}@ active=%{public}@)"
+ "Calibration debounce fired with stale occupant; dismissing and retrying (occupant=%{public}@ target=%{public}@)"
+ "Calibration finished presenting on stale display; dismissing (presented=%{public}@ active=%{public}@)"
+ "Calibration request for non-active display ignored (target=%{public}@ active=%{public}@ reason=%{public}@)"
+ "EyeTrackingCoordinator: dismissCalibrationUI called with no presentedViewController; treating as already dismissed"
+ "EyeTrackingCoordinator: showCalibrationUI ignored - calibration is already presented; converging state"
+ "HNDCalibrationCoordinator"
+ "HNDDisplayManager displayOrientation: id=%{public}@ scene=%@ interfaceOrientation=%ld deviceOrientation=%d -> %d"
+ "Hiding emergency-tap alert due to active display change"
+ "In-flight present watchdog fired; didShow never arrived. Clearing inFlightTarget (display=%{public}@)"
+ "Pending candidate left foreground; cancelling pending change (display=%{public}@)"
+ "Presenting calibration on display=%{public}@ reason=%{public}@"
+ "Registering global mouse events for displayID=%u contextID=%u hardwareIdentifier=%{public}@"
+ "Restoring focus to element before popup: %{public}@"
+ "SCATIcon_device_atv_remote"
+ "Scene did become active, active display=%{public}@"
+ "Scene will resign active, display=%{public}@"
+ "Settings-Scan-ATV-Remote"
+ "Settle fired but lastActive moved on; deferring (candidate=%{public}@ lastActive=%{public}@)"
+ "Settled active display left foreground; committing pending change immediately (display=%{public}@)"
+ "Skipping global mouse event registration: already registered for displayID=%u (existing contextID=%u, requested=%u)"
+ "Skipping global mouse event registration: contextID is 0 (displayID=%u, hardwareIdentifier=%{public}@)"
+ "T@\"<SCATElement>\",&,N,V_elementBeforePopup"
+ "T@\"HNDCalibrationCoordinator\",N,R"
+ "T@\"HNDDisplayManager\",N,&,VpresentingDisplay"
+ "T@\"HNDDisplayManager\",W,N,V_lastActiveDisplay"
+ "TB,N,VemergencyAlertVisible"
+ "TB,N,VfaceGuidanceComplete"
+ "Td,N,V_lastPopupTime"
+ "Td,N,V_lastRestoredElementBeforePopupTime"
+ "T{CGPoint=dd},N,V_avoidanceRegionOffset"
+ "_avoidanceRegionInView:"
+ "_avoidanceRegionOffset"
+ "_axAvoidanceRegionDidChange:"
+ "_displayManagerForScene:"
+ "_elementBeforePopup"
+ "_handleScreenWillChangeNotification:"
+ "_lastActiveDisplay"
+ "_lastPopupTime"
+ "_lastRestoredElementBeforePopupTime"
+ "_scanningModeForExitFromTrackingMode"
+ "_title:image:forExitDestination:"
+ "activationState"
+ "active-display-change"
+ "activeChangeSettleTimer"
+ "activeDisplayDidChangeFromDisplay:toDisplay:"
+ "assistiveTouchPreviousScanningMode"
+ "assistivetouchd4"
+ "assistivetouchd5"
+ "assistivetouchd6"
+ "assistivetouchd7"
+ "avoidanceRegionOffset"
+ "cancelPendingPresentation"
+ "debounceTimer"
+ "didCompleteFaceGuidanceOnDisplay:"
+ "didDismissCalibrationUIOnDisplay:"
+ "didShowCalibrationUIOnDisplay:"
+ "dismissCalibration"
+ "dismissCalibrationUIIfPresented"
+ "dismissingDueToForceDismiss"
+ "dismissingDueToStaleDisplay"
+ "displayOrientation"
+ "displaySceneLeftForegroundActiveOnDisplay:"
+ "effectiveGeometry"
+ "elementBeforePopup"
+ "emergencyAlertVisible"
+ "forceDismissCalibrationWithReason:onDisplay:"
+ "forceDismissReason"
+ "handleEmergencyTapForceDismiss"
+ "hideAlert"
+ "inFlightTarget"
+ "inFlightWatchdogTimer"
+ "interfaceOrientation"
+ "isAnyDisplayShowingCalibrationUI"
+ "lastActiveDisplay"
+ "lastPopupTime"
+ "lastRestoredElementBeforePopupTime"
+ "needsRecalibrationInternal"
+ "needsRecalibrationOnDisplay:"
+ "paused for likely screen change; suppressing rescan from top because we just restored elementBeforePopup"
+ "pendingActiveDisplay"
+ "pendingDisplay"
+ "presentCalibrationUIIfPossible"
+ "presentCalibrationUIIfPossible returned NO; clearing inFlightTarget (display=%{public}@)"
+ "presentCalibrationUIIfPossible: prevented by error code %ld"
+ "presentCalibrationUIIfPossible: skipping - shouldShowUncalibratedPoints is set"
+ "presentingDisplay"
+ "requestCalibrationOnDisplay:reason:"
+ "resetForceDismissReason"
+ "sceneDidBecomeActive: displayID=%u contextID=%u hardwareIdentifier=%{public}@"
+ "sceneDidBecomeActive: no displayManager for scene yet (hardwareIdentifier=%{public}@)"
+ "screenWillChange:data:"
+ "setAssistiveTouchPreviousScanningMode:"
+ "setAvoidanceRegionOffset:"
+ "setElementBeforePopup:"
+ "setEmergencyAlertVisible:"
+ "setLastActiveDisplay:"
+ "setLastPopupTime:"
+ "setLastRestoredElementBeforePopupTime:"
+ "setNeedsRecalibration"
+ "setNeedsRecalibration:onDisplay:"
+ "setNubbitVisible:animated:"
+ "setPresentingDisplay:"
+ "settledActiveDisplay"
+ "stale-dismiss-retry"
+ "v28@0:8I16@20"
+ "v40@0:8@\"AVCaptureMetadataOutput\"16@\"NSArray\"24@\"AVCaptureConnection\"32"
+ "v40@0:8^@16^@24q32"
+ "was not scanning the keyboard; suppressing rescan from top because we just restored elementBeforePopup"
+ "willShowCalibrationUIOnDisplay:"
+ "windowSceneActivationState"
+ "\xf0\xf0\xc1"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0A"
- "EyeTrackingCoordinator: dismissCalibrationUI called but no presentedViewController found"
- "TB,N,V_faceGuidanceComplete"
- "TB,N,V_isActiveDisplay"
- "TB,N,V_needsRecalibration"
- "_faceGuidanceComplete"
- "_forceCalibrationDismissReason"
- "_isActiveDisplay"
- "_needsRecalibration"
- "_showingCalibrationUI"
- "screenWillChange:"
- "setActiveDisplayWithHardwareIdentifier:"
- "setIsActiveDisplay:"
- "showCalibrationUI: prevented by error code %ld"
- "showCalibrationUI: skipping - shouldShowUncalibratedPoints is set"
- "v40@0:8@\"AVCaptureOutput\"16@\"NSArray\"24@\"AVCaptureConnection\"32"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0a"
```
