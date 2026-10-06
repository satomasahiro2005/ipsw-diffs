## TextInputUI

> `/System/Library/PrivateFrameworks/TextInputUI.framework/TextInputUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x140a10` | `0x14bef4` | **`+0xb4e4`** |
| `__DATA.__bss` | `0x35d8` | `0x3e58` | **`+0x880`** |
| `__TEXT.__eh_frame` | `0x1bfc` | `0x2254` | **`+0x658`** |
| `__TEXT.__const` | `0x3c9e` | `0x41fe` | **`+0x560`** |
| `__AUTH.__data` | `0xb80` | `0x1038` | **`+0x4b8`** |
| `__AUTH_CONST.__const` | `0x3028` | `0x3398` | **`+0x370`** |
| `__AUTH_CONST.__objc_const` | `0x1a608` | `0x1a910` | **`+0x308`** |
| `__TEXT.__unwind_info` | `0x4480` | `0x4710` | **`+0x290`** |
| `__TEXT.__constg_swiftt` | `0x1868` | `0x1acc` | **`+0x264`** |
| `__TEXT.__swift5_fieldmd` | `0xe38` | `0xfe4` | **`+0x1ac`** |
| `__DATA.__data` | `0x2d28` | `0x2e68` | **`+0x140`** |
| `__TEXT.__swift5_typeref` | `0x1dee` | `0x1f0a` | **`+0x11c`** |
| `__TEXT.__swift5_capture` | `0x624` | `0x6e0` | **`+0xbc`** |
| `__TEXT.__swift_as_cont` | `0x154` | `0x200` | **`+0xac`** |
| `__AUTH_CONST.__auth_got` | `0x1da8` | `0x1e28` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x107cc` | `0x1083c` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0xd95` | `0xe05` | **`+0x70`** |
| `__DATA_CONST.__got` | `0x1628` | `0x1680` | **`+0x58`** |
| `__DATA_DIRTY.__objc_data` | `0x20f8` | `0x20a0` | **`-0x58`** |
| `__TEXT.__swift5_proto` | `0x17c` | `0x1c0` | **`+0x44`** |
| `__DATA_CONST.__objc_selrefs` | `0xa990` | `0xa9c8` | **`+0x38`** |
| `__TEXT.__swift5_assocty` | `0x370` | `0x3a0` | **`+0x30`** |
| `__TEXT.__swift5_types` | `0x144` | `0x170` | **`+0x2c`** |
| `__TEXT.__oslogstring` | `0x6533` | `0x6558` | **`+0x25`** |
| `__AUTH_CONST.__cfstring` | `0xec40` | `0xec60` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x730` | `0x750` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x168` | `0x17c` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x74` | `0x88` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x78` | `0x8c` | **`+0x14`** |
| `__TEXT.__cstring` | `0xd977` | `0xd988` | **`+0x11`** |
| `__AUTH.__objc_data` | `0x3b58` | `0x3b68` | **`+0x10`** |
| `__DATA.__common` | `0x288` | `0x290` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1258` | `0x1254` | **`-0x4`** |

### Other Changes

```diff

-9127.1.7.2.101
+9127.1.12.0.0

