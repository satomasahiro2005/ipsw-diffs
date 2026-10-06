## SiriPlaybackControlIntents

> `/System/Library/PrivateFrameworks/SiriPlaybackControlIntents.framework/SiriPlaybackControlIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24c550` | `0x24ce10` | **`+0x8c0`** |
| `__TEXT.__oslogstring` | `0x1d7d6` | `0x1d976` | **`+0x1a0`** |
| `__AUTH_CONST.__const` | `0x16560` | `0x16618` | **`+0xb8`** |
| `__TEXT.__eh_frame` | `0x50a0` | `0x5154` | **`+0xb4`** |
| `__TEXT.__swift5_capture` | `0x5bb0` | `0x5be4` | **`+0x34`** |
| `__TEXT.__const` | `0x1ac28` | `0x1ac48` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x26c8` | `0x26e0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x7210` | `0x7228` | **`+0x18`** |
| `__DATA.__data` | `0x43d8` | `0x43e8` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x6c24` | `0x6c34` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x60e8` | `0x60f8` | **`+0x10`** |
| `__AUTH.__data` | `0x7298` | `0x72a0` | **`+0x8`** |
| `__AUTH.__objc_data` | `0x58e0` | `0x58e8` | **`+0x8`** |

### Other Changes

```diff

-3600.26.17.0.0
+3605.12.1.0.0

-  Functions: 15196
-  Symbols:   4017
-  CStrings:  2062
+  Functions: 15218
+  Symbols:   4024
+  CStrings:  2066
Symbols:
+ _AFIsLinwoodEnabledAndAvailable
+ _OUTLINED_FUNCTION_352
+ _OUTLINED_FUNCTION_353
+ _OUTLINED_FUNCTION_354
+ _OUTLINED_FUNCTION_355
+ _OUTLINED_FUNCTION_356
+ ___swift_closure_destructor.138Tm
+ _symbolic _____ySb_____G s6ResultOsRi_zRi0_zrlE 26SiriPlaybackControlSupport13LanguageErrorO
- ___swift_closure_destructor.137Tm
CStrings:
+ "No device queries in intent but %ld streams playing. Returning multipleStreamsPlaying"
+ "PauseMediaHandleIntentStrategy.makeIntentHandledResponse() suppressSnippet=%s shouldSuppressSnippet=%s"
+ "SiriPlaybackControlsOutputProvider.mediaPlayerSnippetOutput Missing snippet and empty dialog, returning EmptyOutput"
+ "fetchSubtitleActiveState failed with error: %s; attempting disable anyway"
+ "nowPlaying is .audio with no declared subtype. Requested %{public}s treated as a match: %{bool}d"
- "PauseMediaHandleIntentStrategy.makeIntentHandledResponse() suppressSnippet=%s shouldBuildSnippet=%s"
```
