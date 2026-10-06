## CardKit

> `/System/Library/PrivateFrameworks/CardKit.framework/CardKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10e48` | `0x10dec` | **`-0x5c`** |

### Other Changes

```text
Functions:
~ -[CRKCardPresentation _updateViewConfigurationsDebugMode:] : 252 -> 248
~ ___55-[CRKCardPresentation _loadAndRegisterBundleProviders:]_block_invoke : 356 -> 352
~ -[CRKComposedStackView sizeThatFits:] : 300 -> 296
~ -[CRKCardSectionViewController _performAllCommands] : 444 -> 440
~ -[CRKCardSectionViewController _destinationPunchout] : 368 -> 364
~ -[CRKCardSectionViewController _preferredPunchoutCommand] : 424 -> 420
~ -[CRKCardViewController cardEventDidOccur:withIdentifier:userInfo:] : 344 -> 340
~ -[CRKCardViewController _cancelTouchesIfNecessary] : 252 -> 248
~ -[CRKCardViewController _resumeTouchesIfNecessary] : 252 -> 248
~ -[CRKCardViewController _removeCardSectionViewControllersFromParentViewController:] : 296 -> 292
~ -[CRKCardViewController _finishLoading] : 916 -> 912
~ ___59-[CRKCardViewController _setCard:loadProvidersImmediately:]_block_invoke : 584 -> 580
~ -[CRKCardViewController viewWillDisappear:] : 304 -> 300
~ -[CRKCardViewController _fireAndForgetOutboundCommand:] : 1136 -> 1128
~ -[_CRKProviderBundle _initializeProviderWithClass:] : 828 -> 824
~ -[_CRKBundleManager loadBundles] : 984 -> 980
~ -[_CRKCardSectionViewControllerFactory _registerCardSectionViewControllerClass:] : 268 -> 264
~ -[_CRKSendMessageCardFactory buildCardForContent:completion:] : 1968 -> 1964
~ -[_CRKCardSectionViewLoader _loadIdentifiedCardSectionViewProvidersFromCard:identifiedProviders:delegate:completion:] : 912 -> 908
~ ___117-[_CRKCardSectionViewLoader _loadIdentifiedCardSectionViewProvidersFromCard:identifiedProviders:delegate:completion:]_block_invoke : 876 -> 872
~ ___117-[_CRKCardSectionViewLoader _loadIdentifiedCardSectionViewProvidersFromCard:identifiedProviders:delegate:completion:]_block_invoke.5 : 724 -> 720
~ -[_CRKCardSectionViewLoader _allViewConfigurations] : 316 -> 312
```