-  Functions: 7073
-  Symbols:   11031
-  CStrings:  2753
+  Functions: 7248
+  Symbols:   11089
+  CStrings:  2756
Symbols:
+ +[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]
+ +[TUISmartReplyGenerator isChinaPolicyEnabled]
+ -[TUIKeyboardPathEffectView _displayLinkFired:]
+ _NSFileModificationDate
+ _NSFileSize
+ _NSRunLoopCommonModes
+ _OBJC_CLASS_$_NSRunLoop
+ _OBJC_CLASS_$_TCFedstatsTrie
+ __DATA__TtC11TextInputUI22FedstatsPhraseResolver
+ __DATA__TtC11TextInputUI25GenmojiAssetRequestLedger
+ __DATA__TtC11TextInputUIP33_221B2D3BC24C1B5ECA018BD75C9CBA3021_GenmojiResourceStore
+ __DATA__TtC11TextInputUIP33_221B2D3BC24C1B5ECA018BD75C9CBA3025_GenmojiGenerationTracker
+ __IVARS__TtC11TextInputUI22FedstatsPhraseResolver
+ __IVARS__TtC11TextInputUI25GenmojiAssetRequestLedger
+ __IVARS__TtC11TextInputUIP33_221B2D3BC24C1B5ECA018BD75C9CBA3021_GenmojiResourceStore
+ __IVARS__TtC11TextInputUIP33_221B2D3BC24C1B5ECA018BD75C9CBA3025_GenmojiGenerationTracker
+ __METACLASS_DATA__TtC11TextInputUI22FedstatsPhraseResolver
+ __METACLASS_DATA__TtC11TextInputUI25GenmojiAssetRequestLedger
+ __METACLASS_DATA__TtC11TextInputUIP33_221B2D3BC24C1B5ECA018BD75C9CBA3021_GenmojiResourceStore
+ __METACLASS_DATA__TtC11TextInputUIP33_221B2D3BC24C1B5ECA018BD75C9CBA3025_GenmojiGenerationTracker
+ __OBJC_$_CLASS_METHODS_TUIInputSession
+ ___92+[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]_block_invoke
+ ___92+[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]_block_invoke_2
+ ___swift_closure_destructor.36Tm
+ _associated conformance 11TextInputUI11TempFoldMap33_221B2D3BC24C1B5ECA018BD75C9CBA30LLV10CodingKeysOSHAASQ
+ _associated conformance 11TextInputUI11TempFoldMap33_221B2D3BC24C1B5ECA018BD75C9CBA30LLV10CodingKeysOs0P3KeyAAs23CustomStringConvertible
+ _associated conformance 11TextInputUI11TempFoldMap33_221B2D3BC24C1B5ECA018BD75C9CBA30LLV10CodingKeysOs0P3KeyAAs28CustomDebugStringConvertible
+ _associated conformance So18NSFileAttributeKeyaSHSCSQ
+ _associated conformance So18NSFileAttributeKeyas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So18NSFileAttributeKeyas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _swift_defaultActor_deallocate
+ _swift_defaultActor_destroy
+ _swift_defaultActor_initialize
+ _symbolic BD
+ _symbolic SDyS2SG
+ _symbolic SDySS_____G 11TextInputUI22FedstatsPhraseResolverC5Entry33_221B2D3BC24C1B5ECA018BD75C9CBA30LLV
+ _symbolic SaySSGz_Xx
+ _symbolic Say_____G 11TextInputUI25GenmojiAssetRequestLedgerC6_Entry33_6709F06DB16606D4601383BD19E636D5LLV
+ _symbolic Say_____G 14SuggestedImage12AssetRequestV
+ _symbolic ScTyyt_____G s5NeverO
+ _symbolic Siz_Xx
+ _symbolic So14TCFedstatsTrieC
+ _symbolic _____ 10Foundation4DateV
+ _symbolic _____ 11TextInputUI11TempFoldMap33_221B2D3BC24C1B5ECA018BD75C9CBA30LLV
+ _symbolic _____ 11TextInputUI11TempFoldMap33_221B2D3BC24C1B5ECA018BD75C9CBA30LLV10CodingKeysO
+ _symbolic _____ 11TextInputUI21_GenmojiResourceStore33_221B2D3BC24C1B5ECA018BD75C9CBA30LLC
+ _symbolic _____ 11TextInputUI22FedstatsPhraseResolverC
+ _symbolic _____ 11TextInputUI22FedstatsPhraseResolverC12FileIdentity33_221B2D3BC24C1B5ECA018BD75C9CBA30LLV
+ _symbolic _____ 11TextInputUI22FedstatsPhraseResolverC5Entry33_221B2D3BC24C1B5ECA018BD75C9CBA30LLV
+ _symbolic _____ 11TextInputUI22FedstatsPhraseResolverC5MatchV
+ _symbolic _____ 11TextInputUI25GenmojiAssetRequestLedgerC
+ _symbolic _____ 11TextInputUI25GenmojiAssetRequestLedgerC6_Entry33_6709F06DB16606D4601383BD19E636D5LLV
+ _symbolic _____ 11TextInputUI25_GenmojiGenerationTracker33_221B2D3BC24C1B5ECA018BD75C9CBA30LLC
+ _symbolic _____ 14SuggestedImage0aB8ProviderC
+ _symbolic _____ 14SuggestedImage12AssetRequestV
+ _symbolic _____ So18NSFileAttributeKeya
+ _symbolic _____Sg 11TextInputUI22FedstatsPhraseResolverC12FileIdentity33_221B2D3BC24C1B5ECA018BD75C9CBA30LLV
+ _symbolic _____Sg 11TextInputUI22FedstatsPhraseResolverC5Entry33_221B2D3BC24C1B5ECA018BD75C9CBA30LLV
+ _symbolic _____Sg_ABt 11TextInputUI22FedstatsPhraseResolverC12FileIdentity33_221B2D3BC24C1B5ECA018BD75C9CBA30LLV
+ _symbolic _____XDXMT 11TextInputUI25GenmojiAssetRequestLedgerC
+ _symbolic _____ySSG s10ArraySliceV
+ _symbolic _____ySS_____G s18_DictionaryStorageC 11TextInputUI22FedstatsPhraseResolverC5Entry33_221B2D3BC24C1B5ECA018BD75C9CBA30LLV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 11TextInputUI11TempFoldMap33_221B2D3BC24C1B5ECA018BD75C9CBA30LLV10CodingKeysO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 11TextInputUI22FedstatsPhraseResolverC5MatchV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 11TextInputUI25GenmojiAssetRequestLedgerC6_Entry33_6709F06DB16606D4601383BD19E636D5LLV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 14SuggestedImage12AssetRequestV
+ _type_layout_string 11TextInputUI11TempFoldMap33_221B2D3BC24C1B5ECA018BD75C9CBA30LLV
+ _type_layout_string 11TextInputUI22FedstatsPhraseResolverC5MatchV
+ _type_layout_string So18NSFileAttributeKeya
+ _type_layout_string So6CGSizeV
- -[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]
- _OBJC_CLASS_$__UIKBFeedbackGeneratorPartner
- _OBJC_IVAR_$_TUIEmojiSearchInputViewController._feedbackGenerator
- ___92-[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]_block_invoke
- ___92-[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]_block_invoke_2
- ___swift_closure_destructor.35Tm
- _swift_task_isCancelledWithFlags
- _symbolic So14TCFedstatsTrieCSg
- _symbolic So28TIKeyboardCandidateResultSetC
- _symbolic So6NSLockC
- _type_layout_string So14IAPayloadValuea
- _type_layout_string So7CGPointV
CStrings:
+ "Armenian-Western"
+ "Failed to reap superseded asset request: %s"
+ "Reaping %{public}ld superseded asset request(s)"
+ "[%{public}s] Could not decode associated phrase asset in any known format"
+ "[%{public}s] Request endures, not tracking"
+ "[%{public}s] asset() returned nil for inserted phrase"
+ "[FedStats] '%s': derived fold map locally, %ld phrases, %ld multi-word, %ld entries"
+ "[FedStats] '%s': precomputed fold map, %ld entries"
+ "[FedStats] Fold map disagrees with local folding; deriving locally"
+ "[FedStats] No trie for locale '%s': %@"
+ "[FedStats] Skipping '%{private}s' — existing emoji covers it"
+ "\xf0A"
- "Autocorrection list contains candidates to be redacted.  Unsupported selector `redactedList`.  Sending empty autocorrection list instead."
- "Candidate result set contains candidates to be redacted.  Unsupported selector `redactedSet`.  Sending empty result set instead."
- "[%s] Could not decode associated phrase asset in any known format"
- "[%s] asset() returned nil for inserted phrase"
- "[FedStats] Loaded trie for locale '%s'"
- "[FedStats] Skipping '%s' — existing emoji covers it"
- "[FedStats] Trie not initialized"
- "[FedStats] Trie not initialized for response check"
- "\xf0Q"
```
