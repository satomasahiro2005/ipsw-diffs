## SiriTranslationIntents

> `/System/Library/PrivateFrameworks/SiriTranslationIntents.framework/SiriTranslationIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5dd2c` | `0x5f3ec` | **`+0x16c0`** |
| `__TEXT.__eh_frame` | `0x3520` | `0x3700` | **`+0x1e0`** |
| `__TEXT.__const` | `0x3d34` | `0x3e24` | **`+0xf0`** |
| `__AUTH.__data` | `0x1fe0` | `0x20a0` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x29a8` | `0x2a68` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0x2ee0` | `0x2f90` | **`+0xb0`** |
| `__AUTH_CONST.__auth_got` | `0x1308` | `0x13a8` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x18bc` | `0x1948` | **`+0x8c`** |
| `__TEXT.__swift5_typeref` | `0x10b0` | `0x1130` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x1b40` | `0x1bb0` | **`+0x70`** |
| `__DATA.__data` | `0x12f0` | `0x1350` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x1290` | `0x12e4` | **`+0x54`** |
| `__AUTH.__objc_data` | `0xc20` | `0xc70` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0xe53` | `0xe83` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x460` | `0x488` | **`+0x28`** |
| `__TEXT.__cstring` | `0x1033` | `0x1053` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x3728` | `0x3740` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x21c` | `0x234` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0xb7c` | `0xb8c` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x188` | `0x198` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x118` | `0x120` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x134` | `0x13c` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x138` | `0x140` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x29c` | `0x2a0` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x24` | `0x28` | **`+0x4`** |

### Other Changes

```diff

-3605.3.2.0.0
+3605.7.1.0.0

+  - /System/Library/PrivateFrameworks/SiriTTSService.framework/SiriTTSService

-  Functions: 2687
-  Symbols:   963
-  CStrings:  400
+  Functions: 2730
+  Symbols:   979
+  CStrings:  403
Symbols:
+ _OBJC_CLASS_$_NSLock
+ _OUTLINED_FUNCTION_134
+ _OUTLINED_FUNCTION_135
+ __DATA__TtC22SiriTranslationIntents20SpeakContinuationBox
+ __IVARS__TtC22SiriTranslationIntents20SpeakContinuationBox
+ __METACLASS_DATA__TtC22SiriTranslationIntents20SpeakContinuationBox
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
+ _symbolic $s22SiriTranslationIntents21TTSDurationEstimatingP
+ _symbolic ScCySd_____G s5NeverO
+ _symbolic ScCyyt_____G s5NeverO
+ _symbolic ScCyyt_____GSg s5NeverO
+ _symbolic So6NSLockC
+ _symbolic _____ 22SiriTranslationIntents20SpeakContinuationBoxC
+ _symbolic _____ 22SiriTranslationIntents26SystemTTSDurationEstimatorV
+ _symbolic ______p 22SiriTranslationIntents21TTSDurationEstimatingP
CStrings:
+ "Delaying translation readout %fs (intro est %fs, publish blocked %fs) so it follows the spoken intro."
+ "Estimated spoken intro duration: %fs (cutoff %fs). rdar://184314736"
+ "Skipping long spoken source intro; reading translation only. rdar://184314736"
+ "TranslatePhraseResponseFlow | Response mode is %s."
+ "estimateDuration(text:)"
- "Constructed command: %s with viewId %s and play button id %s"
- "TranslatePhraseResponseFlow | Response mode is %s, voice modes are %s."
```
