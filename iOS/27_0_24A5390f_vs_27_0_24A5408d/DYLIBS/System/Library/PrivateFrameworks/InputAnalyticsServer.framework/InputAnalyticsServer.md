## InputAnalyticsServer

> `/System/Library/PrivateFrameworks/InputAnalyticsServer.framework/InputAnalyticsServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7b708` | `0x7e28c` | **`+0x2b84`** |
| `__AUTH_CONST.__cfstring` | `0x6780` | `0x6aa0` | **`+0x320`** |
| `__TEXT.__oslogstring` | `0x7840` | `0x7b50` | **`+0x310`** |
| `__TEXT.__cstring` | `0x6282` | `0x64e2` | **`+0x260`** |
| `__TEXT.__objc_methlist` | `0x609c` | `0x62a4` | **`+0x208`** |
| `__DATA_CONST.__objc_selrefs` | `0x30c0` | `0x31c8` | **`+0x108`** |
| `__AUTH_CONST.__objc_intobj` | `0x17b8` | `0x1878` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x1778` | `0x1818` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x14d8` | `0x1558` | **`+0x80`** |
| `__AUTH_CONST.__objc_const` | `0xa528` | `0xa5a8` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x1740` | `0x17b8` | **`+0x78`** |
| `__TEXT.__const` | `0xa50` | `0xab0` | **`+0x60`** |
| `__AUTH.__objc_data` | `0xad8` | `0xa88` | **`-0x50`** |
| `__DATA_CONST.__got` | `0x18f0` | `0x1930` | **`+0x40`** |
| `__DATA.__bss` | `0x740` | `0x770` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0xd50` | `0xd28` | **`-0x28`** |
| `__DATA.__objc_ivar` | `0x738` | `0x74c` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0xbf0` | `0xc00` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x3d0` | `0x3c8` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x210` | `0x218` | **`+0x8`** |

### Other Changes

```diff

-147.0.0.0.0
+153.0.0.0.0

+  - /System/Library/PrivateFrameworks/BackBoardServices.framework/BackBoardServices

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 2792
-  Symbols:   974
-  CStrings:  1463
+  Functions: 2848
+  Symbols:   982
+  CStrings:  1500
Symbols:
+ _IADataStoreObjectTypeCounter
+ _IAPayloadKeyImageGenerationAssetID
+ _IAPayloadKeyImageGenerationUnredactedStyle
+ _IAPayloadKeyPencilSystemDisplayIdentifier
+ _IASignalImageGenerationPCCImageGenerated
+ _IASignalImageGenerationPIRImageGenerated
+ _MGCopyAnswerWithError
+ _OBJC_CLASS_$_BKSDisplayService
CStrings:
+ "Always-on Proofreading"
+ "Assistant Enabled"
+ "Dropping AOP event: missing/unparseable GrammarUUID %{private}@"
+ "EventCount"
+ "Failed to load AOP daily event counter: %{private}@"
+ "Failed to reset AOP daily event counter: %{private}@"
+ "IASImageGenerationImageInteractionAnalyzer.m"
+ "MobileGestalt read failed for DeviceSupportsApplePencil (error=%{private}d, answer=%{private}@) - falling back to device model prefix check"
+ "PersonalizedSmartReplies"
+ "Proofread"
+ "Replaced nil bundleId with com.apple.nilBundleId."
+ "Rewrite"
+ "Rolled dedup caches and reset daily event count in periodic24HourEvents"
+ "ShownPersonalizeSmartRepliesAlert"
+ "Siri"
+ "Smart Reply"
+ "Writing Tools"
+ "[%{private}@] Biome ImageInteraction: %{sensitive}@"
+ "[%{private}@] Dropping ImageInteraction with no assetIdentifier for signal %{private}@"
+ "campoAvailability"
+ "com.apple.assistant.support"
+ "com.apple.inputAnalytics.IASAOPAnalyzer"
+ "com.apple.inputAnalytics.server.IASImageGenerationImageInteractionAnalyzer"
+ "com.apple.nilBundleId"
+ "content_dismissed"
+ "content_generated"
+ "custom_measure_type"
+ "custom_measure_value"
+ "group.com.apple.mail"
+ "isEnhancedSiriAvailable called"
+ "periodic24HourEvents: Campo available:%{private}lu"
+ "periodic24HourEvents: mail defaults initialized"
+ "periodic24HourEventsWithModelAvailability: grabbing siri settings"
+ "periodic24HourEventsWithModelAvailability: siri settings grabbed"
+ "personalizedSmartRepliesAlertShown"
+ "personalizedSmartRepliesEnabled"
+ "siriSettings"
+ "unredactedStyle"
+ "yhHcB0iH0d1XzPO/CFd3ow"
- "&"
- "Rolled dedup caches in periodic24HourEvents"
```
