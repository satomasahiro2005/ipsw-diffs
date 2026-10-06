## TextUnderstandingRuntime

> `/System/Library/PrivateFrameworks/TextUnderstandingRuntime.framework/TextUnderstandingRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22a8d8` | `0x21641c` | **`-0x144bc`** |
| `__DATA.__bss` | `0x1c950` | `0x1b040` | **`-0x1910`** |
| `__TEXT.__eh_frame` | `0x14c28` | `0x13758` | **`-0x14d0`** |
| `__AUTH_CONST.__const` | `0xf980` | `0xe758` | **`-0x1228`** |
| `__TEXT.__const` | `0x132d8` | `0x123e8` | **`-0xef0`** |
| `__TEXT.__unwind_info` | `0x7918` | `0x6ea8` | **`-0xa70`** |
| `__TEXT.__cstring` | `0xd303` | `0xcd02` | **`-0x601`** |
| `__DATA_DIRTY.__bss` | `0x2e00` | `0x2900` | **`-0x500`** |
| `__TEXT.__swift5_capture` | `0x1f78` | `0x1bac` | **`-0x3cc`** |
| `__TEXT.__oslogstring` | `0x91be` | `0x8eea` | **`-0x2d4`** |
| `__TEXT.__swift5_fieldmd` | `0x4290` | `0x4014` | **`-0x27c`** |
| `__DATA_DIRTY.__data` | `0x2fc0` | `0x2df0` | **`-0x1d0`** |
| `__TEXT.__constg_swiftt` | `0x36a8` | `0x3520` | **`-0x188`** |
| `__AUTH_CONST.__auth_got` | `0x3e48` | `0x3f68` | **`+0x120`** |
| `__TEXT.__swift_as_cont` | `0xbb0` | `0xab4` | **`-0xfc`** |
| `__TEXT.__swift5_proto` | `0x10d0` | `0xfe0` | **`-0xf0`** |
| `__TEXT.__swift_as_ret` | `0x788` | `0x698` | **`-0xf0`** |
| `__TEXT.__swift5_typeref` | `0x4a35` | `0x494f` | **`-0xe6`** |
| `__TEXT.__swift5_reflstr` | `0x2f4c` | `0x2e8c` | **`-0xc0`** |
| `__DATA.__data` | `0x3180` | `0x30d0` | **`-0xb0`** |
| `__TEXT.__swift_as_entry` | `0x56c` | `0x4e4` | **`-0x88`** |
| `__DATA_DIRTY.__common` | `0x320` | `0x2b0` | **`-0x70`** |
| `__TEXT.__swift5_assocty` | `0xf70` | `0xf10` | **`-0x60`** |
| `__AUTH_CONST.__objc_const` | `0x25f8` | `0x25a0` | **`-0x58`** |
| `__AUTH.__objc_data` | `0x170` | `0x1c0` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x4e0` | `0x498` | **`-0x48`** |
| `__TEXT.__swift5_types` | `0x4c8` | `0x494` | **`-0x34`** |
| `__AUTH.__data` | `0xf58` | `0xf38` | **`-0x20`** |
| `__DATA.__common` | `0x2a0` | `0x288` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xe10` | `0xe28` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x6dc` | `0x6f0` | **`+0x14`** |
| `__DATA_CONST.__objc_protolist` | `0x98` | `0xa8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x128` | `0x120` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x80` | `0x84` | **`+0x4`** |

### Other Changes

