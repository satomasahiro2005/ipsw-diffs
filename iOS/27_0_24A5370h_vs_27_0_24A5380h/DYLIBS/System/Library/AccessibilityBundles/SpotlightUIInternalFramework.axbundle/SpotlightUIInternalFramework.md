## SpotlightUIInternalFramework

> `/System/Library/AccessibilityBundles/SpotlightUIInternalFramework.axbundle/SpotlightUIInternalFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0xb80` | `0x8c0` | **`-0x2c0`** |
| `__TEXT.__cstring` | `0x79f` | `0x627` | **`-0x178`** |
| `__TEXT.__text` | `0x1e0c` | `0x1cd8` | **`-0x134`** |
| `__AUTH_CONST.__objc_const` | `0x870` | `0x990` | **`+0x120`** |
| `__DATA_CONST.__const` | `0x1c0` | `0xf8` | **`-0xc8`** |
| `__AUTH.__objc_data` | `0xa0` | `0x140` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x31c` | `0x33c` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x78` | `0x88` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x78` | `0x80` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x128` | `0x130` | **`+0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 67
-  Symbols:   231
-  CStrings:  101
+  Functions: 68
+  Symbols:   241
+  CStrings:  79
Symbols:
+ +[SPUISecureWindowAccessibility _accessibilityPerformValidations:]
+ +[SPUISecureWindowAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[SPUISecureWindowAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[SPUISecureWindowAccessibility accessibilityElementsHidden]
+ GCC_except_table17
+ GCC_except_table61
+ _OBJC_CLASS_$_SPUISecureWindowAccessibility
+ _OBJC_CLASS_$_UIWindow
+ _OBJC_CLASS_$___SPUISecureWindowAccessibility_super
+ _OBJC_METACLASS_$_SPUISecureWindowAccessibility
+ _OBJC_METACLASS_$___SPUISecureWindowAccessibility_super
+ __OBJC_$_CLASS_METHODS_SPUISecureWindowAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_SPUISecureWindowAccessibility
+ __OBJC_CLASS_RO_$_SPUISecureWindowAccessibility
+ __OBJC_CLASS_RO_$___SPUISecureWindowAccessibility_super
+ __OBJC_METACLASS_RO_$_SPUISecureWindowAccessibility
+ __OBJC_METACLASS_RO_$___SPUISecureWindowAccessibility_super
- -[SPUIResultsViewControllerAccessibility _axPreviousGoResult]
- -[SPUIResultsViewControllerAccessibility _axSetPreviousGoResult:]
- -[SPUIResultsViewControllerAccessibility _axStringForType:]
- GCC_except_table18
- GCC_except_table60
- ___SPUIResultsViewControllerAccessibility___axPreviousGoResult
- _objc_release_x28
CStrings:
+ "SPUISecureWindow"
+ "SPUISecureWindowAccessibility"
+ "UIWindow"
+ "isOverlayTodayViewVisible"
- "_isShowingSearchableTodayView"
- "goTakeoverResult"
- "resultBundleId"
- "search.clip"
- "search.go.baidu"
- "search.go.bing"
- "search.go.calculator"
- "search.go.conversion"
- "search.go.dictionary"
- "search.go.duckduckgo"
- "search.go.ecosia"
- "search.go.format"
- "search.go.google"
- "search.go.local"
- "search.go.qihoo"
- "search.go.safari"
- "search.go.show.more"
- "search.go.siri.shortcut"
- "search.go.siri.suggestion"
- "search.go.sogou"
- "search.go.suggestion"
- "search.go.yahoo"
- "search.go.yandex"
- "secondaryTitle"
- "type"
- "web.clip"
```
