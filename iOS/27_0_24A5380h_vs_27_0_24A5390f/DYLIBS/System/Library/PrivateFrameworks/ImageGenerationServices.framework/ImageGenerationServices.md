## ImageGenerationServices

> `/System/Library/PrivateFrameworks/ImageGenerationServices.framework/ImageGenerationServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x89ad0` | `0x8ed84` | **`+0x52b4`** |
| `__TEXT.__eh_frame` | `0x3d38` | `0x40c0` | **`+0x388`** |
| `__DATA.__bss` | `0x5700` | `0x5980` | **`+0x280`** |
| `__TEXT.__oslogstring` | `0x16f2` | `0x18d2` | **`+0x1e0`** |
| `__TEXT.__const` | `0x6315` | `0x64d5` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x7932` | `0x7a62` | **`+0x130`** |
| `__AUTH_CONST.__const` | `0x4560` | `0x4640` | **`+0xe0`** |
| `__AUTH_CONST.__auth_got` | `0x1648` | `0x1718` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x1fd0` | `0x2098` | **`+0xc8`** |
| `__TEXT.__swift5_reflstr` | `0x1575` | `0x1615` | **`+0xa0`** |
| `__DATA.__data` | `0x910` | `0x990` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x1664` | `0x16e2` | **`+0x7e`** |
| `__DATA_CONST.__const` | `0xd8` | `0x108` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x848` | `0x870` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x2c0` | `0x2e8` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0xfe4` | `0x1008` | **`+0x24`** |
| `__DATA_DIRTY.__data` | `0x1958` | `0x1938` | **`-0x20`** |
| `__TEXT.__swift5_builtin` | `0x104` | `0xf0` | **`-0x14`** |
| `__TEXT.__swift5_capture` | `0x294` | `0x2a8` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x368` | `0x37c` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x174` | `0x188` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x104` | `0x110` | **`+0xc`** |
| `__TEXT.__swift5_fieldmd` | `0x15e0` | `0x15d8` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x18c` | `0x190` | **`+0x4`** |

### Other Changes

```diff

-193.1.0.0.0
+194.1.0.0.0

+  - /System/Library/Frameworks/ImagePlayground.framework/ImagePlayground

+  - /System/Library/Frameworks/UIKit.framework/UIKit

+  - /usr/lib/swift/libswiftGLKit.dylib

+  - /usr/lib/swift/libswiftMetalKit.dylib
+  - /usr/lib/swift/libswiftModelIO.dylib

+  - /usr/lib/swift/libswiftSceneKit.dylib
+  - /usr/lib/swift/libswiftSpatial.dylib

-  Functions: 2448
-  Symbols:   1436
-  CStrings:  339
+  Functions: 2486
+  Symbols:   1458
+  CStrings:  351
Symbols:
+ _CFDataCreateMutable
+ _CGImageDestinationAddImage
+ _CGImageDestinationCreateWithData
+ _CGImageDestinationFinalize
+ _CGRectIntersection
+ _CGRectIsEmpty
+ ___swift_closure_destructorTm
+ ___swift_memcpy81_8
+ __swift_FORCE_LOAD_$_swiftGLKit
+ __swift_FORCE_LOAD_$_swiftGLKit_$_ImageGenerationServices
+ __swift_FORCE_LOAD_$_swiftMetalKit
+ __swift_FORCE_LOAD_$_swiftMetalKit_$_ImageGenerationServices
+ __swift_FORCE_LOAD_$_swiftModelIO
+ __swift_FORCE_LOAD_$_swiftModelIO_$_ImageGenerationServices
+ __swift_FORCE_LOAD_$_swiftSceneKit
+ __swift_FORCE_LOAD_$_swiftSceneKit_$_ImageGenerationServices
+ __swift_FORCE_LOAD_$_swiftSpatial
+ __swift_FORCE_LOAD_$_swiftSpatial_$_ImageGenerationServices
+ __swift_FORCE_LOAD_$_swiftUIKit
+ __swift_FORCE_LOAD_$_swiftUIKit_$_ImageGenerationServices
+ _associated conformance 16VisualGeneration5ImageO0cB8ServicesE18PNGConversionErrorOSHADSQ
+ _associated conformance 23ImageGenerationServices05AsyncA9GeneratorC0B13ConfigurationV30DirectManipulationRequestErrorO10Foundation09LocalizedJ0AAs0J0
+ _associated conformance 23ImageGenerationServices05AsyncA9GeneratorC0B13ConfigurationV30DirectManipulationRequestErrorOSHAASQ
+ _symbolic SS4name______5imaget 16VisualGeneration5ImageO
+ _symbolic _____ 16VisualGeneration5ImageO0cB8ServicesE18PNGConversionErrorO
+ _symbolic _____ 23ImageGenerationServices05AsyncA9GeneratorC0B13ConfigurationV30DirectManipulationRequestErrorO
+ _symbolic _____10canvasSize______12subjectFrameAA11translation_____5scaleAF8rotationt So6CGSizeV So6CGRectV 12CoreGraphics7CGFloatV
+ _symbolic ______p 16VisualGeneration13InternalStateP
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation3URLV
+ _type_layout_string So6CGSizeV
- _CGAffineTransformDecompose
- ___swift_memcpy48_8
- _associated conformance 23ImageGenerationServices05AsyncA9GeneratorC22DirectManipulationInfoV6IntentOSHAASQ
- _symbolic _____ So17CGAffineTransformV
- _symbolic _____Sg 16VisualGeneration30ImageDirectManipulationRequestV
- _symbolic _____Sg So17CGAffineTransformV
- _type_layout_string So17CGAffineTransformV
- _type_layout_string So7CGPointV
CStrings:
+ "Cannot build direct manipulation request: baseImage is missing on the configuration."
+ "Cannot build direct manipulation request: directManipulationInfo is missing on the configuration."
+ "DM debug dry-run produced no SerializedInferenceRequest"
+ "DirectManipulationDebugExtract"
+ "DirectManipulationRequest"
+ "Face crop rect did not intersect image extent"
+ "Failed to convert DM debug image '%s' to PNG: %@"
+ "Failed to serialize directManipulationPromptAnalyzerMetadata (safeMode=%{bool,public}d): %{public}@"
+ "Vision face perform failed: %{public}s"
+ "VisualGeneration.ImagePlayground.SheetAPI.Creation.Base.1p"
+ "VisualGeneration.ImagePlayground.SheetAPI.Creation.Base.3p"
+ "VisualGeneration.ImagePlayground.SheetAPI.Creation.Personalized.1p"
+ "VisualGeneration.ImagePlayground.SheetAPI.Creation.Personalized.3p"
+ "VisualGeneration.ImagePlayground.SheetAPI.ImageWand.1p"
+ "faceRegionOfInterest(in:)"
+ "makeDirectManipulationRequest failed: baseImage is missing"
+ "makeDirectManipulationRequest failed: directManipulationInfo is missing"
- "VisualGeneration.ImagePlaygroundSheetAPI.Creation.Base.1p"
- "VisualGeneration.ImagePlaygroundSheetAPI.Creation.Base.3p"
- "VisualGeneration.ImagePlaygroundSheetAPI.Creation.Personalized.1p"
- "VisualGeneration.ImagePlaygroundSheetAPI.Creation.Personalized.3p"
- "VisualGeneration.ImagePlaygroundSheetAPI.ImageWand.1p"
```
