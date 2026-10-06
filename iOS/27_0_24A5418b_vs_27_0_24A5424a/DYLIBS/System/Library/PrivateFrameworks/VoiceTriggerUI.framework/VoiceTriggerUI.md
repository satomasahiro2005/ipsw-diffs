## VoiceTriggerUI

> `/System/Library/PrivateFrameworks/VoiceTriggerUI.framework/VoiceTriggerUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6bf30` | `0x6c07c` | **`+0x14c`** |
| `__TEXT.__cstring` | `0x5e15` | `0x5e45` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x2ea0` | `0x2ec0` | **`+0x20`** |

### Other Changes

```diff

-3600.16.8.11.1
+3600.16.8.11.101

-  CStrings:  856
+  CStrings:  857
Functions:
~ -[VTUIDictationDataSharingOptInPresenter dataSharingOptInView] : 780 -> 828
~ -[VTUISiriDataSharingOptInPresenter _modalViewControllerForViewStyle:] : 768 -> 816
~ -[VTUIProximityDataSharingOptInView _setupContent] : 1472 -> 1708
CStrings:
+ "DATA_SHARING_CONFIRMATION_BUTTON_TITLE_GM"
+ "DATA_SHARING_DETAIL_VISION_GM"
- "DATA_SHARING_DETAIL"
```
