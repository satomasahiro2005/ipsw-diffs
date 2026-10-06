## MediaControls

> `/System/Library/AccessibilityBundles/MediaControls.axbundle/MediaControls`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa1f8` | `0xa7a4` | **`+0x5ac`** |
| `__TEXT.__cstring` | `0x2201` | `0x23ca` | **`+0x1c9`** |
| `__AUTH_CONST.__cfstring` | `0x2ee0` | `0x3080` | **`+0x1a0`** |
| `__AUTH_CONST.__objc_const` | `0x3450` | `0x3570` | **`+0x120`** |
| `__AUTH.__objc_data` | `0xa0` | `0x140` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x1284` | `0x1304` | **`+0x80`** |
| `__DATA_CONST.__objc_classlist` | `0x2e8` | `0x2f8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x680` | `0x690` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x458` | `0x468` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x100` | `0x108` | **`+0x8`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 358
-  Symbols:   985
-  CStrings:  415
+  Functions: 367
+  Symbols:   1004
+  CStrings:  434
Symbols:
+ +[MediaControlsModuleSessionViewAccessibility _accessibilityPerformValidations:]
+ +[MediaControlsModuleSessionViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[MediaControlsModuleSessionViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[MediaControlsModuleSessionViewAccessibility _accessibilitySupplementaryFooterViews]
+ -[MediaControlsModuleSessionViewAccessibility _axHeaderView]
+ -[MediaControlsModuleSessionViewAccessibility _axIsCollapsed]
+ -[MediaControlsModuleSessionViewAccessibility accessibilityLabel]
+ -[MediaControlsModuleSessionViewAccessibility accessibilityTraits]
+ -[MediaControlsModuleSessionViewAccessibility isAccessibilityElement]
+ GCC_except_table171
+ GCC_except_table195
+ GCC_except_table203
+ GCC_except_table220
+ GCC_except_table273
+ GCC_except_table308
+ GCC_except_table345
+ GCC_except_table75
+ GCC_except_table78
+ _OBJC_CLASS_$_MediaControlsModuleSessionViewAccessibility
+ _OBJC_CLASS_$___MediaControlsModuleSessionViewAccessibility_super
+ _OBJC_METACLASS_$_MediaControlsModuleSessionViewAccessibility
+ _OBJC_METACLASS_$___MediaControlsModuleSessionViewAccessibility_super
+ __OBJC_$_CLASS_METHODS_MediaControlsModuleSessionViewAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_MediaControlsModuleSessionViewAccessibility
+ __OBJC_CLASS_RO_$_MediaControlsModuleSessionViewAccessibility
+ __OBJC_CLASS_RO_$___MediaControlsModuleSessionViewAccessibility_super
+ __OBJC_METACLASS_RO_$_MediaControlsModuleSessionViewAccessibility
+ __OBJC_METACLASS_RO_$___MediaControlsModuleSessionViewAccessibility_super
- GCC_except_table166
- GCC_except_table190
- GCC_except_table198
- GCC_except_table211
- GCC_except_table264
- GCC_except_table299
- GCC_except_table336
- GCC_except_table70
- GCC_except_table73
CStrings:
+ "MediaControls.MediaControlsModuleNowPlayingView"
+ "MediaControls.MediaControlsModuleSessionView"
+ "MediaControls.SessionAccessoryView"
+ "MediaControls.SessionHeaderView"
+ "MediaControls.TransportButton"
+ "MediaControlsModuleNowPlayingView"
+ "MediaControlsModuleSessionViewAccessibility"
+ "RoutePickerSessionViewState"
+ "SessionAccessoryView"
+ "SessionActionButton"
+ "SessionHeaderView"
+ "TransportButton"
+ "accessoryView"
+ "actionButton"
+ "headerOnly"
+ "headerView"
+ "mode"
+ "nowPlayingView"
+ "sessionViewState"
```
