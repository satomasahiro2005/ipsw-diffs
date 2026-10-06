## IMSharedUtilities

> `/System/Library/PrivateFrameworks/IMSharedUtilities.framework/IMSharedUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3598f4` | `0x35fe1c` | **`+0x6528`** |
| `__AUTH_CONST.__objc_const` | `0x26f88` | `0x27538` | **`+0x5b0`** |
| `__TEXT.__objc_methlist` | `0x18df8` | `0x19188` | **`+0x390`** |
| `__DATA.__bss` | `0x38620` | `0x388e0` | **`+0x2c0`** |
| `__TEXT.__cstring` | `0x27543` | `0x277e3` | **`+0x2a0`** |
| `__TEXT.__const` | `0x1f2c0` | `0x1f530` | **`+0x270`** |
| `__TEXT.__eh_frame` | `0xe78c` | `0xe9a8` | **`+0x21c`** |
| `__AUTH_CONST.__const` | `0x175f0` | `0x177e8` | **`+0x1f8`** |
| `__AUTH.__objc_data` | `0x81d0` | `0x83c0` | **`+0x1f0`** |
| `__TEXT.__oslogstring` | `0x1e196` | `0x1e386` | **`+0x1f0`** |
| `__TEXT.__unwind_info` | `0xf518` | `0xf6d8` | **`+0x1c0`** |
| `__DATA_CONST.__objc_selrefs` | `0xd070` | `0xd208` | **`+0x198`** |
| `__AUTH_CONST.__cfstring` | `0x239e0` | `0x23b20` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x6bd8` | `0x6c88` | **`+0xb0`** |
| `__DATA.__data` | `0xa788` | `0xa818` | **`+0x90`** |
| `__TEXT.__swift5_capture` | `0x14d4` | `0x1554` | **`+0x80`** |
| `__AUTH.__data` | `0x6548` | `0x65c0` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x7d68` | `0x7dcc` | **`+0x64`** |
| `__TEXT.__swift5_assocty` | `0x1ed8` | `0x1f38` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x763c` | `0x768e` | **`+0x52`** |
| `__TEXT.__gcc_except_tab` | `0x9d50` | `0x9d90` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x1068` | `0x1098` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x6993` | `0x69c3` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1b80` | `0x1ba8` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0xdd0` | `0xdf8` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x4e4` | `0x50c` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x2bb0` | `0x2bd0` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x67bc` | `0x67dc` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x370` | `0x388` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x2fc` | `0x314` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x2e4` | `0x2f8` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x1d30` | `0x1d44` | **`+0x14`** |
| `__DATA_CONST.__objc_superrefs` | `0x650` | `0x660` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0xec8` | `0xed8` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x80c` | `0x810` | **`+0x4`** |

### Other Changes

```diff

-1486.100.5.2.1
+1487.100.6.2.2

-  Functions: 20803
-  Symbols:   4164
-  CStrings:  7958
+  Functions: 20972
+  Symbols:   4180
+  CStrings:  7984
Symbols:
+ _CFPreferencesCopyMultiple
+ _IMMetricsCollectorEventFamilyValidationEnded
+ _IMMetricsCollectorEventFamilyValidationFamilyPhoneNumberAvailability
+ _IMMetricsCollectorEventFamilyValidationStarted
+ _OBJC_CLASS_$_IMDiagnosticCollector
+ _OBJC_CLASS_$_IMDiagnosticSwiftBridge
+ _OBJC_CLASS_$_IMMessageAssistantActionCompletionContext
+ _OBJC_CLASS_$_IMMessagePartAdaptiveImageGlyphDescriptor
+ _OBJC_CLASS_$_IMSpamModelMetadata
+ _OBJC_METACLASS_$_IMDiagnosticCollector
+ _OBJC_METACLASS_$_IMDiagnosticSwiftBridge
+ _OBJC_METACLASS_$_IMMessageAssistantActionCompletionContext
+ _OBJC_METACLASS_$_IMMessagePartAdaptiveImageGlyphDescriptor
+ _OBJC_METACLASS_$_IMSpamModelMetadata
+ _dispatch_get_specific
+ _dispatch_queue_set_specific
CStrings:
+ "%{public}s Early returning NO based on the value of IMServiceImpl because this is iMessage or iMessage Lite"
+ "%{public}s Early returning YES based on the value of IMServiceImpl because this is iMessage or iMessage Lite"
+ "%{public}s IDS daemon not connected; falling back to IM-layer checks"
+ "Calling UserSafety -analyzeImageFile:options:completionHandler:"
+ "Captured attachment path %@ does not have collection directory prefix %@!"
+ "IMDiagnosticCollector"
+ "IMSharedUtilities.IMMessageAssistantActionCompletionContext"
+ "IMSharedUtilities.IMSpamModelMetadata"
+ "No _LTLanguageStatus symbol, not starting observation"
+ "No change in translation languages"
+ "ReindexVacuumCompleted"
+ "ReindexVacuumRequirements"
+ "awaitFirstObservation timed out"
+ "com.apple.family.Messages.ValidationEnded"
+ "com.apple.family.Messages.ValidationFamilyPhoneNumberAvailability"
+ "com.apple.family.Messages.ValidationStarted"
+ "com.apple.messages.IMDiagnosticCollection"
+ "com_apple_mobilesms_inlineGlyphPartIndicesAndRanges"
+ "com_apple_mobilesms_isInlineGlyph"
+ "com_apple_mobilesms_partIndices"
+ "decisioningMetadata"
+ "historyQuery(_:chatID:services:finishedWithResult:limit:hasMessagesBefore:hasMessagesAfter:)"
+ "messagePartIndex"
+ "nil LanguageStatus observation"
+ "ranges"
+ "reportingMetadata"
+ "v16@?0@?<v@?>8"
+ "v32@?0@\"NSString\"8@\"NSMutableArray\"16^B24"
- "Early returning based on the value of IMServiceImpl because this is iMessage or iMessage Lite"
- "historyQuery(_:chatID:services:finishedWithResult:limit:)"
```
