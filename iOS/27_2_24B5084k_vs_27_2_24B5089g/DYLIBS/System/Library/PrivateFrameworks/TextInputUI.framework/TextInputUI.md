## TextInputUI

> `/System/Library/PrivateFrameworks/TextInputUI.framework/TextInputUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1400fc` | `0x140a10` | **`+0x914`** |
| `__AUTH_CONST.__objc_const` | `0x1a1c0` | `0x1a608` | **`+0x448`** |
| `__DATA.__bss` | `0x33b8` | `0x35d8` | **`+0x220`** |
| `__TEXT.__objc_methlist` | `0x10604` | `0x107cc` | **`+0x1c8`** |
| `__DATA_CONST.__objc_selrefs` | `0xa830` | `0xa990` | **`+0x160`** |
| `__TEXT.__constg_swiftt` | `0x19c0` | `0x1868` | **`-0x158`** |
| `__AUTH.__objc_data` | `0x3c38` | `0x3b58` | **`-0xe0`** |
| `__DATA.__data` | `0x2ca8` | `0x2d28` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0xebe0` | `0xec40` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x7ab8` | `0x7b00` | **`+0x48`** |
| `__TEXT.__cstring` | `0xd935` | `0xd977` | **`+0x42`** |
| `__AUTH_CONST.__const` | `0x2fe8` | `0x3028` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x15e8` | `0x1628` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x1220` | `0x1258` | **`+0x38`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x288` | `0x2b8` | **`+0x30`** |
| `__AUTH_CONST.__objc_doubleobj` | `0x170` | `0x1a0` | **`+0x30`** |
| `__DATA_CONST.__objc_arraydata` | `0xae0` | `0xb10` | **`+0x30`** |
| `__DATA_DIRTY.__objc_data` | `0x20d0` | `0x20f8` | **`+0x28`** |
| `__DATA_DIRTY.__bss` | `0x4e0` | `0x500` | **`+0x20`** |
| `__TEXT.__const` | `0x3c7e` | `0x3c9e` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x1c14` | `0x1bfc` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x720` | `0x730` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x2b8` | `0x2c0` | **`+0x8`** |

### Other Changes

