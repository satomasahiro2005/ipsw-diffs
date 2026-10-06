## TextUnderstandingRuntime

> `/System/Library/PrivateFrameworks/TextUnderstandingRuntime.framework/TextUnderstandingRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x230838` | `0x2377dc` | **`+0x6fa4`** |
| `__TEXT.__eh_frame` | `0x15248` | `0x158a4` | **`+0x65c`** |
| `__TEXT.__oslogstring` | `0x955a` | `0x97ca` | **`+0x270`** |
| `__AUTH_CONST.__const` | `0xe888` | `0xeac8` | **`+0x240`** |
| `__TEXT.__const` | `0x12948` | `0x12b88` | **`+0x240`** |
| `__TEXT.__unwind_info` | `0x78d8` | `0x7768` | **`-0x170`** |
| `__TEXT.__swift5_typeref` | `0x4c0b` | `0x4d3d` | **`+0x132`** |
| `__TEXT.__cstring` | `0x4fa2` | `0x50d2` | **`+0x130`** |
| `__DATA.__bss` | `0x1b530` | `0x1b630` | **`+0x100`** |
| `__AUTH_CONST.__auth_got` | `0x4110` | `0x41e8` | **`+0xd8`** |
| `__AUTH_CONST.__objc_const` | `0x29e8` | `0x2ac0` | **`+0xd8`** |
| `__AUTH.__data` | `0xea8` | `0xf78` | **`+0xd0`** |
| `__TEXT.__constg_swiftt` | `0x3694` | `0x374c` | **`+0xb8`** |
| `__TEXT.__swift5_fieldmd` | `0x3ec0` | `0x3f78` | **`+0xb8`** |
| `__DATA.__data` | `0x2ed0` | `0x2f80` | **`+0xb0`** |
| `__DATA_DIRTY.__data` | `0x35d8` | `0x3538` | **`-0xa0`** |
| `__TEXT.__swift5_reflstr` | `0x2eec` | `0x2f6c` | **`+0x80`** |
| `__TEXT.__swift_as_cont` | `0xcf8` | `0xd48` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x1d24` | `0x1d5c` | **`+0x38`** |
| `__DATA.__common` | `0x190` | `0x1c0` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x750` | `0x774` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0xeb0` | `0xed0` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x570` | `0x58c` | **`+0x1c`** |
| `__TEXT.__swift5_proto` | `0x105c` | `0x106c` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x498` | `0x4a4` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x138` | `0x140` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x88` | `0x8c` | **`+0x4`** |

### Other Changes

```diff

-175.0.0.0.0
+176.3.0.0.0

+  - /System/Library/PrivateFrameworks/CorePhoneNumbers.framework/CorePhoneNumbers

+  - /System/Library/PrivateFrameworks/PrivateCloudCompute.framework/PrivateCloudCompute

-  Functions: 12104
-  Symbols:   590
-  CStrings:  988
+  Functions: 12182
+  Symbols:   591
+  CStrings:  1001
Symbols:
+ _OBJC_CLASS_$_CSCustomAttributeKey
+ _OBJC_CLASS_$_ECSnippetTextClassifier
- _swift_getExistentialMetatypeMetadata
CStrings:
+ "<Processor: SmartRepliesEligibilityProcessor>"
+ "CarKeyDataProcessor: legacy fallback JSON decode failed: %{public}@"
+ "CarKeyDataProcessor: legacy fallback produced non-UTF-8 output"
+ "CarKeyDataProcessor: legacy generateWithSchema fallback completed successfully"
+ "CarKeyDataProcessor: template %{public}s missing from adapter metadata; falling back to generateWithSchema"
+ "CarKeyDetectionResult"
+ "Eligibility: Document %{private}s cannot be processed because it is too old"
+ "Eligibility: Document cannot be processed because it is from %s for which the user has disabled the \"Learn from this App\" toggle"
+ "Failed to decode fallback CarKey result: "
+ "Invalid UTF-8 from OEE fallback"
+ "MailSmartRepliesProfileProcessor.RateLimiter: failed to construct TrustedCloudComputeClient: %{public}s"
+ "MailSmartRepliesProfileProcessor: Profile extraction async stream finished without yielding, this should not happen."
+ "MailSmartRepliesProfileProcessor: Profile extraction was cancelled, surfacing as interrupted for retry."
+ "MailSmartRepliesProfileProcessor: extractProfile threw unexpected error %s - this should not happen."
+ "PersonalizedSmartReplies"
+ "PromptContentTemplateError.templateNotFound"
+ "SmartRepliesEligibilityProcessor: Mail Smart Replies blocked by the allowMailSmartReplies MDM restriction"
+ "SmartRepliesEligibilityProcessor: Mail Smart Replies disabled via the PersonalizedSmartReplies Mail setting"
+ "SmartRepliesEligibilityProcessor: personalizedSmartReplies feature flag is disabled"
+ "com.apple.textComposition.OpenEndedExtract.carkey"
+ "com_apple_mobilephone_documentnormalizedphonenumbers"
+ "group.com.apple.mail"
- "CarKeyDataProcessor: Failed to convert adapter output to UTF-8 data"
- "CarKeyDataProcessor: JSON decoding failed with error: %@"
- "DocumentEligibilityProcessor: Document %{private}s cannot be processed because it is is too old"
- "DocumentEligibilityProcessor: document cannot be processed because it is from %s) for which the user has disabled the \"Learn from this App\" toggle"
- "Failed to decode car key detection result: "
- "Invalid UTF-8 output from adapter"
- "MailSmartRepliesProfileProcessor: Ignoring because PersonalizedSmartReplies feature flag is disabled"
- "MailSmartRepliesProfileProcessor: Ignoring because allowMailSmartReplies MDM restriction is set"
- "MessagesSmartRepliesProfileProcessor: ignoring because PersonalizedSmartReplies feature flag is disabled"
```
