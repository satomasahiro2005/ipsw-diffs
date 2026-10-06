## MagnifierServices

> `/System/Library/PrivateFrameworks/MagnifierServices.framework/MagnifierServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5094` | `0x6168` | **`+0x10d4`** |
| `__AUTH_CONST.__const` | `0x718` | `0xbf8` | **`+0x4e0`** |
| `__DATA.__bss` | `0xf00` | `0x1300` | **`+0x400`** |
| `__TEXT.__cstring` | `0x36b` | `0x673` | **`+0x308`** |
| `__TEXT.__const` | `0x832` | `0xac2` | **`+0x290`** |
| `__TEXT.__swift5_reflstr` | `0xac` | `0x2b5` | **`+0x209`** |
| `__TEXT.__swift5_fieldmd` | `0x128` | `0x248` | **`+0x120`** |
| `__TEXT.__swift5_typeref` | `0x228` | `0x286` | **`+0x5e`** |
| `__TEXT.__unwind_info` | `0x2c0` | `0x318` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0x168` | `0x1bc` | **`+0x54`** |
| `__TEXT.__swift5_capture` | `0x60` | `0xa0` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x3c0` | `0x3f0` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `—` | `0x30` | **`+0x30`** |
| `__DATA.__data` | `0x3f0` | `0x418` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0x78` | `0x98` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x2c` | `0x38` | **`+0xc`** |

### Other Changes

```diff

-275.0.0.0.0
+278.0.0.0.0

-  Functions: 239
-  Symbols:   246
-  CStrings:  25
+  Functions: 288
+  Symbols:   260
+  CStrings:  48
Symbols:
+ __swiftImmortalRefCount
+ _associated conformance 17MagnifierServices19MAGAnalyticsSurfaceOSHAASQ
+ _associated conformance 17MagnifierServices25MAGAnalyticsVqaErrorLabelOSHAASQ
+ _associated conformance 17MagnifierServices26MAGAnalyticsVqaRequestTypeOSHAASQ
+ _swift_arrayDestroy
+ _swift_initStackObject
+ _swift_setDeallocating
+ _symbolic $sSY
+ _symbolic SS
+ _symbolic SS_So8NSObjectCt
+ _symbolic _____ 17MagnifierServices19MAGAnalyticsSurfaceO
+ _symbolic _____ 17MagnifierServices25MAGAnalyticsVqaErrorLabelO
+ _symbolic _____ 17MagnifierServices26MAGAnalyticsVqaRequestTypeO
+ _symbolic _____ySS_So8NSObjectCtG s23_ContiguousArrayStorageC
CStrings:
+ "com.apple.accessibility.liverecognition.vqa.conversation"
+ "com.apple.accessibility.liverecognition.vqa.modelresponseerror"
+ "com.apple.accessibility.magnifier.vqa.conversation"
+ "com.apple.accessibility.magnifier.vqa.modelresponseerror"
+ "generativeModelsUnavailable"
+ "hadDefaultQuestion"
+ "inputDetectedAsJailbreakAttempt"
+ "inputFailedMultimodalGuardrail"
+ "inputImageBlurry"
+ "inputImageContainsSensitiveContent"
+ "inputImageConversionFailed"
+ "inputImageDark"
+ "itemSearchFailed"
+ "modelBundleNotFound"
+ "modelInvocationError"
+ "modelResponseFormattingFailed"
+ "multiTurn"
+ "noValidImagesForVQA"
+ "safetyRejected"
+ "safetyRejectedOffensiveWords"
+ "sceneDescription"
+ "simpleVQA"
+ "unknown"
```
