## FlowToolsRegistry

> `/System/Library/PrivateFrameworks/FlowToolsRegistry.framework/FlowToolsRegistry`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa9e84` | `0xa4b38` | **`-0x534c`** |
| `__DATA.__bss` | `0x5be0` | `0x6540` | **`+0x960`** |
| `__TEXT.__cstring` | `0x5634` | `0x4d44` | **`-0x8f0`** |
| `__TEXT.__const` | `0x53c8` | `0x5828` | **`+0x460`** |
| `__DATA_DIRTY.__common` | `0x1538` | `0x13b8` | **`-0x180`** |
| `__AUTH_CONST.__const` | `0x3600` | `0x3710` | **`+0x110`** |
| `__TEXT.__swift5_typeref` | `0x17dc` | `0x18b4` | **`+0xd8`** |
| `__DATA_DIRTY.__bss` | `0x33a0` | `0x32f0` | **`-0xb0`** |
| `__TEXT.__constg_swiftt` | `0x15f0` | `0x1680` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x1638` | `0x16c0` | **`+0x88`** |
| `__DATA.__data` | `0x6e0` | `0x738` | **`+0x58`** |
| `__TEXT.__swift5_reflstr` | `0xcc4` | `0xd14` | **`+0x50`** |
| `__DATA.__common` | `0xd0` | `0x88` | **`-0x48`** |
| `__TEXT.__swift5_proto` | `0x484` | `0x4cc` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x248` | `0x208` | **`-0x40`** |
| `__TEXT.__eh_frame` | `0x2880` | `0x2848` | **`-0x38`** |
| `__TEXT.__swift5_capture` | `0x950` | `0x920` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x1e88` | `0x1ea8` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x258` | `0x268` | **`+0x10`** |

### Other Changes

```diff

-3600.59.31.1.2
+3600.65.8.0.0

-  Functions: 4060
+  Functions: 4011

-  CStrings:  575
+  CStrings:  531
CStrings:
+ "SiriVideoMovieEntity"
+ "SiriVideoTvEpisodeEntity"
+ "SiriVideoTvSeasonEntity"
+ "SiriVideoTvShowEntity"
+ "optionalWithDefault"
+ "optionalWithoutDefault"
- "Control media playback across devices including pause, seek, skip, speed, repeat, shuffle, subtitles, and audio language"
- "Control media playback across devices including pause, seek, skip, speed, repeat, shuffle, subtitles, and audio language."
- "Create Incoming Geofence"
- "Create Outgoing Geofence"
- "Create an incoming geofence notification for a person at a location."
- "Create an outgoing geofence notification for a person at a location."
- "CreateIncomingGeofenceTool"
- "CreateOutgoingGeofenceTool"
- "Find Item Location"
- "Find the location of a Find My item."
- "FindItemLocationTool"
- "ISO 8601 duration for seek operations (e.g. PT30S)"
- "MediaPlaybackControlAction"
- "MediaPlaybackControls"
- "MediaPlaybackControlsFlowTool"
- "MediaPlaybackStreamEntity"
- "Play a sound on a Find My item."
- "PlayItemSoundTool"
- "Relative playback speed qualifier (normal, faster, slower)"
- "SiriFindMyFlowTools"
- "SiriFindMyFlowTools.flowtool"
- "SiriPlaybackControlFlowTools"
- "SiriPlaybackControlFlowTools.flowtool"
- "The item to find the location of"
- "The item to play a sound on"
- "The language to set for audio or subtitles"
- "The location for the geofence"
- "The media playback streams to control (fetches MediaPlaybackStreamEntity)"
- "The numeric playback speed value (e.g. 1.5, 2.0)"
- "The person to create a geofence for"
- "The playback control action to perform (fetches MediaPlaybackControlAction)"
- "The trigger condition for the geofence"
- "The type of language setting (audio or subtitle)"
- "VideoSearchEntity"
- "Whether the geofence notification is recurring"
- "Whether the user explicitly targeted a specific device"
- "Whether the user needs to confirm the target stream"
- "Whether the user needs to disambiguate between multiple streams"
- "com.apple.findmy"
- "com.apple.siri.-MediaIntents-AppIntents.MediaIntents"
- "com.apple.siri.SiriPlaybackControlAppIntentsExtension"
- "com.apple.siri.SiriPlaybackControlAppIntentsExtension.MediaPlaybackControlsPlaceholderAppIntent"
- "com.apple.siri.SiriPlaybackControlFlowTools"
- "com.apple.siri.findmy.SiriFindMyFlowTools"
- "isTargetedDevice"
- "needsConfirmation"
- "needsDisambiguation"
- "playbackControls"
- "playbackSpeedNumber"
- "playbackSpeedQualifier"
```
