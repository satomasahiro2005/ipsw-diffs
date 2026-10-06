## SiriPlaybackControlIntents

> `/System/Library/PrivateFrameworks/SiriPlaybackControlIntents.framework/SiriPlaybackControlIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24bb74` | `0x24c5ac` | **`+0xa38`** |
| `__TEXT.__oslogstring` | `0x1d696` | `0x1d7d6` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0x72d8` | `0x7200` | **`-0xd8`** |
| `__TEXT.__eh_frame` | `0x50d8` | `0x50a0` | **`-0x38`** |
| `__AUTH_CONST.__const` | `0x16538` | `0x16560` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x5b90` | `0x5bb0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x26d8` | `0x26c8` | **`-0x10`** |
| `__TEXT.__const` | `0x1ac38` | `0x1ac28` | **`-0x10`** |

### Other Changes

```diff

-3600.26.5.0.0
+3600.26.17.0.0

-  Functions: 15193
-  Symbols:   4022
-  CStrings:  2060
+  Functions: 15185
+  Symbols:   4016
+  CStrings:  2062
Symbols:
+ ___swift_closure_destructor.12Tm
- _AFIsLinwoodEnabledAndAvailable
- _OUTLINED_FUNCTION_351
- _OUTLINED_FUNCTION_352
- _OUTLINED_FUNCTION_353
- _OUTLINED_FUNCTION_354
- _OUTLINED_FUNCTION_355
- ___swift_closure_destructor.9Tm
CStrings:
+ "GetVolumeLevelHandleIntentStrategy#intentHandledResponse No now-playing app (nil/empty bundle id); returning text-only completion view to avoid an empty media platter"
+ "GetVolumeLevelHandleIntentStrategy#intentHandledResponse Now-playing app present (%{public}s); returning media player snippet"
+ "MediaControlsViewProvider.mediaPlayerSnippet System Aperture/ambient — returning nil (no result snippet)"
- "MediaControlsViewProvider.mediaPlayerSnippet creating empty media player snippet"
```
