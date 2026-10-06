## PriMLETL

> `/System/Library/PrivateFrameworks/PriMLETL.framework/PriMLETL`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb85d4` | `0xb8570` | **`-0x64`** |
| `__DATA.__data` | `0x1868` | `0x1838` | **`-0x30`** |
| `__TEXT.__const` | `0x8f58` | `0x8f28` | **`-0x30`** |
| `__TEXT.__swift5_typeref` | `0x1b55` | `0x1b25` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x188` | `0x1a8` | **`+0x20`** |

### Other Changes

```diff

-31.0.0.0.0
+35.0.0.0.0

+  - /usr/lib/swift/libswiftAVFoundation.dylib

+  - /usr/lib/swift/libswiftAppleArchive.dylib
+  - /usr/lib/swift/libswiftCompression.dylib

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

-  Symbols:   1056
+  Symbols:   1058
Symbols:
+ __swift_FORCE_LOAD_$_swiftAVFoundation
+ __swift_FORCE_LOAD_$_swiftAVFoundation_$_PriMLETL
+ __swift_FORCE_LOAD_$_swiftAppleArchive
+ __swift_FORCE_LOAD_$_swiftAppleArchive_$_PriMLETL
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCompression_$_PriMLETL
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ __swift_FORCE_LOAD_$_swiftCoreMIDI_$_PriMLETL
- _symbolic _____Sg 8PriMLETL20ExtractSmsParametersV
- _symbolic _____Sg 8PriMLETL22ExtractEmailParametersV
- _symbolic _____Sg 8PriMLETL26ExtractSpotlightParametersV
- _symbolic _____Sg 8PriMLETL30ExtractGenmojiPromptParametersV
- _symbolic _____Sg 8PriMLETL33ExtractSiriConversationParametersV
- _symbolic _____Sg 8PriMLETL39ExtractSpotlightNotificationsParametersV
Functions:
~ sub_292d2b1f4 -> sub_297635314 : 4240 -> 4148
~ sub_292d4449c -> sub_29764e560 : 580 -> 576
~ sub_292d4bb20 -> sub_297655be0 : 968 -> 964
~ sub_292d4bee8 -> sub_297655fa4 : 1032 -> 1020
~ sub_292d4c9f8 -> sub_297656aa8 : 392 -> 388
~ sub_292d4cb80 -> sub_297656c2c : 392 -> 388
~ sub_292d69e88 -> sub_297673f30 : 344 -> 324
~ sub_292d7182c -> sub_29767b8c0 : 544 -> 540
~ sub_292d77520 -> sub_2976815b0 : 856 -> 880
~ sub_292d80048 -> sub_29768a0f0 : 1524 -> 1556
~ sub_292d8fb28 -> sub_297699bf0 : 1504 -> 1492
```
