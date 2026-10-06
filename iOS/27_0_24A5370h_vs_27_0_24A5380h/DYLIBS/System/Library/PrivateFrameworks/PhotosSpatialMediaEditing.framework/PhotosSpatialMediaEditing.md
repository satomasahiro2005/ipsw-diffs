## PhotosSpatialMediaEditing

> `/System/Library/PrivateFrameworks/PhotosSpatialMediaEditing.framework/PhotosSpatialMediaEditing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x318c0` | `0x32d5c` | **`+0x149c`** |
| `__DATA_DIRTY.__data` | `0xc8` | `0x8e0` | **`+0x818`** |
| `__AUTH.__data` | `0x850` | `0x178` | **`-0x6d8`** |
| `__AUTH.__objc_data` | `0x580` | `0x288` | **`-0x2f8`** |
| `__DATA_DIRTY.__objc_data` | `0x220` | `0x518` | **`+0x2f8`** |
| `__TEXT.__const` | `0x1bc8` | `0x1e88` | **`+0x2c0`** |
| `__TEXT.__swift5_reflstr` | `0x7e6` | `0x9f6` | **`+0x210`** |
| `__AUTH_CONST.__objc_const` | `0x1990` | `0x1b48` | **`+0x1b8`** |
| `__DATA.__bss` | `0x2180` | `0x2300` | **`+0x180`** |
| `__AUTH_CONST.__const` | `0xf08` | `0x1020` | **`+0x118`** |
| `__TEXT.__swift5_fieldmd` | `0x78c` | `0x894` | **`+0x108`** |
| `__TEXT.__cstring` | `0xe8f` | `0xf8f` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x5bf` | `0x4ff` | **`-0xc0`** |
| `__TEXT.__constg_swiftt` | `0xa6c` | `0xb20` | **`+0xb4`** |
| `__TEXT.__swift5_typeref` | `0x7ac` | `0x83c` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0xcd0` | `0xd50` | **`+0x80`** |
| `__DATA.__data` | `0x9e0` | `0xa40` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0xd50` | `0xd98` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x130` | `0x170` | **`+0x40`** |
| `__DATA.__common` | `0x138` | `0x114` | **`-0x24`** |
| `__DATA_DIRTY.__common` | `0x10` | `0x30` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x8d0` | `0x8e8` | **`+0x18`** |
| `__TEXT.__eh_frame` | `0xdc8` | `0xdb0` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x50` | `0x64` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x98` | `0xa8` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x10c` | `0x118` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x70` | `0x78` | **`+0x8`** |

### Other Changes

```diff

-910.21.101.0.0
+910.27.103.0.0

+  - /System/Library/Frameworks/ImageIO.framework/ImageIO

-  Functions: 1358
-  Symbols:   720
-  CStrings:  116
+  Functions: 1428
+  Symbols:   746
+  CStrings:  120
Symbols:
+ __DATA__TtC25PhotosSpatialMediaEditing36SpatialReframePipelineAnalyticsStash
+ __IVARS__TtC25PhotosSpatialMediaEditing36SpatialReframePipelineAnalyticsStash
+ __METACLASS_DATA__TtC25PhotosSpatialMediaEditing36SpatialReframePipelineAnalyticsStash
+ ___swift_memcpy112_16
+ ___swift_memcpy4_4
+ ___swift_memcpy64_8
+ ___swift_memcpy72_16
+ _acosf
+ _associated conformance So11CFStringRefa14CoreFoundation9_CFObjectSCSH
+ _associated conformance So11CFStringRefaSHSCSQ
+ _kCGImagePropertyExifDictionary
+ _kCGImagePropertyExifFocalLength
+ _kCGImagePropertyOrientation
+ _objc_retain_x28
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_dynamicCastObjCClass
+ _swift_release_n
+ _swift_setDeallocating
+ _symbolic SDy_____ypG So11CFStringRefa
+ _symbolic Sd
+ _symbolic Su
+ _symbolic Su_SSt
+ _symbolic _____ 24PhotosGenerativeServices13FaceViewpointV
+ _symbolic _____ 25PhotosSpatialMediaEditing0B29ReframePipelineAnalyticsStashC
+ _symbolic _____ 25PhotosSpatialMediaEditing0B29ReframePipelineAnalyticsStashC8SnapshotV
+ _symbolic _____ So16os_unfair_lock_sV
+ _symbolic _____ySf5depth______ySfG8paddingstG s23_ContiguousArrayStorageC s5SIMD4V
+ _symbolic _____ySu_SStG s23_ContiguousArrayStorageC
+ _symbolic _____yytG 2os21OSAllocatedUnfairLockV
+ _symbolic _____yyt_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _type_layout_string 25PhotosSpatialMediaEditing0B29ReframePipelineAnalyticsStashC8SnapshotV
+ _type_layout_string So16os_unfair_lock_sV
- ___swift_memcpy120_16
- ___swift_memcpy76_16
- _objc_retain_x10
- _objc_retain_x27
- _swift_bridgeObjectRelease_n
- _swift_retain_x21
- _swift_willThrowTypedImpl
CStrings:
+ "Face viewed too steeply"
+ "Reframe no-face pivot: RSI=%f (thr %f) → %s depth %f"
+ "Reframe pivot: face=%f, salient=%f → %f"
+ "SpatialPhotoReframeEnableViewingAngleRestriction"
+ "SpatialPhotoReframeGeneralNearHeadboxPaddings"
+ "SpatialPhotoReframeQuantileDepthFraction"
+ "SpatialPhotoReframeSensitivityThreshold"
+ "SpatialPhotoReframeSideViewGoodSideReductionRate"
+ "SpatialPhotoReframeSideViewMaxAngleDegrees"
+ "SpatialPhotoReframeSideViewMinAngleDegrees"
+ "SpatialPhotoReframeSideViewYawThresholdDegrees"
+ "imageSizeValidation"
+ "photoDepthEffect"
+ "viewingAngle"
- "Depth clamped: %f (nearestDepth=%f, d10=%f, d75=%f)"
- "Reframe detected face depth %f, salient depth %f. Using face depth: %f"
- "Reframe detected face depth %f, salient depth %f. Using salient depth: %f"
- "Reframe no detected face, salient depth %f. Using salient depth: %f"
- "Side-view face restricted"
- "SpatialPhotoReframeLandscapeScoreThreshold"
- "SpatialPhotoReframeSubjectGeneralHeadboxPaddings"
- "SpatialPhotoReframeSubjectGuardrailHeadboxPaddings"
- "landscapeScore"
- "rejectedTooSmall"
```
