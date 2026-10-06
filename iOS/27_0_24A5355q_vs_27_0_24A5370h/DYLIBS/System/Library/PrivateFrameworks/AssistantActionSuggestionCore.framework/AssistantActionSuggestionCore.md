## AssistantActionSuggestionCore

> `/System/Library/PrivateFrameworks/AssistantActionSuggestionCore.framework/AssistantActionSuggestionCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x211530` | `0x2206a4` | **`+0xf174`** |
| `__TEXT.__eh_frame` | `0xe5e4` | `0xeefc` | **`+0x918`** |
| `__TEXT.__oslogstring` | `0x6996` | `0x6e36` | **`+0x4a0`** |
| `__DATA.__bss` | `0xcaf0` | `0xcf70` | **`+0x480`** |
| `__TEXT.__const` | `0xb4b8` | `0xb938` | **`+0x480`** |
| `__AUTH_CONST.__const` | `0x51b8` | `0x5420` | **`+0x268`** |
| `__TEXT.__unwind_info` | `0x46f8` | `0x4960` | **`+0x268`** |
| `__TEXT.__cstring` | `0x6ea6` | `0x7046` | **`+0x1a0`** |
| `__TEXT.__swift5_typeref` | `0x3966` | `0x3b00` | **`+0x19a`** |
| `__AUTH_CONST.__auth_got` | `0x3190` | `0x3310` | **`+0x180`** |
| `__DATA.__data` | `0x3068` | `0x31a8` | **`+0x140`** |
| `__TEXT.__swift5_reflstr` | `0x23a4` | `0x24c4` | **`+0x120`** |
| `__TEXT.__constg_swiftt` | `0x28c0` | `0x29c4` | **`+0x104`** |
| `__AUTH_CONST.__objc_const` | `0x4fe8` | `0x50d8` | **`+0xf0`** |
| `__TEXT.__swift5_fieldmd` | `0x2c24` | `0x2d08` | **`+0xe4`** |
| `__AUTH.__data` | `0x2b58` | `0x2c38` | **`+0xe0`** |
| `__DATA_CONST.__got` | `0x1868` | `0x1940` | **`+0xd8`** |
| `__DATA_CONST.__objc_selrefs` | `0x7a8` | `0x840` | **`+0x98`** |
| `__TEXT.__swift5_capture` | `0x6a4` | `0x730` | **`+0x8c`** |
| `__TEXT.__swift_as_cont` | `0xb28` | `0xba8` | **`+0x80`** |
| `__AUTH.__objc_data` | `0x588` | `0x5d8` | **`+0x50`** |
| `__TEXT.__swift_as_ret` | `0x4d0` | `0x51c` | **`+0x4c`** |
| `__TEXT.__swift_as_entry` | `0x4ac` | `0x4e8` | **`+0x3c`** |
| `__TEXT.__swift5_proto` | `0x734` | `0x758` | **`+0x24`** |
| `__DATA_DIRTY.__data` | `0x1020` | `0x1038` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x198` | `0x1b0` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x350` | `0x364` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x178` | `0x168` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1f8` | `0x200` | **`+0x8`** |

### Other Changes

