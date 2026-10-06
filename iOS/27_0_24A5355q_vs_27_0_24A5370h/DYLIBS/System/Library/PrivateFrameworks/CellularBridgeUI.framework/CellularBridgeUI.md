## CellularBridgeUI

> `/System/Library/PrivateFrameworks/CellularBridgeUI.framework/CellularBridgeUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x159d4` | `0x15978` | **`-0x5c`** |

### Other Changes

```diff

-1151.2.0.0.0
+1155.0.0.0.0
Functions:
~ +[NSString(NSString_StringWithPositionalSpecifiersFormat) stringWithPositionalSpecifiersFormat:arguments:] : 788 -> 784
~ -[NPHCellularSetupViewController updateUIToShowUserVisibleError] : 936 -> 932
~ +[NSError(NPHCellularError) NPHCellularSanitizedError:forSubscriptionContext:] : 700 -> 696
~ -[NPHCellularBridgeUIManager _updateSIMStatusForAllSubscriptionContexts] : 352 -> 348
~ -[NPHCellularBridgeUIManager _updateTransferableCellularPlanFromDeviceWithCSN:] : 1576 -> 1572
~ -[NPHCellularBridgeUIManager _activeDeviceCSNList] : 484 -> 480
~ -[NPHCellularBridgeUIManager updateCellularPlansWithFetch:] : 664 -> 660
~ -[NPHCellularBridgeUIManager _updateShouldShowAddNewRemotePlan] : 412 -> 408
~ -[NPHCellularBridgeUIManager _updateIsRemotePlanCapable] : 468 -> 464
~ -[NPHCellularBridgeUIManager serviceSubscriptionsToOfferUser] : 1244 -> 1240
~ -[NPHCellularBridgeUIManager serviceSubscriptionsInUse] : 456 -> 452
~ -[NPHCellularBridgeUIManager serviceSubscriptionsShouldShowAddNewRemotePlan] : 468 -> 464
~ -[NPHCellularBridgeUIManager serviceSubscriptionsOfferingRemotePlan] : 572 -> 568
~ -[NPHCellularBridgeUIManager serviceSubscriptionsOfferingTrialPlan] : 468 -> 464
~ -[NPHCellularBridgeUIManager cellularPlanIsSetUp] : 412 -> 408
~ -[NPHCellularBridgeUIManager isAnyCellularPlanActivating] : 628 -> 624
~ -[NPHCellularBridgeUIManager startRemoteProvisioning] : 296 -> 292
~ -[NPHCellularBridgeUIManager finishRemoteProvisioning] : 296 -> 292
~ -[NPHCellularBridgeUIManager subscriptionContextForCellularPlanItem:] : 364 -> 360
~ -[NPHCellularBridgeUIManager displayNameForCellularPlan:] : 452 -> 448
~ -[NPHCellularBridgeUIManager cellularUseErrors] : 528 -> 524
~ -[NSArray(Filtering) max:] : 368 -> 364
~ -[NSArray(Filtering) nph_map:] : 360 -> 356
```
