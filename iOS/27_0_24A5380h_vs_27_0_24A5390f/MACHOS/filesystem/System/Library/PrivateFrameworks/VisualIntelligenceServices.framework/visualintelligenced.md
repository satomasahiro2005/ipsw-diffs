## visualintelligenced

> `/System/Library/PrivateFrameworks/VisualIntelligenceServices.framework/visualintelligenced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x335d0` | `0x35da4` | **`+0x27d4`** |
| `__TEXT.__eh_frame` | `0x20a0` | `0x2240` | **`+0x1a0`** |
| `__DATA.__objc_const` | `0xcd0` | `0xda8` | **`+0xd8`** |
| `__DATA.__data` | `0xe48` | `0xf18` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x8a9` | `0x959` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x7c3` | `0x865` | **`+0xa2`** |
| `__DATA_CONST.__const` | `0x13a0` | `0x1440` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0xae8` | `0xb70` | **`+0x88`** |
| `__TEXT.__const` | `0x14d8` | `0x1558` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0x1d80` | `0x1dd0` | **`+0x50`** |
| `__TEXT.__objc_classname` | `0x357` | `0x3a7` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x664` | `0x6b0` | **`+0x4c`** |
| `__TEXT.__constg_swiftt` | `0x51c` | `0x560` | **`+0x44`** |
| `__TEXT.__swift5_fieldmd` | `0x448` | `0x47c` | **`+0x34`** |
| `__TEXT.__oslogstring` | `0x146a` | `0x149a` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0xec8` | `0xef0` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x324` | `0x344` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x6b8` | `0x6d0` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x1bc` | `0x1d0` | **`+0x14`** |
| `__TEXT.__objc_methname` | `0x318` | `0x324` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x114` | `0x120` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0xcc` | `0xd8` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x3e8` | `0x3f0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x5c` | `0x60` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`

### Other Changes

```diff

-224.1.0.0.0
+234.0.0.0.0

-  Functions: 708
-  Symbols:   786
-  CStrings:  234
+  Functions: 736
+  Symbols:   795
+  CStrings:  241
Symbols:
+ _$s22VisualIntelligenceCore0C22RecognitionReaderCacheC28arePreheatableModelsCompiledSbyYaFZ
+ _$s22VisualIntelligenceCore0C22RecognitionReaderCacheC28arePreheatableModelsCompiledSbyYaFZTu
+ _$s22VisualIntelligenceCore0C22RecognitionReaderCacheCMa
+ _$s22VisualIntelligenceCore11EntityStateO8reservedyA2CmFWC
+ _$s22VisualIntelligenceCore15ActionPredictorCMn
+ _$s22VisualIntelligenceCore17EntityPersistenceO20reserveAndAttachHEIC4from9predictor9timestamp5pinID9storeTaskSS0aB8Services21CodableFileDescriptorV_AA15ActionPredictorCSd10Foundation4UUIDVyScTyyts5NeverOGYaXEtYaKFZ
+ _$s22VisualIntelligenceCore17EntityPersistenceO20reserveAndAttachHEIC4from9predictor9timestamp5pinID9storeTaskSS0aB8Services21CodableFileDescriptorV_AA15ActionPredictorCSd10Foundation4UUIDVyScTyyts5NeverOGYaXEtYaKFZTu
+ _$s22VisualIntelligenceCore19E5GroundingProviderC02isE13ModelCompiledSbyFZ
+ _$s22VisualIntelligenceCore19E5GroundingProviderCMa
+ _$s26VisualIntelligenceServices15SaliencySessionC20UnavailabilityReasonO7unknownyAESScAEmFWC
+ _$sSbN
+ _$sScTss5NeverORs_rlE5valuexvg
+ _$sScTss5NeverORs_rlE5valuexvgTu
+ _swift_retain_x11
- _$s22VisualIntelligenceCore11EntityStateO11mediaBackedyA2CmFWC
- _$s22VisualIntelligenceCore17EntityPersistenceO23persistMaterializedHEIC4fromAA0D13RequestResultV0aB8Services21CodableFileDescriptorV_tYaKFZ
- _$s22VisualIntelligenceCore17EntityPersistenceO23persistMaterializedHEIC4fromAA0D13RequestResultV0aB8Services21CodableFileDescriptorV_tYaKFZTu
- _$s26VisualIntelligenceServices14EntityResponseO011mediaBackedD2IDyACSScACmFWC
- _swift_retain_x12
CStrings:
+ "%s handleCheckRichAnalysisAvailability(%s): available=%{bool}d, classifiers: %s"
+ "%s rich readiness [OCR] (%s): ocrReady=%{bool}d — OCR recognizers %s"
+ "%s rich readiness [VIVG] (%s): vivgReady=%{bool}d — grounding model %s"
+ "Action predictor deallocated"
+ "CoreRecognition: OCR models not yet compiled"
+ "Failed to reserve entity for HEIC: "
+ "Grounding (VIVG) model not yet compiled"
+ "_TtCC19visualintelligenced29VisualActionPredictionService11StatusCache"
+ "cached"
+ "not yet compiled"
+ "statusCache"
- "%s handleCheckRichAnalysisAvailability(%s): %s"
- "Client supplied a media-backed entity ID for pin %s — deprecated path; client should migrate to the HEIC file descriptor response"
- "Failed to ingest HEIC: "
- "_cachedStatus"
```