```diff

-9127.1.6.0.0
+9127.1.7.2.101

-  Functions: 7070
-  Symbols:   10927
-  CStrings:  2750
+  Functions: 7073
+  Symbols:   11031
+  CStrings:  2753
Symbols:
+ +[TUICandidateCell candidateFontForCandidate:style:]
+ +[TUIKeyboardHitDebugTouchChannel _deliverSample:]
+ +[TUIKeyboardHitDebugTouchChannel _isRepeatOfRecentSample:]
+ +[TUIKeyboardHitDebugTouchChannel _observers]
+ +[TUIKeyboardHitDebugTouchChannel addObserver:]
+ +[TUIKeyboardHitDebugTouchChannel publishTouchEvent:]
+ +[TUIKeyboardHitDebugTouchChannel removeObserver:]
+ -[TUIKeyboardHitDebugOverlay _applyMarkerPathForSample:trail:toMarker:]
+ -[TUIKeyboardHitDebugOverlay _beginTapMarkerAtSample:pathKey:]
+ -[TUIKeyboardHitDebugOverlay _closeOutTapMarkerForPathKey:]
+ -[TUIKeyboardHitDebugOverlay _evictableTapMarker]
+ -[TUIKeyboardHitDebugOverlay _extendTapMarkerWithSample:pathKey:isFinal:]
+ -[TUIKeyboardHitDebugOverlay _removeAllTapMarkers]
+ -[TUIKeyboardHitDebugOverlay _removeTapMarker:]
+ -[TUIKeyboardHitDebugOverlay _restartFadeForMarker:]
+ -[TUIKeyboardHitDebugOverlay _startObservingEngineChannels]
+ -[TUIKeyboardHitDebugOverlay _stopObservingEngineChannels]
+ -[TUIKeyboardHitDebugOverlay _updateTapMarkerColors]
+ -[TUIKeyboardHitDebugOverlay didReceiveTouchSample:]
+ -[TUIKeyboardHitDebugOverlay setShowsKeyHitGeometry:]
+ -[TUIKeyboardHitDebugOverlay setShowsTouchPointMarkers:]
+ -[TUIKeyboardHitDebugOverlay setTapMarkerContainerLayer:]
+ -[TUIKeyboardHitDebugOverlay setTapMarkerFadeGeneration:]
+ -[TUIKeyboardHitDebugOverlay setTapMarkerReferenceSize:]
+ -[TUIKeyboardHitDebugOverlay setTapMarkers:]
+ -[TUIKeyboardHitDebugOverlay setTapMarkersByPathIndex:]
+ -[TUIKeyboardHitDebugOverlay setTapTrailsByPathIndex:]
+ -[TUIKeyboardHitDebugOverlay showsKeyHitGeometry]
+ -[TUIKeyboardHitDebugOverlay showsTouchPointMarkers]
+ -[TUIKeyboardHitDebugOverlay stopObserving]
+ -[TUIKeyboardHitDebugOverlay tapMarkerContainerLayer]
+ -[TUIKeyboardHitDebugOverlay tapMarkerFadeGeneration]
+ -[TUIKeyboardHitDebugOverlay tapMarkerReferenceSize]
+ -[TUIKeyboardHitDebugOverlay tapMarkersByPathIndex]
+ -[TUIKeyboardHitDebugOverlay tapMarkers]
+ -[TUIKeyboardHitDebugOverlay tapTrailsByPathIndex]
+ -[_TUITapMarkerTrail .cxx_destruct]
+ -[_TUITapMarkerTrail lastDotLocation]
+ -[_TUITapMarkerTrail lastFadeRestartTimestamp]
+ -[_TUITapMarkerTrail linePath]
+ -[_TUITapMarkerTrail sampleLayer]
+ -[_TUITapMarkerTrail samplePath]
+ -[_TUITapMarkerTrail setLastDotLocation:]
+ -[_TUITapMarkerTrail setLastFadeRestartTimestamp:]
+ -[_TUITapMarkerTrail setLinePath:]
+ -[_TUITapMarkerTrail setSampleLayer:]
+ -[_TUITapMarkerTrail setSamplePath:]
+ -[_TUITapMarkerTrail setStartLocation:]
+ -[_TUITapMarkerTrail startLocation]
+ _OBJC_CLASS_$_CAKeyframeAnimation
+ _OBJC_CLASS_$_CALayer
+ _OBJC_CLASS_$_TUIKeyboardHitDebugTouchChannel
+ _OBJC_CLASS_$__TUITapMarkerTrail
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._showsKeyHitGeometry
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._showsTouchPointMarkers
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._tapMarkerContainerLayer
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._tapMarkerFadeGeneration
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._tapMarkerReferenceSize
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._tapMarkers
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._tapMarkersByPathIndex
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._tapTrailsByPathIndex
+ _OBJC_IVAR_$__TUITapMarkerTrail._lastDotLocation
+ _OBJC_IVAR_$__TUITapMarkerTrail._lastFadeRestartTimestamp
+ _OBJC_IVAR_$__TUITapMarkerTrail._linePath
+ _OBJC_IVAR_$__TUITapMarkerTrail._sampleLayer
+ _OBJC_IVAR_$__TUITapMarkerTrail._samplePath
+ _OBJC_IVAR_$__TUITapMarkerTrail._startLocation
+ _OBJC_METACLASS_$_TUIKeyboardHitDebugTouchChannel
+ _OBJC_METACLASS_$__TUITapMarkerTrail
+ _TIGetShowTouchPointDebugUIValue.onceToken
+ _TUICandidateFont
+ _TUICandidateRowHeight
+ _TUIKeyboardHitDebugTouchChannelHasObservers
+ _TUIMinimumCandidateLabelHeight
+ __OBJC_$_CLASS_METHODS_TUIKeyboardHitDebugTouchChannel
+ __OBJC_$_INSTANCE_METHODS__TUITapMarkerTrail
+ __OBJC_$_INSTANCE_VARIABLES__TUITapMarkerTrail
+ __OBJC_$_PROP_LIST__TUITapMarkerTrail
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_TUIKeyboardHitDebugTouchObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_TUIKeyboardHitDebugTouchObserver
+ __OBJC_$_PROTOCOL_REFS_TUIKeyboardHitDebugTouchObserver
+ __OBJC_CLASS_PROTOCOLS_$_TUIKeyboardHitDebugOverlay
+ __OBJC_CLASS_RO_$_TUIKeyboardHitDebugTouchChannel
+ __OBJC_CLASS_RO_$__TUITapMarkerTrail
+ __OBJC_LABEL_PROTOCOL_$_TUIKeyboardHitDebugTouchObserver
+ __OBJC_METACLASS_RO_$_TUIKeyboardHitDebugTouchChannel
+ __OBJC_METACLASS_RO_$__TUITapMarkerTrail
+ __OBJC_PROTOCOL_$_TUIKeyboardHitDebugTouchObserver
+ __TUITapMarkerTrailColor
+ ___44-[TUIKeyboardHitDebugOverlay initWithFrame:]_block_invoke
+ ___45+[TUIKeyboardHitDebugTouchChannel _observers]_block_invoke
+ ___52-[TUIKeyboardHitDebugOverlay _restartFadeForMarker:]_block_invoke
+ ___53+[TUIKeyboardHitDebugTouchChannel publishTouchEvent:]_block_invoke
+ ___59-[TUIKeyboardHitDebugOverlay _startObservingEngineChannels]_block_invoke
+ ___59-[TUIKeyboardHitDebugOverlay _startObservingEngineChannels]_block_invoke_2
+ ___TIGetShowTouchPointDebugUIValue_block_invoke
+ ___block_descriptor_56_8_32s40w_e5_v8?0ls32l8w40l8
+ ___block_descriptor_88_e5_v8?0l
+ __isRepeatOfRecentSample:.nextSlot
+ __isRepeatOfRecentSample:.recentPathIndices
+ __isRepeatOfRecentSample:.recentTimestamps
+ __observers.observers
+ __observers.onceToken
+ _kCAFillRuleEvenOdd
+ _kCALineCapRound
+ _kCALineJoinRound
+ _kCAMediaTimingFunctionEaseIn
+ _sHasObservers
+ _type_layout_string So7CGPointV
- -[TUIKeyboardHitDebugOverlay startObservingEngineChannels]
- -[TUIKeyboardHitDebugOverlay stopObservingEngineChannels]
- ___58-[TUIKeyboardHitDebugOverlay startObservingEngineChannels]_block_invoke
- ___58-[TUIKeyboardHitDebugOverlay startObservingEngineChannels]_block_invoke_2
- _type_layout_string So6CGSizeV
CStrings:
+ "8"
+ "ShowTouchPointDebugUI"
+ "TUITapMarkerFade"
+ "TUITapMarkerFadeGeneration"
- "4"
```
