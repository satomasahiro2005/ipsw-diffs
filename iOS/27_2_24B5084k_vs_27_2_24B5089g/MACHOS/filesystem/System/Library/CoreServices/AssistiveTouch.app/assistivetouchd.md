## assistivetouchd

> `/System/Library/CoreServices/AssistiveTouch.app/assistivetouchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__unwind_info` | `0x6668` | `0x61e0` | **`-0x488`** |
| `__TEXT.__text` | `0x166e00` | `0x167248` | **`+0x448`** |
| `__TEXT.__objc_methname` | `0x383b0` | `0x38500` | **`+0x150`** |
| `__DATA_CONST.__cfstring` | `0x9e40` | `0x9f40` | **`+0x100`** |
| `__TEXT.__objc_stubs` | `0x2bfa0` | `0x2c060` | **`+0xc0`** |
| `__TEXT.__cstring` | `0xe157` | `0xe1e2` | **`+0x8b`** |
| `__TEXT.__objc_methtype` | `0x76f3` | `0x7761` | **`+0x6e`** |
| `__DATA_CONST.__const` | `0x6ea0` | `0x6ef8` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x157e4` | `0x1581c` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0xc528` | `0xc558` | **`+0x30`** |
| `__DATA_CONST.__objc_intobj` | `0x810` | `0x840` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x4200` | `0x4230` | **`+0x30`** |
| `__DATA_CONST.__objc_dictobj` | `0x280` | `0x2a8` | **`+0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0x658` | `0x678` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x2110` | `0x2128` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x6ea3` | `0x6eae` | **`+0xb`** |
| `__DATA_CONST.__got` | `0x1c18` | `0x1c20` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1510.4.0.0.0
+1510.4.1.0.0

-  Functions: 9384
-  Symbols:   2340
-  CStrings:  12009
+  Functions: 9389
+  Symbols:   2344
+  CStrings:  12026
Symbols:
+ _BKSHIDEventSetPointerAttributes
+ _IOHIDEventAppendEvent
+ _IOHIDEventSetPhase
+ _OBJC_CLASS_$_BKSHIDEventPointerAttributes
CStrings:
+ "B32@0:8B16B20Q24"
+ "B56@0:8{CGPoint=dd}16{CGPoint=dd}32q48"
+ "Height"
+ "SurfaceDimensions"
+ "T@\"<BSInvalidatable>\",&,N,V_trackpadHitTestCategoryAssertion"
+ "Width"
+ "^{__IOHIDEvent=}56@0:8{CGPoint=dd}16{CGPoint=dd}32q48"
+ "_copyScrollEventWithDelta:atLocation:phase:"
+ "_deviceDescriptorPropertiesWithUniqueID:"
+ "_handleScrollWithDelta:atLocation:phase:"
+ "_trackpadHitTestCategoryAssertion"
+ "arrow.left.arrow.right"
+ "handleScrollWithDelta: %@ phase: %ld, success: %@"
+ "handleScrollWithDelta:atLocation:phase:"
+ "multitasking_dismissLeft"
+ "multitasking_dismissRight"
+ "multitasking_swap"
+ "setFingerDownCount:"
+ "setTrackpadHitTestCategoryAssertion:"
+ "shouldRecreateDrawnMousePointerFingerWhenPointerBehavesLikeFinger:dwellControlEnabled:currentFingerCount:"
+ "trackpadHitTestCategoryAssertion"
+ "xmark.rectangle"
- "T{CGPoint=dd},N,V_previousPointerPoint"
- "_previousPointerPoint"
- "handleScrollWithDelta: %@, success: %@"
- "previousPointerPoint"
- "setPreviousPointerPoint:"
```
