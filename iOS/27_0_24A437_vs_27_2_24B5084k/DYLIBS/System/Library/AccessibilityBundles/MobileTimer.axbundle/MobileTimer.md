## MobileTimer

> `/System/Library/AccessibilityBundles/MobileTimer.axbundle/MobileTimer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8eb0` | `0x8bdc` | **`-0x2d4`** |
| `__AUTH_CONST.__cfstring` | `0x2580` | `0x24c0` | **`-0xc0`** |
| `__TEXT.__cstring` | `0x17d9` | `0x179e` | **`-0x3b`** |
| `__TEXT.__objc_methlist` | `0xfb8` | `0xf88` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x2a0` | `0x2c8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x770` | `0x758` | **`-0x18`** |
| `__TEXT.__gcc_except_tab` | `0x1cc` | `0x1e0` | **`+0x14`** |
| `__TEXT.__unwind_info` | `0x3f0` | `0x3f8` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 305
+  Functions: 301

-  CStrings:  324
+  CStrings:  319
Symbols:
+ GCC_except_table175
+ GCC_except_table219
+ GCC_except_table247
+ GCC_except_table48
+ GCC_except_table56
+ GCC_except_table65
+ GCC_except_table68
+ GCC_except_table80
+ GCC_except_table83
+ _AXDeviceGetMainScreenBounds
+ _CGRectIntersection
+ _OBJC_CLASS_$_UIPageControl
+ _UIAccessibilityConvertFrameToScreenCoordinates
+ ___75-[MTAAlarmEditViewControllerAccessibility tableView:cellForRowAtIndexPath:]_block_invoke
+ ___block_descriptor_40_e8_32w_e36_{CGRect={CGPoint=dd}{CGSize=dd}}8?0lw32l8
- -[MT_UIPageControlAccessibility _axPagingController]
- -[MT_UIPageControlAccessibility _axStopWatchAdjustPage:]
- -[MT_UIPageControlAccessibility accessibilityDecrement]
- -[MT_UIPageControlAccessibility accessibilityIncrement]
- GCC_except_table174
- GCC_except_table218
- GCC_except_table246
- GCC_except_table55
- GCC_except_table64
- GCC_except_table67
- GCC_except_table79
- GCC_except_table82
- _OBJC_CLASS_$_UIViewController
- ___56-[MT_UIPageControlAccessibility _axStopWatchAdjustPage:]_block_invoke
- _objc_retain_x3
CStrings:
+ "{CGRect={CGPoint=dd}{CGSize=dd}}8@?0"
- "MTAStopwatchPagingViewController"
- "NSArray"
- "currentPage"
- "pages"
- "pagingViewController"
- "setCurrentPage:"
```
