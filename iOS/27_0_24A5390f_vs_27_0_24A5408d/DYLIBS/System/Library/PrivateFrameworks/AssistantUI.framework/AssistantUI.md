## AssistantUI

> `/System/Library/PrivateFrameworks/AssistantUI.framework/AssistantUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x65b50` | `0x65e14` | **`+0x2c4`** |
| `__TEXT.__oslogstring` | `0x5749` | `0x57f3` | **`+0xaa`** |
| `__TEXT.__cstring` | `0x89e6` | `0x8a46` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x7270` | `0x7290` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x53b0` | `0x53c0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x21a0` | `0x21b0` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x83c8` | `0x83d0` | **`+0x8`** |

### Other Changes

```diff

-3600.55.30.0.0
+3600.55.37.11.2

-  Functions: 2801
-  Symbols:   4436
-  CStrings:  1219
+  Functions: 2803
+  Symbols:   4439
+  CStrings:  1222
Symbols:
+ -[AFUISiriSession _prewarmAudioSystemForPlaybackIfNeededWithOptions:]
+ -[AFUISiriViewController tamaleViewRequestsReturnToViewfinder]
+ GCC_except_table328
+ GCC_except_table445
+ GCC_except_table446
+ GCC_except_table452
+ ___62-[AFUISiriViewController tamaleViewRequestsReturnToViewfinder]_block_invoke
- +[SRUIFSiriFeatureFlag(SWEFeatureFlags) isAssistedLinwoodVoiceResponseFromCompanionEnabled]
- GCC_except_table443
- GCC_except_table444
- GCC_except_table448
CStrings:
+ "%s #carPlay #prewarm Prewarming audio system for user-initiated prescribed invocation use case %ld before dispatching request"
+ "%s #vi tamaleViewRequestsReturnToViewfinder"
+ "-[AFUISiriSession _prewarmAudioSystemForPlaybackIfNeededWithOptions:]"
+ "-[AFUISiriViewController tamaleViewRequestsReturnToViewfinder]"
- "assisted_linwood_voice_response_from_companion"
```
