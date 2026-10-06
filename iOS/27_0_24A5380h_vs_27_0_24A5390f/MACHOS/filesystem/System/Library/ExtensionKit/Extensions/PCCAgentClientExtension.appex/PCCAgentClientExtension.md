## PCCAgentClientExtension

> `/System/Library/ExtensionKit/Extensions/PCCAgentClientExtension.appex/PCCAgentClientExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4c554` | `0x2c650` | **`-0x1ff04`** |
| `__DATA.__bss` | `0x8000` | `0xa80` | **`-0x7580`** |
| `__TEXT.__const` | `0x49a2` | `0xcd2` | **`-0x3cd0`** |
| `__DATA_CONST.__const` | `0x2f70` | `0x550` | **`-0x2a20`** |
| `__TEXT.__swift5_fieldmd` | `0x1810` | `0x25c` | **`-0x15b4`** |
| `__TEXT.__eh_frame` | `0x2be0` | `0x1f90` | **`-0xc50`** |
| `__DATA.__data` | `0x1590` | `0x9f8` | **`-0xb98`** |
| `__TEXT.__auth_stubs` | `0x1dd0` | `0x12b0` | **`-0xb20`** |
| `__TEXT.__swift5_typeref` | `0xea9` | `0x443` | **`-0xa66`** |
| `__TEXT.__constg_swiftt` | `0xdb4` | `0x390` | **`-0xa24`** |
| `__TEXT.__unwind_info` | `0x1298` | `0x8a8` | **`-0x9f0`** |
| `__TEXT.__swift5_reflstr` | `0x8d8` | `0x1e8` | **`-0x6f0`** |
| `__DATA_CONST.__auth_got` | `0xef0` | `0x960` | **`-0x590`** |
| `__TEXT.__cstring` | `0xcae` | `0x78e` | **`-0x520`** |
| `__TEXT.__swift5_proto` | `0x408` | `0x5c` | **`-0x3ac`** |
| `__DATA_CONST.__got` | `0x578` | `0x288` | **`-0x2f0`** |
| `__TEXT.__swift5_types` | `0x168` | `0x30` | **`-0x138`** |
| `__DATA_CONST.__auth_ptr` | `0x4a0` | `0x388` | **`-0x118`** |
| `__DATA.__objc_const` | `0x6b8` | `0x5e0` | **`-0xd8`** |
| `__TEXT.__objc_classname` | `0x20d` | `0x1dd` | **`-0x30`** |
| `__TEXT.__swift5_builtin` | `0x14` | `—` | **`-0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x38` | `0x30` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0x8` | `—` | **`-0x8`** |
| `__TEXT.__objc_methname` | `0x122` | `0x11c` | **`-0x6`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-43.0.0.0.0
+47.0.0.0.0

-  Functions: 1383
-  Symbols:   142
-  CStrings:  222
+  Functions: 440
+  Symbols:   135
+  CStrings:  181
Symbols:
+ _objc_retain_x23
- __swiftEmptySetSingleton
- _bzero
- _objc_retain_x25
- _swift_arrayInitWithCopy
- _swift_arrayInitWithTakeBackToFront
- _swift_arrayInitWithTakeFrontToBack
- _swift_cvw_enumFn_getEnumTag
- _swift_makeBoxUnique
CStrings:
- "ConditioningImage"
- "DirectManipulation"
- "DrawingConditioner"
- "Expected String, Int, or Double"
- "MessageBackground"
- "MessagesBackground"
- "PersonalizationImage"
- "SpatialReframing"
- "_TtC23PCCAgentClientExtension15ConnectionCache"
- "activeAdapterIdentifier"
- "additionalResults"
- "boundingBoxCount"
- "cache"
- "canPersonalizeFromConditioningImage"
- "candidateKnowledgeIds"
- "com.apple.fm.service.hksvprocessing.v1"
- "com.apple.fm.service.hksvprocessing_pro.v1"
- "com.apple.fm.service.vlu.v1"
- "containPreviousProcessing"
- "debiasingMetadataByteCount"
- "desiredResolution"
- "directManipulationOperation"
- "domainPrediction"
- "durationTimeScale"
- "durationTimeValue"
- "emojiHasBackground"
- "fragmentSequenceNumber"
- "generatedImageDimensions"
- "generationControl"
- "imageTransformsCount"
- "imageVariationsCount"
- "layoutConfiguration"
- "modelPredictions"
- "performBackgroundRemoval"
- "performPostProcessingSafetyCheck"
- "performPreProcessingSafetyCheck"
- "performSafetyCheck"
- "previousCaptions"
- "previousEmbeddings"
- "representationNumber"
- "structuredLocales"
```
