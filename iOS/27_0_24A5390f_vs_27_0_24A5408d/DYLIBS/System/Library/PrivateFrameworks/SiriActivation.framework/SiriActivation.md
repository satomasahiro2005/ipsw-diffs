## SiriActivation

> `/System/Library/PrivateFrameworks/SiriActivation.framework/SiriActivation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f570` | `0x743f8` | **`+0x4e88`** |
| `__TEXT.__oslogstring` | `0x90da` | `0x934c` | **`+0x272`** |
| `__TEXT.__cstring` | `0xca82` | `0xcc42` | **`+0x1c0`** |
| `__TEXT.__eh_frame` | `0xee8` | `0xf58` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x1d1` | `0x241` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x2050` | `0x20a0` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0xb88` | `0xbd8` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0xb138` | `0xb188` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x6f54` | `0x6fa4` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x3e4` | `0x42c` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x732` | `0x77a` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x1e60` | `0x1ea8` | **`+0x48`** |
| `__DATA.__data` | `0x1660` | `0x16a0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x34f0` | `0x3528` | **`+0x38`** |
| `__TEXT.__const` | `0x11ac` | `0x11dc` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x1488` | `0x14b0` | **`+0x28`** |
| `__DATA_CONST.__got` | `0xa60` | `0xa80` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x198` | `0x1b0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0xc88` | `0xc8c` | **`+0x4`** |

### Other Changes

```diff

-3600.55.30.0.0
+3600.55.37.11.2

-  Functions: 2880
-  Symbols:   4629
-  CStrings:  1792
+  Functions: 2906
+  Symbols:   4644
+  CStrings:  1806
Symbols:
+ -[SASPresentationManager _locked_requestState]
+ -[SASPresentationManager updateIsPreprocessRequestForActivePresentations:]
+ -[SASPresentationServer resetSiriToOff]
+ -[SASPresentationServer speechRequestStartedFromPresentationInterface]
+ -[SiriActivationService _activationConditionForRequest:systemState:presentationIdentifier:]
+ -[SiriActivationServiceClientConnection speechRequestStartedFromPresentationInterface]
+ GCC_except_table100
+ GCC_except_table106
+ GCC_except_table164
+ GCC_except_table17
+ GCC_except_table69
+ ___70-[SASPresentationServer speechRequestStartedFromPresentationInterface]_block_invoke
+ ___swift_closure_destructor.247Tm
+ ___swift_destroy_boxed_opaque_existential_1Tm
+ _swift_arrayDestroy
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _swift_release_x12
+ _symbolic Shy_____G 10Foundation4UUIDV
+ _symbolic So17SAFRequestOptionsCSg
+ _symbolic _____Sg 10Foundation4UUIDV
+ _symbolic _____y_____G s11_SetStorageC 10Foundation4UUIDV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation4UUIDV
- +[SRUIFSiriFeatureFlag(SWEFeatureFlags) isAssistedLinwoodVoiceResponseFromCompanionEnabled]
- GCC_except_table104
- GCC_except_table16
- GCC_except_table163
- GCC_except_table18
- GCC_except_table65
- GCC_except_table99
- ___swift_closure_destructor.240Tm
CStrings:
+ " was initiated by the presented assistant interface"
+ "#activation Request "
+ "%s #activation NO: Ignoring post-activation voice trigger that is not allowed to activate"
+ "%s #activation SAS client notified SAS that a speech request started from the presentation interface."
+ "%s #activation SAS client notifying SAS that a speech request started from the presentation interface..."
+ "%s #activation Shell indicates that speech request was started via a presented assistant interface"
+ "%s #activation _shouldRejectActivationWithButtonIdentifier - rejecting: Siri is disabled while passcode locked"
+ "%s #activation speech request state did change (state = %ld) and self request state: %ld"
+ "%s #myriad BTLE advertising a watch in-task voice trigger"
+ "%s %p #activation resetSiriToOff"
+ "-[SASPresentationManager _locked_requestState]"
+ "-[SASPresentationManager updateIsPreprocessRequestForActivePresentations:]"
+ "-[SASPresentationServer resetSiriToOff]"
+ "-[SASPresentationServer speechRequestStartedFromPresentationInterface]_block_invoke"
+ "-[SiriActivationServiceClientConnection speechRequestStartedFromPresentationInterface]"
+ "notifySpeechRequestInitiatedFromApplicationIfNeeded(_:)"
- "%s #activation speech request state did change (state = %ld)"
- "assisted_linwood_voice_response_from_companion"
```
