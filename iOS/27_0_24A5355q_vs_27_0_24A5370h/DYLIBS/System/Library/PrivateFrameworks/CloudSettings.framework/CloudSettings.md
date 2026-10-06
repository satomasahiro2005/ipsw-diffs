## CloudSettings

> `/System/Library/PrivateFrameworks/CloudSettings.framework/CloudSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x64d8` | `0x64c0` | **`-0x18`** |

### Other Changes

```text
Functions:
~ -[CloudSettingsManager performFirstTimeSetup:] : 1128 -> 1124
~ -[CloudSettingsService applyCloudSettingsToDevice:forStore:] : 912 -> 908
~ -[CloudSettingsService writeToCloudSettingsDict:forStore:] : 724 -> 720
~ -[CloudSettingsService performSmartMergeWithStoreSettings:] : 1384 -> 1380
~ -[CloudSettingsDispatchingMediator deviceSettingsForKeys:] : 560 -> 556
~ -[CloudSettingsDispatchingMediator mergeSettings:] : 1176 -> 1172
```
