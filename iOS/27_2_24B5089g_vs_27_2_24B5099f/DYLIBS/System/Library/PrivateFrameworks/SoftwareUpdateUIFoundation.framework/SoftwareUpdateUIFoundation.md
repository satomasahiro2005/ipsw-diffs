## SoftwareUpdateUIFoundation

> `/System/Library/PrivateFrameworks/SoftwareUpdateUIFoundation.framework/SoftwareUpdateUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xae414` | `0xae624` | **`+0x210`** |
| `__AUTH_CONST.__cfstring` | `0x3f80` | `0x4000` | **`+0x80`** |
| `__TEXT.__cstring` | `0x6d98` | `0x6db8` | **`+0x20`** |

### Other Changes

```diff

-772.40.11.0.0
+772.40.12.0.0

-  CStrings:  975
+  CStrings:  978
Functions:
~ _SUUIAnalyticsEventTypeToString : 140 -> 204
~ -[SUUIAnalyticsEvent initWithCoder:] : 544 -> 540
~ -[SUUIAnalyticsEvent descriptionDictionary] : 768 -> 888
~ +[SUUIAudienceTypeUtilities description:] : 192 -> 256
~ +[SUUIDownloadPhaseUtilities description:] : 192 -> 256
~ +[SUUIMDMSoftwareUpdatePathUtilities description:] : 236 -> 300
~ +[SUUISoftwareUpdateTypeUtilities description:] : 280 -> 344
~ +[SUUISoftwareUpdateVersionTypeUtilities description:] : 192 -> 256
~ _SUUIUserDefaultsEntryTypeToString : 360 -> 388
CStrings:
+ "<unknown %@: %lld>"
+ "path"
+ "phase"
```
