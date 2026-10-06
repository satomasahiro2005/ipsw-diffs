## EventKitUIFramework

> `/System/Library/AccessibilityBundles/EventKitUIFramework.axbundle/EventKitUIFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x370` | `0x190` | **`-0x1e0`** |
| `__DATA_DIRTY.__objc_data` | `0x1f90` | `0x2170` | **`+0x1e0`** |
| `__TEXT.__cstring` | `0x2d92` | `0x2da1` | **`+0xf`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0
Symbols:
+ -[EKDayViewAccessibility initWithFrame:sizeClass:aspectRatioType:displayDate:backgroundColor:opaque:scrollbarShowsInside:isMiniPreviewInEventDetail:rightClickDelegate:]
- -[EKDayViewAccessibility initWithFrame:sizeClass:orientation:displayDate:backgroundColor:opaque:scrollbarShowsInside:isMiniPreviewInEventDetail:rightClickDelegate:]
CStrings:
+ "EKEventDetailTableView"
+ "initWithFrame:sizeClass:aspectRatioType:displayDate:backgroundColor:opaque:scrollbarShowsInside:isMiniPreviewInEventDetail:rightClickDelegate:"
- "UITableView"
- "initWithFrame:sizeClass:orientation:displayDate:backgroundColor:opaque:scrollbarShowsInside:isMiniPreviewInEventDetail:rightClickDelegate:"
```
