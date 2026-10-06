## PromotedContentUI

> `/System/Library/PrivateFrameworks/PromotedContentUI.framework/PromotedContentUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x184254` | `0x191d0c` | **`+0xdab8`** |
| `__AUTH_CONST.__objc_const` | `0x9fe0` | `0xa9f0` | **`+0xa10`** |
| `__AUTH.__objc_data` | `0x2a18` | `0x33f8` | **`+0x9e0`** |
| `__AUTH_CONST.__const` | `0xac50` | `0xb398` | **`+0x748`** |
| `__TEXT.__swift5_reflstr` | `0x5ce8` | `0x6428` | **`+0x740`** |
| `__TEXT.__const` | `0xe304` | `0xe834` | **`+0x530`** |
| `__TEXT.__constg_swiftt` | `0x7404` | `0x791c` | **`+0x518`** |
| `__TEXT.__swift5_fieldmd` | `0x53e4` | `0x5858` | **`+0x474`** |
| `__AUTH.__data` | `0x1fd0` | `0x2388` | **`+0x3b8`** |
| `__DATA.__data` | `0x32e8` | `0x3650` | **`+0x368`** |
| `__TEXT.__swift5_typeref` | `0x6bc2` | `0x6ebc` | **`+0x2fa`** |
| `__DATA_DIRTY.__objc_data` | `0x3e88` | `0x3c18` | **`-0x270`** |
| `__TEXT.__oslogstring` | `0x5834` | `0x5a94` | **`+0x260`** |
| `__TEXT.__unwind_info` | `0x4990` | `0x4b70` | **`+0x1e0`** |
| `__AUTH_CONST.__auth_got` | `0x3390` | `0x3530` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x7784` | `0x7901` | **`+0x17d`** |
| `__TEXT.__swift5_capture` | `0x18c4` | `0x1a0c` | **`+0x148`** |
| `__DATA.__bss` | `0xa780` | `0xa880` | **`+0x100`** |
| `__DATA_CONST.__got` | `0x15f8` | `0x16b8` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x1fec` | `0x20a4` | **`+0xb8`** |
| `__DATA.__common` | `0x200` | `0x258` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x1cf8` | `0x1d48` | **`+0x50`** |
| `__TEXT.__swift5_proto` | `0x7d8` | `0x818` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x608c` | `0x60c0` | **`+0x34`** |
| `__DATA_CONST.__const` | `0x408` | `0x438` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x5b68` | `0x5b98` | **`+0x30`** |
| `__TEXT.__swift5_types` | `0x500` | `0x52c` | **`+0x2c`** |
| `__DATA_CONST.__objc_classlist` | `0x3a0` | `0x3c8` | **`+0x28`** |
| `__TEXT.__swift5_protos` | `0x10c` | `0x128` | **`+0x1c`** |
| `__TEXT.__swift5_builtin` | `0x208` | `0x21c` | **`+0x14`** |
| `__DATA_DIRTY.__common` | `0x168` | `0x158` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x354` | `0x360` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x1c8` | `0x1cc` | **`+0x4`** |

### Other Changes

```diff

-557.1.16.0.0
+557.1.21.0.0

-  Functions: 6321
-  Symbols:   493
-  CStrings:  955
+  Functions: 6519
+  Symbols:   502
+  CStrings:  970
Symbols:
+ _NSKernAttributeName
+ _NSParagraphStyleAttributeName
+ _OBJC_CLASS_$_NSAttributedString
+ _OBJC_CLASS_$_NSMutableParagraphStyle
+ _OBJC_CLASS_$_NSParagraphStyle
+ _OBJC_CLASS_$_UIFontMetrics
+ _OBJC_CLASS_$_UILayoutGuide
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
CStrings:
+ "AdCardViewConfiguration: audio content type is not supported."
+ "AdCardViewConfiguration: encountered unknown content type %s."
+ "Ag"
+ "AgeNoisingDistributionDiagnostics"
+ "AgeNoisingStatusDiagnostics"
+ "Context %s couldn't get the size of the modal ad."
+ "Failed to create a `ModalAdViewConfiguration` from a `PromotedContent`. The `AdCardViewConfiguration` is not an `AdCardImageViewConfiguration` or an `AdCardVideoViewConfiguration`."
+ "Failed to create a `ModalAdViewConfiguration` from a `PromotedContent`. The `AdCardViewConfiguration` is not valid."
+ "Failed to create a `ModalAdViewConfiguration` from a `PromotedContent`. The `bestRepresentation` is not a `ClientLayoutRepresentation`."
+ "Failed to create a `ModalAdViewConfiguration` from a `PromotedContent`. The `sponsoredByAssetProxyURL` is nil."
+ "Failed to make AdCardViewConfiguration: bestRepresentation is not a ClientLayoutRepresentation for promoted content %s."
+ "Failed to make AdCardViewConfiguration: element has no asset or content type."
+ "Failed to make AdCardViewConfiguration: representation contains no elements."
+ "Failure creating a promoted modal ad view."
+ "PC %@: Unable to push layoutChange. No webProcessProxy found."
+ "PromotedContentUI.ImageModalAdView"
+ "PromotedContentUI.VideoModalAdView"
+ "PromotedContentUI/ImageModalAdView.swift"
+ "PromotedContentUI/VideoModalAdView.swift"
+ "Sending CoreAnalytics event '%s' with payload: %s"
+ "Unable to determine action button placement using trait collection: %ld."
+ "appstore_storefront"
+ "com.apple.adplatforms.agenoising.buckets.noised"
+ "com.apple.adplatforms.agenoising.population"
+ "middleAdolescent"
+ "noNoiseInvalidAge"
- "Advertisement. %@"
- "Audio content type is not supported by AdCardViewConfiguration.MediaType."
- "Encountered unknown ClientLayoutAssetInfo.ContentType %s. Returning nil."
- "Failed to initialize AdCardViewConfiguration: bestRepresentation is not a ClientLayoutRepresentation for promoted content %s."
- "Failed to initialize AdCardViewConfiguration: element has no asset or content type."
- "Failed to initialize AdCardViewConfiguration: representation contains no elements."
- "Failed to initialize AdCardViewConfiguration: unsupported content type."
- "PromotedContentUI.ModalAdView"
- "PromotedContentUI/ModalAdView.swift"
- "Scroll view is not target scroll view or adSize not set."
- "Unable to determine collection view inset using trait collection: %ld."
```
