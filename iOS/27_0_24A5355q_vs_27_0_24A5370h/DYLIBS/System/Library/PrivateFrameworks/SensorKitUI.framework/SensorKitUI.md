## SensorKitUI

> `/System/Library/PrivateFrameworks/SensorKitUI.framework/SensorKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbbd8` | `0xbb94` | **`-0x44`** |

### Other Changes

```diff

-1025.0.0.0.0
+1027.0.0.0.0
Functions:
~ -[SRAuthorizationGroup localizedCollectedData] : 316 -> 312
~ -[SRAuthorizationGroup localizedNotCollectedData] : 316 -> 312
~ -[SRAuthorizationGroup localizedWhenShared] : 316 -> 312
~ -[SRAuthorizationGroup localizedWhatIsShared] : 316 -> 312
~ -[SRAuthorizationGroup localizedPlatforms] : 596 -> 592
~ -[SRAuthorizationGroup localizedSampleData] : 320 -> 316
~ -[SRAuthorizationGroup localizedExampleDataValue:] : 1440 -> 1432
~ +[SRSampleViewController sampleViewControllerForAuthGroup:] : 604 -> 600
~ -[SRResearchDataPerCategoryViewController viewDidLoad] : 2488 -> 2472
~ -[SRResearchDataPerCategoryViewController exportData] : 1224 -> 1220
~ -[SRResearchDataPerCategoryViewController deleteAllUnreleasedData] : 304 -> 300
~ +[NSBundle(SensorKitUI) skui_bundleForAuthorizationService:] : 584 -> 580
~ -[SRResearchDaysViewController viewDidLoad] : 376 -> 372
```
