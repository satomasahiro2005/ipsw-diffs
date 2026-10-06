## InputAnalyticsServer

> `/System/Library/PrivateFrameworks/InputAnalyticsServer.framework/InputAnalyticsServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x74ab8` | `0x7b324` | **`+0x686c`** |
| `__AUTH_CONST.__objc_const` | `0x9de8` | `0xa498` | **`+0x6b0`** |
| `__TEXT.__cstring` | `0x5ab7` | `0x6152` | **`+0x69b`** |
| `__AUTH_CONST.__cfstring` | `0x5fc0` | `0x6540` | **`+0x580`** |
| `__TEXT.__oslogstring` | `0x7373` | `0x7810` | **`+0x49d`** |
| `__TEXT.__objc_methlist` | `0x5c54` | `0x605c` | **`+0x408`** |
| `__AUTH_CONST.__objc_intobj` | `0x1458` | `0x1770` | **`+0x318`** |
| `__DATA_CONST.__got` | `0x1630` | `0x18c0` | **`+0x290`** |
| `__DATA_DIRTY.__objc_data` | `0x1ab8` | `0x1d10` | **`+0x258`** |
| `__DATA_DIRTY.__bss` | `0x428` | `0x678` | **`+0x250`** |
| `__AUTH_CONST.__const` | `0x12c8` | `0x14b8` | **`+0x1f0`** |
| `__DATA.__bss` | `0x8d0` | `0x730` | **`-0x1a0`** |
| `__DATA_CONST.__const` | `0x14a8` | `0x1638` | **`+0x190`** |
| `__DATA_CONST.__objc_selrefs` | `0x2f20` | `0x30a0` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0x1660` | `0x1778` | **`+0x118`** |
| `__DATA_DIRTY.__data` | `0x140` | `0x240` | **`+0x100`** |
| `__TEXT.__gcc_except_tab` | `0xcb0` | `0xd64` | **`+0xb4`** |
| `__DATA.__data` | `0x588` | `0x4e8` | **`-0xa0`** |
| `__AUTH.__objc_data` | `0xa10` | `0xa88` | **`+0x78`** |
| `__AUTH_CONST.__auth_got` | `0xb78` | `0xbf0` | **`+0x78`** |
| `__DATA_CONST.__objc_classlist` | `0x380` | `0x3c8` | **`+0x48`** |
| `__TEXT.__const` | `0xa18` | `0xa50` | **`+0x38`** |
| `__AUTH.__data` | `0x50` | `0x28` | **`-0x28`** |
| `__DATA.__objc_ivar` | `0x71c` | `0x738` | **`+0x1c`** |
| `__TEXT.__swift5_typeref` | `0x297` | `0x2aa` | **`+0x13`** |

### Other Changes

```diff

-141.0.0.0.0
+145.0.0.0.0

+  - /usr/lib/swift/libswiftRegexBuilder.dylib

