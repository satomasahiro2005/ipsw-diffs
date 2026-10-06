## SuggestedImage

> `/System/Library/PrivateFrameworks/SuggestedImage.framework/SuggestedImage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfbfbc` | `0x103db8` | **`+0x7dfc`** |
| `__TEXT.__oslogstring` | `0x22f8` | `0x2788` | **`+0x490`** |
| `__AUTH_CONST.__const` | `0x4c80` | `0x5090` | **`+0x410`** |
| `__TEXT.__eh_frame` | `0xc520` | `0xc850` | **`+0x330`** |
| `__TEXT.__const` | `0x7b7d` | `0x7e0d` | **`+0x290`** |
| `__DATA.__bss` | `0x6c40` | `0x6ec0` | **`+0x280`** |
| `__TEXT.__unwind_info` | `0x43d0` | `0x4500` | **`+0x130`** |
| `__TEXT.__swift5_capture` | `0x59c` | `0x694` | **`+0xf8`** |
| `__TEXT.__swift5_fieldmd` | `0x1c34` | `0x1d20` | **`+0xec`** |
| `__TEXT.__swift5_reflstr` | `0x1837` | `0x1917` | **`+0xe0`** |
| `__TEXT.__constg_swiftt` | `0x1c90` | `0x1d54` | **`+0xc4`** |
| `__TEXT.__swift5_typeref` | `0x16aa` | `0x1748` | **`+0x9e`** |
| `__DATA.__data` | `0xd28` | `0xda8` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x1368` | `0x13d8` | **`+0x70`** |
| `__TEXT.__cstring` | `0x5b26` | `0x5b76` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x4c8` | `0x510` | **`+0x48`** |
| `__DATA_DIRTY.__data` | `0x1aa8` | `0x1ad8` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0x44c` | `0x460` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x208` | `0x21c` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0xb34` | `0xb44` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x39c` | `0x3ac` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x678` | `0x688` | **`+0x10`** |

### Other Changes

```diff

-198.2.7.100.0
+198.2.11.0.0

-  Functions: 3901
-  Symbols:   1703
-  CStrings:  472
+  Functions: 3997
+  Symbols:   1722
+  CStrings:  486
Symbols:
+ ___swift_closure_destructor.281Tm
+ ___swift_memcpy22_8
+ _associated conformance 14SuggestedImage15FedstatsFoldMapV10CodingKeys33_C65FEC2E73F120A18EFD64312048A3B5LLOSHAASQ
+ _associated conformance 14SuggestedImage15FedstatsFoldMapV10CodingKeys33_C65FEC2E73F120A18EFD64312048A3B5LLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 14SuggestedImage15FedstatsFoldMapV10CodingKeys33_C65FEC2E73F120A18EFD64312048A3B5LLOs0F3KeyAAs28CustomDebugStringConvertible
+ _swift_release_x11
+ _symbolic ShySSGz_Xx
+ _symbolic Si5found_Si8expectedt
+ _symbolic _____ 14SuggestedImage15FedstatsFoldMapV
+ _symbolic _____ 14SuggestedImage15FedstatsFoldMapV10CodingKeys33_C65FEC2E73F120A18EFD64312048A3B5LLO
+ _symbolic _____ 14SuggestedImage21FedstatsPhraseFoldingO
+ _symbolic _____ 14SuggestedImage21SourceAssetVisibilityV
+ _symbolic _____ 14SuggestedImage22PhotosDeleteWakePolicyO
+ _symbolic _____Sg 10Foundation6LocaleV
+ _symbolic _____yS2SG s18_DictionaryStorageC
+ _symbolic _____ySSSaySSGG s18_DictionaryStorageC
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14SuggestedImage15FedstatsFoldMapV10CodingKeys33_C65FEC2E73F120A18EFD64312048A3B5LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14SuggestedImage15FedstatsFoldMapV10CodingKeys33_C65FEC2E73F120A18EFD64312048A3B5LLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 14SuggestedImage21SourceAssetVisibilityV
+ _type_layout_string 14SuggestedImage15FedstatsFoldMapV
+ _type_layout_string 14SuggestedImage21SourceAssetVisibilityV
- ___swift_closure_destructor.276Tm
- _associated conformance 14SuggestedImage18FedstatsTrieLoaderV5ErrorOSHAASQ
CStrings:
+ " representsBurst="
+ "Conditioning asset round-trip mismatch [%{public}s]: requested %{private}s, Photos returned %{private}s."
+ "Could not resolve source-asset visibility for %{public}s: %@"
+ "Deleted %{public}ld wallpaper poster request(s); refreshing poster descriptors."
+ "Deleted %{public}s suggestion [%{public}s]: source asset absent from photo library."
+ "Donate %{public}s [%{public}s] %{public}s suggestion %{private}s asset %{private}s."
+ "Failed to delete %{public}s suggestion [%{public}s]: %@"
+ "Finished writing fold map for case-normalized identifier: %s; entries: %ld"
+ "Generate [%{public}s] matched=%{public}ld roundTrip=%{bool,public}d hidden=%{bool,public}d trashed=%{bool,public}d burst=%{bool,public}d."
+ "No-op delete for %{public}s suggestion [%{public}s]: nothing found at the request's journal path. Identifier %{private}s."
+ "PhotosDeleteWake.lastPruneAt"
+ "PhotosDeleteWake.needsDeferredPrune"
+ "Prune %{public}s [%{public}s] %{public}s identifier %{private}s."
+ "Prune %{public}s: %{public}ld request(s), %{public}ld carrying a source identifier."
+ "Running a prune deferred by a previously suppressed Photos.Delete wake."
+ "Suppressing a Photos.Delete wake %{public}lds into a %{public}lds window; deferring to the next wake."
+ "Wrote fold map for %{public}s: %ld entries"
+ "_loadPhotoAsConditioningImage(localIdentifier:targetSize:traceTag:)"
- "Deleting %s suggestion '%s': asset deleted from photo library"
- "Failed to delete %s suggestion '%s': %@"
- "_loadPhotoAsConditioningImage(localIdentifier:targetSize:)"
- "commonPhrases pre-generation is disabled"
```
