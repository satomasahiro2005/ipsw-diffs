## MobileSafariUI

> `/System/Library/AccessibilityBundles/MobileSafariUI.axbundle/MobileSafariUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xadbc` | `0xa4e0` | **`-0x8dc`** |
| `__AUTH.__objc_data` | `0x690` | `0x50` | **`-0x640`** |
| `__DATA_DIRTY.__objc_data` | `0xf50` | `0x14f0` | **`+0x5a0`** |
| `__AUTH_CONST.__cfstring` | `0x2f80` | `0x2d40` | **`-0x240`** |
| `__AUTH_CONST.__objc_const` | `0x2788` | `0x2668` | **`-0x120`** |
| `__TEXT.__cstring` | `0x2490` | `0x2399` | **`-0xf7`** |
| `__TEXT.__objc_methlist` | `0xe18` | `0xd60` | **`-0xb8`** |
| `__DATA_CONST.__objc_selrefs` | `0x7e0` | `0x788` | **`-0x58`** |
| `__TEXT.__unwind_info` | `0x3d0` | `0x3a8` | **`-0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x230` | `0x220` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x190` | `0x188` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xf0` | `0xe8` | **`-0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 288
-  Symbols:   826
-  CStrings:  426
+  Functions: 274
+  Symbols:   798
+  CStrings:  408
Symbols:
+ -[UnifiedTabBarAccessibility _setResolvedItemArrangement:animated:andScrollTo:completionHandler:]
+ GCC_except_table251
+ GCC_except_table260
- +[TabBarItemViewAccessibility _accessibilityPerformValidations:]
- +[TabBarItemViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[TabBarItemViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[TabBarItemViewAccessibility _accessibilityHitTest:withEvent:]
- -[TabBarItemViewAccessibility _accessibilityIsSpeakThisElement]
- -[TabBarItemViewAccessibility _accessibilityLoadAccessibilityInformation]
- -[TabBarItemViewAccessibility _accessibilityUpdateAXInfo]
- -[TabBarItemViewAccessibility accessibilityLabel]
- -[TabBarItemViewAccessibility isAccessibilityElement]
- -[TabBarItemViewAccessibility setActive:]
- -[TabBarItemViewAccessibility setFrame:]
- -[TabBarItemViewAccessibility setPinned:]
- -[TabBarItemViewAccessibility setTitleText:]
- -[TabControllerAccessibility _axTabBarItemViewForTabDocument:]
- -[UnifiedTabBarAccessibility _setResolvedItemArrangement:animated:keepingItemVisible:completionHandler:]
- GCC_except_table265
- GCC_except_table274
- _CGRectContainsPoint
- _OBJC_CLASS_$_TabBarItemViewAccessibility
- _OBJC_CLASS_$___TabBarItemViewAccessibility_super
- _OBJC_METACLASS_$_TabBarItemViewAccessibility
- _OBJC_METACLASS_$___TabBarItemViewAccessibility_super
- _UIAccessibilityFrameForBounds
- _UIAccessibilityPointForPoint
- _UIAccessibilityTraitSelected
- __OBJC_$_CLASS_METHODS_TabBarItemViewAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_TabBarItemViewAccessibility
- __OBJC_CLASS_RO_$_TabBarItemViewAccessibility
- __OBJC_CLASS_RO_$___TabBarItemViewAccessibility_super
- __OBJC_METACLASS_RO_$_TabBarItemViewAccessibility
- __OBJC_METACLASS_RO_$___TabBarItemViewAccessibility_super
CStrings:
+ "_setResolvedItemArrangement:animated:andScrollTo:completionHandler:"
- "TabBarItem"
- "TabBarItemLayoutInfo"
- "TabBarItemView"
- "TabBarItemViewAccessibility"
- "_isPinnedAndNarrow"
- "_setResolvedItemArrangement:animated:keepingItemVisible:completionHandler:"
- "_tabBarItem"
- "_titleLabel"
- "_titleText"
- "close.tab"
- "closeButton"
- "isPinned"
- "layoutInfo"
- "setPinned:"
- "setTitleText:"
- "tab.hint"
- "tab.pinned"
- "tab.view"
- "tabBarItemView"
```
