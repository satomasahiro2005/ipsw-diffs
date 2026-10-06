## CoverSheet

> `/System/Library/AccessibilityBundles/CoverSheet.axbundle/CoverSheet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x1e40` | `0x1ee0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x18cf` | `0x1934` | **`+0x65`** |
| `__TEXT.__text` | `0x5cbc` | `0x5d1c` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x2d0` | `0x2d8` | **`+0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  CStrings:  268
+  CStrings:  273
Functions:
~ ___49+[AXCoverSheetGlue accessibilityInitializeBundle]_block_invoke : 40 -> 340
~ ___49+[AXCoverSheetGlue accessibilityInitializeBundle]_block_invoke_3 : 644 -> 452
~ _AXSBMainDisplayWindowScene : 312 -> 308
~ _AXSBContinuityDisplayWindowScene : 312 -> 308
~ -[CSCoverSheetViewAccessibility _childFocusViews] : 420 -> 416
CStrings:
+ "CSProminentDisplayView"
+ "CSProminentSubtitleDateView"
+ "CSProminentTextElementView"
+ "subtitleView"
+ "textLabel"
```
