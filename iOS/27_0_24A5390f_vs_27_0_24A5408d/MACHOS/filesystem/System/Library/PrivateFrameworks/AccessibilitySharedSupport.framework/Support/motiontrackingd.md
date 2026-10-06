## motiontrackingd

> `/System/Library/PrivateFrameworks/AccessibilitySharedSupport.framework/Support/motiontrackingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b728` | `0x2b904` | **`+0x1dc`** |
| `__TEXT.__objc_methtype` | `0x1e73` | `0x1ef9` | **`+0x86`** |
| `__TEXT.__oslogstring` | `0x267e` | `0x2633` | **`-0x4b`** |
| `__DATA.__objc_const` | `0x4cb8` | `0x4c88` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0xa08` | `0xa20` | **`+0x18`** |
| `__TEXT.__const` | `0x3ec` | `0x3fc` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x306c` | `0x307c` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xa84` | `0xa78` | **`-0xc`** |
| `__TEXT.__objc_methname` | `0x9a71` | `0x9a7d` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x21d8` | `0x21e0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3f4` | `0x3f0` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`

### Other Changes

```diff

-584.0.0.0.0
+587.0.0.0.0

-  Functions: 1074
+  Functions: 1075
CStrings:
+ "B88@0:8{?=[4]}16^{?=dddddddd{CGRect={CGPoint=dd}{CGSize=dd}}}80"
+ "_altHeadTrackingPrepareFrameWithPose:outFrame:"
+ "_altHeadTrackingScreenPointForDeflection:screenBounds:clampToScreen:"
+ "_iOSAccumulateJoystickNormalizedPosePoint:"
+ "{CGPoint=dd}68@0:8{CGPoint=dd}16{CGRect={CGPoint=dd}{CGSize=dd}}32B64"
- "AXMT[AltHeadTrackingPose] holding cursor: confidence %ld < %ld (acquiring)"
- "T{CGPoint=dd},N,V__altHeadTrackingInterfacePoint"
- "__altHeadTrackingInterfacePoint"
- "_altHeadTrackingInterfacePoint"
- "set_altHeadTrackingInterfacePoint:"
```
