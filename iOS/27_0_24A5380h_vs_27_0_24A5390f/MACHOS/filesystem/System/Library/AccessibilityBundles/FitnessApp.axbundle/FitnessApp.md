## FitnessApp

> `/System/Library/AccessibilityBundles/FitnessApp.axbundle/FitnessApp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf13c` | `0xee28` | **`-0x314`** |
| `__DATA.__objc_const` | `0x5068` | `0x4f48` | **`-0x120`** |
| `__DATA.__objc_data` | `0x2c60` | `0x2bc0` | **`-0xa0`** |
| `__TEXT.__objc_methname` | `0x1ab8` | `0x1a4d` | **`-0x6b`** |
| `__TEXT.__objc_methlist` | `0x18e8` | `0x1898` | **`-0x50`** |
| `__DATA_CONST.__cfstring` | `0x32a0` | `0x3260` | **`-0x40`** |
| `__TEXT.__objc_stubs` | `0x1820` | `0x1800` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0x200` | `0x1e3` | **`-0x1d`** |
| `__DATA.__objc_selrefs` | `0x798` | `0x788` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x470` | `0x460` | **`-0x10`** |
| `__TEXT.__objc_classname` | `0x1997` | `0x1987` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x5c0` | `0x5b8` | **`-0x8`** |
| `__TEXT.__cstring` | `0x2bba` | `0x2bbc` | **`+0x2`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1034.0.0.0.0
+1035.0.0.0.0

-  Functions: 467
-  Symbols:   1559
-  CStrings:  744
+  Functions: 462
+  Symbols:   1543
+  CStrings:  735
Symbols:
+ +[TrendDownMetricCollectionViewCellAccessibility _accessibilityPerformValidations:]
+ +[TrendDownMetricCollectionViewCellAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[TrendDownMetricCollectionViewCellAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[TrendDownMetricCollectionViewCellAccessibility accessibilityLabel]
+ -[TrendDownMetricCollectionViewCellAccessibility accessibilityTraits]
+ -[TrendDownMetricCollectionViewCellAccessibility isAccessibilityElement]
+ GCC_except_table139
+ GCC_except_table162
+ GCC_except_table172
+ GCC_except_table206
+ GCC_except_table224
+ GCC_except_table237
+ GCC_except_table255
+ GCC_except_table264
+ GCC_except_table315
+ GCC_except_table319
+ GCC_except_table329
+ GCC_except_table371
+ GCC_except_table376
+ GCC_except_table387
+ GCC_except_table393
+ GCC_except_table408
+ GCC_except_table64
+ GCC_except_table73
+ GCC_except_table94
+ _OBJC_CLASS_$_TrendDownMetricCollectionViewCellAccessibility
+ _OBJC_CLASS_$___TrendDownMetricCollectionViewCellAccessibility_super
+ _OBJC_METACLASS_$_TrendDownMetricCollectionViewCellAccessibility
+ _OBJC_METACLASS_$___TrendDownMetricCollectionViewCellAccessibility_super
+ __OBJC_$_CLASS_METHODS_TrendDownMetricCollectionViewCellAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_TrendDownMetricCollectionViewCellAccessibility
+ __OBJC_CLASS_RO_$_TrendDownMetricCollectionViewCellAccessibility
+ __OBJC_CLASS_RO_$___TrendDownMetricCollectionViewCellAccessibility_super
+ __OBJC_METACLASS_RO_$_TrendDownMetricCollectionViewCellAccessibility
+ __OBJC_METACLASS_RO_$___TrendDownMetricCollectionViewCellAccessibility_super
- +[FitDayCellLayerAccessibility _accessibilityPerformValidations:]
- +[FitDayCellLayerAccessibility activityCellImageWithDiameter:thickness:calories:briskMinutes:hourlyBreak:fadeInnerRings:fadeAll:]
- +[FitDayCellLayerAccessibility(SafeCategory) safeCategoryBaseClass]
- +[FitDayCellLayerAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[WeekViewAccessibility _accessibilityPerformValidations:]
- +[WeekViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[WeekViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[FitDayCellLayerAccessibility accessibilityLabel]
- -[FitDayCellLayerAccessibility accessibilityValue]
- -[FitDayCellLayerAccessibility isAccessibilityElement]
- -[WeekViewAccessibility accessibilityElements]
- GCC_except_table133
- GCC_except_table156
- GCC_except_table166
- GCC_except_table200
- GCC_except_table218
- GCC_except_table231
- GCC_except_table249
- GCC_except_table258
- GCC_except_table313
- GCC_except_table317
- GCC_except_table327
- GCC_except_table369
- GCC_except_table374
- GCC_except_table385
- GCC_except_table391
- GCC_except_table406
- GCC_except_table58
- GCC_except_table67
- GCC_except_table88
- _OBJC_CLASS_$_FitDayCellLayerAccessibility
- _OBJC_CLASS_$_WeekViewAccessibility
- _OBJC_CLASS_$___FitDayCellLayerAccessibility_super
- _OBJC_CLASS_$___WeekViewAccessibility_super
- _OBJC_METACLASS_$_FitDayCellLayerAccessibility
- _OBJC_METACLASS_$_WeekViewAccessibility
- _OBJC_METACLASS_$___FitDayCellLayerAccessibility_super
- _OBJC_METACLASS_$___WeekViewAccessibility_super
- __OBJC_$_CLASS_METHODS_FitDayCellLayerAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_WeekViewAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_FitDayCellLayerAccessibility
- __OBJC_$_INSTANCE_METHODS_WeekViewAccessibility
- __OBJC_CLASS_RO_$_FitDayCellLayerAccessibility
- __OBJC_CLASS_RO_$_WeekViewAccessibility
- __OBJC_CLASS_RO_$___FitDayCellLayerAccessibility_super
- __OBJC_CLASS_RO_$___WeekViewAccessibility_super
- __OBJC_METACLASS_RO_$_FitDayCellLayerAccessibility
- __OBJC_METACLASS_RO_$_WeekViewAccessibility
- __OBJC_METACLASS_RO_$___FitDayCellLayerAccessibility_super
- __OBJC_METACLASS_RO_$___WeekViewAccessibility_super
- _objc_msgSend$contents
CStrings:
+ "FitnessApp.TrendDownMetricCollectionViewCell"
+ "TrendDownMetricCollectionViewCellAccessibility"
+ "__TrendDownMetricCollectionViewCellAccessibility_super"
+ "metricView"
- "@64@0:8d16d24d32d40d48B56B60"
- "CALayer"
- "FitDayCellLayer"
- "FitDayCellLayerAccessibility"
- "WeekView"
- "WeekViewAccessibility"
- "__FitDayCellLayerAccessibility_super"
- "__WeekViewAccessibility_super"
- "activityCellImageWithDiameter: thickness: calories: briskMinutes: hourlyBreak: fadeInnerRings: fadeAll:"
- "activityCellImageWithDiameter:thickness:calories:briskMinutes:hourlyBreak:fadeInnerRings:fadeAll:"
- "contents"
- "isToday"
- "ringLayer"
```
