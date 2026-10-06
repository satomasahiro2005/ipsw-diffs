## SetupAssistantSupportUI

> `/System/Library/PrivateFrameworks/SetupAssistantSupportUI.framework/SetupAssistantSupportUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x79e44` | `0x7b988` | **`+0x1b44`** |
| `__DATA.__bss` | `0x4498` | `0x4598` | **`+0x100`** |
| `__AUTH_CONST.__const` | `0x4070` | `0x4148` | **`+0xd8`** |
| `__AUTH.__data` | `0x2e40` | `0x2da8` | **`-0x98`** |
| `__AUTH.__objc_data` | `0xf10` | `0xfa8` | **`+0x98`** |
| `__TEXT.__eh_frame` | `0x1aa8` | `0x1af0` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x858` | `0x8a0` | **`+0x48`** |
| `__TEXT.__cstring` | `0x184b` | `0x188b` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1328` | `0x1358` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x178f` | `0x17bf` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1f50` | `0x1f80` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x13a8` | `0x13d0` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x1a3c` | `0x1a64` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x416f` | `0x4197` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x668` | `0x678` | **`+0x10`** |
| `__TEXT.__const` | `0x48a0` | `0x48b0` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x1937` | `0x1947` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x224` | `0x22c` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x2c18` | `0x2c14` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x1ec` | `0x1f0` | **`+0x4`** |

### Other Changes

```diff

-567.101.0.0.0
+568.1.3.0.0

-  Functions: 2892
-  Symbols:   1630
-  CStrings:  321
+  Functions: 2906
+  Symbols:   1638
+  CStrings:  323
Symbols:
+ _CGRectInset
+ _CGRectIntersection
+ _CGRectIntersectsRect
+ _CGRectOffset
+ _CTFramesetterSuggestFrameSizeWithConstraints
+ _OBJC_CLASS_$_UIApplication
+ _OBJC_CLASS_$_UIScene
+ _OBJC_CLASS_$_UIWindowScene
+ ___swift_closure_destructor.12Tm
+ ___swift_closure_destructor.22Tm
+ _associated conformance 23SetupAssistantSupportUI18BookendViewWrapperC14AnimationStateOSHAASQ
+ _associated conformance 23SetupAssistantSupportUI9HelloViewC19PendingFrameRequest33_C70A6F0B14EE99C9BAC79BE9473ED057LLOSHAASQ
+ _swift_dynamicCastObjCClass
+ _symbolic So8UIScreenC
+ _symbolic _____ 23SetupAssistantSupportUI18BookendViewWrapperC14AnimationStateO
+ _symbolic _____ 23SetupAssistantSupportUI9HelloViewC19PendingFrameRequest33_C70A6F0B14EE99C9BAC79BE9473ED057LLO
+ _symbolic _____Sg 23SetupAssistantSupportUI9HelloViewC19PendingFrameRequest33_C70A6F0B14EE99C9BAC79BE9473ED057LLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So7CGPointV
+ _symbolic _____z_Xx 12CoreGraphics7CGFloatV
- _CGPathGetPathBoundingBox
- _CGPathIsRect
- _CTLineGetTypographicBounds
- _OBJC_CLASS_$_UIScreen
- ___swift_closure_destructor.11Tm
- ___swift_closure_destructor.21Tm
- _associated conformance 23SetupAssistantSupportUI18BookendViewWrapperC14AnimationState33_AD4A13777B11A6832A98F7B787266297LLOSHAASQ
- _symbolic _____ 23SetupAssistantSupportUI18BookendViewWrapperC14AnimationState33_AD4A13777B11A6832A98F7B787266297LLO
- _symbolic _____ So16CGMutablePathRefa
- _symbolic _____ So9CGPathRefa
- _symbolic _____Sg So9CGPathRefa
CStrings:
+ "Rendering a single frame while %s: %s"
+ "background texture changed"
+ "drawable size changed"
- "Text size: {%f, %f}"
```
