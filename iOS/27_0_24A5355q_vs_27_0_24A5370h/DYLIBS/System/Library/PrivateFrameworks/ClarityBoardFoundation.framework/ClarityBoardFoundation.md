## ClarityBoardFoundation

> `/System/Library/PrivateFrameworks/ClarityBoardFoundation.framework/ClarityBoardFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc9ec` | `0xc858` | **`-0x194`** |
| `__AUTH_CONST.__cfstring` | `0x7c0` | `0x7e0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x8cd` | `0x8e9` | **`+0x1c`** |
| `__DATA_CONST.__const` | `0x418` | `0x420` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3d8` | `0x3e0` | **`+0x8`** |

### Other Changes

```diff

-158.0.0.0.0
+161.0.0.0.0

-  Symbols:   434
-  CStrings:  92
+  Symbols:   435
+  CStrings:  93
Symbols:
+ _CLBAssistantBundleIdentifier
Functions:
~ -[CLBMobileKeybagManager _handleFirstUnlock] : 540 -> 536
~ -[CLBMobileKeybagManager _performOnQueueAndNotifyIfNeeded:] : 488 -> 484
~ sub_250f3d790 -> sub_252216788 : 280 -> 276
~ sub_250f3fdb4 -> sub_252218da8 : 116 -> 132
~ sub_250f4069c -> sub_2522196a0 : 848 -> 436
~ sub_250f41ce8 -> sub_25221ab50 : 344 -> 340
~ sub_250f41f8c -> sub_25221adf0 : 152 -> 164
~ sub_250f44290 -> sub_25221d100 : 232 -> 236
~ sub_250f45598 -> sub_25221e40c : 364 -> 356
CStrings:
+ "com.apple.AssistantServices"
```
