## SiriUIFoundation

> `/System/Library/PrivateFrameworks/SiriUIFoundation.framework/SiriUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x910e8` | `0x9193c` | **`+0x854`** |
| `__TEXT.__unwind_info` | `0x2690` | `0x2738` | **`+0xa8`** |
| `__AUTH_CONST.__objc_const` | `0x8ff0` | `0x9080` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x46b8` | `0x4748` | **`+0x90`** |
| `__TEXT.__cstring` | `0x66f6` | `0x6676` | **`-0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x2f38` | `0x2fa8` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x1978` | `0x19b0` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x112a` | `0x10fa` | **`-0x30`** |
| `__AUTH_CONST.__cfstring` | `0x23a0` | `0x23c0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xa78` | `0xa98` | **`+0x20`** |
| `__TEXT.__const` | `0x389c` | `0x387c` | **`-0x20`** |
| `__TEXT.__oslogstring` | `0x6fcb` | `0x6fab` | **`-0x20`** |
| `__DATA.__data` | `0x1768` | `0x1750` | **`-0x18`** |
| `__TEXT.__swift5_fieldmd` | `0xf88` | `0xf7c` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0xf38` | `0xf40` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x430` | `0x438` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x97c` | `0x984` | **`+0x8`** |

### Other Changes

```diff

-3600.55.30.0.0
+3600.55.37.11.2

-  Functions: 3358
-  Symbols:   3726
-  CStrings:  1132
+  Functions: 3376
+  Symbols:   3746
+  CStrings:  1129
Symbols:
+ -[SRUIFInstrumentationManager clearPendingLinkTapBreadcrumb]
+ -[SRUIFInstrumentationManager emitBreadcrumbReturnedIfNeeded]
+ -[SRUIFInstrumentationManager emitCanvasToAppExpanded]
+ -[SRUIFInstrumentationManager emitIslandToCanvasExpanded]
+ -[SRUIFInstrumentationManager emitLinkTappedWithType:isPersonalEntity:opensExternally:]
+ -[SRUIFInstrumentationManager emitSourceListExpandedWithSourceCount:]
+ -[SRUIFInstrumentationManager emitUUFRShownForPresentationType:dialogPhase:mode:viewRegion:]
+ -[SRUIFInstrumentationManager pendingLinkTapBreadcrumbTurn]
+ -[SRUIFInstrumentationManager setPendingLinkTapBreadcrumbTurn:]
+ -[SRUIFSpeechSynthesizer audioPowerLevelUpdatesEnabled]
+ -[SRUIFSpeechSynthesizer setAudioPowerLevelUpdatesEnabled:]
+ GCC_except_table102
+ GCC_except_table104
+ GCC_except_table111
+ GCC_except_table20
+ GCC_except_table36
+ GCC_except_table40
+ GCC_except_table63
+ GCC_except_table79
+ _OBJC_CLASS_$_SISchemaUEIBreadcrumbReturned
+ _OBJC_CLASS_$_SISchemaUEICanvasToAppExpanded
+ _OBJC_CLASS_$_SISchemaUEIIslandToCanvasExpanded
+ _OBJC_CLASS_$_SISchemaUEILinkTapped
+ _OBJC_CLASS_$_SISchemaUEISourceListExpanded
+ _OBJC_IVAR_$_SRUIFSpeechSynthesizer._audioPowerLevelUpdatesEnabled
+ _OBJC_IVAR_$_SRUIFSpeechSynthesizer._audioPowerSignpostID
+ ___54-[SRUIFInstrumentationManager emitCanvasToAppExpanded]_block_invoke
+ ___57-[SRUIFInstrumentationManager emitIslandToCanvasExpanded]_block_invoke
+ ___61-[SRUIFInstrumentationManager emitBreadcrumbReturnedIfNeeded]_block_invoke
+ ___69-[SRUIFInstrumentationManager emitSourceListExpandedWithSourceCount:]_block_invoke
+ ___87-[SRUIFInstrumentationManager emitLinkTappedWithType:isPersonalEntity:opensExternally:]_block_invoke
+ ___block_descriptor_61_e8_32s40w_e5_v8?0lw40l8s32l8
+ ___swift_closure_destructor.194Tm
+ ___swift_closure_destructor.201Tm
+ _keypath_get_selector_audioPowerLevelUpdatesEnabled
- +[SRUIFSiriFeatureFlag(SWEFeatureFlags) isAssistedLinwoodVoiceResponseFromCompanionEnabled]
- +[SRUIFSpeechSynthesizer _inlineStreamMarkerRequestTextForText:inlineStreamId:companionVoiceResponseEnabled:]
- GCC_except_table28
- GCC_except_table38
- GCC_except_table60
- GCC_except_table74
- GCC_except_table76
- GCC_except_table86
- GCC_except_table88
- GCC_except_table90
- GCC_except_table97
- _SRUIFIsCompanionVoiceResponseEnabled
- __OBJC_$_CLASS_METHODS_SRUIFSpeechSynthesizer
- ___swift_closure_destructor.192Tm
- ___swift_closure_destructor.199Tm
CStrings:
+ "PendingLinkTapBreadcrumbTurnIdentifier"
+ "TTSAudioPowerPolling"
+ "com.apple.SiriViewService.tests"
+ "\xd2"
- "\v6"
- "%@%@\\%@"
- "%s #tts inline-stream marker+text from streamId: %@"
- "+[SRUIFSpeechSynthesizer _inlineStreamMarkerRequestTextForText:inlineStreamId:companionVoiceResponseEnabled:]"
- "GenerateCompanionVoiceResponse"
- "assisted_linwood_voice_response_from_companion"
- "\xc2"
```
