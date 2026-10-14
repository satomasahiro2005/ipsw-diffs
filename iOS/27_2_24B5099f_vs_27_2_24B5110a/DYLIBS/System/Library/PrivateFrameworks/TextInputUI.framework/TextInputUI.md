## TextInputUI

> `/System/Library/PrivateFrameworks/TextInputUI.framework/TextInputUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14bef4` | `0x14c48c` | **`+0x598`** |
| `__TEXT.__objc_methlist` | `0x1083c` | `0x1089c` | **`+0x60`** |
| `__DATA.__data` | `0x2e68` | `0x2eb8` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x1a910` | `0x1a948` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x1680` | `0x16b8` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0xa9c8` | `0xa9f0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x4710` | `0x4738` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x1254` | `0x1250` | **`-0x4`** |

### Other Changes

```diff

-9127.1.12.0.0
+9127.1.13.1.105

-  Functions: 7248
-  Symbols:   11089
+  Functions: 7262
+  Symbols:   11095
Symbols:
+ -[TUIHandwritingKeyboardGrabber didMoveToSuperview]
+ -[TUIHandwritingKeyboardGrabber gestureRecognizer:shouldBeRequiredToFailByGestureRecognizer:]
+ -[TUIHandwritingKeyboardGrabber gestureRecognizer:shouldReceiveTouch:]
+ -[TUIHandwritingKeyboardGrabber gestureRecognizerShouldBegin:]
+ -[TUIHandwritingKeyboardGrabber setTranslationAtDragStart:]
+ -[TUIHandwritingKeyboardGrabber translationAtDragStart]
+ -[TUIKeyplaneView _clampedHandwritingResizeOffset:]
+ -[TUIKeyplaneView _rubberBandedHandwritingResizeOffset:]
+ -[TUIKeyplaneView grabberWillBeginDragging:]
+ -[TUIKeyplaneView resizeRegionHeightForGrabber:]
+ _OBJC_IVAR_$_TUIHandwritingKeyboardGrabber._translationAtDragStart
+ __OBJC_CLASS_PROTOCOLS_$_TUIHandwritingKeyboardGrabber
+ __UIDynamicAnimationFrictionHigh
+ ___block_descriptor_48_8_32s40s_e8_v12?0i8ls32l8s40l8
- -[TUIHandwritingKeyboardGrabber maximumResizeOffset]
- -[TUIHandwritingKeyboardGrabber minimumResizeOffset]
- -[TUIHandwritingKeyboardGrabber setMaximumResizeOffset:]
- -[TUIHandwritingKeyboardGrabber setMinimumResizeOffset:]
- _OBJC_IVAR_$_TUIHandwritingKeyboardGrabber._maximumResizeOffset
- _OBJC_IVAR_$_TUIHandwritingKeyboardGrabber._minimumResizeOffset
- ___75-[TUIKeyboardTrackingProvider keyboardInputSceneRelativeGeometryDidUpdate:]_block_invoke
- ___block_descriptor_56_8_32s_e8_v12?0i8ls32l8
```
