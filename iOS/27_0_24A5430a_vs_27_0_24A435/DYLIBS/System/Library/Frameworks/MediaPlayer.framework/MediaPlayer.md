## MediaPlayer

> `/System/Library/Frameworks/MediaPlayer.framework/MediaPlayer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38df00` | `0x38df30` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x2b38` | `0x2b40` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 17204
+  Functions: 17203
Symbols:
+ _swift_release_x28
- _OUTLINED_FUNCTION_12
Functions:
~ __ZNSt3__16vectorIiNS_9allocatorIiEEE24__emplace_back_slow_pathIJiEEEPiDpOT_ : 184 -> 176
~ __ZL37_MPMLInsertPredicatesForIdentifierSetRNSt3__16vectorINS_10shared_ptrIN6mlcore9PredicateEEENS_9allocatorIS4_EEEEP7NSArrayIP15MPIdentifierSetEPNS2_13ModelPropertyIxEESG_SG_SG_PNSE_INS_12basic_stringIcNS_11char_traitsIcEENS5_IcEEEEEESG_SN_SN_ : 4912 -> 4920
~ __ZNSt3__16vectorIPN6mlcore17ModelPropertyBaseENS_9allocatorIS3_EEE24__emplace_back_slow_pathIJS3_EEEPS3_DpOT_ : 184 -> 176
~ -[MPLibraryObjectDatabase updateTokensForResults:] : 12248 -> 12256
~ __ZNSt3__16vectorIU8__strongPU44objcproto33MPObjectDatabaseProgressiveResult11objc_objectNS_9allocatorIS3_EEE24__emplace_back_slow_pathIJRU8__strongKS2_EEEPS3_DpOT_ : 268 -> 256
~ -[MPServerObjectDatabase updateTokensForResults:] : 2824 -> 2816
~ ___49-[MPServerObjectDatabase updateTokensForResults:]_block_invoke.187 : 3152 -> 3156
~ -[MPMediaLibraryEntityTranslator MLCoreSortDescriptorsForModelSortDescriptors:] : 2168 -> 2120
~ __ZNSt3__16vectorIxNS_9allocatorIxEEE24__emplace_back_slow_pathIJxEEEPxDpOT_ : 184 -> 176
~ -[MPQueueFeederIdentifierRegistry applyChanges:identifierSetLookupBlock:itemIdentifierLookupBlock:] : 1156 -> 1160
~ _$sSo27MPMusicPlayerPlayParametersC05MediaB0E6encode2toys7Encoder_p_tKF : 1020 -> 1156
~ _OUTLINED_FUNCTION_1 : 20 -> 28
~ _OUTLINED_FUNCTION_3 : 12 -> 20
~ _OUTLINED_FUNCTION_4 : 32 -> 12
~ _OUTLINED_FUNCTION_5 : 16 -> 32
~ _OUTLINED_FUNCTION_7 : 28 -> 16
~ _OUTLINED_FUNCTION_11 : 20 -> 32
- _OUTLINED_FUNCTION_12
```
