## SystemStatusUI

> `/System/Library/PrivateFrameworks/SystemStatusUI.framework/SystemStatusUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa0bc0` | `0xa123c` | **`+0x67c`** |
| `__AUTH_CONST.__cfstring` | `0x3b40` | `0x3ca0` | **`+0x160`** |
| `__TEXT.__cstring` | `0x2ae4` | `0x2bba` | **`+0xd6`** |
| `__TEXT.__oslogstring` | `0x507` | `0x581` | **`+0x7a`** |
| `__TEXT.__objc_methlist` | `0xaed4` | `0xaf34` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x52d8` | `0x5330` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x13b28` | `0x13af8` | **`-0x30`** |
| `__TEXT.__gcc_except_tab` | `0xfa0` | `0xf7c` | **`-0x24`** |
| `__TEXT.__unwind_info` | `0x25a8` | `0x25c0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x518` | `0x520` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1ae8` | `0x1af0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1090` | `0x1098` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x388` | `0x390` | **`+0x8`** |
| `__TEXT.__const` | `0x3418` | `0x3420` | **`+0x8`** |

### Other Changes

```diff

-279.100.0.0.0
+282.0.0.0.0

-  Functions: 4166
-  Symbols:   6894
-  CStrings:  614
+  Functions: 4174
+  Symbols:   6910
+  CStrings:  625
Symbols:
+ +[STUIStatusBarDisplayItemPlacementAdditionalEntriesGroup groupWithHighPriority:lowPriority:identifiersByPriority:]
+ +[STUIStatusBarDisplayItemPlacementNetworkGroup _groupWithCellularGroup:wifiGroup:includeCellularName:wifiSuppressesCellularType:]
+ +[STUIStatusBarDisplayItemPlacementNetworkGroup groupWithHighPriority:lowPriority:cellularItemClass:wifiItemClass:cellularTypeClass:includeCellularName:allowDualNetwork:wifiSuppressesCellularType:]
+ +[STUIStatusBarDisplayItemPlacementNetworkGroup groupWithHighPriority:lowPriority:cellularItemClass:wifiItemClass:includeCellularName:wifiSuppressesCellularType:]
+ +[STUIStatusBarDisplayItemPlacementWirelessChargerGroup groupWithHighPriority:lowPriority:identifiersByPriority:intraGroupSpacerWidth:]
+ -[STUIStatusBarCarPlayWirelessChargerIdentifier .cxx_destruct]
+ -[STUIStatusBarCarPlayWirelessChargerIdentifier chargerIndex]
+ -[STUIStatusBarCarPlayWirelessChargerIdentifier displayItemIdentifierString]
+ -[STUIStatusBarCarPlayWirelessChargerIdentifier groupID]
+ -[STUIStatusBarCarPlayWirelessChargerIdentifier initWithDisplayItemIdentifierString:]
+ -[STUIStatusBarCarPlayWirelessChargerIdentifier initWithGroupID:chargerIndex:]
+ -[STUIStatusBarWirelessChargerItem _chargerEntryForDisplayItemIdentifier:fromData:]
+ -[STUIStatusBarWirelessChargerItem _lazyChargerViewForIdentifier:]
+ -[STUIStatusBarWirelessChargerItem chargerViews]
+ _OBJC_CLASS_$_NSScanner
+ _OBJC_CLASS_$_STUIStatusBarCarPlayWirelessChargerIdentifier
+ _OBJC_IVAR_$_STUIStatusBarCarPlayWirelessChargerIdentifier._chargerIndex
+ _OBJC_IVAR_$_STUIStatusBarCarPlayWirelessChargerIdentifier._groupID
+ _OBJC_IVAR_$_STUIStatusBarWirelessChargerItem._chargerViews
+ _OBJC_METACLASS_$_STUIStatusBarCarPlayWirelessChargerIdentifier
+ _STUIStatusBarCarPlayPartIdentifierSuffix
+ _STUIStatusBarMakeCarPlayPartIdentifier
+ _STUIStatusBarPartIdentifierCarPlayAutomakerStatusItem
+ _STUIStatusBarPartIdentifierCarPlayBluetooth
+ _STUIStatusBarPartIdentifierCarPlayCellular
+ _STUIStatusBarPartIdentifierCarPlayCurrentUser
+ _STUIStatusBarPartIdentifierCarPlayWifi
+ _STUIStatusBarPartIdentifierCarPlayWirelessCharger
+ __OBJC_$_INSTANCE_METHODS_STUIStatusBarCarPlayWirelessChargerIdentifier
+ __OBJC_$_INSTANCE_VARIABLES_STUIStatusBarCarPlayWirelessChargerIdentifier
+ __OBJC_$_PROP_LIST_STUIStatusBarCarPlayWirelessChargerIdentifier
+ __OBJC_CLASS_RO_$_STUIStatusBarCarPlayWirelessChargerIdentifier
+ __OBJC_METACLASS_RO_$_STUIStatusBarCarPlayWirelessChargerIdentifier
+ __UIUnitClamp
- +[STUIStatusBarDisplayItemPlacementAdditionalEntriesGroup groupWithHighPriority:lowPriority:inAscendingPriority:identifiersByPriority:]
- +[STUIStatusBarDisplayItemPlacementNetworkGroup _groupWithCellularGroup:wifiGroup:includeCellularName:]
- +[STUIStatusBarDisplayItemPlacementNetworkGroup groupWithHighPriority:lowPriority:cellularItemClass:wifiItemClass:cellularTypeClass:includeCellularName:allowDualNetwork:]
- +[STUIStatusBarDisplayItemPlacementNetworkGroup groupWithHighPriority:lowPriority:cellularItemClass:wifiItemClass:includeCellularName:]
- +[STUIStatusBarDisplayItemPlacementWirelessChargerGroup groupWithHighPriority:lowPriority:inAscendingPriority:identifiersByPriority:]
- -[STUIStatusBarWirelessChargerItem groupViews]
- -[STUIStatusBarWirelessChargerItem lazyViewForGroupIdentifier:]
- _OBJC_CLASS_$_STUIStatusBarWirelessChargerGroupView
- _OBJC_IVAR_$_STUIStatusBarWirelessChargerItem._groupViews
- _OBJC_METACLASS_$_STUIStatusBarWirelessChargerGroupView
- _OBJC_METACLASS_$_UIStackView
- __OBJC_$_PROP_LIST_STUIStatusBarWirelessChargerGroupView
- __OBJC_CLASS_PROTOCOLS_$_STUIStatusBarWirelessChargerGroupView
- __OBJC_CLASS_RO_$_STUIStatusBarWirelessChargerGroupView
- __OBJC_METACLASS_RO_$_STUIStatusBarWirelessChargerGroupView
- ___60+[STUIStatusBarDataConverter convertData:fromReferenceData:]_block_invoke
- ___block_descriptor_64_e8_32s40r48r_e11_v16?0i8I12ls32l8r40l8r48l8
- _objc_retain_x5
CStrings:
+ "%@%@%@"
+ "%@%@%lu"
+ "-"
+ "WirelessChargerGroup: out of priority budget (offset=%lu, slotsPerGroup=%lu, window=%ld); dropping %lu groups: %{public}@"
+ "_"
+ "carPlayAutomakerStatusItemPartIdentifier"
+ "carPlayBluetoothPartIdentifier"
+ "carPlayCellularPartIdentifier"
+ "carPlayCurrentUserPartIdentifier"
+ "carPlayWifiPartIdentifier"
+ "carPlayWirelessChargerPartIdentifier"
+ "ethernet"
- "v16@?0i8I12"
```
