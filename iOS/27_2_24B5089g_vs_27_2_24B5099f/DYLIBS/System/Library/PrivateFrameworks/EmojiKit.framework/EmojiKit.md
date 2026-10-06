## EmojiKit

> `/System/Library/PrivateFrameworks/EmojiKit.framework/EmojiKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc9c8` | `0xcbcc` | **`+0x204`** |
| `__AUTH_CONST.__objc_const` | `0x2068` | `0x20f8` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0x2a0` | `0x320` | **`+0x80`** |
| `__TEXT.__cstring` | `0x427` | `0x488` | **`+0x61`** |
| `__AUTH.__objc_data` | `0x320` | `0x370` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x10ac` | `0x10ec` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x1a8` | `0x1e0` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0xdc8` | `0xdf8` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0xa0` | `0xc0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x520` | `0x540` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x468` | `0x478` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x150` | `0x15c` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x80` | `0x88` | **`+0x8`** |

### Other Changes

```diff

-43.0.0.0.0
+44.0.0.0.0

+  - /System/Library/PrivateFrameworks/InputAnalytics.framework/InputAnalytics

-  Functions: 348
-  Symbols:   826
-  CStrings:  76
+  Functions: 354
+  Symbols:   845
+  CStrings:  80
Symbols:
+ +[EMKInputAnalyticsHelper _reportUsageType:]
+ +[EMKInputAnalyticsHelper reportAccepted]
+ +[EMKInputAnalyticsHelper reportHighlightShown]
+ +[EMKInputAnalyticsHelper reportSuggestionShown]
+ -[_EMKTextKit2Controller _reportHighlightsShown]
+ GCC_except_table38
+ GCC_except_table45
+ _IAChannelGenmoji
+ _IAPayloadKeyGenmojiImageType
+ _IAPayloadKeyGenmojiUsageSource
+ _IAPayloadKeyGenmojiUsageType
+ _IAPayloadValueGenmojiImageTypeEmoji
+ _IASignalGenmojiUsage
+ _OBJC_CLASS_$_EMKInputAnalyticsHelper
+ _OBJC_CLASS_$_IASignalAnalytics
+ _OBJC_METACLASS_$_EMKInputAnalyticsHelper
+ __OBJC_$_CLASS_METHODS_EMKInputAnalyticsHelper
+ __OBJC_CLASS_RO_$_EMKInputAnalyticsHelper
+ __OBJC_METACLASS_RO_$_EMKInputAnalyticsHelper
+ ___48-[_EMKTextKit2Controller _reportHighlightsShown]_block_invoke
+ ___block_descriptor_32_e42_B32?0"EMKEmojiTokenList"8{_NSRange=QQ}16l
- GCC_except_table36
- GCC_except_table43
CStrings:
+ "FindAndReplace"
+ "FindAndReplaceAccepted"
+ "FindAndReplaceHighlightShown"
+ "FindAndReplaceSuggestionShown"
```
