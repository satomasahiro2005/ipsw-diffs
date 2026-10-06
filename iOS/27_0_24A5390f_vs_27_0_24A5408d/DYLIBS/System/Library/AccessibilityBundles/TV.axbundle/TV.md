## TV

> `/System/Library/AccessibilityBundles/TV.axbundle/TV`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2964` | `0x2af8` | **`+0x194`** |
| `__DATA_CONST.__objc_selrefs` | `0x2d0` | `0x2e8` | **`+0x18`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Symbols:   332
+  Symbols:   334
Symbols:
+ _AXAttributedStringForVariables3
+ _AXCompactDurationStringForDuration
Functions:
~ -[VideosChaptersTableViewControllerAccessibility tableView:cellForRowAtIndexPath:] : 692 -> 892
~ -[VideosTVEpisodesTableViewControllerAccessibility configureCell:atIndexPath:withEntity:invalidationContext:] : 528 -> 732
```
