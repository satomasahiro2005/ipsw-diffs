## TSAccessibility

> `/private/var/staged_system_apps/Freeform.app/Frameworks/TSAccessibility.framework/TSAccessibility`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcd00` | `0xcc70` | **`-0x90`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-646.0.0.202.4
+649.0.0.0.3
Functions:
~ -[TSAccessibility performValidation] : 416 -> 412
~ -[TSUIApplicationAccessibility _tsaxMainWindow] : 552 -> 548
~ _TSAccessibilityInstallSafeCategories : 956 -> 920
~ +[TSAccessibilitySafeCategory _tsaxInstallSafeCategoryOnClass:] : 600 -> 588
~ ___TSAccessibilityValidateInstanceMethod : 304 -> 308
~ ___TSAccessibilityValidateBlockSignature : 1536 -> 1524
~ __TSAccessibilitySafeCategoryAddDependenciesToArray : 300 -> 296
~ -[TSAccessibilityGroupButtonElement(iOS) accessibilityTraits] : 288 -> 284
~ -[TSAccessibilitySummaryContainerElement initWithAccessibilityContainer:containedElements:] : 348 -> 344
~ -[TSAccessibilitySummaryContainerElement accessibilityFrame] : 556 -> 552
~ -[TSAccessibilitySummaryContainerElement accessibilityLabel] : 356 -> 352
~ -[UIView(TSAccessibility) tsaxAccessibleSubviews] : 552 -> 548
~ -[UIView(TSAccessibility) tsaxFirstAccessibleSubview] : 528 -> 524
~ -[TSUISliderAccessibility _tsaxPerformTargetActionsForControlEvents:] : 492 -> 488
~ -[NSMutableArray(TSAccessibility) tsaxAddObjectsInReverseOrder:] : 280 -> 276
~ -[TSAccessibilityEditMenuController editMenuTitlesForItemProvider:] : 512 -> 508
~ -[TSAccessibilityEditMenuController performActionTitled:forEditMenuProvider:] : 548 -> 544
~ -[TSAccessibilityEditMenuController _tsaxEditMenuCommandsFromMenuElements:firstResponder:] : 632 -> 620
~ -[NSObject(TSAccessibility_iOS) tsaxChildren] : 556 -> 552
~ -[NSObject(TSAccessibility_iOS) tsaxInvalidateChildren] : 464 -> 460
~ -[NSArray(TSAccessibility) tsaxExtractElementsOfType:] : 312 -> 308
~ -[NSArray(TSAccessibility) tsaxFirstElementOfType:] : 296 -> 292
~ -[NSArray(TSAccessibility) tsaxPerformBlock:onElementsOfType:] : 304 -> 300
~ -[TSAccessibilityGroupButtonElement _boundingFrame] : 352 -> 348
```
