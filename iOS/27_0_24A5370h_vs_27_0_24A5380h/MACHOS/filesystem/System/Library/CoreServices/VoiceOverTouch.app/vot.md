## vot

> `/System/Library/CoreServices/VoiceOverTouch.app/vot`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16e8f0` | `0x172ebc` | **`+0x45cc`** |
| `__TEXT.__objc_methname` | `0x36e78` | `0x373f8` | **`+0x580`** |
| `__TEXT.__eh_frame` | `0x17c8` | `0x1b60` | **`+0x398`** |
| `__TEXT.__objc_stubs` | `0x29760` | `0x29a60` | **`+0x300`** |
| `__TEXT.__cstring` | `0xf647` | `0xf76b` | **`+0x124`** |
| `__TEXT.__const` | `0x1b30` | `0x1c40` | **`+0x110`** |
| `__DATA.__objc_selrefs` | `0xc520` | `0xc620` | **`+0x100`** |
| `__DATA.__objc_const` | `0x146a0` | `0x14790` | **`+0xf0`** |
| `__TEXT.__oslogstring` | `0x9591` | `0x94ae` | **`-0xe3`** |
| `__TEXT.__objc_methlist` | `0x1125c` | `0x1133c` | **`+0xe0`** |
| `__DATA_CONST.__got` | `0x2560` | `0x2630` | **`+0xd0`** |
| `__DATA_CONST.__cfstring` | `0xe120` | `0xe1e0` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x48f0` | `0x49a8` | **`+0xb8`** |
| `__DATA.__bss` | `0x19b8` | `0x1a58` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0x3af0` | `0x3b30` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0xc2e` | `0xbf0` | **`-0x3e`** |
| `__DATA_CONST.__const` | `0x5a00` | `0x59c8` | **`-0x38`** |
| `__TEXT.__swift_as_cont` | `0x120` | `0x150` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x1d88` | `0x1da8` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x9c` | `0xbc` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0xbfc` | `0xc18` | **`+0x1c`** |
| `__DATA.__objc_ivar` | `0x14e8` | `0x14fc` | **`+0x14`** |
| `__DATA.__data` | `0x23b0` | `0x23a0` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2d98` | `0x2da8` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x608` | `0x618` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0xa8` | `0xb4` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x418` | `0x420` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x6cc` | `0x6c4` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x88` | `0x8c` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x7c` | `0x80` | **`+0x4`** |
| `__TEXT.__objc_methtype` | `0x4ed3` | `0x4ed0` | **`-0x3`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-2470.0.0.0.0
+2472.1.0.0.0

-  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

