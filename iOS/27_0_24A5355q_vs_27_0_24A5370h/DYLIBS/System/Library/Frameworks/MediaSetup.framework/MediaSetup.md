## MediaSetup

> `/System/Library/Frameworks/MediaSetup.framework/MediaSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x126c4` | `0x1269c` | **`-0x28`** |

### Other Changes

```text
Functions:
~ -[HMHome(MediaSetup) isUpdatedForBolt] : 276 -> 272
~ -[MSServer serviceSettingDidUpdate:homeUserID:] : 388 -> 384
~ -[MSServer userDidRemoveService:homeUserID:] : 388 -> 384
~ -[MSServer userDidUpdateDefaultService:homeUserID:] : 388 -> 384
~ -[HMAccessorySettings(MediaSetup) _getMusicGroup] : 352 -> 348
~ +[MSAssistantPreferences intentExamples] : 488 -> 484
~ -[NSError(MediaSetup) CKErrorHasUnderlyingErrorCode:] : 424 -> 420
~ -[NSArray(MediaSetup) ms_anyPassingTest:] : 288 -> 284
~ _findSettingWithKeyPath : 512 -> 504
```
