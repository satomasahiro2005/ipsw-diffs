## SiriUIFoundation

> `/System/Library/PrivateFrameworks/SiriUIFoundation.framework/SiriUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x910dc` | `0x916d8` | **`+0x5fc`** |
| `__AUTH.__objc_data` | `0x12e8` | `0x1170` | **`-0x178`** |
| `__DATA_DIRTY.__objc_data` | `0xdd0` | `0xf48` | **`+0x178`** |
| `__TEXT.__cstring` | `0x6796` | `0x6836` | **`+0xa0`** |
| `__DATA.__bss` | `0x4710` | `0x4680` | **`-0x90`** |
| `__DATA_DIRTY.__bss` | `0x1a8` | `0x238` | **`+0x90`** |
| `__DATA_DIRTY.__data` | `0x960` | `0x9d0` | **`+0x70`** |
| `__DATA_CONST.__got` | `0xa38` | `0xa78` | **`+0x40`** |
| `__AUTH.__data` | `0xc58` | `0xc28` | **`-0x30`** |
| `__TEXT.__oslogstring` | `0x700b` | `0x703b` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x10fa` | `0x112a` | **`+0x30`** |
| `__DATA.__common` | `0x70` | `0x48` | **`-0x28`** |
| `__DATA.__data` | `0x1790` | `0x1768` | **`-0x28`** |
| `__DATA_DIRTY.__common` | `0x60` | `0x88` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x23f0` | `0x23c8` | **`-0x28`** |
| `__AUTH_CONST.__auth_got` | `0xf20` | `0xf40` | **`+0x20`** |
| `__AUTH_CONST.__cfstring` | `0x2420` | `0x2400` | **`-0x20`** |
| `__TEXT.__const` | `0x386c` | `0x388c` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2f10` | `0x2f28` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0xf7c` | `0xf88` | **`+0xc`** |
| `__TEXT.__objc_methlist` | `0x46b0` | `0x46a8` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x178` | `0x180` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x26b0` | `0x26b8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x420` | `0x424` | **`+0x4`** |
| `__TEXT.__swift5_typeref` | `0x1590` | `0x1594` | **`+0x4`** |

### Other Changes

```diff

-3600.55.10.0.0
+3600.55.26.0.0

-  Functions: 3364
-  Symbols:   3744
-  CStrings:  1134
+  Functions: 3369
+  Symbols:   3741
+  CStrings:  1137
Symbols:
+ +[SRUIFSiriFeatureFlag(SWEFeatureFlags) isAssistedLinwoodVoiceResponseFromCompanionEnabled]
+ +[SRUIFSpeechSynthesizer _inlineStreamMarkerRequestTextForText:inlineStreamId:companionVoiceResponseEnabled:]
+ -[SRUIFVisualCaptureContext surfaces]
+ _OBJC_IVAR_$_SRUIFVisualCaptureContext._surfaces
+ _SRUIFIsCompanionVoiceResponseEnabled
+ __OBJC_$_CLASS_METHODS_SRUIFSpeechSynthesizer
+ ___block_descriptor_72_e8_32s40bs48bs56w64w_e21_v16?0"AFVoiceInfo"8lw56l8w64l8s32l8s40l8s48l8
+ _symbolic _____Sg 14SiriTTSService16SynthesisContextC15VoicePacePresetO
+ _symbolic _____Sg 14SiriTTSService16SynthesisContextC23VoiceExpressivityPresetO
- +[SRUIFVisualCaptureContext supportsSecureCoding]
- -[SRUIFVisualCaptureContext description]
- -[SRUIFVisualCaptureContext encodeWithCoder:]
- -[SRUIFVisualCaptureContext initWithCoder:]
- _OBJC_CLASS_$_NSKeyedArchiver
- _OBJC_CLASS_$_NSKeyedUnarchiver
- __OBJC_$_CLASS_METHODS_SRUIFVisualCaptureContext
- __OBJC_$_CLASS_PROP_LIST_SRUIFVisualCaptureContext
- __OBJC_CLASS_PROTOCOLS_$_SRUIFVisualCaptureContext
- ___block_descriptor_80_e8_32s40s48bs56bs64w72w_e21_v16?0"AFVoiceInfo"8lw64l8w72l8s32l8s40l8s48l8s56l8
- _get_type_metadata s8SendableRzsAAR_r0_l15Synchronization5MutexVyytG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "%@%@\\%@"
+ "%s #tts inline-stream marker+text from streamId: %@"
+ "+[SRUIFSpeechSynthesizer _inlineStreamMarkerRequestTextForText:inlineStreamId:companionVoiceResponseEnabled:]"
+ "GenerateCompanionVoiceResponse"
+ "assisted_linwood_voice_response_from_companion"
- "SRUIFVisualCaptureContext %@"
- "_data"
```
