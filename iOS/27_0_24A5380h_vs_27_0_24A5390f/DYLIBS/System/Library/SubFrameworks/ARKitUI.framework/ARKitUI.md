## ARKitUI

> `/System/Library/SubFrameworks/ARKitUI.framework/ARKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a2f8` | `0x2b150` | **`+0xe58`** |
| `__AUTH_CONST.__objc_const` | `0x7410` | `0x75c8` | **`+0x1b8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2178` | `0x2248` | **`+0xd0`** |
| `__TEXT.__objc_methlist` | `0x2888` | `0x2910` | **`+0x88`** |
| `__DATA_CONST.__const` | `0x380` | `0x330` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0x1917` | `0x18d2` | **`-0x45`** |
| `__DATA.__objc_ivar` | `0x558` | `0x588` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xc00` | `0xc20` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x3c0` | `0x3a0` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x570` | `0x590` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xcf8` | `0xcd8` | **`-0x20`** |
| `__DATA.__bss` | `0x250` | `0x240` | **`-0x10`** |
| `__TEXT.__const` | `0x958` | `0x948` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xc08` | `0xc10` | **`+0x8`** |
| `__TEXT.__cstring` | `0xdb6` | `0xdb4` | **`-0x2`** |

### Other Changes

```diff

-781.0.1.0.4
+781.0.4.0.0

-  Functions: 969
-  Symbols:   2117
-  CStrings:  235
+  Functions: 972
+  Symbols:   2135
+  CStrings:  234
Symbols:
+ -[ARSCNCompositor setViewRotationAngle:]
+ -[ARSCNCompositor viewRotationAngle]
+ -[ARSCNView _applyPreviewRotationFromAngle:hasOldAngle:toAngle:]
+ -[ARSCNView _assignViewLayerToSessionOnMainThread]
+ -[ARSCNView _assignViewLayerToSession]
+ -[ARSCNView _drawAtTime:]
+ -[ARSCNView _installSnapshotIfNeeded]
+ -[ARSCNView _pollResumeAfterDrawableResize]
+ -[ARSCNView _publishOrientationSwapAtAngle:fromAngle:]
+ -[ARSCNView _renderCapturedPixelBuffer:withOrientation:]
+ -[ARSCNView _setupRenderSublayer]
+ -[ARSCNView _updateCamera:withViewRotationAngle:viewportSize:]
+ -[ARSCNView _viewRotationAngleDidChange:]
+ -[ARSCNView _windowWillRotate:]
+ -[ARSCNView safeAreaInsetsDidChange]
+ -[ARSCNView session:didChangeViewRotationAngle:]
+ -[ARSKView _setLayerOnMain]
+ -[ARSKView _updateNode:forAnchor:projectionMatrix:camera:viewRotationAngle:]
+ -[ARSKView session:didChangeViewRotationAngle:]
+ _ARCameraImageToViewTransformWithAngle
+ _ARCorrectedViewRotationAngleForRotation
+ _ARDisplayRotationFromViewRotationAngle
+ _ARInterfaceOrientationFromViewRotationAngle
+ _ARViewToCameraImageTransformWithAngle
+ _CATransform3DMakeRotation
+ _CGPointZero
+ _NSRunLoopCommonModes
+ _OBJC_CLASS_$_CABasicAnimation
+ _OBJC_CLASS_$_CAMediaTimingFunction
+ _OBJC_CLASS_$_NSThread
+ _OBJC_IVAR_$_ARSCNCompositor._viewRotationAngle
+ _OBJC_IVAR_$_ARSCNView._baselineBounds
+ _OBJC_IVAR_$_ARSCNView._hasBaselineBounds
+ _OBJC_IVAR_$_ARSCNView._pendingNewOrientation
+ _OBJC_IVAR_$_ARSCNView._pendingResumeDrawableSize
+ _OBJC_IVAR_$_ARSCNView._pendingResumeMetalLayer
+ _OBJC_IVAR_$_ARSCNView._pendingResumeStage
+ _OBJC_IVAR_$_ARSCNView._pendingResumeStage0TicksRemaining
+ _OBJC_IVAR_$_ARSCNView._pendingResumeStage1TicksRemaining
+ _OBJC_IVAR_$_ARSCNView._pendingRotationBaselineSize
+ _OBJC_IVAR_$_ARSCNView._renderTargetLock
+ _OBJC_IVAR_$_ARSCNView._renderTargetOrientation
+ _OBJC_IVAR_$_ARSCNView._renderTargetViewAngle
+ _OBJC_IVAR_$_ARSCNView._renderTicksAtSuspendClear
+ _OBJC_IVAR_$_ARSCNView._rendererFrameCounter
+ _OBJC_IVAR_$_ARSCNView._resumePoller
+ _OBJC_IVAR_$_ARSCNView._viewRotationAngle
+ ___27-[ARSKView _setLayerOnMain]_block_invoke
+ ___38-[ARSCNView _assignViewLayerToSession]_block_invoke
+ ___block_descriptor_40_e8_32w_e5_v8?0lw32l8
+ _kCAMediaTimingFunctionEaseInEaseOut
+ _os_unfair_lock_assert_owner
- -[ARSCNCompositor currentOrientation]
- -[ARSCNCompositor setCurrentOrientation:]
- -[ARSCNView cleanupLingeringRotationState]
- -[ARSCNView frameToRemoveRotationSnapshotOn]
- -[ARSCNView setFrameToRemoveRotationSnapshotOn:]
- -[ARSCNView windowDidRotateNotification:]
- -[ARSCNView windowWillAnimateRotateNotification:]
- -[ARSCNView windowWillRotateNotification:]
- -[ARSKView _updateNode:forAnchor:projectionMatrix:camera:orientation:]
- GCC_except_table22
- _ARCameraImageToViewTransform
- _ARCameraToDisplayRotation
- _ARViewToCameraImageTransform
- _CGAffineTransformIdentity
- _CGAffineTransformIsIdentity
- _NSStringFromUIInterfaceOrientation
- _OBJC_CLASS_$_NSBundle
- _OBJC_IVAR_$_ARSCNCompositor._currentOrientation
- _OBJC_IVAR_$_ARSCNView._frameToRemoveRotationSnapshotOn
- _OBJC_IVAR_$_ARSCNView._interfaceOrientation
- _OBJC_IVAR_$_ARSCNView._lastInterfaceOrientation
- _OBJC_IVAR_$_ARSKView._interfaceOrientation
- ___28-[ARSCNView didMoveToWindow]_block_invoke
- ___36-[ARSCNView _renderer:updateAtTime:]_block_invoke
- ___42-[ARSCNView cleanupLingeringRotationState]_block_invoke
- ___42-[ARSCNView windowWillRotateNotification:]_block_invoke
- ___42-[ARSCNView windowWillRotateNotification:]_block_invoke_2
- ___49-[ARSCNView windowWillAnimateRotateNotification:]_block_invoke
- ___49-[ARSCNView windowWillAnimateRotateNotification:]_block_invoke_2
- ___block_descriptor_40_e8_32s_e8_v12?0B8ls32l8
- ___block_descriptor_48_ea8_32s40s_e5_v8?0ls32l8s40l8
- ___block_descriptor_56_e8_32s_e5_v8?0ls32l8
- __alwaysRotateCounterclockwise
- _didMoveToWindow.onceToken
CStrings:
+ "%{public}@ <%p>: Layout changed to %{public}@, %.2fx"
+ "%{public}@ <%p>: [ARSKView] Layout changed to %{public}@, viewRotationAngle=%g°"
+ "%{public}@ <%p>: viewRotationAngle updated to %.0f"
+ "counterRotation"
+ "transform"
+ "viewRotationAngle updated to %.0f"
- "%{public}@ <%p>: ARSCNViewRotationSnapshotStateSetUp"
- "%{public}@ <%p>: ARSCNViewRotationSnapshotStateSettingUp"
- "%{public}@ <%p>: Layout changed to %{public}@, %.2fx, %{public}@"
- "%{public}@ <%p>: Removing rotation snapshot"
- "%{public}@ <%p>: [ARSKView] Layout changed to %{public}@, %{public}@"
- "UIRequiresFullScreen"
- "v12@?0B8"
```
