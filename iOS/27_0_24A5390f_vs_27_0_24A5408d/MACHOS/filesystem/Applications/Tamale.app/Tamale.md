## Tamale

> `/Applications/Tamale.app/Tamale`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x101c18` | `0x101d4c` | **`+0x134`** |
| `__TEXT.__auth_stubs` | `0x58f0` | `0x5940` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x2c80` | `0x2ca8` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x7398` | `0x73c0` | **`+0x28`** |
| `__DATA.__data` | `0x83d8` | `0x83f8` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x111c6` | `0x111e6` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x6081` | `0x6071` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x17b8` | `0x17c8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3120` | `0x3128` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-234.0.0.0.0
+246.0.0.0.0

-  Functions: 4354
-  Symbols:   2502
+  Functions: 4355
+  Symbols:   2507
Symbols:
+ _$s12SiriSharedUI36VisualIntelligenceActionClientToHostC013requestReturnh10ViewfinderF0ACyFZ
+ _$s12SiriSharedUI36VisualIntelligenceActionClientToHostCMa
+ _$s20VisualIntelligenceUI13Scanwave2ViewV4data16highQualityImage7trigger8useDepth10onCompleteAcA12ScanwaveDataO_So7UIImageCSg05SwiftC07BindingVySiGSgSbyycSgtcfC
+ _$s20VisualIntelligenceUI13Scanwave2ViewV4data16highQualityImage7trigger8useDepth10onCompleteAcA12ScanwaveDataO_So7UIImageCSg05SwiftC07BindingVySiGSgSbyycSgtcfcfA2_
+ _$s20VisualIntelligenceUI16NewSaliencyModelC21montaraDismissHandleryycSgvs
+ _$s20VisualIntelligenceUI18CameraContentModelC17displayFrameImageSo7UIImageCSgvg
+ _$s20VisualIntelligenceUI18CameraContentModelC27standaloneDisplayFrameImageSo7UIImageCSgvg
+ _$s7SwiftUI45_AccessibilityIgnoresInvertColorsViewModifierVAA0gH0AAWP
+ _OBJC_CLASS_$__UIHostedWindowScene
- _$s20VisualIntelligenceUI13Scanwave2ViewV4data8useDepth10onCompleteAcA12ScanwaveDataO_SbyycSgtcfC
- _$s31VisualIntelligenceCameraSupport26StreamingSessionControllerC12displayFrameSo11CVBufferRefaSgvg
- _$s7SwiftUI45_AccessibilityIgnoresInvertColorsViewModifierVAA0gH0AAMc
- _$s7SwiftUI45_AccessibilityIgnoresInvertColorsViewModifierVN
CStrings:
+ "sendAction:"
- "_initWithIOSurface:imageOrientation:"
```
