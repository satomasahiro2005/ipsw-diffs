## InputAnalytics

> `/System/Library/PrivateFrameworks/InputAnalytics.framework/InputAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f9f0` | `0x1fbdc` | **`+0x1ec`** |
| `__AUTH_CONST.__cfstring` | `0x92a0` | `0x9480` | **`+0x1e0`** |
| `__TEXT.__cstring` | `0x5fd2` | `0x61a2` | **`+0x1d0`** |
| `__DATA_CONST.__const` | `0x1f78` | `0x1ff0` | **`+0x78`** |
| `__AUTH_CONST.__objc_intobj` | `0x1230` | `0x1260` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x608` | `0x628` | **`+0x20`** |
| `__DATA.__bss` | `0x128` | `0x138` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1248` | `0x1250` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x26c4` | `0x26cc` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x988` | `0x980` | **`-0x8`** |

### Other Changes

```diff

-147.0.0.0.0
+153.0.0.0.0

-  Functions: 1043
-  Symbols:   2656
-  CStrings:  1368
+  Functions: 1046
+  Symbols:   2675
+  CStrings:  1383
Symbols:
+ +[IAGenmojiAnalytics genmojiSignalToEnumMap]
+ _IAPayloadKeyImageGenerationAssetID
+ _IAPayloadKeyImageGenerationUnredactedStyle
+ _IAPayloadKeyPencilSystemDisplayIdentifier
+ _IASignalGenmojiPregeneratedImageUsedCommonPhrases
+ _IASignalGenmojiPregeneratedImageUsedContactsAvatar
+ _IASignalGenmojiPregeneratedImageUsedContactsPoster
+ _IASignalGenmojiPregeneratedImageUsedMixmoji
+ _IASignalGenmojiPregeneratedImageUsedPersonalizedGenmoji
+ _IASignalGenmojiPregeneratedImageUsedPersonalizedImagePlayground
+ _IASignalGenmojiPregeneratedImageUsedPersonalizedMixmoji
+ _IASignalGenmojiPregeneratedImageUsedPlaygroundSuggestion
+ _IASignalGenmojiPregeneratedImageUsedSavedFromMessages
+ _IASignalGenmojiPregeneratedImageUsedWallpaperPoster
+ _IASignalImageGenerationPCCImageGenerated
+ _IASignalImageGenerationPIRImageGenerated
+ ___44+[IAGenmojiAnalytics genmojiSignalToEnumMap]_block_invoke
+ _genmojiSignalToEnumMap.mapping
+ _genmojiSignalToEnumMap.onceToken
CStrings:
+ "AssetID"
+ "PCCImageGenerated"
+ "PIRImageGenerated"
+ "PregeneratedImageUsedCommonPhrases"
+ "PregeneratedImageUsedContactsAvatar"
+ "PregeneratedImageUsedContactsPoster"
+ "PregeneratedImageUsedMixmoji"
+ "PregeneratedImageUsedPersonalizedGenmoji"
+ "PregeneratedImageUsedPersonalizedImagePlayground"
+ "PregeneratedImageUsedPersonalizedMixmoji"
+ "PregeneratedImageUsedPlaygroundSuggestion"
+ "PregeneratedImageUsedSavedFromMessages"
+ "PregeneratedImageUsedWallpaperPoster"
+ "UnredactedStyle"
+ "systemDisplayIdentifier"
```
