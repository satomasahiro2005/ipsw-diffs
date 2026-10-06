## NanoHomeScreenServices

> `/System/Library/PrivateFrameworks/NanoHomeScreenServices.framework/NanoHomeScreenServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5058` | `0x5194` | **`+0x13c`** |
| `__TEXT.__oslogstring` | `0x408` | `0x4b6` | **`+0xae`** |
| `__TEXT.__const` | `0x7a` | `0x82` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x280` | `0x278` | **`-0x8`** |

### Other Changes

```diff

-337.0.0.0.0
+348.0.0.0.0

-  Symbols:   387
-  CStrings:  74
+  Symbols:   389
+  CStrings:  78
Symbols:
+ _objc_release_x26
+ _objc_release_x28
Functions:
~ -[NHSSSmartStackSuggestionDefaults setWidgetSuggestionsUnmuteDate:forContainerBundleIdentifier:extensionBundleIdentifier:kind:] : 264 -> 404
~ -[NHSSSmartStackSuggestionDefaults _cleanUpExpiredMutePreferences] : 448 -> 560
~ ___78-[NHSSSmartStackSuggestionDefaults _scheduleTimerToUnmuteWidgetForKey:onDate:]_block_invoke : 200 -> 264
CStrings:
+ "mute cleared for %{public}@"
+ "mute set for %{public}@ until %{public}@"
+ "pruning expired mute for %{public}@ (expired %{public}@)"
+ "unmute timer fired, mute removed for %{public}@"
```
