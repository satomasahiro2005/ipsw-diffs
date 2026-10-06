## InputAnalytics

> `/System/Library/PrivateFrameworks/InputAnalytics.framework/InputAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x8b80` | `0x91e0` | **`+0x660`** |
| `__TEXT.__cstring` | `0x5a92` | `0x5f22` | **`+0x490`** |
| `__DATA_CONST.__const` | `0x1da0` | `0x1f48` | **`+0x1a8`** |
| `__TEXT.__text` | `0x1f7e8` | `0x1f960` | **`+0x178`** |
| `__AUTH_CONST.__objc_intobj` | `0x1038` | `0x11a0` | **`+0x168`** |
| `__AUTH.__objc_data` | `0xa98` | `0xa70` | **`-0x28`** |
| `__DATA_DIRTY.__objc_data` | `0x708` | `0x730` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x258` | `0x278` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x26b4` | `0x26c4` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x4200` | `0x4208` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1240` | `0x1248` | **`+0x8`** |

### Other Changes

```diff

-141.0.0.0.0
+145.0.0.0.0

-  Functions: 1042
-  Symbols:   2595
-  CStrings:  1311
+  Functions: 1043
+  Symbols:   2650
+  CStrings:  1362
Symbols:
+ +[IASAnalyzer periodic14DayEvents]
+ _IAChannelSidecar
+ _IAPayloadKeySidecarInteractionDuration
+ _IAPayloadKeySidecarInteractionModality
+ _IAPayloadKeySidecarInteractionTranslation
+ _IAPayloadKeyWritingToolsBundleID
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
+ _OBJC_CLASS_$_NSValue
Functions:
~ -[IASignalAnalyticsObject(NSSecureCoding) initWithCoder:] : 508 -> 524
~ ___58+[IAImageGenerationAnalytics imageCreationSignalToEnumMap]_block_invoke : 1416 -> 1772
+ +[IASAnalyzer periodic14DayEvents]
CStrings:
+ "AppSwitcher"
+ "ControlInteraction"
+ "CreateImageIntent"
+ "Desktop"
+ "Dock"
+ "Duration"
+ "GeneralInteraction"
+ "GenerateImageIntent"
+ "IntentInsertText"
+ "IntentKeyPoints"
+ "IntentPresentResult"
+ "IntentProofread"
+ "IntentRequestEditingContext"
+ "IntentRewrite"
+ "IntentSummarize"
+ "IntentTransformList"
+ "IntentTransformTable"
+ "Keyboard"
+ "Modality"
+ "Mouse"
+ "PregeneratedImageCreatedMixmoji"
+ "PregeneratedImageCreatedPersonalizedImagePlayground"
+ "PregeneratedImageCreatedPersonalizedMixmoji"
+ "PregeneratedImageCreatedPlaygroundSuggestion"
+ "PregeneratedImageCreatedSavedFromMessages"
+ "PregeneratedImageRequestedCommonPhrases"
+ "PregeneratedImageRequestedContactsAvatar"
+ "PregeneratedImageRequestedContactsPoster"
+ "PregeneratedImageRequestedMixmoji"
+ "PregeneratedImageRequestedPersonalizedGenmoji"
+ "PregeneratedImageRequestedPersonalizedImagePlayground"
+ "PregeneratedImageRequestedPersonalizedMixmoji"
+ "PregeneratedImageRequestedPlaygroundSuggestion"
+ "PregeneratedImageRequestedSavedFromMessages"
+ "PregeneratedImageRequestedWallpaperPoster"
+ "SessionEnded"
+ "ShortcutsAdjustTone"
+ "ShortcutsFormatList"
+ "ShortcutsFormatTable"
+ "ShortcutsProofread"
+ "ShortcutsRewrite"
+ "ShortcutsSummarize"
+ "Sidecar"
+ "Stylus"
+ "Touch"
+ "Translation"
+ "WindowClose"
+ "WindowMinimize"
+ "WindowMove"
+ "WindowResize"
+ "WindowZoom"
```
