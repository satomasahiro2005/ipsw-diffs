## AssistantUI

> `/System/Library/PrivateFrameworks/AssistantUI.framework/AssistantUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x65990` | `0x65a98` | **`+0x108`** |
| `__TEXT.__objc_methlist` | `0x71d8` | `0x7238` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x579a` | `0x5749` | **`-0x51`** |
| `__TEXT.__cstring` | `0x89f6` | `0x89b6` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x1b78` | `0x1ba0` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x1200` | `0x121c` | **`+0x1c`** |
| `__AUTH_CONST.__objc_const` | `0x83a0` | `0x83b8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x5380` | `0x5398` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2190` | `0x21a0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xc50` | `0xc48` | **`-0x8`** |

### Other Changes

```diff

-3600.49.31.1.6
+3600.55.10.0.0

-  Functions: 2793
-  Symbols:   4425
-  CStrings:  1219
+  Functions: 2798
+  Symbols:   4430
+  CStrings:  1218
Symbols:
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isSiriReadThisV3Enabled]
+ -[AFUISiriSession _handleDidChangeAudioRecordingPowerWithPeakLevel:frequencyBands:]
+ -[AFUISiriSession audioPowerUpdaterDidUpdate:averagePower:peakPower:frequencyBands:]
+ -[AFUISiriViewController siriSessionAudioRecordingDidChangePowerLevel:peakLevel:frequencyBands:]
+ GCC_except_table155
+ GCC_except_table184
+ GCC_except_table185
+ GCC_except_table216
+ GCC_except_table218
+ GCC_except_table227
+ GCC_except_table231
+ GCC_except_table268
+ GCC_except_table277
+ GCC_except_table297
+ GCC_except_table397
+ GCC_except_table400
+ GCC_except_table413
+ GCC_except_table416
+ GCC_except_table418
+ GCC_except_table425
+ GCC_except_table427
+ GCC_except_table429
+ GCC_except_table431
+ GCC_except_table439
+ GCC_except_table444
+ GCC_except_table448
+ GCC_except_table450
+ _AFIsLinwoodEnabledAndWasEverAvailable
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SRUIFAudioPowerLevelUpdaterDelegate
+ ___83-[AFUISiriSession _handleDidChangeAudioRecordingPowerWithPeakLevel:frequencyBands:]_block_invoke
+ ___block_descriptor_52_e8_32s40w_e35_v16?0"<AFUISiriSessionDelegate>"8lw40l8s32l8
- GCC_except_table182
- GCC_except_table183
- GCC_except_table213
- GCC_except_table215
- GCC_except_table217
- GCC_except_table219
- GCC_except_table224
- GCC_except_table228
- GCC_except_table251
- GCC_except_table294
- GCC_except_table322
- GCC_except_table396
- GCC_except_table399
- GCC_except_table412
- GCC_except_table415
- GCC_except_table417
- GCC_except_table424
- GCC_except_table426
- GCC_except_table428
- GCC_except_table430
- GCC_except_table437
- GCC_except_table442
- GCC_except_table447
- GCC_except_table449
- _AFIsLinwoodEnabled
- _AFIsLinwoodEnabledAndAvailable
CStrings:
+ "siri_read_this_v3"
- "%s #statefeedback not passing along speech end estimate due to ui free view mode"
- "-[AFUISiriSession assistantConnectionUpdatedSpeechEndEstimate:speechEndEstimate:]"
```
