## BiometricKitUI

> `/System/Library/PrivateFrameworks/BiometricKitUI.framework/BiometricKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6ec9c` | `0x6fcfc` | **`+0x1060`** |
| `__TEXT.__oslogstring` | `0x6253` | `0x6573` | **`+0x320`** |
| `__TEXT.__gcc_except_tab` | `0xd34` | `0xde4` | **`+0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0x4880` | `0x48d0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1a78` | `0x1ac0` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x1260` | `0x1238` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0x3380` | `0x33a0` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x106a0` | `0x106c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x2fe6` | `0x2fc6` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x958` | `0x970` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x72a0` | `0x72b8` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x2aa` | `0x2c2` | **`+0x18`** |
| `__TEXT.__const` | `0xd34` | `0xd44` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x104` | `0x114` | **`+0x10`** |
| `__AUTH_CONST.__const` | `0xc48` | `0xc50` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x9f0` | `0x9f4` | **`+0x4`** |

### Other Changes

```diff

-678.0.0.0.0
+680.0.0.0.0

-  Functions: 2852
-  Symbols:   4567
-  CStrings:  1042
+  Functions: 2865
+  Symbols:   4575
+  CStrings:  1055
Symbols:
+ +[BKUIDevice setSharedInstance:]
+ +[BKUIIndicatorWindow indicatorControllerInScene:]
+ -[BKUIAlertView presentingWindowScene]
+ -[BKUIAlertView setIndicatorInstructionHidden:]
+ -[BKUIAlertView setPresentingWindowScene:]
+ -[BKUIDevice isNonHomeButtonTouchIDDevice]
+ -[BKUIFingerprintEnrollViewController viewIsAppearing:]
+ -[BKUIIndicatorViewController setInstructionTextHidden:]
+ -[BKUIPearlJindoEnrollViewController jindoTraitChangeRegistration]
+ -[BKUIPearlJindoEnrollViewController setJindoTraitChangeRegistration:]
+ -[BKUIPearlJindoEnrollViewController viewDidDisappear:]
+ GCC_except_table33
+ GCC_except_table9
+ _NSStringFromCGSize
+ _OBJC_IVAR_$_BKUIAlertView._presentingWindowScene
+ _OBJC_IVAR_$_BKUIPearlJindoEnrollViewController._jindoTraitChangeRegistration
+ _OBJC_IVAR_$_BKUIPearlVideoCaptureSession._runningObserverRegistered
+ ___67-[BKUIFingerprintEnrollViewController _failEnrollment:withMessage:]_block_invoke
+ ___block_descriptor_45_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_68_e8_32s40bs48r56w_e5_v8?0lw56l8s32l8r48l8s40l8
+ __sharedInstance
+ _swift_release_x27
+ _swift_retain_x23
+ _swift_retain_x25
+ _swift_retain_x27
+ _symbolic _____SgXw 14BiometricKitUI35EnrollStateDispatchWorkItemsManagerC
+ _symbolic _____SgXwz_Xx 14BiometricKitUI35EnrollStateDispatchWorkItemsManagerC
- -[BKUIDevice setShouldUseDeviceSceneBackground:]
- -[BKUIDevice shouldUseDeviceSceneBackground]
- -[BKUIFingerPrintEnrollTutorialViewController _topTouchButtonIpad]
- -[BKUIFingerPrintEnrollmentPhaseViewController _topTouchButtonIpad]
- -[BKUIFingerprintEnrollViewController _topTouchButtonIpad]
- -[BKUIFingerprintEnrollViewController preferredContentSize]
- -[BKUIPearlJindoEnrollViewController setTraitChangeRegistration:]
- -[BKUIPearlJindoEnrollViewController traitChangeRegistration]
- GCC_except_table29
- _OBJC_IVAR_$_BKUIDevice._shouldUseDeviceSceneBackground
- _OBJC_IVAR_$_BKUIPearlJindoEnrollViewController._traitChangeRegistration
- ___28+[BKUIDevice sharedInstance]_block_invoke
- ___block_descriptor_48_e8_32s40w_e52_v24?0"<UITraitEnvironment>"8"UITraitCollection"16lw40l8s32l8
- ___block_descriptor_53_e8_32s40w_e5_v8?0ls32l8w40l8
- ___block_descriptor_60_e8_32s40bs48r_e5_v8?0ls32l8r48l8s40l8
- _sharedInstance.environment
- _sharedInstance.onceToken
- _swift_release_x28
- _swift_retain_x24
CStrings:
+ "!\"1"
+ "AVAudioPlayerNode play threw %{public}@: %{public}@"
+ "AVAudioPlayerNode scheduleBuffer: threw %{public}@: %{public}@"
+ "AVAudioPlayerNode scheduleBuffer:atTime:options: threw %{public}@: %{public}@"
+ "AVAudioPlayerNode stop threw %{public}@: %{public}@"
+ "Capture session suddenly stopped running. mediaserverd crash? (restart attempt %lu of %lu, retrying in %lldms)"
+ "Failed to remove orphan identity: %@"
+ "Init: isZoomEnabled: %{public}d, shouldUseUnifiedMesaEnrollment: %{public}d"
+ "Init: title: `%{public}@`, subtitle: `%{public}@`, isNonHomeButton: %{public}@"
+ "PearlJindoEnrollVC: viewDidDisappear"
+ "Removing Phase 1 identity left behind by failed enrollment: %@"
+ "Skipping AVAudioPlayerNode play — engine not running"
+ "Skipping restart: capture session was torn down during backoff"
+ "nil"
+ "preferredContentSize/viewIsAppearing: animated=%{public}d viewBounds=%{public}@ window=%{public}@ scene=%{public}@ horizSizeClass=%{public}ld obkResult=%{public}@ current=%{public}@ willPush=%{public}d"
+ "set"
+ "setEnrollViewState: skipButton added: `%{public}@`"
+ "setInstructionTextHidden: %{public}@"
- "!\""
- "Capture session suddenly stopped running. mediaserverd crash?"
- "DeviceSupportsSecureDoubleClick"
- "Init: isZoomEnabled: %{public}d, shouldUseUnifiedMesaEnrollment: %{public}d, shouldUseDeviceSceneBackground: %{public}d"
- "Init: title: `%{public}@`, subtitle: `%{public}@`, isTopTouchButtonIpad: %{public}@"
```
