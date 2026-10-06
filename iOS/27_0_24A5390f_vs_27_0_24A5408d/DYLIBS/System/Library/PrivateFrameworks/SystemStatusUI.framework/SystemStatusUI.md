## SystemStatusUI

> `/System/Library/PrivateFrameworks/SystemStatusUI.framework/SystemStatusUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa1fa4` | `0xa2758` | **`+0x7b4`** |
| `__TEXT.__const` | `0x3870` | `0x39b0` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0x13b28` | `0x13c10` | **`+0xe8`** |
| `__TEXT.__objc_methlist` | `0xaf24` | `0xafd4` | **`+0xb0`** |
| `__DATA.__data` | `0x16e0` | `0x1740` | **`+0x60`** |
| `__TEXT.__cstring` | `0x2bba` | `0x2b5e` | **`-0x5c`** |
| `__AUTH.__objc_data` | `0x1238` | `0x1288` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x5330` | `0x5370` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x1af0` | `0x1b18` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x3ca0` | `0x3c80` | **`-0x20`** |
| `__AUTH_CONST.__const` | `0x1408` | `0x1428` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x50` | `0x38` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x25d8` | `0x25f0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0xf7c` | `0xf90` | **`+0x14`** |
| `__DATA.__bss` | `0x1d98` | `0x1da8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x648` | `0x650` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x140` | `0x148` | **`+0x8`** |

### Other Changes

```diff

-284.1.0.0.0
+286.101.0.0.0

-  Functions: 4182
-  Symbols:   6922
-  CStrings:  625
+  Functions: 4194
+  Symbols:   6944
+  CStrings:  624
Symbols:
+ +[STUIStatusBarDisplayItemPlacementBatteryGroup groupWithHighPriority:lowPriority:includePercentPlacement:includeNotChargingPlacement:]
+ +[STUIStatusBarDisplayItemPlacementNetworkGroup _groupWithCellularGroup:wifiGroup:includeCellularName:wifiSuppressesCellularType:placeVPNFirst:]
+ +[STUIStatusBarDisplayItemPlacementNetworkGroup groupWithHighPriority:lowPriority:cellularItemClass:wifiItemClass:cellularTypeClass:includeCellularName:allowDualNetwork:wifiSuppressesCellularType:placeVPNFirst:]
+ +[STUIStatusBarDisplayItemPlacementNetworkGroup groupWithHighPriority:lowPriority:cellularItemClass:wifiItemClass:includeCellularName:wifiSuppressesCellularType:placeVPNFirst:]
+ +[STUIStatusBarDisplayItemPlacementNetworkGroup secondaryGroupWithHighPriority:lowPriority:cellularItemClass:wifiItemClass:placeVPNFirst:]
+ +[STUIStatusBarDisplayItemPlacementNetworkGroup wifiSuppressesCellularTypeForCurrentRegion]
+ -[STUIStatusBar menuBarLeadingItemSpacing]
+ -[STUIStatusBarBatteryItem initWithIdentifier:statusBar:]
+ -[STUIStatusBarIndicatorItem useHierarchicalSystemImageForUpdate:]
+ -[STUIStatusBarIndicatorNotChargingItem canEnableDisplayItem:fromData:]
+ -[STUIStatusBarIndicatorNotChargingItem indicatorEntryKey]
+ -[STUIStatusBarIndicatorNotChargingItem systemImageNameForUpdate:]
+ -[STUIStatusBarIndicatorNotChargingItem useHierarchicalSystemImageForUpdate:]
+ -[STUIStatusBarVisualProvider_Pad leadingItemSpacing]
+ GCC_except_table59
+ _OBJC_CLASS_$_STUIStatusBarIndicatorNotChargingItem
+ _OBJC_METACLASS_$_STUIStatusBarIndicatorNotChargingItem
+ __OBJC_$_INSTANCE_METHODS_STUIStatusBarIndicatorNotChargingItem
+ __OBJC_$_PROTOCOL_CLASS_METHODS_STUIStatusBarBatteryView_Internal
+ __OBJC_$_PROTOCOL_METHOD_TYPES_STUIStatusBarBatteryView_Internal
+ __OBJC_$_PROTOCOL_REFS_STUIStatusBarBatteryView_Internal
+ __OBJC_CLASS_RO_$_STUIStatusBarIndicatorNotChargingItem
+ __OBJC_LABEL_PROTOCOL_$_STUIStatusBarBatteryView_Internal
+ __OBJC_METACLASS_RO_$_STUIStatusBarIndicatorNotChargingItem
+ __OBJC_PROTOCOL_$_STUIStatusBarBatteryView_Internal
+ ___91+[STUIStatusBarDisplayItemPlacementNetworkGroup wifiSuppressesCellularTypeForCurrentRegion]_block_invoke
+ ___block_descriptor_40_e8_32w_e8_v16?0q8lw32l8
- +[STUIStatusBarDisplayItemPlacementBatteryGroup groupWithHighPriority:lowPriority:]
- +[STUIStatusBarDisplayItemPlacementNetworkGroup _groupWithCellularGroup:wifiGroup:includeCellularName:wifiSuppressesCellularType:]
- +[STUIStatusBarDisplayItemPlacementNetworkGroup groupWithHighPriority:lowPriority:cellularItemClass:wifiItemClass:cellularTypeClass:includeCellularName:allowDualNetwork:wifiSuppressesCellularType:]
- +[STUIStatusBarDisplayItemPlacementNetworkGroup groupWithHighPriority:lowPriority:cellularItemClass:wifiItemClass:includeCellularName:wifiSuppressesCellularType:]
- +[STUIStatusBarDisplayItemPlacementNetworkGroup secondaryGroupWithHighPriority:lowPriority:cellularItemClass:wifiItemClass:]
CStrings:
+ "-[STUIStatusBarVisualProvider_Fallback setupInContainerView:]"
+ "bolt.slash.fill"
- "Class  _Nonnull STUIStatusBarGetVisualProviderClassForScreen(UIScreen *__strong _Nonnull, NSDictionary * _Nullable __strong)"
- "STUIStatusBarVisualProvider_RoundierPad"
- "main"
```
