## Portrait

> `/System/Library/PrivateFrameworks/Portrait.framework/Portrait`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x894d0` | `0x88af8` | **`-0x9d8`** |
| `__AUTH_CONST.__cfstring` | `0x4e20` | `0x4d40` | **`-0xe0`** |
| `__TEXT.__cstring` | `0x4f4e` | `0x4e7a` | **`-0xd4`** |
| `__TEXT.__gcc_except_tab` | `0x1938` | `0x19e4` | **`+0xac`** |
| `__AUTH_CONST.__objc_const` | `0x1c710` | `0x1c670` | **`-0xa0`** |
| `__TEXT.__objc_methlist` | `0x93f4` | `0x936c` | **`-0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0x4f40` | `0x4ee8` | **`-0x58`** |
| `__DATA.__bss` | `0x20c` | `0x234` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x8e8` | `0x910` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x178c` | `0x1778` | **`-0x14`** |
| `__TEXT.__oslogstring` | `0x4b10` | `0x4b0c` | **`-0x4`** |

### Other Changes

```diff

-546.0.0.0.0
+551.0.0.0.0

-  Functions: 3726
-  Symbols:   6471
-  CStrings:  1393
+  Functions: 3716
+  Symbols:   6458
+  CStrings:  1386
Symbols:
+ -[PTCinematographyFrame _flushCachedDetectionsDictionaries]
+ -[PTCinematographyFrameFocuser forceProcessNextFrame]
+ -[PTCinematographyFrameFocuser pendingInputFrameTime]
+ -[PTEffect setUnsafeDelegateDirectAccess:]
+ -[PTEffect unsafeDelegateDirectAccess]
+ -[PTEffect updateEffectDelegate:synchronousReconfigure:]
+ -[PTEffectPersonSegmentation personSegmentationProviderRotated]
+ -[PTEffectPersonSegmentation setPersonSegmentationProviderRotated:]
+ -[PTEffectReactionProvider initWithEffectDescriptor:sharedResources:useExternalHandDetections:]
+ -[PTEffectRenderer personSegmentation]
+ -[PTEffectRenderer setPersonSegmentation:]
+ -[PTEffectResources personSegmentationProviderRotated]
+ -[PTEffectResources setPersonSegmentationProviderRotated:]
+ -[PTHandGestureDetector initWithFrameSize:asyncInitQueue:useExternalHandDetections:externalCamera:]
+ GCC_except_table35
+ GCC_except_table43
+ GCC_except_table46
+ GCC_except_table47
+ GCC_except_table49
+ GCC_except_table54
+ GCC_except_table65
+ GCC_except_table66
+ GCC_except_table68
+ GCC_except_table75
+ GCC_except_table76
+ _OBJC_IVAR_$_PTEffect._unsafeDelegateDirectAccess
+ _OBJC_IVAR_$_PTEffectPersonSegmentation._sharedResources
+ _OBJC_IVAR_$_PTEffectResources._personSegmentationProviderRotated
+ ___56-[PTEffect updateEffectDelegate:synchronousReconfigure:]_block_invoke
+ ___56-[PTEffect updateEffectDelegate:synchronousReconfigure:]_block_invoke_2
+ ___60+[PTTuningParameters noiseScaleFactorForHwModelID:sensorID:]_block_invoke
+ ___99-[PTHandGestureDetector initWithFrameSize:asyncInitQueue:useExternalHandDetections:externalCamera:]_block_invoke
+ ___block_descriptor_64_e8_32s40w_e5_v8?0lw40l8s32l8
+ _noiseScaleFactorForHwModelID:sensorID:.onceToken
- -[PTCinematographyFrame(Private) _flushCachedDetectionsDictionaries]
- -[PTCinematographyFrameFocuser _cacheTransitionDetectionsForRange:fromDecision:toDecision:]
- -[PTCinematographyFrameFocuser _calculateTransitionRangeFrom:to:]
- -[PTCinematographyFrameFocuser _ensureTransitionCalculated]
- -[PTCinematographyFrameFocuser _findDetectionForTrack:atOrBeforeTime:]
- -[PTCinematographyFrameFocuser _processNextFrameBackward:]
- -[PTCinematographyFrameFocuser _processTransitionFrame:fromDetection:toDetection:transition:transitionRange:]
- -[PTCinematographyFrameFocuser _startTimeOfDynamicTransitionToDecision:]
- -[PTCinematographyFrameFocuser _startTimeOfFixedTransitionToDecision:]
- -[PTCinematographyFrameFocuser _trimOldInputFrames]
- -[PTCinematographyFrameFocuser _useFixedTransition]
- -[PTCinematographyFrameFocuser currentTransitionRange]
- -[PTCinematographyFrameFocuser currentTransition]
- -[PTCinematographyFrameFocuser initWithTrackDecisions:rackFocusOptions:focusPuller:]
- -[PTCinematographyFrameFocuser setCurrentTransition:]
- -[PTCinematographyFrameFocuser setCurrentTransitionRange:]
- -[PTCinematographyFrameFocuser setTransitionEndDetection:]
- -[PTCinematographyFrameFocuser setTransitionStartDetection:]
- -[PTCinematographyFrameFocuser transitionEndDetection]
- -[PTCinematographyFrameFocuser transitionStartDetection]
- -[PTEffect updateEffectDelegate:]
- -[PTEffectDescriptor externalHandDetectionsEnabled]
- -[PTEffectDescriptor setExternalHandDetectionsEnabled:]
- -[PTEffectReactionProvider initWithEffectDescriptor:sharedResources:externalHandDetectionsEnabled:]
- -[PTHandGestureDetector initWithFrameSize:asyncInitQueue:externalHandDetectionsEnabled:externalCamera:]
- GCC_except_table38
- GCC_except_table41
- GCC_except_table44
- GCC_except_table45
- GCC_except_table50
- GCC_except_table60
- GCC_except_table63
- GCC_except_table78
- _CMTimeRangeCopyAsDictionary
- _CMTimeRangeMakeFromDictionary
- _OBJC_IVAR_$_PTCinematographyFrameFocuser._currentTransition
- _OBJC_IVAR_$_PTCinematographyFrameFocuser._currentTransitionRange
- _OBJC_IVAR_$_PTCinematographyFrameFocuser._transitionEndDetection
- _OBJC_IVAR_$_PTCinematographyFrameFocuser._transitionStartDetection
- _OBJC_IVAR_$_PTDisparityFilterDEMA_LKT._samplerState
- _OBJC_IVAR_$_PTEffect._delegate
- _OBJC_IVAR_$_PTEffectDescriptor._externalHandDetectionsEnabled
- _OBJC_IVAR_$_PTEffectRenderer._externalHandDetectionsAvailable
- ___103-[PTHandGestureDetector initWithFrameSize:asyncInitQueue:externalHandDetectionsEnabled:externalCamera:]_block_invoke
- ___33-[PTEffect updateEffectDelegate:]_block_invoke
- ___33-[PTEffect updateEffectDelegate:]_block_invoke_2
- _kMaxDetectionGapTime
CStrings:
+ "\f"
+ "Cannot find usable detection for track %lu at frame time %@"
+ "Initialize reaction provider"
+ "Initializing rotated network %f x %f"
+ "Motion threshold must be strict min < max"
+ "No detection for track %lu, using autoFocus wholesale at frame time %@"
+ "Patched focusDistance on track %lu with autoFocus at frame time %@"
+ "PortTypeMonocular"
+ "Reusing rotated network size %f x %f"
+ "Update PTEffect %li quality %li passthrough %i synchronous %i"
+ "Use external hand detections: %@"
+ "strongSelf.personSegmentationProviderRotated"
- "\v"
- "Cannot find detection for track %lu at frame time %@"
- "Cannot find end detection for transition to track %lu at time %@"
- "Cannot find start detection for transition from track %lu at time %@"
- "External hand detections available: %@"
- "External hand detections expected but not provided in effectRenderRequest.detectedObjects"
- "Force [_MTLDevice _purgeDevice] not supported"
- "Initializing rotated network"
- "Invalid detections for transition at frame time %@"
- "PortTypeBackTelephoto"
- "PortTypeFront"
- "PortTypeFrontInfrared"
- "_temporalFilterDEMA_LKT_VisualizeMotion"
- "currentTransitionKind"
- "currentTransitionRange"
- "strongSelf->_personSegmentationProviderRotated"
- "temporalFilterDEMA_LKT_VisualizeMotion"
- "transitionEndDetection"
- "transitionStartDetection"
```
