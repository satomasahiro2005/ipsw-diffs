## SystemApertureUI

> `/System/Library/PrivateFrameworks/SystemApertureUI.framework/SystemApertureUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15028` | `0x150dc` | **`+0xb4`** |
| `__TEXT.__objc_methlist` | `0x243c` | `0x244c` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xac4` | `0xad0` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x10b0` | `0x10b8` | **`+0x8`** |

### Other Changes

```diff

-96.0.0.0.0
+97.0.0.0.0

-  Functions: 602
+  Functions: 603
Symbols:
+ -[SAUISystemApertureManager _concurrentCeilingLayoutModeForElementViewController:preferredLayoutMode:indexOfElement:effectiveElementCount:maximumNumberOfElements:]
+ GCC_except_table55
- GCC_except_table54
- GCC_except_table61
Functions:
~ -[SAUISystemApertureManager _temporallyOrderedVisibleAlertAndActivityElements] : 648 -> 644
~ -[SAUISystemApertureManager _reevaluatePromotedElements] : 1780 -> 1860
~ -[SAUISystemApertureManager _elementViewControllerForElement:creatingIfNecessary:] : 1276 -> 1272
~ -[SAUIIndicatorElementViewController _enumerateObserversRespondingToSelector:usingBlock:] : 400 -> 396
~ -[SAUILayoutSpecifyingOverrider _firstParticipantThatRespondsToSelector:] : 372 -> 368
~ -[SAUILayoutSpecifyingElementViewController(SubclassSupport) temporallyOrderedAlertingActivityAssertions] : 416 -> 412
~ -[SAUILayoutSpecifyingElementViewController _enumerateObserversRespondingToSelector:usingBlock:] : 400 -> 396
~ -[SAUISystemApertureManager _purgeRemovedElementViewControllers] : 556 -> 552
~ -[SAUILayoutSpecifyingElementViewController isTrackingTransitionWithReason:] : 392 -> 388
~ -[SAUIBlankingRegionElementViewController _enumerateObserversRespondingToSelector:usingBlock:] : 400 -> 396
~ -[SAUISystemApertureManager registerElement:] : 1000 -> 996
~ -[SAUISystemApertureManager blankingRegionElementViewControllers] : 448 -> 444
+ -[SAUISystemApertureManager _concurrentCeilingLayoutModeForElementViewController:preferredLayoutMode:indexOfElement:effectiveElementCount:maximumNumberOfElements:]
~ -[SAUILayoutSpecifyingOverrider description] : 576 -> 572
```
