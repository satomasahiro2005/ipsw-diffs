## FitnessApp

> `/System/Library/AccessibilityBundles/FitnessApp.axbundle/FitnessApp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xee28` | `0xe6a8` | **`-0x780`** |
| `__DATA_CONST.__cfstring` | `0x3260` | `0x30a0` | **`-0x1c0`** |
| `__TEXT.__objc_stubs` | `0x1800` | `0x1680` | **`-0x180`** |
| `__TEXT.__objc_methname` | `0x1a4d` | `0x1906` | **`-0x147`** |
| `__TEXT.__cstring` | `0x2bbc` | `0x2a84` | **`-0x138`** |
| `__DATA.__objc_const` | `0x4f48` | `0x4e28` | **`-0x120`** |
| `__DATA.__objc_data` | `0x2bc0` | `0x2b20` | **`-0xa0`** |
| `__TEXT.__objc_methlist` | `0x1898` | `0x1800` | **`-0x98`** |
| `__DATA.__objc_selrefs` | `0x788` | `0x708` | **`-0x80`** |
| `__TEXT.__objc_classname` | `0x1987` | `0x1921` | **`-0x66`** |
| `__TEXT.__unwind_info` | `0x5b8` | `0x598` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0x1e3` | `0x1c5` | **`-0x1e`** |
| `__DATA_CONST.__got` | `0x180` | `0x170` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x460` | `0x450` | **`-0x10`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1040.4.0.0.0
+1040.4.1.0.0

-  Functions: 462
-  Symbols:   1543
-  CStrings:  735
+  Functions: 451
+  Symbols:   1508
+  CStrings:  700
Symbols:
+ GCC_except_table128
+ GCC_except_table151
+ GCC_except_table161
+ GCC_except_table195
+ GCC_except_table213
+ GCC_except_table226
+ GCC_except_table244
+ GCC_except_table253
+ GCC_except_table304
+ GCC_except_table308
+ GCC_except_table318
+ GCC_except_table360
+ GCC_except_table365
+ GCC_except_table382
+ GCC_except_table397
- +[CHWorkoutDetailHeartRateChartViewAccessibility _accessibilityPerformValidations:]
- +[CHWorkoutDetailHeartRateChartViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[CHWorkoutDetailHeartRateChartViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[CHWorkoutDetailHeartRateChartViewAccessibility _accessibilityHoursPerSlice]
- -[CHWorkoutDetailHeartRateChartViewAccessibility _accessibilityNumberOfSlices]
- -[CHWorkoutDetailHeartRateChartViewAccessibility _accessibilityQuantityForSliceAtIndex:]
- -[CHWorkoutDetailHeartRateChartViewAccessibility _accessibilityShouldUseSlices]
- -[CHWorkoutDetailHeartRateChartViewAccessibility _accessibilityTimeIntervalPerSlice]
- -[CHWorkoutDetailHeartRateChartViewAccessibility _axDateInterval]
- -[CHWorkoutDetailHeartRateChartViewAccessibility _decimalForDate:]
- -[CHWorkoutDetailHeartRateChartViewAccessibility accessibilityElements]
- GCC_except_table139
- GCC_except_table162
- GCC_except_table172
- GCC_except_table206
- GCC_except_table224
- GCC_except_table237
- GCC_except_table255
- GCC_except_table264
- GCC_except_table315
- GCC_except_table319
- GCC_except_table329
- GCC_except_table371
- GCC_except_table387
- GCC_except_table393
- GCC_except_table408
- _OBJC_CLASS_$_CHWorkoutDetailHeartRateChartViewAccessibility
- _OBJC_CLASS_$_HKHeartRateSummaryReading
- _OBJC_CLASS_$_NSDateInterval
- _OBJC_CLASS_$___CHWorkoutDetailHeartRateChartViewAccessibility_super
- _OBJC_METACLASS_$_CHWorkoutDetailHeartRateChartViewAccessibility
- _OBJC_METACLASS_$___CHWorkoutDetailHeartRateChartViewAccessibility_super
- __OBJC_$_CLASS_METHODS_CHWorkoutDetailHeartRateChartViewAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_CHWorkoutDetailHeartRateChartViewAccessibility
- __OBJC_CLASS_RO_$_CHWorkoutDetailHeartRateChartViewAccessibility
- __OBJC_CLASS_RO_$___CHWorkoutDetailHeartRateChartViewAccessibility_super
- __OBJC_METACLASS_RO_$_CHWorkoutDetailHeartRateChartViewAccessibility
- __OBJC_METACLASS_RO_$___CHWorkoutDetailHeartRateChartViewAccessibility_super
- _objc_msgSend$_accessibilityNumberOfSlices
- _objc_msgSend$_accessibilityTimeIntervalPerSlice
- _objc_msgSend$_axDateInterval
- _objc_msgSend$components:fromDate:
- _objc_msgSend$containsDate:
- _objc_msgSend$duration
- _objc_msgSend$hour
- _objc_msgSend$initWithStartDate:endDate:
- _objc_msgSend$minute
- _objc_msgSend$quantity
- _objc_msgSend$second
- _objc_msgSend$validateClass:conformsToProtocol:
CStrings:
- "@24@0:8Q16"
- "CHWorkoutDetailHeartRateChartView"
- "CHWorkoutDetailHeartRateChartViewAccessibility"
- "FIUIChartDataSource"
- "FIUIChartView"
- "HKQuantity"
- "__CHWorkoutDetailHeartRateChartViewAccessibility_super"
- "_accessibilityHoursPerSlice"
- "_accessibilityNumberOfSlices"
- "_accessibilityQuantityForSliceAtIndex:"
- "_accessibilityShouldUseSlices"
- "_accessibilityTimeIntervalPerSlice"
- "_axDateInterval"
- "_chartView"
- "_containerView"
- "_dateInterval"
- "_decimalForDate:"
- "_hasAdequateDataForDisplay"
- "_heartRateChartPoints"
- "_heartRateReadings"
- "ch_beatsPerMinute"
- "components:fromDate:"
- "containsDate:"
- "d16@0:8"
- "dateInterval"
- "duration"
- "f24@0:8@16"
- "heart.rate.graph.range"
- "heart.rate.graph.single"
- "hour"
- "initWithStartDate:endDate:"
- "minute"
- "quantity"
- "second"
- "validateClass:conformsToProtocol:"
```
