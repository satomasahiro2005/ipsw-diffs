## assistivetouchd

> `/System/Library/CoreServices/AssistiveTouch.app/assistivetouchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15e3c0` | `0x15e8bc` | **`+0x4fc`** |
| `__TEXT.__oslogstring` | `0x6c4f` | `0x6ad8` | **`-0x177`** |
| `__DATA_CONST.__got` | `0x1b08` | `0x1be8` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x376e0` | `0x377c0` | **`+0xe0`** |
| `__TEXT.__eh_frame` | `0x4810` | `0x48d0` | **`+0xc0`** |
| `__DATA.__bss` | `0x4cb0` | `0x4d30` | **`+0x80`** |
| `__TEXT.__cstring` | `0xddfe` | `0xde66` | **`+0x68`** |
| `__TEXT.__objc_stubs` | `0x2b660` | `0x2b6c0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x6a20` | `0x6a70` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x4030` | `0x4080` | **`+0x50`** |
| `__TEXT.__const` | `0x45a0` | `0x45f0` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x9e60` | `0x9e20` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x5f08` | `0x5f48` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x754` | `0x788` | **`+0x34`** |
| `__DATA_CONST.__auth_got` | `0x2028` | `0x2050` | **`+0x28`** |
| `__DATA.__objc_const` | `0x1c368` | `0x1c388` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1537c` | `0x1539c` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xc2b8` | `0xc2d0` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0xb68` | `0xb80` | **`+0x18`** |
| `__DATA.__data` | `0x41a0` | `0x4190` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x1568` | `0x1578` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x75ba` | `0x75ad` | **`-0xd`** |
| `__DATA.__objc_ivar` | `0x12a0` | `0x12a4` | **`+0x4`** |
| `__TEXT.__swift5_proto` | `0x260` | `0x264` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x304` | `0x308` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x3d8` | `0x3dc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1497.0.0.0.0
+1500.0.0.0.0

-  Functions: 9167
-  Symbols:   2274
-  CStrings:  11874
+  Functions: 9180
+  Symbols:   2282
+  CStrings:  11875
Symbols:
+ _$s16AssistiveTouchUI0aB20VolumeLevelProvidingMp
+ _$s16AssistiveTouchUI0aB20VolumeLevelProvidingP06volumeE012CoreGraphics7CGFloatVvgTq
+ _$s16AssistiveTouchUI0aB9MenuStateC19volumeLevelProviderAA0ab6VolumeG9Providing_pSgvsTj
+ _$s28AccessibilitySharedUISupport0A23FloatingUIAvoidanceRectV10isSystemUI0G8Keyboard19pushesPerpendicular5frameACSb_S2bSo6CGRectVtcfC
+ _$s28AccessibilitySharedUISupport0A29FloatingUIPositioningDelegateP29floatingUIInteractionOccurredyyFTq
+ _$s28AccessibilitySharedUISupport0A29FloatingUIPositioningDelegateP35floatingContentNormalizedGuidePointSo7CGPointVSgvgTq
+ _$ss9_typeName_9qualifiedSSypXp_SbtF
+ __UIClamp
+ __UIWindowDidAttachContextNotification
+ __UIWindowDidDetachContextNotification
+ _swift_isEscapingClosureAtFileLocation
+ _swift_task_getMainExecutor
+ _swift_task_isCurrentExecutor
- _$s28AccessibilitySharedUISupport0A23FloatingUIAvoidanceRectV10isSystemUI0G8Keyboard5frameACSb_SbSo6CGRectVtcfC
- _$s28AccessibilitySharedUISupport0A29FloatingUIPositioningDelegateP25floatingContentGuidePointSo7CGPointVvgTq
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- _swift_willThrowTypedImpl
CStrings:
+ "Incorrect actor executor assumption; Expected same executor as "
+ "T@\"NSValue\",R,N"
+ "_registeredPointerDisplayID"
+ "_windowContextDidAttach:"
+ "_windowContextDidDetach:"
+ "addKeyboardAvoidanceFrame:"
+ "assistivetouchd/HNDDisplayManager.swift"
+ "astMenuNormalizedGuidePoint"
+ "displayManager:windowContextDidAttachWithDisplayID:contextID:"
+ "displayManager:windowContextDidDetachWithDisplayID:"
+ "removeKeyboardAvoidanceFrame"
+ "removeObserver:name:object:"
+ "resetSystemPointerStateForDisplayChangeWithSeedPoint:"
- "HandGestures: Error handling removed Hand reference"
- "Registering global mouse events for displayID=%u contextID=%u hardwareIdentifier=%{public}@"
- "Skipping global mouse event registration: already registered for displayID=%u (existing contextID=%u, requested=%u)"
- "Skipping global mouse event registration: contextID is 0 (displayID=%u, hardwareIdentifier=%{public}@)"
- "_handleDisplayContextDidChange:"
- "_screenHeight"
- "_updateAvoidanceRects"
- "addAvoidanceFrame:forIdentifier:"
- "astMenuGuidePoint"
- "homeAffordance"
- "removeAvoidanceFrameForIdentifier:"
- "topNotch"
```