```diff

-161.1.0.0.0
+167.1.0.0.0

-  Functions: 12204
-  Symbols:   569
-  CStrings:  977
+  Functions: 11597
+  Symbols:   573
+  CStrings:  950
Symbols:
+ _bzero
+ _os_transaction_create
+ _swift_getTupleTypeMetadata3
+ _swift_release_x15
CStrings:
+ "Cache.SQLStore.get"
+ "Cache.SQLStore.touch"
+ "Cache.SQLStore.upsert"
+ "Cache.SQLStore: read failed: %@"
+ "Cache.SQLStore: upsert failed: %@"
+ "CarKeyDataPipeline: carKeyDataExtraction feature flag is disabled"
+ "EventsPipeline: no events detected in schema"
+ "IdentificationDocumentProcessor: using %s extraction"
+ "MailSmartRepliesProfileProcessor: WebTextExtractor failed, falling back to fullCleanedContent: %@"
+ "OpenEndedExtractionAdapter: Truncated generateWithSchema input from %ld to %ld characters"
+ "OrdersPipeline: no orders detected in schema"
+ "PDFIdentificationDocumentProcessor: using %s extraction"
+ "Pipeline: device is not eligible for Apple Intelligence"
+ "ProcessingXPCServer: process: constructPipeline for %s with %{private}s input (taskPriority=%hhu)"
+ "ProcessingXPCServer: processingAvailability called for unregistered descriptor: %s"
+ "ProcessingXPCServer: processingAvailability: end"
+ "ProcessingXPCServer: processingAvailability: start"
+ "ReceiptsPipeline: no receipts detected in schema"
+ "TextUnderstanding.Cache"
+ "TextUnderstandingRuntime.WebViewNavigationDelegate"
+ "WebTextExtractor.extract: cached web content process is suspended; resetting web process before load"
+ "WebTextExtractor.getOrCreateWebView: discarding web view idle for over %s"
+ "com.apple.textunderstandingd.WebTextExtractor.extractText"
+ "output renderedPrompt rawOutput "
- "6_FPV2KNSwL4pdAjP6HiCuPMtrU."
- "6zCq0c478MY8L00fQ76mlXH6Gng."
- "CarKeyDataProcessor: feature flag is disabled."
- "ContactsProcessor: LanguageIdentificationProcessor must return non-nil documentLanguage or throw, but nil was returned."
- "EventsProcessor: LanguageIdentificationProcessor must return non-nil documentLanguage or throw, but nil was returned."
- "EventsProcessor: SchemaDetectionProcessor must return non-nil output or throw, but nil output was returned."
- "EventsProcessor: no events detected in schema"
- "IdentificationDocumentProcessor: using %s %s extraction"
- "InstantReceiver: Supported bundle requests map: %s"
- "InstantReceiver: bundle identifier '%s' missing from request map."
- "InstantReceiver: requests for %s: %s"
- "LanguageIdentificationProcessor: GenerativeModelsAvailability check indicates that this device is not eligible for Apple Intelligence"
- "LanguageIdentificationProcessor: ignoring orders request because TextUnderstanding/openEndedEventsAndOrders feature flag is disabled"
- "MessagesProfileExtractionAdapter: Failed to create ResourceBundleQuery: %@"
- "MessagesProfileExtractionAdapter: generateConstrained failed with GenerativeError: %@"
- "MessagesProfileExtractionAdapter: generateConstrained failed with ModelManagerError: %@"
- "MessagesProfileExtractionAdapter: generateConstrained failed: %@"
- "ObservationsProcessor: LanguageIdentificationProcessor must return non-nil documentLanguage or throw, but nil was returned"
- "OpenEndedExtractionAdapter: Truncated v11 generateWithSchema input from %ld to %ld characters"
- "OpenEndedExtractionAdapter: Using v11 instruction-based path for %{public}s"
- "OpenEndedExtractionAdapter: Using v9 template-based path for %{public}s"
- "OpenEndedExtractionAdapter: formatting document input failed (v11): %@"
- "OpenEndedExtractionAdapter: generateConstrained (v11) failed: %@"
- "OpenEndedExtractionAdapter: generateWithSchema (v11) failed: %@"
- "OpenEndedExtractionAdapter: truncateTextByTokenCount (v11) failed: %@"
- "OpenEndedExtractionSchemaDetector: prompt template not found, falling back to deprecated schema"
- "OrdersProcessor: LanguageIdentificationProcessor must return non-nil documentLanguage or throw, but nil was returned."
- "OrdersProcessor: SchemaDetectionProcessor must return non-nil output or throw, but nil output was returned."
- "OrdersProcessor: no orders detected in schema"
- "OuK_DuYSm1XO0ZGGlFzM2V1jMac."
- "PDFIdentificationDocumentProcessor: using %s %s extraction"
- "PljOtP6n_c3s_S2aQRKYkU9HlVQ."
- "ProcessingXPCServer: process: constructPipeline for %s with %{private}s input"
- "ReceiptsProcessor: LanguageIdentificationProcessor must return non-nil documentLanguage or throw, but nil was returned"
- "ReceiptsProcessor: SchemaDetectionProcessor must return non-nil output or throw, but nil output was returned."
- "ReceiptsProcessor: no receipts detected in schema"
- "SchemaDetectionProcessor: LanguageIdentificationProcessor must return non-nil documentLanguage or throw, but nil was returned."
- "SpotlightDocumentUpdateDistributor: setting %s = %ld"
- "TextUnderstandingRuntime/ContactsProcessor.swift"
- "TextUnderstandingRuntime/ObservationsProcessor.swift"
- "TextUnderstandingRuntime/OrdersProcessor.swift"
- "TextUnderstandingRuntime/ReceiptsProcessor.swift"
- "TextUnderstandingRuntime/SchemaDetectionProcessor.swift"
- "_OverrideConfigurationHelper.samplingParameters(samplingParameters)"
- "cancellation"
- "com.apple.textComposition.OpenEndedExtract.extractioncandidates"
- "confirmation"
- "maXDCLB2xDd2jvYFnyp-Da7CsRI."
- "v_NNVExg6QHZ5uLvBnT5CHnXfn4."
- "vtAwsTnhT5xaJq-CvB-g43BdU44."
- "zit5qiSxUOBR0GvyITczE0PvKOM."
```