-  Functions: 2669
-  Symbols:   913
-  CStrings:  1369
+  Functions: 2786
+  Symbols:   968
+  CStrings:  1444
Symbols:
+ _CFPreferencesCopyAppValue
+ _IAChannelSidecar
+ _IAPayloadKeySidecarInteractionDuration
+ _IAPayloadKeySidecarInteractionModality
+ _IAPayloadKeySidecarInteractionTranslation
+ _IAPayloadValueImageGenerationFeatureUnspecified
+ _IAPayloadValueImageGenerationStartActionCreateImageIntent
+ _IAPayloadValueImageGenerationStartActionGenerateImageIntent
+ _IAPayloadValueSidecarInteractionModalityKeyboard
+ _IAPayloadValueSidecarInteractionModalityMouse
+ _IAPayloadValueSidecarInteractionModalityStylus
+ _IAPayloadValueSidecarInteractionModalityTouch
+ _IASignalImageGenerationPregeneratedImageCreatedMixmoji
+ _IASignalImageGenerationPregeneratedImageCreatedPersonalizedImagePlayground
+ _IASignalImageGenerationPregeneratedImageCreatedPersonalizedMixmoji
+ _IASignalImageGenerationPregeneratedImageCreatedPlaygroundSuggestion
+ _IASignalImageGenerationPregeneratedImageCreatedSavedFromMessages
+ _IASignalImageGenerationPregeneratedImageRequestedCommonPhrases
+ _IASignalImageGenerationPregeneratedImageRequestedContactsAvatar
+ _IASignalImageGenerationPregeneratedImageRequestedContactsPoster
+ _IASignalImageGenerationPregeneratedImageRequestedMixmoji
+ _IASignalImageGenerationPregeneratedImageRequestedPersonalizedGenmoji
+ _IASignalImageGenerationPregeneratedImageRequestedPersonalizedImagePlayground
+ _IASignalImageGenerationPregeneratedImageRequestedPersonalizedMixmoji
+ _IASignalImageGenerationPregeneratedImageRequestedPlaygroundSuggestion
+ _IASignalImageGenerationPregeneratedImageRequestedSavedFromMessages
+ _IASignalImageGenerationPregeneratedImageRequestedWallpaperPoster
+ _IASignalSidecarAppSwitcher
+ _IASignalSidecarControlInteraction
+ _IASignalSidecarDesktop
+ _IASignalSidecarDock
+ _IASignalSidecarGeneralInteraction
+ _IASignalSidecarMenuBar
+ _IASignalSidecarSessionEnded
+ _IASignalSidecarWindowClose
+ _IASignalSidecarWindowMinimize
+ _IASignalSidecarWindowMove
+ _IASignalSidecarWindowResize
+ _IASignalSidecarWindowZoom
+ _IASignalWritingToolsIntentInsertText
+ _IASignalWritingToolsIntentKeyPoints
+ _IASignalWritingToolsIntentPresentResult
+ _IASignalWritingToolsIntentProofread
+ _IASignalWritingToolsIntentRequestEditingContext
+ _IASignalWritingToolsIntentRewrite
+ _IASignalWritingToolsIntentSummarize
+ _IASignalWritingToolsIntentTransformList
+ _IASignalWritingToolsIntentTransformTable
+ _IASignalWritingToolsShortcutsAdjustTone
+ _IASignalWritingToolsShortcutsFormatList
+ _IASignalWritingToolsShortcutsFormatTable
+ _IASignalWritingToolsShortcutsProofread
+ _IASignalWritingToolsShortcutsRewrite
+ _IASignalWritingToolsShortcutsSummarize
+ _OBJC_CLASS_$_TIPreferencesController
+ _swift_release_x19
+ _swift_retain_x25
- _swift_release_x24
- _swift_retain_x24
CStrings:
+ "%{private}@ periodic14DayEvents called. Will call %{private}@"
+ "(?m)[ \\t]*\\([A-Za-z]{3}, (\\d{1,2}) ([A-Za-z]{3}) \\d{4} (\\d{2}):(\\d{2}):\\d{2}\\)$"
+ "3rd_party"
+ "AppCanShowSiriSuggestionsBlacklist"
+ "Created substitute analytics session ID for session-starter %{private}@"
+ "Creating analyzer on CAPE/Siri panel intent invocation"
+ "Creating analyzer on Shortcuts invocation"
+ "DELETE FROM %@"
+ "Display name of file attachment on the Report a Concern form for Smart Actions feedback. The attachment contains the conversation used to generate the smart action; the format argument is the number of messages in the conversation."
+ "Display name of file attachment on the Report a Concern form for Smart Actions feedback. The attachment contains the email used to generate the smart action."
+ "Display name of file attachment on the Report a Concern form for Smart Actions feedback. The attachment contains the voicemail used to generate the smart action."
+ "Document Language:"
+ "Failed to prepare reset statement: %{private}s"
+ "Failed to update lifecycle usage for signal: %@ %@"
+ "IASSidecar"
+ "IASSidecarAnalyzerDataStoreLifecycleTable"
+ "IASSidecarAnalyzerDataStoreUsageTable"
+ "IASSmartActionsEnablement"
+ "Ignoring lifecycle usage for signal: %@ %@"
+ "Multiple analyzers (%lu) tried to claim PanelAppeared; associating latest requester %{private}@ and terminating the rest (%{sensitive}@)"
+ "Name of file attachment on the Report a Concern form where users share feedback with Apple. The Input attachment contains the email, voicemail, or conversation used to generate a smart action."
+ "Received signal: %@ without expected payload"
+ "SidecarLifecycleAnalytics"
+ "Signal: %@ failed to update data store"
+ "Signal: %@ unknown modality %@"
+ "Signal: %@ unknown signal"
+ "Visual Generation"
+ "[%{private}@] Biome: Shortcuts/Siri session, will skip Requests event"
+ "^Person([A-Z]+|[0-9]+)"
+ "accidentalCount"
+ "com.apple.FaceTime"
+ "com.apple.facetime"
+ "com.apple.inputAnalytics.server.IASSidecarAnalyzer"
+ "com.apple.inputAnalytics.server.IASSmartActionsEnablement"
+ "com.apple.inputAnalytics.sidecar"
+ "com.apple.intelligence.CommonEvent"
+ "com.apple.mobilephone"
+ "com.apple.settings.smartActionEnablement"
+ "com.apple.suggestions"
+ "content_applied"
+ "content_engaged"
+ "content_presented"
+ "copy"
+ "currently_enabled"
+ "didAction received CAPE/Siri invocation with existing session ID. Letting existing analyzer handle it %{sensitive}@"
+ "didAction received Shortcuts invocation with existing session ID. Letting existing analyzer handle it %{sensitive}@"
+ "distance"
+ "duplicate"
+ "duration"
+ "facetime voicemail"
+ "handleSidecarSignal:%@, bundleID=%@, timestamp=%f"
+ "initiated_by"
+ "input_mode"
+ "insert"
+ "intentionalCount"
+ "keyboard suggestions"
+ "lifecycle"
+ "mail"
+ "messages"
+ "modality"
+ "periodic14DayEvents called"
+ "periodic14DayEvents completed"
+ "periodic14DayEvents has nil server"
+ "periodic14DayEvents was unable to convert weak reference to strong within block"
+ "periodic14DayEvents: periodic14DayEvents"
+ "periodic24HourEvents: IASSmartActionsEnablement: Caught %{private}@"
+ "person"
+ "reportSmartActionsEnablement: %{public}@ currently_enabled %{private}ld"
+ "request_dismissed"
+ "request_failed"
+ "request_made"
+ "result_surface"
+ "share"
+ "smart_action"
+ "sub_feature"
+ "text"
+ "version_id"
+ "voicemail"
- "Created substitute analytics session ID for PanelRequested %{private}@"
- "Multiple analyzers (%lu) tried to claim PanelAppeared (%{sensitive}@)"
- "Name of file attachment on the Report a Concern form where users share feedback with Apple. The Input attachment contains the email, voicemail, or conversation used to generate a smart action"
```
