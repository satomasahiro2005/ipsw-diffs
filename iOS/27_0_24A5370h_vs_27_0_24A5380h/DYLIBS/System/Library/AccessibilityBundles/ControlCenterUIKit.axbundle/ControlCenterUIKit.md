## ControlCenterUIKit

> `/System/Library/AccessibilityBundles/ControlCenterUIKit.axbundle/ControlCenterUIKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5784` | `0x586c` | **`+0xe8`** |
| `__AUTH.__objc_data` | `0xf0` | `0x50` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x870` | `0x910` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0xf40` | `0xee0` | **`-0x60`** |
| `__TEXT.__cstring` | `0xecf` | `0xe8c` | **`-0x43`** |
| `__AUTH_CONST.__const` | `0x160` | `0x180` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x450` | `0x440` | **`-0x10`** |
| `__DATA_CONST.__got` | `0xc8` | `0xd0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x278` | `0x280` | **`+0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Symbols:   461
-  CStrings:  149
+  Symbols:   464
+  CStrings:  145
Symbols:
+ ___stack_chk_fail
+ ___stack_chk_guard
+ _objc_enumerationMutation
+ _objc_release_x25
- _objc_retain_x23
Functions:
~ +[CCUIControlTemplateViewAccessibility _accessibilityPerformValidations:] : 428 -> 340
~ -[CCUIControlTemplateViewAccessibility accessibilityActivate] : 404 -> 652
~ ___61-[CCUIControlTemplateViewAccessibility accessibilityActivate]_block_invoke : 8 -> 80
CStrings:
+ "CCUIConnectivityModuleViewController"
+ "contentViewController"
+ "orderedButtonViewControllers"
- "CCUIAirDropModuleViewController"
- "NSMutableArray"
- "UIGestureRecognizer"
- "UIGestureRecognizerTarget"
- "_glyphViewForExpandedConnectivityModuleTapped"
- "_targets"
- "target"
```
