## SystemStatusUI

> `/System/Library/PrivateFrameworks/SystemStatusUI.framework/SystemStatusUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa2758` | `0xa290c` | **`+0x1b4`** |
| `__AUTH_CONST.__objc_const` | `0x13c10` | `0x13c70` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0xafd4` | `0xb034` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x5370` | `0x53a8` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x25f0` | `0x2600` | **`+0x10`** |
| `__DATA_DIRTY.__objc_ivar` | `0x52c` | `0x534` | **`+0x8`** |
| `__TEXT.__cstring` | `0x2b5e` | `0x2b5f` | **`+0x1`** |

### Other Changes

```diff

-286.101.0.0.0
+286.104.0.0.0

-  Functions: 4194
-  Symbols:   6944
+  Functions: 4202
+  Symbols:   6952
Symbols:
+ +[STUIStatusBarCellularFlatSignalView _verticalOffsetForIconSize:]
+ +[STUIStatusBarCellularSignalView _verticalOffsetForIconSize:]
+ +[STUIStatusBarCellularSmallSignalView _verticalOffsetForIconSize:]
+ -[STUIStatusBarBatteryItem adjustBaselineInNonExpandedModes]
+ -[STUIStatusBarBatteryItem adjustsBaselineForCondensedPercentageDisplay]
+ -[STUIStatusBarBatteryItem setAdjustBaselineInNonExpandedModes:]
+ -[STUIStatusBarBatteryItem setAdjustsBaselineForCondensedPercentageDisplay:]
+ -[STUIStatusBarVisualProvider_DynamicSplit additionalEdgeInsetAdjustments]
+ _OBJC_IVAR_$_STUIStatusBarBatteryItem._adjustsBaselineForCondensedPercentageDisplay
- _OBJC_IVAR_$_STUIStatusBarBatteryItem._usesCondensedPercentageDisplay
CStrings:
+ "ar"
- "Q\x82"
```
