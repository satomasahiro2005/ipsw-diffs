## SettingsCellularUI

> `/System/Library/PrivateFrameworks/SettingsCellularUI.framework/SettingsCellularUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x93324` | `0x938fc` | **`+0x5d8`** |
| `__AUTH_CONST.__objc_const` | `0x102c8` | `0x103d0` | **`+0x108`** |
| `__TEXT.__objc_methlist` | `0x9c2c` | `0x9c9c` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x8720` | `0x86e0` | **`-0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x5648` | `0x5680` | **`+0x38`** |
| `__TEXT.__cstring` | `0x912e` | `0x914a` | **`+0x1c`** |
| `__DATA.__objc_ivar` | `0x628` | `0x63c` | **`+0x14`** |
| `__DATA_CONST.__got` | `0xac0` | `0xac8` | **`+0x8`** |
| `__DATA_DIRTY.__objc_ivar` | `0x5f0` | `0x5f8` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x1864` | `0x186c` | **`+0x8`** |

### Other Changes

```diff

-746.0.0.0.0
+750.0.0.0.0

-  Functions: 3349
-  Symbols:   5605
-  CStrings:  2064
+  Functions: 3357
+  Symbols:   5619
+  CStrings:  2060
Symbols:
+ +[PSUITurnOnThisLineSpecifier specifierWithPlanUniversalReference:cellularPlanManager:planManagerCache:callCache:simStatusCache:hostController:isActivating:]
+ +[SettingsCellularUtils shouldUseSIMConfigSwitchFlowForPlan:simStatusCache:]
+ -[PSUICarrierAppGroup initWithListController:parentSpecifier:featureFlagProvider:]
+ -[PSUICarrierSpaceGroup initWithListController:groupSpecifier:parentSpecifier:ctClient:featureFlagProvider:]
+ -[PSUICarrierSpaceServicesController initWithFeatureFlagProvider:]
+ -[PSUIDataModeSubgroup createTARandomizationSpecifiersIfNeededForDescriptor:]
+ -[PSUIDataModeSubgroup taRandomizationSpecifiersExist]
+ -[PSUISubscriptionContextMenusGroup featureFlagProvider]
+ -[PSUISubscriptionContextMenusGroup setFeatureFlagProvider:]
+ -[PSUISubscriptionContextMenusProductionFactory createCarrierAppGroupWithFeatureFlagProvider:]
+ -[PSUISubscriptionContextMenusProductionFactory createCarrierSpaceSubgroupWithFeatureFlagProvider:]
+ -[PSUISubscriptionContextMenusProductionFactory createFeatureFlagProvider]
+ -[PSUITurnOnThisLineSpecifier initWithPlanUniversalReference:planUUID:cellularPlanManager:planManagerCache:callCache:simStatusCache:hostController:isActivating:]
+ -[PSUITurnOnThisLineSpecifier setSimStatusCache:]
+ -[PSUITurnOnThisLineSpecifier simStatusCache]
+ _OBJC_CLASS_$_SettingsCellularFeatureFlagManager
+ _OBJC_IVAR_$_PSUICarrierAppGroup._featureFlagProvider
+ _OBJC_IVAR_$_PSUICarrierSpaceGroup._featureFlagProvider
+ _OBJC_IVAR_$_PSUIDataModeSubgroup._cachedRegulatoryDisabled
+ _OBJC_IVAR_$_PSUIDataModeSubgroup._cachedServiceDescriptor
+ _OBJC_IVAR_$_PSUISubscriptionContextMenusGroup._featureFlagProvider
+ _objc_retain_x7
- +[PSUITurnOnThisLineSpecifier specifierWithPlanUniversalReference:cellularPlanManager:planManagerCache:callCache:hostController:isActivating:]
- -[PSUICarrierAppGroup initWithListController:parentSpecifier:]
- -[PSUICarrierSpaceGroup initWithListController:groupSpecifier:parentSpecifier:ctClient:]
- -[PSUIDataModeSubgroup createTARandomizationSpecifiersIfNeeded]
- -[PSUISubscriptionContextMenusProductionFactory createCarrierAppGroup]
- -[PSUISubscriptionContextMenusProductionFactory createCarrierSpaceSubgroup]
- -[PSUITurnOnThisLineSpecifier initWithPlanUniversalReference:planUUID:cellularPlanManager:planManagerCache:callCache:hostController:isActivating:]
- _objc_retain_x6
CStrings:
+ "QS_DETAILS_ESIM_SETUP"
+ "QS_DETAILS_IOS_VERSION"
+ "QS_DETAILS_MODEL_NAME"
+ "QS_DETAILS_NAME"
+ "QS_DETAILS_SERIAL_NUMBER"
+ "s"
- "CarrierAppInSettings"
- "Model Name"
- "Name"
- "Off"
- "On"
- "S"
- "Serial Number"
- "c"
- "eSIM Setup"
- "iOS Version"
```
