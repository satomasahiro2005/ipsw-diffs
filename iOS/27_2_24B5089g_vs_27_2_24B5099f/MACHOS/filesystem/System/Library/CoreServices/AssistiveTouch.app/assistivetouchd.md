## assistivetouchd

> `/System/Library/CoreServices/AssistiveTouch.app/assistivetouchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x167248` | `0x168408` | **`+0x11c0`** |
| `__TEXT.__objc_methname` | `0x38500` | `0x38800` | **`+0x300`** |
| `__TEXT.__objc_stubs` | `0x2c060` | `0x2c220` | **`+0x1c0`** |
| `__TEXT.__oslogstring` | `0x6eae` | `0x6fac` | **`+0xfe`** |
| `__TEXT.__objc_methlist` | `0x1581c` | `0x158f4` | **`+0xd8`** |
| `__TEXT.__objc_methtype` | `0x7761` | `0x7814` | **`+0xb3`** |
| `__TEXT.__eh_frame` | `0x4cd8` | `0x4d78` | **`+0xa0`** |
| `__DATA.__objc_const` | `0x1c7b0` | `0x1c848` | **`+0x98`** |
| `__DATA_CONST.__cfstring` | `0x9f40` | `0x9fc0` | **`+0x80`** |
| `__DATA.__objc_selrefs` | `0xc558` | `0xc5c8` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x61e0` | `0x6248` | **`+0x68`** |
| `__TEXT.__cstring` | `0xe1e2` | `0xe22e` | **`+0x4c`** |
| `__DATA_CONST.__const` | `0x6ef8` | `0x6f40` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0x4230` | `0x4260` | **`+0x30`** |
| `__TEXT.__const` | `0x4b20` | `0x4b40` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x2128` | `0x2140` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x2a28` | `0x2a3c` | **`+0x14`** |
| `__DATA.__objc_ivar` | `0x12e0` | `0x12f0` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0xc70` | `0xc78` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1c20` | `0x1c28` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x334` | `0x33c` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x40c` | `0x414` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
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
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1510.4.1.0.0
+1510.4.3.0.0

-  Functions: 9389
-  Symbols:   2344
-  CStrings:  12026
+  Functions: 9411
+  Symbols:   2349
+  CStrings:  12058
Symbols:
+ _$s26AccessibilitySharedSupport0A12SystemActionO7HandlerP0A19PhysicalInteractionE6handleyAA0aeF6ResultOAC7PinPairVF
+ _$s26AccessibilitySharedSupport0A12SystemActionO7HandlerP0A19PhysicalInteractionE6handleyAA0aeF6ResultOAC9UnpinPairVF
+ _$s26AccessibilitySharedSupport0A12SystemActionO7HandlerP6handleyAA0aeF6ResultOAC7PinPairVYaFTq
+ _$s26AccessibilitySharedSupport0A12SystemActionO7HandlerP6handleyAA0aeF6ResultOAC9UnpinPairVYaFTq
+ _AXSSSymbolNameOfCurrentDevice
+ _IOHIDElementIsRelative
+ _OBJC_CLASS_$_ASTUIDragMenuGesturePerformer
- _$s26AccessibilitySharedSupport0A12SystemActionO7HandlerP0A19PhysicalInteractionE6handleyAA0aeF6ResultOAC12MultitaskingVF
- _$s26AccessibilitySharedSupport0A12SystemActionO7HandlerP6handleyAA0aeF6ResultOAC12MultitaskingVYaFTq
CStrings:
+ "B40@0:8^@16^{CGRect={CGPoint=dd}{CGSize=dd}}24^i32"
+ "Dwell: motion tracking loss persisted past grace, cancelling dwell"
+ "Dwell: motion tracking lost, deferring dwell cancel"
+ "Dwell: motion tracking resumed within grace window, dwell preserved"
+ "TAD: pointer positioning mode: %{public}s (logical range %ld..%ld)"
+ "_activeSweepLayer:bounds:axis:"
+ "_beginDeferredDwellCancelForMotionTrackingLoss"
+ "_canStartDwellTimerForCurrentButtonState"
+ "_deferredDwellCancelTimer"
+ "_menuItems:containEnabledItemOfType:"
+ "_primaryNavigationToggleIsRedundantWithTrackingExit"
+ "_resolveDwellAfterMotionTrackingResumed"
+ "_tadmorPointForNormalizedPosition:"
+ "_tadmorPointerIsAbsolute"
+ "_tadmorPointerLogicalMaximum"
+ "_tadmorPointerLogicalMinimum"
+ "absolute"
+ "applyScanningModeForDimensionality:"
+ "inputController:didReceiveAbsolutePosition:dimensionality:"
+ "isDwellTimerRunning"
+ "isSidecarMoveMenuDragPerformer:"
+ "moveActiveAxisToNormalizedPosition:"
+ "multitasking_pinPair"
+ "multitasking_unpinPair"
+ "pin"
+ "pin.slash"
+ "pointerDidMoveToAbsolutePosition:dimensionality:"
+ "relative"
+ "switchControlMenuItemTypeEnabled:"
+ "tadmorInputSource:didReceiveAbsolutePosition:dimensionality:"
+ "v48@0:8@\"SCATInputController\"16{CGPoint=dd}24q40"
+ "v48@0:8@\"SCATTadmorInputSource\"16{CGPoint=dd}24q40"
+ "v48@0:8@16{CGPoint=dd}24q40"
+ "\xf0\xf0\xd1"
- "minimumLineHeight"
- "\xf0\xf0\xc1"
```
