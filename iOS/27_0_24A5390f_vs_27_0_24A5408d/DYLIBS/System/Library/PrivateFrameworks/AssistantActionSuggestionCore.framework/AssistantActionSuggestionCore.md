## AssistantActionSuggestionCore

> `/System/Library/PrivateFrameworks/AssistantActionSuggestionCore.framework/AssistantActionSuggestionCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x232ad8` | `0x2349e4` | **`+0x1f0c`** |
| `__TEXT.__unwind_info` | `0x4ba0` | `0x50a8` | **`+0x508`** |
| `__TEXT.__eh_frame` | `0xf6c4` | `0xfa04` | **`+0x340`** |
| `__TEXT.__oslogstring` | `0x7656` | `0x785a` | **`+0x204`** |
| `__TEXT.__cstring` | `0x7646` | `0x7736` | **`+0xf0`** |
| `__TEXT.__const` | `0xbb68` | `0xbc48` | **`+0xe0`** |
| `__AUTH_CONST.__objc_const` | `0x52a0` | `0x5358` | **`+0xb8`** |
| `__AUTH.__data` | `0xc20` | `0xcc0` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x55e8` | `0x5670` | **`+0x88`** |
| `__TEXT.__swift5_capture` | `0x78c` | `0x7cc` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x2674` | `0x26b4` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x33f0` | `0x3428` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x2e50` | `0x2e84` | **`+0x34`** |
| `__TEXT.__constg_swiftt` | `0x2aa4` | `0x2ad0` | **`+0x2c`** |
| `__DATA_DIRTY.__data` | `0x4408` | `0x43e0` | **`-0x28`** |
| `__TEXT.__swift_as_cont` | `0xbe4` | `0xc0c` | **`+0x28`** |
| `__DATA.__data` | `0x2188` | `0x21a8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1988` | `0x19a8` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x3c7e` | `0x3c9a` | **`+0x1c`** |
| `__TEXT.__swift_as_ret` | `0x544` | `0x560` | **`+0x1c`** |
| `__DATA_CONST.__objc_classlist` | `0x208` | `0x210` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0x188` | `0x180` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x4f8` | `0x500` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x764` | `0x768` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x374` | `0x378` | **`+0x4`** |

### Other Changes

```diff

-667.0.0.0.0
+671.0.2.0.0

+  - /System/Library/PrivateFrameworks/TCC.framework/TCC

-  Functions: 4977
-  Symbols:   1995
-  CStrings:  1180
+  Functions: 5020
+  Symbols:   2004
+  CStrings:  1189
Symbols:
+ _OBJC_CLASS_$_NSArray
+ _TCCAccessCopyBundleIdentifiersDisabledForService
+ __DATA__TtC29AssistantActionSuggestionCore37WritingToolsEditableTextPromotionRule
+ __IVARS__TtC29AssistantActionSuggestionCore37WritingToolsEditableTextPromotionRule
+ __METACLASS_DATA__TtC29AssistantActionSuggestionCore37WritingToolsEditableTextPromotionRule
+ ___swift_closure_destructor.28Tm
+ _kTCCServiceSiriAccess
+ _symbolic _____ 29AssistantActionSuggestionCore37WritingToolsEditableTextPromotionRuleC
+ _symbolic _____ySSSaySSGG s18_DictionaryStorageC
+ _symbolic _____ySS_____G s18_DictionaryStorageC s5Int64V
- _symbolic SaySfGSg
CStrings:
+ "ATXConversationResurfacingSemanticSearchEnabledOverride"
+ "PRAGMA cache_size = -128"
+ "PRAGMA cache_size = -512"
+ "SuggestAppPolicy: TCCAccessCopyBundleIdentifiersDisabledForService returned nil for kTCCServiceSiriAccess"
+ "WTUIRequestedToolRewriteOpenEnded"
+ "[ConvResurfacing] Filtered out %{public}ld conversation(s) not found in AgentSessionStore, without a title, or older than the semantic max-age window"
+ "[ConvResurfacing] Filtering out conversation %{private}s: lastModifiedDate %{public}s is older than semantic max-age cutoff %{public}s"
+ "[ConvResurfacing] Semantic search disabled by configuration; recent-conversation path only"
+ "[ConvResurfacing][Eval] Filtered conversation (semantic too old): id=%{public}s, lastModifiedDate=%{public}s"
+ "conversationResurfacingSemanticMaxAgeSeconds"
+ "conversationResurfacingSemanticSearchEnabled"
- "WritingToolsComposeIntent"
- "[ConvResurfacing] Filtered out %{public}ld conversation(s) not found in AgentSessionStore or without a title"
```
