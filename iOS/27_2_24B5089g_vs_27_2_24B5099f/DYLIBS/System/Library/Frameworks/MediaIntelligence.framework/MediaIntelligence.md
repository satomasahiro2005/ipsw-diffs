## MediaIntelligence

> `/System/Library/Frameworks/MediaIntelligence.framework/MediaIntelligence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a594` | `0x1c438` | **`+0x1ea4`** |
| `__TEXT.__eh_frame` | `0xa08` | `0xb80` | **`+0x178`** |
| `__TEXT.__swift5_typeref` | `0x90e` | `0x9f2` | **`+0xe4`** |
| `__AUTH_CONST.__const` | `0x1140` | `0x1208` | **`+0xc8`** |
| `__TEXT.__swift5_capture` | `0xc8` | `0x13c` | **`+0x74`** |
| `__TEXT.__cstring` | `0x3e3` | `0x453` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0x858` | `0x8c0` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x5e0` | `0x648` | **`+0x68`** |
| `__TEXT.__const` | `0x1788` | `0x17e8` | **`+0x60`** |
| `__DATA.__data` | `0x4a8` | `0x4e8` | **`+0x40`** |
| `__TEXT.__swift_as_entry` | `0x6c` | `0x78` | **`+0xc`** |
| `__TEXT.__swift_as_cont` | `0x5c` | `0x64` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x44` | `0x48` | **`+0x4`** |

### Other Changes

```diff

-460.8.2.0.0
+460.12.1.0.0

-  Functions: 565
-  Symbols:   487
-  CStrings:  52
+  Functions: 586
+  Symbols:   500
+  CStrings:  55
Symbols:
+ ___swift_closure_destructorTm
+ _get_enum_tag_for_layout_string SD8IteratorV8_VariantOy17MediaIntelligence17FaceGroupAnalyzerC6EntityV2IDVSayAE0cD10ImageAssetVAJVG__G
+ _get_witness_table Scsy17MediaIntelligence0aB10ImageAssetV2IDV05assetE0_SayAA17FaceGroupAnalyzerC0G0VG5facests5Error_pGSciHPyHC
+ _swift_retain_x21
+ _swift_retain_x22
+ _swift_retain_x27
+ _swift_task_create
+ _symbolic Say_____G 17MediaIntelligence0aB10ImageAssetV
+ _symbolic ScA_pSg
+ _symbolic ScPSg
+ _symbolic Scsy_____7assetID_Say_____G5facest______pG 17MediaIntelligence0aB10ImageAssetV2IDV AA17FaceGroupAnalyzerC0F0V s5ErrorP
+ _symbolic _____y_____7assetID_Say_____G5facest______p_G Scs12ContinuationV 17MediaIntelligence0bC10ImageAssetV2IDV AC17FaceGroupAnalyzerC0G0V s5ErrorP
+ _symbolic _____y_____7assetID_Say_____G5facest______p__G Scs12ContinuationV11YieldResultO 17MediaIntelligence0dE10ImageAssetV2IDV AE17FaceGroupAnalyzerC0I0V s5ErrorP
+ _symbolic _____y_____7assetID_Say_____G5facest______p__G Scs12ContinuationV15BufferingPolicyO 17MediaIntelligence0dE10ImageAssetV2IDV AE17FaceGroupAnalyzerC0I0V s5ErrorP
+ _symbolic ytIeAgHr_
+ _type_layout_string 17MediaIntelligence17FaceGroupAnalyzerC22FacesByAssetIDSequenceV
+ _type_layout_string 17MediaIntelligence17FaceGroupAnalyzerC26AssetIDsByEntityIDSequenceV8IteratorV
- _get_enum_tag_for_layout_string SD8IteratorV8_VariantOy17MediaIntelligence0cD10ImageAssetV2IDVSayAE17FaceGroupAnalyzerC0H0VG__G
- _swift_release_x1
- _type_layout_string 17MediaIntelligence17FaceGroupAnalyzerC22FacesByAssetIDSequenceV8IteratorV
- _type_layout_string 17MediaIntelligence17FaceGroupAnalyzerC23FacesByEntityIDSequenceV
CStrings:
+ " asset(s), skipped "
+ "Rolling back changes in MIDataStore for asset "
+ "identifyFaces: processed "
+ "insertOrUpdateAssets: processed "
- "Failed to analyze faces for asset "
```
