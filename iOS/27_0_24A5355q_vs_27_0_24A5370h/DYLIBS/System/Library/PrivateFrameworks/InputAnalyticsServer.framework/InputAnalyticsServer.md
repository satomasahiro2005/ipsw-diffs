## InputAnalyticsServer

> `/System/Library/PrivateFrameworks/InputAnalyticsServer.framework/InputAnalyticsServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72bf4` | `0x74ab8` | **`+0x1ec4`** |
| `__AUTH_CONST.__objc_const` | `0x9bb8` | `0x9de8` | **`+0x230`** |
| `__TEXT.__objc_methlist` | `0x5a4c` | `0x5c54` | **`+0x208`** |
| `__AUTH_CONST.__cfstring` | `0x5e20` | `0x5fc0` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x5917` | `0x5ab7` | **`+0x1a0`** |
| `__AUTH_CONST.__objc_intobj` | `0x12f0` | `0x1458` | **`+0x168`** |
| `__AUTH_CONST.__const` | `0x11c8` | `0x12c8` | **`+0x100`** |
| `__DATA_CONST.__objc_selrefs` | `0x2e38` | `0x2f20` | **`+0xe8`** |
| `__DATA_CONST.__got` | `0x1568` | `0x1630` | **`+0xc8`** |
| `__DATA_CONST.__const` | `0x13f8` | `0x14a8` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0x15b8` | `0x1660` | **`+0xa8`** |
| `__AUTH.__objc_data` | `0x970` | `0xa10` | **`+0xa0`** |
| `__DATA.__bss` | `0x850` | `0x8d0` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x7313` | `0x7373` | **`+0x60`** |
| `__DATA.__objc_ivar` | `0x708` | `0x71c` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0xb68` | `0xb78` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x370` | `0x380` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x200` | `0x210` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x28d` | `0x297` | **`+0xa`** |
| `__DATA.__data` | `0x580` | `0x588` | **`+0x8`** |
| `__TEXT.__const` | `0xa10` | `0xa18` | **`+0x8`** |

### Other Changes

```diff

-139.0.0.0.0
+141.0.0.0.0

+  - /System/Library/Frameworks/UIKit.framework/UIKit

+  - /System/Library/PrivateFrameworks/GenerativePartnerService.framework/GenerativePartnerService

+  - /usr/lib/swift/libswiftSpatial.dylib

-  Functions: 2604
-  Symbols:   892
-  CStrings:  1352
+  Functions: 2669
+  Symbols:   913
+  CStrings:  1369
Symbols:
+ _IAPayloadKeyImageGenerationImageHeight
+ _IAPayloadKeyImageGenerationImageWidth
+ _IAPayloadKeyWritingToolsAlwaysOnBundleID
+ _IAPayloadKeyWritingToolsAlwaysOnGrammarUUID
+ _IAPayloadKeyWritingToolsAlwaysOnInputTokenCount
+ _IAPayloadKeyWritingToolsAlwaysOnModelInfo
+ _IAPayloadKeyWritingToolsAlwaysOnSuggestionCategory
+ _IAPayloadKeyWritingToolsAlwaysOnSuggestionCount
+ _IASignalImageGenerationCreateImageIntentInvoked
+ _IASignalImageGenerationGenerateImageIntentInvoked
+ _IASignalImageGenerationPreviewGenerationFailed
+ _IASignalWritingToolsAlwaysOnProofreadingAcceptAllSuggestionsEngaged
+ _IASignalWritingToolsAlwaysOnProofreadingIgnoreAllSuggestionsEngaged
+ _IASignalWritingToolsAlwaysOnProofreadingPanelDismissed
+ _IASignalWritingToolsAlwaysOnProofreadingPanelIndexChanged
+ _IASignalWritingToolsAlwaysOnProofreadingPanelShown
+ _IASignalWritingToolsAlwaysOnProofreadingSuggestionAccepted
+ _IASignalWritingToolsAlwaysOnProofreadingSuggestionAcceptedInPanel
+ _IASignalWritingToolsAlwaysOnProofreadingSuggestionBubbleShown
+ _IASignalWritingToolsAlwaysOnProofreadingSuggestionIgnored
+ _IASignalWritingToolsAlwaysOnProofreadingSuggestionShown
+ _IASignalWritingToolsAlwaysOnProofreadingTemporarilyPauseSuggestionsEngaged
+ __swift_FORCE_LOAD_$_swiftSpatial
+ __swift_FORCE_LOAD_$_swiftUIKit
- _IAPayloadKeyImageGenerationResolution
- _OBJC_CLASS_$_GATSettings
- _swift_release_x27
CStrings:
+ "%ld x %ld"
+ "Could not resolve bundleId for signal %{private}@"
+ "IAAlwaysOnProofreading"
+ "IASAlwaysOnProofreadingAnalyzer.m"
+ "IASSignalAnalyticsReplayTestsEventNameKey"
+ "Rolled dedup caches in periodic24HourEvents"
+ "acceptAllEngaged"
+ "com.apple.inputAnalytics.alwaysOnProofread"
+ "com.apple.inputAnalytics.aopSuggestionCategory"
+ "com.apple.inputAnalytics.server.IASAlwaysOnProofreadingAnalyzer"
+ "ignoreSuggestions"
+ "imageDimensions"
+ "mainPanelEngaged"
+ "numSuggestionViewed"
+ "numSuggestionsAccepted"
+ "numSuggestionsOffered"
+ "suggestionCategory"
```
