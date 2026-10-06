## GAXSpringboardServer

> `/System/Library/AccessibilityBundles/GAXSpringboardServer.bundle/GAXSpringboardServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x158bc` | `0x15b8c` | **`+0x2d0`** |
| `__DATA.__objc_const` | `0x3df8` | `0x3ce0` | **`-0x118`** |
| `__TEXT.__oslogstring` | `0x19d7` | `0x1ac0` | **`+0xe9`** |
| `__DATA.__objc_data` | `0x1bd0` | `0x1b30` | **`-0xa0`** |
| `__DATA_CONST.__const` | `0x1188` | `0x1218` | **`+0x90`** |
| `__TEXT.__objc_stubs` | `0x2e80` | `0x2f00` | **`+0x80`** |
| `__DATA_CONST.__cfstring` | `0x4bc0` | `0x4c20` | **`+0x60`** |
| `__TEXT.__objc_classname` | `0xd4f` | `0xcff` | **`-0x50`** |
| `__TEXT.__gcc_except_tab` | `0x42c` | `0x46c` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1f04` | `0x1ec4` | **`-0x40`** |
| `__TEXT.__objc_methname` | `0x58cb` | `0x590b` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x14a8` | `0x14c0` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x2c8` | `0x2b8` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x6c8` | `0x6d8` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x160` | `0x158` | **`-0x8`** |
| `__TEXT.__objc_methtype` | `0xf7a` | `0xf7e` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__cstring`

### Other Changes

```diff

-1061.0.0.0.0
+1064.0.0.0.0

-  Functions: 544
-  Symbols:   546
-  CStrings:  1578
+  Functions: 543
+  Symbols:   543
+  CStrings:  1585
Symbols:
+ _GAXUIMessageKeyShouldDriveSiriAssessmentRestriction
- _OBJC_CLASS_$_GAXSBSBLockScreenOrientationManager
- _OBJC_CLASS_$___GAXSBSBLockScreenOrientationManager_super
- _OBJC_METACLASS_$_GAXSBSBLockScreenOrientationManager
- _OBJC_METACLASS_$___GAXSBSBLockScreenOrientationManager_super
CStrings:
+ "Could not make SpringBoard frontmost within %.0f seconds; failing fast so GAX releases the input block"
+ "Guided Access orientation restore"
+ "Guided Access restoring TraitsArbiter orientation on exit (userLocked=%d orientation=%ld)"
+ "SBHomeButtonPressHandler"
+ "SBOrientationLockManager"
+ "SBPolicyAggregator"
+ "SBReachabilityController"
+ "Session app (%@) is already foreground and running; skipping making SpringBoard frontmost"
+ "TRAArbiter"
+ "TRAArbiterUpdateContext"
+ "configureWithWorkspaceEntity:referenceFrame:contentOrientation:containerOrientation:layoutRole:sbsDisplayLayoutRole:zOrderIndex:spaceConfiguration:floatingConfiguration:hasClassicAppOrientationMismatch:sizingPolicy:"
+ "homeButtonPressHandler"
+ "iconModel"
+ "idleTimerGlobalCoordinator"
+ "initWithBuilder:"
+ "isUserLocked"
+ "reduceAmbientFullScreenLiveActivityWithServerInstance:"
+ "setNeedsUpdateArbitrationWithContext:"
+ "setReason:"
+ "setUserInteractionEnabled:"
+ "should drive siri assessment restriction"
+ "systemGestureManager"
+ "userLockOrientation"
+ "v124@0:8@16{CGRect={CGPoint=dd}{CGSize=dd}}24q56q64q72q80q88q96q104B112q116"
+ "validateClass:hasProperty:withType:"
- "GAXSBSBLockScreenOrientationManager"
- "Guided Access orientation unlock"
- "Guided Access unlocking TraitsArbiter orientation"
- "SBLockScreenOrientationManager"
- "SBMainDisplayPolicyAggregator"
- "SBReachabilityManager"
- "SBUIController"
- "TRAArbitrator"
- "__GAXSBSBLockScreenOrientationManager_super"
- "_shouldBeginFloatingApplicationPinGesture:"
- "_uiController"
- "appSwitcherHeaderIconImageCache"
- "configureWithWorkspaceEntity:referenceFrame:contentOrientation:containerOrientation:layoutRole:sbsDisplayLayoutRole:spaceConfiguration:floatingConfiguration:hasClassicAppOrientationMismatch:sizingPolicy:"
- "model"
- "scene:didReceiveActions:"
- "setNeedsUpdateArbitrationWithReason:"
- "updateInterfaceOrientationWithRequestedOrientation:animated:"
- "v116@0:8@16{CGRect={CGPoint=dd}{CGSize=dd}}24q56q64q72q80q88q96B104q108"
```
