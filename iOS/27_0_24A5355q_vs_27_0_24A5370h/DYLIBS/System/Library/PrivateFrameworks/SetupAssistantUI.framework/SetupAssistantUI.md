## SetupAssistantUI

> `/System/Library/PrivateFrameworks/SetupAssistantUI.framework/SetupAssistantUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2384c` | `0x237d8` | **`-0x74`** |

### Other Changes

```diff

-5403.100.0.0.0
+5405.0.0.0.0
Functions:
~ +[NSLocale(MultilingualFlow) buddySubregionLocalesForCellularInformation:] : 840 -> 832
~ +[NSLocale(MultilingualFlow) buddySuggestedLanguages] : 456 -> 452
~ +[NSLocale(MultilingualFlow) buddyDefaultLanguages] : 456 -> 452
~ -[BFFLinkLabelFooterView setEnabled:] : 284 -> 280
~ -[BFFLinkLabelFooterView sizeThatFits:shouldSetSize:] : 2024 -> 2016
~ -[BFFNavigationControllerDefaultDelegate navigationController:willShowViewController:animated:] : 572 -> 568
~ -[BFFNavigationControllerDefaultDelegate navigationController:didShowViewController:animated:] : 788 -> 784
~ -[BFFSplashController removeAllButtons] : 288 -> 284
~ -[BFFSplashController setTint:] : 420 -> 416
~ -[BFFSplashController _updateButtonFonts] : 364 -> 360
~ -[BFFSplashController setButtonsEnabled:] : 284 -> 280
~ -[BFFSplashController viewDidLayoutSubviews] : 2484 -> 2476
~ +[BFFFinishSetupViewController _keyValueDictionaryForURL:] : 464 -> 460
~ +[BFFFinishSetupViewController _orderedFlowIdentifiersFromFlowIdentifiers:] : 472 -> 468
~ ___62-[BFFPasscodeView animateTransitionToPasscodeInput:animation:]_block_invoke : 192 -> 184
~ -[BFFNavigationController setViewControllers:animated:] : 652 -> 644
~ -[BFFFlow startFlowAnimated:] : 312 -> 308
~ -[BFFFlow startFlowWithAllFlowItems] : 404 -> 400
~ -[BFFFlow precedingItems] : 488 -> 484
~ -[BFFFlow firstItem] : 516 -> 512
~ -[BFFFlow viewControllers] : 324 -> 320
~ +[BFFFlow applicableDispositions] : 264 -> 260
~ -[BFFFlow responsibleForViewController:] : 356 -> 352
~ sub_29bc0ff60 -> sub_29d091ef0 : 280 -> 276
```
