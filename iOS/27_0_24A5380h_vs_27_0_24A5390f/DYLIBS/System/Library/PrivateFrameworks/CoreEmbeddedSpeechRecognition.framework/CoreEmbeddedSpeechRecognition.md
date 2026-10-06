## CoreEmbeddedSpeechRecognition

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/CoreEmbeddedSpeechRecognition`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x32793c` | `0x3265bc` | **`-0x1380`** |
| `__AUTH_CONST.__const` | `0x22cc8` | `0x227c8` | **`-0x500`** |
| `__TEXT.__swift5_capture` | `0xc89c` | `0xc68c` | **`-0x210`** |
| `__TEXT.__oslogstring` | `0xcd2d` | `0xcb3d` | **`-0x1f0`** |
| `__TEXT.__swift5_typeref` | `0x42eb` | `0x4385` | **`+0x9a`** |
| `__AUTH_CONST.__objc_const` | `0xb340` | `0xb380` | **`+0x40`** |
| `__DATA_DIRTY.__objc_data` | `0x1b90` | `0x1bb8` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x591c` | `0x5944` | **`+0x28`** |
| `__DATA.__data` | `0x23a0` | `0x23c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0xdbd4` | `0xdbf4` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x2692` | `0x26b2` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x22e0` | `0x22c8` | **`-0x18`** |
| `__TEXT.__constg_swiftt` | `0x2624` | `0x263c` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x2538` | `0x2550` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x4670` | `0x4658` | **`-0x18`** |
| `__TEXT.__swift_as_cont` | `0x6dc` | `0x6d0` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x1a78` | `0x1a70` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3618` | `0x3620` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x260` | `0x258` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x2d4` | `0x2d0` | **`-0x4`** |

### Other Changes

```diff

-3600.70.20.1.1
+3600.70.32.0.0

-  Functions: 10466
-  Symbols:   4739
-  CStrings:  2414
+  Functions: 10426
+  Symbols:   4738
+  CStrings:  2407
Symbols:
+ _symbolic SDySS_____Sg6preITN_AB04postB0tG 6Speech11TranscriberC18MultisegmentResultV
+ _symbolic SS3key______Sg6preITN_AC04postC0t5valuet 6Speech11TranscriberC18MultisegmentResultV
+ _symbolic SS3key______Sg6preITN_AC04postC0t5valuetSg 6Speech11TranscriberC18MultisegmentResultV
+ _symbolic SS______Sg6preITN_AB04postB0tt 6Speech11TranscriberC18MultisegmentResultV
+ _symbolic SaySo17ASRSchemaASRTokenCG_SaySo0aB5Tier1CGt
+ _symbolic _____Sg6preITN_AB04postB0t 6Speech11TranscriberC18MultisegmentResultV
+ _symbolic _____Sg6preITN_AB04postB0tSg 6Speech11TranscriberC18MultisegmentResultV
+ _symbolic _____ySS_____Sg6preITN_AC04postB0t_G SD8IteratorV 6Speech11TranscriberC18MultisegmentResultV
- _AFDiagnosticsSubmissionAllowed
- _symbolic SS_SaySSGt
- _symbolic SS______t 6Speech11TranscriberC18MultisegmentResultV
- _symbolic SaySDySSSaySSGGG
- _symbolic So39AFSpeechVisualContextAndCorrectionsInfoC
- _symbolic ______SSt 10Foundation4UUIDV
- _symbolic ______SStSg 10Foundation4UUIDV
- _symbolic ______pIegHzo_ s5ErrorP
- _symbolic _____ySS______G SD8IteratorV 6Speech11TranscriberC18MultisegmentResultV
CStrings:
+ "Preheating as region ID has changed"
+ "cancelPreviousRecognitionTimeout"
+ "corespeechd"
+ "performDropAndRemoveDatabase()"
+ "performDropDatabase()"
+ "performUpdateDatabase(with:)"
- "Already processing visual context, skipping"
- "Calling speech framework to compute metrics for visual context and report to SELF"
- "Could not find asrID for interaction %s"
- "Failed to get language string for locale: %s"
- "Received visual context for interactionId:%s"
- "Skipping metrics computation with visual context as both Siri opt-in (%{bool}d) and diagnostics submission (%{bool}d) must be enabled."
- "Using asrID %s and language %s to compute metrics for visual context"
- "dropAndRemoveDatabase()"
- "dropDatabase()"
- "interactionIdentifier is nil .."
- "message"
- "sender"
- "updateDatabase(with:)"
```
