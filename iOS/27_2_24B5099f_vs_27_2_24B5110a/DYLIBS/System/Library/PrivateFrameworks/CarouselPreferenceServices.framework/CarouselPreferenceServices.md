## CarouselPreferenceServices

> `/System/Library/PrivateFrameworks/CarouselPreferenceServices.framework/CarouselPreferenceServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2874c` | `0x286dc` | **`-0x70`** |
| `__AUTH_CONST.__cfstring` | `0x3300` | `0x32a0` | **`-0x60`** |
| `__TEXT.__cstring` | `0x2bf1` | `0x2ba5` | **`-0x4c`** |
| `__DATA.__bss` | `0x2c0` | `0x2d0` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1290` | `0x1280` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x80` | `0x70` | **`-0x10`** |
| `__TEXT.__const` | `0x368` | `0x360` | **`-0x8`** |

### Other Changes

```diff

-1115.1.8.0.0
+1115.1.11.0.0

-  CStrings:  625
+  CStrings:  622
Functions:
~ sub_23bcd7dc0 -> sub_23c8b1dc0 : 176 -> 172
~ _CSLActionTypeToSettingsActionType : 312 -> 284
~ +[CSLPRFStingSettingsModel actionNameForActionType:] : 716 -> 676
~ -[CSLPRFStingSettingsModel _buildDefaultActionTypeItems] : 740 -> 700
CStrings:
- "CreateVoiceNote"
- "STING_ACTION_TYPE_VOICE_NOTE"
- "text.pad.header.badge.waveform"
```