-  Functions: 7065
-  Symbols:   2279
-  CStrings:  12141
+  Functions: 7107
+  Symbols:   2285
+  CStrings:  12189
Symbols:
+ _$s12TextToSpeech11TTSSettingsC27currentRotorVoiceIdentifierSSSgvgTj
+ _$s12TextToSpeech11TTSSettingsC41voiceOverDefaultVoiceSelectionsByLanguageSDy10Foundation6LocaleV0K4CodeV15AXCoreUtilities0H9SelectionVGvgTj
+ _$s12TextToSpeech13VoiceResolverC19currentSystemLocale10Foundation0H0VyYaFTjTu
+ _$s12TextToSpeech13VoiceResolverC6sharedACvgZ
+ _$s12TextToSpeech15CoreSynthesizerC5EventO6pausedyA2EmFWC
+ _$s12TextToSpeech15CoreSynthesizerC5EventO7resumedyA2EmFWC
+ _$s12TextToSpeech15CoreSynthesizerC5EventO8finishedyAESb_tcAEmFWC
+ _$s12TextToSpeech15CoreSynthesizerC5VoiceV14speaksLanguage6localeSb10Foundation6LocaleV_tF
+ _$s12TextToSpeech15CoreSynthesizerC9UtteranceV18ReplacementOptionsV11emojiSuffixAGvgZ
+ _$s12TextToSpeech22VoiceSelectionProviderMp
+ _$s12TextToSpeech22VoiceSelectionProviderP7enabledSbvgTq
+ _$s12TextToSpeech22VoiceSelectionProviderP9selection9forLocale15AXCoreUtilities0dE0VSg10Foundation0I0VSg_tYaFTq
+ _$s15AXCoreUtilities14VoiceSelectionV4rateSfSgvg
+ _$s15AXCoreUtilities22UserVoiceConfigurationV2idSSvg
+ _$s15AXCoreUtilities22UserVoiceConfigurationV7voiceIdSSSgvg
+ _$sSD12TextToSpeech10Foundation6LocaleV12LanguageCodeVRsz15AXCoreUtilities14VoiceSelectionVRs_rlE9selection03forF012withResolver6existsAISgAFSg_AA0jO0CSpySbGSgtYaF
+ _$sSD12TextToSpeech10Foundation6LocaleV12LanguageCodeVRsz15AXCoreUtilities14VoiceSelectionVRs_rlE9selection03forF012withResolver6existsAISgAFSg_AA0jO0CSpySbGSgtYaFTu
+ _$sSS5index_8offsetBy07limitedC0SS5IndexVSgAE_SiAEtF
+ _$sSo10AXSettingsC22AccessibilityUtilitiesE9VoiceOverC22verbosityEmojiFeedbackSo08AXSVoiceeH6OptionVvg
+ _$sSo10AXSettingsC22AccessibilityUtilitiesE9VoiceOverC27verbosityEmojiSuffixEnabledSbvg
+ _$sSo10AXSettingsC22AccessibilityUtilitiesE9VoiceOverC8ActivityV11speakEmojisSbSgvg
+ _$sSo10AXSettingsC22AccessibilityUtilitiesE9VoiceOverC8ActivityV14numberFeedbackSo08AXSVoicee6NumberH0VSgvg
- _$s12FeatureFlags02isA7EnabledySbAA0aB3Key_pF
- _$s12TextToSpeech29VoiceOverAppSelectionProviderVAA0dgH0AAWP
- _$s12TextToSpeech29VoiceOverAppSelectionProviderVACycfC
- _$s12TextToSpeech29VoiceOverAppSelectionProviderVMa
- _$s15AXCoreUtilities25AccessibilityFeatureFlagsO0dE00dE3KeyAAMc
- _$s15AXCoreUtilities25AccessibilityFeatureFlagsO13imageExploreryA2CmFWC
- _$s17BrailleFoundation0A18ClientBoundMessageO19updateSealedChamberyACSS_SSAA0A6DeviceV2IDOtcACmFWC
- _$s17BrailleFoundation0A6DeviceV2IDOSQAAMc
- _$sSS5index_8offsetBySS5IndexVAD_SitF
- _$sSo10AXSettingsC22AccessibilityUtilitiesE13ImageExplorerC19onDeviceModeEnabledSbvs
- _$sSo10AXSettingsC22AccessibilityUtilitiesE13ImageExplorerC38hasShownAppleIntelligencePrivacyPromptSbvg
- _$sSo10AXSettingsC22AccessibilityUtilitiesE13ImageExplorerC38hasShownAppleIntelligencePrivacyPromptSbvs
- _$sSo10AXSettingsC22AccessibilityUtilitiesE13imageExplorerAbCE05ImageE0CvpWvd
- _AXDeviceSupportsAppleIntelligence
- _swift_retain
- _swift_retain_x2
CStrings:
+ "(\\+[0-9]{6,15}|(((\\s?|\\b)([0-9]{2,3}\\s)?(\\(?[0-9]{3}\\)?)?(\\s|-))|\\s)?([0-9]{2,7})(-|\\s)([0-9]{3,7}))(\\s|\\b)"
+ "@\"BRLState\""
+ "Discarding paused speech for incoming announcement."
+ "FOCUS-PRESERVED-RECENT-INTERACTION"
+ "TB,N,V_arrowKeyQuickNavTemporarilyDisabled"
+ "TB,N,V_lastTemporaryArrowKeyQuickNavWasDisabled"
+ "TB,N,V_lastTemporarySingleLetterQuickNavWasDisabled"
+ "TB,N,V_singleLetterQuickNavTemporarilyDisabled"
+ "Temporarily disable quick nav: arrow=%d single=%d"
+ "Tq,N,V_imageCaptionsMode"
+ "_arrowKeyQuickNavTemporarilyDisabled"
+ "_clearLastUserInteractionTimestamps"
+ "_firstElementInApplicationForFocusAllowingRemote:"
+ "_handleQuickNavFeedback:types:origin:"
+ "_imageCaptionsMode"
+ "_lastSentStructuredState"
+ "_lastTemporaryArrowKeyQuickNavWasDisabled"
+ "_lastTemporarySingleLetterQuickNavWasDisabled"
+ "_shouldPreserveCurrentFocusAfterRecentUserInteractionWithReason:"
+ "_singleLetterQuickNavTemporarilyDisabled"
+ "_temporarilyChangeSingleLetterQuickNav:"
+ "all.quick.nav.off"
+ "all.quick.nav.on"
+ "arrowKeyQuickNavTemporarilyDisabled"
+ "attributes"
+ "countOfIndexesInRange:"
+ "createMixedLiteralMarkup: literal range start %ld is beyond text length %ld; skipping range"
+ "descriptions"
+ "elementToken"
+ "filterUnacceptableBrailleStrings:"
+ "imageCaptionsMode"
+ "lastTemporaryArrowKeyQuickNavWasDisabled"
+ "lastTemporarySingleLetterQuickNavWasDisabled"
+ "layout change"
+ "layout change (entry)"
+ "lineRelativeSelectionEnd"
+ "lineRelativeSelectionStart"
+ "move-to-element"
+ "role"
+ "screen change"
+ "screen change (entry)"
+ "selectionRange"
+ "setActions:"
+ "setArrowKeyQuickNavTemporarilyDisabled:"
+ "setDescriptions:"
+ "setImageCaptionsMode:"
+ "setImageValue:"
+ "setLastTemporaryArrowKeyQuickNavWasDisabled:"
+ "setLastTemporarySingleLetterQuickNavWasDisabled:"
+ "setSingleLetterQuickNavTemporarilyDisabled:"
+ "setStructuredImageData:forElement:"
+ "setVoiceOverHasActiveUserBrailleDisplay:"
+ "setVoiceOverTouchBraille2DTextMode:"
+ "singleLetterQuickNavTemporarilyDisabled"
+ "stringByFilteringUnacceptableBrailleCharacters:"
+ "temporarilyChangeSingleLetterQuickNavState:"
+ "temporarySingleLetterQuickNavEnabled:"
+ "v36@0:8B16Q20Q28"
+ "voiceOverFunctionKeysDoNotRequireModifier"
+ "voiceOverImageCaptionsMode"
+ "voiceOverTouchBraille2DTextMode"
+ "voiceOverWatchTapToWakeEnabled"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xb1"
- "Not moving focus for layout change because the user interacted recently and the element still exists{%@}"
- "Not moving focus for screen change because the user interacted recently and the element still exists{%@}"
- "SealedChamber"
- "TB,N,V_imageCaptionsEnabled"
- "Temporarily disable quick nav: %d - %d"
- "VoiceOverSealedChamberKey"
- "VoiceOverSealedChamberSecret"
- "[VOT]: User declined Apple Intelligence; proceeding with on-device fallback."
- "_filterUnacceptableBrailleStrings:"
- "_imageCaptionsEnabled"
- "setDisplayDescriptorCallbackEnabled:"
- "setSealedChamberWithSecret:key:"
- "showAlert:withHandler:withData:"
- "voiceOverImageCaptionsEnabled"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xa1"
```
