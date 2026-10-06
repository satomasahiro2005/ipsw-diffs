## CarouselPreferenceServices

> `/System/Library/PrivateFrameworks/CarouselPreferenceServices.framework/CarouselPreferenceServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x286dc` | `0x2874c` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x32a0` | `0x3300` | **`+0x60`** |
| `__TEXT.__cstring` | `0x2bab` | `0x2bf1` | **`+0x46`** |
| `__DATA_CONST.__const` | `0x1280` | `0x1290` | **`+0x10`** |
| `__TEXT.__const` | `0x360` | `0x368` | **`+0x8`** |

### Other Changes

```diff

-1115.0.105.0.0
+1115.1.4.0.0

-  CStrings:  622
+  CStrings:  625
Functions:
~ sub_237f39dc0 -> sub_23c732dc0 : 172 -> 176
~ _CSLActionTypeToSettingsActionType : 284 -> 312
~ +[CSLPRFStingSettingsModel actionNameForActionType:] : 676 -> 716
~ -[CSLPRFStingSettingsModel _buildDefaultActionTypeItems] : 700 -> 740
CStrings:
+ "CreateVoiceNote"
+ "STING_ACTION_TYPE_VOICE_NOTE"
+ "com.apple.readiness"
+ "text.pad.header.badge.waveform"
- "com.apple.cobalt.watchapp"
```
