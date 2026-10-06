## SetupAssistantSupport

> `/System/Library/PrivateFrameworks/SetupAssistantSupport.framework/SetupAssistantSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16574` | `0x16554` | **`-0x20`** |

### Other Changes

```diff

-563.0.0.0.0
+565.0.0.0.0
Functions:
~ -[SASProximityCompanionAuthRequestAction idmsAccountForiCloud] : 624 -> 620
~ +[SASExpressCloudSettings createExpressSettingsWithQueue:] : 2028 -> 2024
~ +[SASExpressCloudSettings gatherExperiencesData] : 1028 -> 1024
~ -[SASExpressSettings dictionaryRepresentation] : 2312 -> 2308
~ -[SASExpressSettings writeTo:] : 1364 -> 1360
~ -[SASExpressSettings copyWithZone:] : 1620 -> 1616
~ -[SASExpressSettings mergeFrom:] : 1576 -> 1572
~ -[SASProximityInformation loadInformation] : 4948 -> 4944
```
