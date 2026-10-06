## NetAppsUtilitiesUI

> `/System/Library/PrivateFrameworks/NetAppsUtilitiesUI.framework/NetAppsUtilitiesUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77ac` | `0x7774` | **`-0x38`** |

### Other Changes

```text
Functions:
~ +[UIView(NAUIAutolayoutDebugging) _naui_beginDebuggingAutolayout] : 760 -> 756
~ -[UITableView(NAUIAdditions) naui_applyGroupedItemDiff:] : 1100 -> 1092
~ +[NSLayoutConstraint(NAUIAdditions) naui_viewsInConstraints:] : 464 -> 460
~ +[NSLayoutConstraint(NAUIAdditions) naui_constraintsWithVisualFormat:options:metrics:views:label:] : 348 -> 344
~ +[NAUIContentSizeLayoutConstraint _maximumWidthOfStrings:withFont:] : 344 -> 340
~ -[NAUILayoutConstraintSet updateConstraintConstants] : 584 -> 580
~ -[UIView(NAUIAutolayoutDebugging) naui_descendantsWithAmbiguousLayout] : 368 -> 364
~ -[UIViewController(NAUIUIKitDebugging) _recursiveDescriptionWithInset:] : 564 -> 560
~ -[NAUIUIViewControllerNoticationObserver dealloc] : 316 -> 312
~ -[UIView(NAUIAdditions) naui_showAllViewBoundsRecursively:] : 388 -> 384
~ -[UIView(NAUIAdditions) naui_addAutoLayoutSubviews:] : 244 -> 240
~ +[UIView(NAUIAdditions) naui_prepareToAutolayoutProperDescendantsOfView:inConstraints:] : 300 -> 296
~ -[UIView(NAUIAdditions) naui_removeNamedConstraints] : 280 -> 276
```
