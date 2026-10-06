## ShaderGraph

> `/System/Library/SubFrameworks/ShaderGraph.framework/ShaderGraph`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e4070` | `0x1e41c4` | **`+0x154`** |
| `__TEXT.__eh_frame` | `0x85cc` | `0x8624` | **`+0x58`** |
| `__TEXT.__const` | `0x127f0` | `0x127c0` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x5548` | `0x5520` | **`-0x28`** |
| `__TEXT.__cstring` | `0x1c62d` | `0x1c64d` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x11a8` | `0x11b8` | **`+0x10`** |
| `__DATA.__data` | `0x38b0` | `0x38a0` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x13a9` | `0x13b9` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x3dec` | `0x3ddc` | **`-0x10`** |

### Other Changes

```diff

-159.0.0.0.1
+159.0.2.0.0

-  Functions: 8139
-  Symbols:   18113
-  CStrings:  3069
+  Functions: 8143
+  Symbols:   18112
+  CStrings:  3071
Symbols:
+ _$s11ShaderGraph04UserB0V11splitGraphsyyKF
+ _$s11ShaderGraph04UserB0V11splitGraphsyyKFyAA5InputVXEfU_
+ _$s11ShaderGraph04UserB0V11splitGraphsyyKFyAA5InputVXEfU_yAA4EdgeVXEfU0_
+ _$s11ShaderGraph12NodeDefStoreV019patchedUsdUVTextureD033_58C10E9536C4718342CF9916B0AAD6BDLLyAA0cD0VAGF
+ _$s11ShaderGraph12NodeDefStoreV25applyStandardLibraryFixes33_58C10E9536C4718342CF9916B0AAD6BDLL3foryAA16MaterialXVersionV_tKFySS_SayAA0cD0V14ImplementationVGtXEfU0_A2LXEfU_
+ _$s11ShaderGraph8DataTypeO_ACtWOh
+ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfC11ShaderGraph0cD4NodeV2IDV_AETt0g5Tf4g_n
+ _$sSa15replaceSubrange_4withySnySiG_qd__nt7ElementQyd__RszSlRd__lFSS_s15EmptyCollectionVySSGTg5Tf4ndn_n
+ _$sSo24NSOperatingSystemVersionawstTm
+ _$ss17_NativeDictionaryV20_copyOrMoveAndResize8capacity12moveElementsySi_SbtF11ShaderGraph0kL4NodeV2IDV_AHTg5
+ _$ss17_NativeDictionaryV4copyyyF11ShaderGraph0dE4NodeV2IDV_AFTg5
+ _$ss17_NativeDictionaryV7_insert2at3key5valueys10_HashTableV6BucketV_xnq_ntF11ShaderGraph0jK4NodeV2IDV_AMTB5
+ _$ss17_NativeDictionaryV8setValue_6forKey8isUniqueyq_n_xSbtF11ShaderGraph0iJ4NodeV2IDV_AHTB5
+ _$ss18_DictionaryStorageCy11ShaderGraph0cD4NodeV2IDVAEGMR
+ _$ss18_DictionaryStorageCy11ShaderGraph0cD4NodeV2IDVAEGMd
+ _objc_retain_x11
+ _swift_release_x12
+ _swift_retain_x10
+ _symbolic _____y__________G s18_DictionaryStorageC 11ShaderGraph0cD4NodeV2IDV AE
- _$s11ShaderGraph04UserB0V16splitSharedNodes12nodeDefStore07surfaceA016geometryModifieryAA04NodehI0V_AA0abM0VAKSgtKF
- _$s11ShaderGraph04UserB0V16splitSharedNodes12nodeDefStore07surfaceA016geometryModifieryAA04NodehI0V_AA0abM0VAKSgtKFyAKXEfU0_
- _$s11ShaderGraph12NodeDefStoreV25applyStandardLibraryFixes33_58C10E9536C4718342CF9916B0AAD6BDLL3foryAA16MaterialXVersionV_tKFySS_SayAA0cD0V14ImplementationVGtXEfU1_A2LXEfU_
- _$s11ShaderGraph5InputV_AC_ACttMR
- _$s11ShaderGraph5InputV_AC_ACttMd
- _$s11ShaderGraph6OutputVSgWOc
- _$s11ShaderGraph6OutputV_AC_ACttMR
- _$s11ShaderGraph6OutputV_AC_ACttMd
- _$s11ShaderGraph6OutputV_ACtSgMR
- _$s11ShaderGraph6OutputV_ACtSgMd
- _$s11ShaderGraph6OutputV_ACtSgWOi_
- _$sSa15replaceSubrange_4withySnySiG_qd__nt7ElementQyd__RszSlRd__lF11ShaderGraph4EdgeV_s15EmptyCollectionVyAHGTg5Tf4ndn_n
- _$sSa15replaceSubrange_4withySnySiG_qd__nt7ElementQyd__RszSlRd__lFSS_s15EmptyCollectionVySSGTg5Tf4ndn_nTm
- _$ss12Zip2SequenceV8IteratorV4next7ElementQz_AFQy_tSgyFSay11ShaderGraph6OutputVG_AMTg5
- _$ss20_ArrayBufferProtocolPsE15replaceSubrange_4with10elementsOfySnySiG_Siqd__ntSlRd__7ElementQyd__AGRtzlFs01_aB0Vy11ShaderGraph4EdgeVG_s15EmptyCollectionVyANGTg5Tf4nndn_n
- _$ss22_ContiguousArrayBufferV19_uninitializedCount15minimumCapacityAByxGSi_SitcfC11ShaderGraph4EdgeV_Tt1g5
- _objc_retain_x10
- _symbolic ______AA_AAtt 11ShaderGraph5InputV
- _symbolic ______AA_AAtt 11ShaderGraph6OutputV
- _symbolic ______AAtSg 11ShaderGraph6OutputV
CStrings:
+ "ERROR unable to find from node or output"
+ "ERROR unable to find to node or input"
+ "ND_UsdUVTexture_23_vector4"
- "Edge destination node isn't a surface node or geometry modifier node."
```