```diff

-658.0.9.0.0
+661.0.7.0.0

+  - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics

+  - /System/Library/Frameworks/ImageIO.framework/ImageIO

+  - /System/Library/Frameworks/Photos.framework/Photos

-  Functions: 4686
-  Symbols:   1891
-  CStrings:  1096
+  Functions: 4834
+  Symbols:   1962
+  CStrings:  1119
Symbols:
+ _CGImageCreateWithImageInRect
+ _CGImageDestinationAddImage
+ _CGImageDestinationCreateWithData
+ _CGImageDestinationFinalize
+ _CGImageGetHeight
+ _CGImageGetWidth
+ _CGImageSourceCopyPropertiesAtIndex
+ _CGImageSourceCreateThumbnailAtIndex
+ _CGImageSourceCreateWithData
+ _CGImageSourceCreateWithURL
+ _OBJC_CLASS_$_NSDictionary
+ _OBJC_CLASS_$_NSLock
+ _OBJC_CLASS_$_NSMutableData
+ _OBJC_CLASS_$_PHAsset
+ _OBJC_CLASS_$_PHCloudIdentifier
+ _OBJC_CLASS_$_PHImageManager
+ _OBJC_CLASS_$_PHImageRequestOptions
+ _OBJC_CLASS_$_PHPhotoLibraryIdentifier
+ _OBJC_CLASS_$_PHPhotoLibraryManager
+ _OBJC_CLASS_$_PHPhotoLibraryOpenOptions
+ __DATA__TtC29AssistantActionSuggestionCoreP33_BA46B95663D59B300878D2A22E0A81AF17PhotoRequestState
+ __IVARS__TtC29AssistantActionSuggestionCoreP33_BA46B95663D59B300878D2A22E0A81AF17PhotoRequestState
+ __METACLASS_DATA__TtC29AssistantActionSuggestionCoreP33_BA46B95663D59B300878D2A22E0A81AF17PhotoRequestState
+ ___swift_closure_destructor.11Tm
+ _associated conformance 29AssistantActionSuggestionCore9AnalyticsV18ConversationSourceOSHAASQ
+ _associated conformance So11CFStringRefa14CoreFoundation9_CFObjectSCSH
+ _associated conformance So11CFStringRefaSHSCSQ
+ _free
+ _kCGImageDestinationLossyCompressionQuality
+ _kCGImagePropertyPixelHeight
+ _kCGImagePropertyPixelWidth
+ _kCGImageSourceCreateThumbnailFromImageAlways
+ _kCGImageSourceCreateThumbnailWithTransform
+ _kCGImageSourceThumbnailMaxPixelSize
+ _objc_retain_x28
+ _swift_coroFrameAlloc
+ _swift_release_x10
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
+ _symbolic SDySS_____G 10Foundation4DataV
+ _symbolic SS______Sgt 10Foundation4DataV
+ _symbolic SS______SgtIeAgHr_ 10Foundation4DataV
+ _symbolic ScCy_____Sg_____G So10CGImageRefa s5NeverO
+ _symbolic ScCy_____Sg_____GSg So10CGImageRefa s5NeverO
+ _symbolic Scgy_____Sg______pG 10Foundation4DataV s5ErrorP
+ _symbolic So6NSLockC
+ _symbolic _____ 15AgentSessionKit0aB0V
+ _symbolic _____ 15AgentSessionKit0aB8ArtifactV
+ _symbolic _____ 29AssistantActionSuggestionCore12TimeoutError33_BA46B95663D59B300878D2A22E0A81AFLLV
+ _symbolic _____ 29AssistantActionSuggestionCore17PhotoRequestState33_BA46B95663D59B300878D2A22E0A81AFLLC
+ _symbolic _____ 29AssistantActionSuggestionCore9AnalyticsV18ConversationSourceO
+ _symbolic _____ s8DurationV
+ _symbolic _____3key______5valuet 10Foundation4UUIDV 29AssistantActionSuggestionCore06RankedcD0V
+ _symbolic _____Sg 10Foundation4DataV
+ _symbolic _____Sg 15AgentSessionKit0aB0V
+ _symbolic _____Sg 15AgentSessionKit0aB15ArtifactContentO
+ _symbolic _____Sg 15AgentSessionKit0aB8ArtifactV
+ _symbolic _____Sg 29AssistantActionSuggestionCore9AnalyticsV18ConversationSourceO
+ _symbolic _____Sg 32AssistantActionSuggestionSupport11OrderSchemaV0E11InformationV
+ _symbolic _____Sg 32AssistantActionSuggestionSupport11OrderSchemaV0E11InformationV0E6StatusO
+ _symbolic _____Sg 32AssistantActionSuggestionSupport11OrderSchemaV18PaymentInformationV
+ _symbolic _____Sg 32AssistantActionSuggestionSupport11OrderSchemaV19ShippingInformationV
+ _symbolic _____Sg So10CGImageRefa
+ _symbolic _____Sg s5Int32V
+ _symbolic _____SgIeghHr_ 10Foundation4DataV
+ _symbolic ___________t 10Foundation4UUIDV 29AssistantActionSuggestionCore06RankedcD0V
+ _symbolic ______ypt So11CFStringRefa
+ _symbolic _____ySS_____G s18_DictionaryStorageC 10Foundation4DataV
+ _symbolic _____ySS______Sgt_G ScG8IteratorV 10Foundation4DataV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 15AgentSessionKit0dE0V
+ _symbolic _____y______yptG s23_ContiguousArrayStorageC So11CFStringRefa
+ _symbolic _____y_____ypG s18_DictionaryStorageC So11CFStringRefa
- ___swift_closure_destructor.10Tm
CStrings:
+ "ATXConversationResurfacingRecentWindowSecondsOverride"
+ "Deeplink URL not found in banner actions"
+ "Rejecting: %s as %s not found"
+ "Text embedding input truncated by MAD tokenizer (input was %{public}ld chars)"
+ "[ConvResurfacing] Resolved %{public}ld thumbnail(s) out of %{public}ld conversation(s) in %{public}ss"
+ "[ConvResurfacing] Thumbnail resolve kind=%{public}s bytes=%{public}ld session=%{private}s"
+ "[ConvResurfacing] Thumbnail resolve timed out or failed for session %{private}s: %{public}s"
+ "[ConvResurfacing][photo] PHAsset.fetchAssets empty session=%{private}s"
+ "[ConvResurfacing][photo] VI library unavailable; cannot resolve session=%{private}s"
+ "[ConvResurfacing][photo] failed to open VI library: %{public}s"
+ "[ConvResurfacing][photo] invalid archival cloud identifier session=%{private}s"
+ "[ConvResurfacing][photo] mapping failure session=%{private}s: %{public}s"
+ "[ConvResurfacing][photo] no mapping for cloud identifier session=%{private}s"
+ "agentMedia-no-id"
+ "bannerActions returned with %ld applicable identities"
+ "com.apple.VisualIntelligence"
+ "com.apple.siri.SiriGeo.SiriGeoAppIntentExtension.ThirdPartyStartNavigationIntent"
+ "conversationResurfacingRecent"
+ "conversationResurfacingSemantic"
+ "conversationResurfacingSemanticEntity"
+ "eval mode: fanning out across all banners for messageID"
+ "executedConversationSource"
+ "extractedOrderFoundInMailBannerActions returned: orderNumber=%s, trackingURL=%s, orderManagementURL=%s, supportURL=%s, supportPhoneNumber=%s, deeplinkURL=%s"
+ "requestCGImage(for:)"
- "ATXSmartActionsLocaleOverride"
```
