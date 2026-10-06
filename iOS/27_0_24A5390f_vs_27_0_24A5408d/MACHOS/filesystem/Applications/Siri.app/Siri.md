## Siri

> `/Applications/Siri.app/Siri`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf0b5c` | `0xf0f28` | **`+0x3cc`** |
| `__TEXT.__oslogstring` | `0xd774` | `0xdb14` | **`+0x3a0`** |
| `__DATA.__objc_const` | `0x10be8` | `0x10e48` | **`+0x260`** |
| `__TEXT.__objc_methname` | `0x2b6bf` | `0x2b91f` | **`+0x260`** |
| `__TEXT.__objc_stubs` | `0x1b4a0` | `0x1b680` | **`+0x1e0`** |
| `__TEXT.__cstring` | `0x243dd` | `0x2455d` | **`+0x180`** |
| `__TEXT.__objc_methlist` | `0xe330` | `0xe400` | **`+0xd0`** |
| `__DATA.__objc_data` | `0x4b18` | `0x4bc8` | **`+0xb0`** |
| `__DATA.__objc_selrefs` | `0x8fc8` | `0x9040` | **`+0x78`** |
| `__DATA.__data` | `0x4780` | `0x47d0` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x19f1` | `0x1a41` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x2504` | `0x254c` | **`+0x48`** |
| `__TEXT.__const` | `0x30e4` | `0x30a4` | **`-0x40`** |
| `__TEXT.__eh_frame` | `0xc88` | `0xcc0` | **`+0x38`** |
| `__TEXT.__objc_classname` | `0x1f93` | `0x1fc3` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x4d88` | `0x4da8` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x3010` | `0x3030` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0xaf71` | `0xaf91` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x3930` | `0x3948` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x8c4` | `0x8d8` | **`+0x14`** |
| `__DATA.__bss` | `0x2100` | `0x2110` | **`+0x10`** |
| `__DATA.__common` | `0x370` | `0x380` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1818` | `0x1828` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x2622` | `0x2632` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x12fc` | `0x1308` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x900` | `0x8f8` | **`-0x8`** |
| `__DATA_CONST.__objc_catlist` | `0x120` | `0x128` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x3a8` | `0x3b0` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x4b0` | `0x4b8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1d8` | `0x1e0` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x6b8` | `0x6bc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.55.30.0.0
+3600.55.37.11.2

+  - /System/Library/PrivateFrameworks/PowerExperience.framework/PowerExperience

-  Functions: 5191
-  Symbols:   1860
-  CStrings:  9014
+  Functions: 5195
+  Symbols:   1862
+  CStrings:  9058
Symbols:
+ _$s7SwiftUI11TransactionV18disablesAnimationsSbvs
+ _$s7SwiftUI11TransactionV9animationAcA9AnimationVSg_tcfC
+ _$s7SwiftUI15withTransactionyxAA0D0V_xyKXEtKlF
+ _$s7SwiftUI6_GlassV15SiriWaveOptionsV11PersonalityV10respondingAGvgZ
+ _$s7SwiftUI9AnimationV6linear8durationACSd_tFZ
+ _OBJC_CLASS_$_ResourceHint
- _$s7SwiftUI6_GlassV13ContentEffectV5lenseAEvgZ
- _$s7SwiftUI6_GlassV13ContentEffectVMa
- _$s7SwiftUI6_GlassV13ContentEffectVMn
- _$s7SwiftUI6_GlassV13contentEffectyA2C07ContentE0VSgF
CStrings:
+ " and speak it when Siri is presented."
+ "#PreprocessNotification Siri is presented invisibly. Let's suppress SayIt "
+ "%s #ResourceHint already active, added a holder (now %ld) — power state unchanged"
+ "%s #ResourceHint could not create the PowerExperience ResourceHint — AssistantMode will not be requested"
+ "%s #ResourceHint drop with no active holders — ignoring unbalanced release"
+ "%s #ResourceHint first holder — entering AssistantMode power state (PowerExperience update %s)"
+ "%s #ResourceHint last holder released — exiting AssistantMode power state (PowerExperience update %s)"
+ "%s #ResourceHint released a holder (%ld still active) — staying in AssistantMode power state"
+ "%s #carplay #ccc Loading an existing conversation. This means that we are launching into a detail screen in the CarPlay Campo app. Relinquish focus."
+ "%s #uifree Adjusting ui free idle timer to %f seconds for follow-up turn after announcement"
+ "%s #uifree Announcement activation (source %ld); using idle timer of %f seconds"
+ "%s #uifree User-interaction activation (source %ld); using idle timer of %f seconds"
+ "%s Presentation wants to suppress SAUISayIt: %@"
+ "-[SRCompactViewController _updateActiveTranscriptItems:upcomingConversationTranscriptItems:]"
+ "-[SRResourceHintAssertion _ensureHint]"
+ "-[SRResourceHintAssertion drop]"
+ "-[SRResourceHintAssertion take]"
+ "-[SiriUIFreePresentation _updateIdleTimeoutForActivationSource:]"
+ "@\"<SRResourceHintUpdating>\""
+ "REJECTED"
+ "SRResourceHintAssertion"
+ "SRResourceHintUpdating"
+ "T@\"SRResourceHintAssertion\",R,N"
+ "_activeCount"
+ "_didAttemptHintCreation"
+ "_didTakeAssistantModeAssertion"
+ "_dropAssistantModeAssertionIfNeeded"
+ "_ensureHint"
+ "_hint"
+ "_isAnnouncementRequestSource:"
+ "_synthesisStartCount"
+ "_takeAssistantModeAssertionForRequestOptionsIfNeeded:"
+ "_updateActiveTranscriptItems:upcomingConversationTranscriptItems:"
+ "_updateIdleTimeoutForActivationSource:"
+ "accepted"
+ "drop"
+ "hasPresentedSnippetThisTurn"
+ "hasPreservedSnippetThisTurn"
+ "initWithHint:"
+ "initWithResourceType:andState:"
+ "isForUIFree"
+ "preprocessedSayIt"
+ "setAudioPowerLevelUpdatesEnabled:"
+ "should clear stale snippet; supplemental SAUIAssistantUtteranceView with no snippet presented this turn"
+ "take"
+ "targetCampoConversationIdentifier"
+ "updateState:"
+ "willBeDiscarded"
+ "willBeDiscardedFromTranscript"
- "%s #uifree Adjusting ui free idle timer to %f seconds for user interaction request source"
- "-[SRCompactViewController _updateActiveTranscriptItems:]"
- "-[SiriUIFreePresentation siriRequestWillStartWithRequestOptions:]"
- "_enableLensing"
- "_updateActiveTranscriptItems:"
```
