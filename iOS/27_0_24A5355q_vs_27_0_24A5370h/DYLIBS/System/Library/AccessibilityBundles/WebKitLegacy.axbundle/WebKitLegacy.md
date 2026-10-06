## WebKitLegacy

> `/System/Library/AccessibilityBundles/WebKitLegacy.axbundle/WebKitLegacy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4354` | `0x4360` | **`+0xc`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  Symbols:   352
+  Symbols:   353
Symbols:
+ _AXProcessIsSandboxedWebKitProcess
Functions:
~ -[UIWebDocumentViewAccessibility _accessibilityResponderElement] : 552 -> 548
~ -[UIWebDocumentViewAccessibility dealloc] : 312 -> 308
~ -[UIWebDocumentViewAccessibility _accessibilityHitTest:withEvent:] : 908 -> 904
~ +[AXWebKitGlueLegacy accessibilityInitializeBundle] : 152 -> 176
```
