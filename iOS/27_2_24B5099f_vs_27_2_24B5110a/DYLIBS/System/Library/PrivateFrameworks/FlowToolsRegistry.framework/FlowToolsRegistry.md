## FlowToolsRegistry

> `/System/Library/PrivateFrameworks/FlowToolsRegistry.framework/FlowToolsRegistry`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa8160` | `0xab018` | **`+0x2eb8`** |
| `__TEXT.__cstring` | `0x4e94` | `0x5484` | **`+0x5f0`** |
| `__TEXT.__eh_frame` | `0x2824` | `0x287c` | **`+0x58`** |
| `__AUTH_CONST.__const` | `0x36a8` | `0x36f0` | **`+0x48`** |
| `__DATA.__common` | `0x2a8` | `0x2f0` | **`+0x48`** |
| `__TEXT.__const` | `0x5808` | `0x5838` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1f28` | `0x1f50` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x950` | `0x970` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x1664` | `0x1680` | **`+0x1c`** |
| `__DATA.__bss` | `0x58e0` | `0x58f0` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x4030` | `0x4040` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x16c8` | `0x16d8` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x18bc` | `0x18c2` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0x264` | `0x268` | **`+0x4`** |

### Other Changes

```diff

-3605.30.2.0.0
+3605.31.1.11.2

-  Functions: 4080
+  Functions: 4142

-  CStrings:  545
+  CStrings:  572
CStrings:
+ "Control media playback across devices including pause, seek, skip, speed, repeat, shuffle, subtitles, and audio language"
+ "Control media playback across devices including pause, seek, skip, speed, repeat, shuffle, subtitles, and audio language."
+ "ISO 8601 duration for seek operations (e.g. PT30S)"
+ "MediaPlaybackControlAction"
+ "MediaPlaybackControls"
+ "MediaPlaybackControlsFlowTool"
+ "MediaPlaybackStreamEntity"
+ "Relative playback speed qualifier (normal, faster, slower)"
+ "SiriPlaybackControlFlowTools"
+ "SiriPlaybackControlFlowTools.flowtool"
+ "The language to set for audio or subtitles"
+ "The media playback streams to control (fetches MediaPlaybackStreamEntity)"
+ "The numeric playback speed value (e.g. 1.5, 2.0)"
+ "The playback control action to perform (fetches MediaPlaybackControlAction)"
+ "The type of language setting (audio or subtitle)"
+ "Whether the user explicitly targeted a specific device"
+ "Whether the user needs to confirm the target stream"
+ "Whether the user needs to disambiguate between multiple streams"
+ "com.apple.siri.SiriPlaybackControlAppIntentsExtension"
+ "com.apple.siri.SiriPlaybackControlAppIntentsExtension.MediaPlaybackControlsPlaceholderAppIntent"
+ "com.apple.siri.SiriPlaybackControlFlowTools"
+ "isTargetedDevice"
+ "needsConfirmation"
+ "needsDisambiguation"
+ "playbackControls"
+ "playbackSpeedNumber"
+ "playbackSpeedQualifier"
```
