## sirittsd

> `/System/Library/PrivateFrameworks/SiriTTSService.framework/sirittsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5ab8c` | `0x5bd10` | **`+0x1184`** |
| `__TEXT.__oslogstring` | `0x21cd` | `0x225d` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0x2eb0` | `0x2ee0` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0xa59` | `0xa89` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xeb8` | `0xee8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1de8` | `0x1dc0` | **`-0x28`** |
| `__TEXT.__swift5_typeref` | `0xb5a` | `0xb78` | **`+0x1e`** |
| `__DATA_CONST.__auth_got` | `0x1760` | `0x1778` | **`+0x18`** |
| `__DATA.__data` | `0x1b98` | `0x1ba8` | **`+0x10`** |
| `__TEXT.__const` | `0x1220` | `0x1230` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x1797` | `0x17a7` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x8f8` | `0x900` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0xe20` | `0xe18` | **`-0x8`** |
| `__TEXT.__swift5_capture` | `0xaa0` | `0xa98` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.113.1.0.0
+3600.123.2.11.3

-  Symbols:   1137
-  CStrings:  575
+  Symbols:   1143
+  CStrings:  578
Symbols:
+ _$s14SiriTTSService11BaseRequestC13onBehalfOfPIDs5Int32VvgTj
+ _$s14SiriTTSService11BaseRequestC13onBehalfOfPIDs5Int32VvsTj
+ _$s14SiriTTSService15FmDisableActionCAA10ActionableAAWP
+ _$s14SiriTTSService15FmDisableActionCACycfC
+ _$s14SiriTTSService15FmDisableActionCMa
+ _$s14SiriTTSService17ClientIdentifiersO19isAllowedForFmVoiceySbSSFZ
+ _$s14SiriTTSService8TTSErrorV0C4CodeO24fmSpeechGenerationFailedyA2EmFWC
+ _$s14SiriTTSService8TTSErrorV0C4CodeO9cancelledyA2EmFWC
+ _$s14SiriTTSService9LanguagesC017unsupportedOspreyC0ShySSGvgZ
+ _$s14SiriTTSService9LanguagesCMa
- _$s14SiriTTSService11BaseRequestC13onBehalfOfPIDSivgTj
- _$s14SiriTTSService11BaseRequestC13onBehalfOfPIDSivsTj
- _$s14SiriTTSService19AFMModelVersionGateO13startObserveryyFZ
- _$s14SiriTTSService29TTSAssetFMDetokenizerProviderC17subscribeIfNeeded10completionyys5Error_pSgcSg_tFTj
CStrings:
+ "#sirittsd ReaderService paragraph preempted by another speech request — pausing"
+ "Language %{public}s is not supported to use Osprey"
+ "Prefer device synthesis for premium vocalizer"
+ "getSynthesisVoiceMatching:clientId:reply:"
+ "v40@0:8@\"SiriTTSSynthesisVoice\"16@\"NSString\"24@?<v@?@\"SiriTTSSynthesisVoice\"@\"NSError\">32"
+ "v40@0:8@16@24@?32"
- "FMDetokenizer: postInstall subscription error: %@"
- "getSynthesisVoiceMatching:reply:"
- "v32@0:8@\"SiriTTSSynthesisVoice\"16@?<v@?@\"SiriTTSSynthesisVoice\"@\"NSError\">24"
```
