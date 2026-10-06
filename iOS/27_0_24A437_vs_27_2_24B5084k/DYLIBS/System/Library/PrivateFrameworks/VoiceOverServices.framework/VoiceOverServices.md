## VoiceOverServices

> `/System/Library/PrivateFrameworks/VoiceOverServices.framework/VoiceOverServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35848` | `0x3595c` | **`+0x114`** |
| `__TEXT.__oslogstring` | `0x4c0` | `0x4f4` | **`+0x34`** |
| `__AUTH_CONST.__cfstring` | `0x92a0` | `0x92c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x7659` | `0x7672` | **`+0x19`** |

### Other Changes

```diff

-3240.9.0.0.0
+3245.7.1.0.0

-  Symbols:   3370
-  CStrings:  1238
+  Symbols:   3371
+  CStrings:  1240
Symbols:
+ _VOTLogQuickSettings
Functions:
~ -[VOSVoiceOverCommandInfo brailleCommandsForCategory:] : 144 -> 156
~ -[VOSCommand .cxx_destruct] : 80 -> 92
~ -[VOSSettingsHelper valueForSettingsItem:] : 3380 -> 3408
~ -[VOSSettingsHelper setValue:forSettingsItem:] : 4048 -> 4212
~ -[VOSSettingsHelper nameForItem:] : 1900 -> 1960
CStrings:
+ "DIRECT_TOUCH_WITH_APP"
+ "Direct Touch toggle ignored: no frontmost app on %@"
```
