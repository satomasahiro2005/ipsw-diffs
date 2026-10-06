## NewsServicesInternal

> `/System/Library/PrivateFrameworks/NewsServicesInternal.framework/NewsServicesInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb62c` | `0xb60c` | **`-0x20`** |

### Other Changes

```diff

-5916.1.0.0.0
+5920.0.0.0.0
Functions:
~ ___NSSDestroyUserDefaultsDataWithItems_block_invoke : 516 -> 512
~ _NSSDestroyDataContainersWithItems : 420 -> 416
~ +[NSSArticleInternal articleFromNotification:completion:] : 720 -> 716
~ ___76+[NSSArticleInternal _articleFromCoreSpotlightIdentifier:domain:completion:]_block_invoke.31 : 816 -> 812
~ -[NSURL(NSSAdditions) _nss_valueForQueryParameterWithKey:] : 456 -> 452
~ -[NSSNewsAnalyticsPBEventAccumulator observeEvents:] : 552 -> 548
~ -[NSSExternalAnalyticsPaneldentifierProvider panelIdentifierWithHostNames:] : 1020 -> 1016
~ ___75-[NSSExternalAnalyticsPaneldentifierProvider panelIdentifierWithHostNames:]_block_invoke : 276 -> 272
```
