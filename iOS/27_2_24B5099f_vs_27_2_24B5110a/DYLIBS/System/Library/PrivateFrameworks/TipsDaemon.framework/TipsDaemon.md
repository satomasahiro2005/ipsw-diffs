## TipsDaemon

> `/System/Library/PrivateFrameworks/TipsDaemon.framework/TipsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa1664` | `0xa3968` | **`+0x2304`** |
| `__AUTH.__objc_data` | `0x1020` | `0x12b0` | **`+0x290`** |
| `__AUTH_CONST.__objc_const` | `0x82a8` | `0x8438` | **`+0x190`** |
| `__TEXT.__cstring` | `0x430c` | `0x444c` | **`+0x140`** |
| `__TEXT.__eh_frame` | `0x4d20` | `0x4e48` | **`+0x128`** |
| `__TEXT.__const` | `0x3288` | `0x3398` | **`+0x110`** |
| `__AUTH_CONST.__const` | `0x2860` | `0x2968` | **`+0x108`** |
| `__TEXT.__constg_swiftt` | `0xee8` | `0xfc0` | **`+0xd8`** |
| `__TEXT.__objc_methlist` | `0x3968` | `0x3a08` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x2d88` | `0x2e28` | **`+0xa0`** |
| `__AUTH.__data` | `0x78` | `0xf0` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x9c8` | `0xa38` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x2a20` | `0x2a80` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x1218` | `0x1260` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x750` | `0x794` | **`+0x44`** |
| `__TEXT.__swift5_typeref` | `0x1180` | `0x11c0` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xd18` | `0xd38` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x540` | `0x560` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x6ce` | `0x6ee` | **`+0x20`** |
| `__DATA.__data` | `0x8b8` | `0x8c8` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1ee0` | `0x1ef0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x118` | `0x128` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x430` | `0x43c` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x26b8` | `0x26c0` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x140` | `0x144` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x208` | `0x20c` | **`+0x4`** |

### Other Changes

```diff

-866.2.3.0.0
+866.2.4.0.0

+  - /System/Library/PrivateFrameworks/EligibilityQuorum.framework/EligibilityQuorum

-  Functions: 3348
-  Symbols:   3483
-  CStrings:  813
+  Functions: 3401
+  Symbols:   3519
+  CStrings:  822
Symbols:
+ -[TPSPairedHomeAccessoryValidation validateWithCompletion:]
+ _HMHomeManagerHomeAccessoryAddedNotification
+ _OBJC_CLASS_$_TPSAudioIntelligenceEligibilityValidation
+ _OBJC_CLASS_$_TPSLiveRewindEligibilityValidation
+ _OBJC_CLASS_$_TPSPairedHomeAccessoryValidation
+ _OBJC_CLASS_$_TPSSiriNotesEligibilityValidation
+ _OBJC_METACLASS_$_TPSAudioIntelligenceEligibilityValidation
+ _OBJC_METACLASS_$_TPSLiveRewindEligibilityValidation
+ _OBJC_METACLASS_$_TPSPairedHomeAccessoryValidation
+ _OBJC_METACLASS_$_TPSSiriNotesEligibilityValidation
+ _TPSHMManagerHomeAccessoryAddedNotificationString
+ __DATA_TPSAudioIntelligenceEligibilityValidation
+ __DATA_TPSLiveRewindEligibilityValidation
+ __DATA_TPSSiriNotesEligibilityValidation
+ __INSTANCE_METHODS_TPSAudioIntelligenceEligibilityValidation
+ __INSTANCE_METHODS_TPSLiveRewindEligibilityValidation
+ __INSTANCE_METHODS_TPSSiriNotesEligibilityValidation
+ __IVARS_TPSAudioIntelligenceEligibilityValidation
+ __METACLASS_DATA_TPSAudioIntelligenceEligibilityValidation
+ __METACLASS_DATA_TPSLiveRewindEligibilityValidation
+ __METACLASS_DATA_TPSSiriNotesEligibilityValidation
+ __OBJC_$_INSTANCE_METHODS_TPSPairedHomeAccessoryValidation
+ __OBJC_CLASS_RO_$_TPSPairedHomeAccessoryValidation
+ __OBJC_METACLASS_RO_$_TPSPairedHomeAccessoryValidation
+ ___swift_memcpy8_8
+ _get_enum_tag_for_layout_string 10TipsDaemon38AudioIntelligenceEligibilityValidationC10QueryState025_A1BA30F774D3ACB411B24854L6CD00F8LLO
+ _kTPSCapabilityLiveRewindEligibility
+ _kTPSCapabilitySiriNotesEligibility
+ _symbolic ScTyyt_____G s5NeverO
+ _symbolic _____ 10TipsDaemon30SiriNotesEligibilityValidationC
+ _symbolic _____ 10TipsDaemon31LiveRewindEligibilityValidationC
+ _symbolic _____ 10TipsDaemon38AudioIntelligenceEligibilityValidationC
+ _symbolic _____ 10TipsDaemon38AudioIntelligenceEligibilityValidationC10QueryState025_A1BA30F774D3ACB411B24854L6CD00F8LLO
+ _symbolic _____XDXMT 10TipsDaemon38AudioIntelligenceEligibilityValidationC
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 10TipsDaemon38AudioIntelligenceEligibilityValidationC10QueryState025_A1BA30F774D3ACB411B24854N6CD00F8LLO
+ _type_layout_string 10TipsDaemon38AudioIntelligenceEligibilityValidationC10QueryState025_A1BA30F774D3ACB411B24854L6CD00F8LLO
CStrings:
+ " - eligibility query failed: "
+ " featureID not specified."
+ "51b1973014923ee0f66d37bbf33d74c526c4d29b"
+ "HomeAccessory"
+ "com.apple.AudioIntelligence"
+ "com.apple.conversation-intelligence.ambient"
+ "com.apple.conversation-intelligence.live-rewind"
+ "dbb8362d72833dd8579c3ddfeacf64829e7cecf0"
+ "ineligible - system: "
```
