## QuickLook

> `/System/Library/AccessibilityBundles/QuickLook.axbundle/QuickLook`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3054` | `0x3120` | **`+0xcc`** |
| `__AUTH_CONST.__cfstring` | `0xe00` | `0xe40` | **`+0x40`** |
| `__TEXT.__cstring` | `0xa83` | `0xa9c` | **`+0x19`** |
| `__TEXT.__objc_methlist` | `0x4ec` | `0x504` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2e0` | `0x2f0` | **`+0x10`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 96
-  Symbols:   353
-  CStrings:  134
+  Functions: 98
+  Symbols:   355
+  CStrings:  136
Symbols:
+ -[QLOverlayPlayButtonAccessibility _accessibilityUpdatePlayButtonLabelForPlaying:]
+ -[QLOverlayPlayButtonAccessibility setPlaying:]
+ GCC_except_table81
- GCC_except_table79
Functions:
~ +[QLOverlayPlayButtonAccessibility _accessibilityPerformValidations:] : 172 -> 212
~ -[QLOverlayPlayButtonAccessibility _accessibilityLoadAccessibilityInformation] : 132 -> 80
+ -[QLOverlayPlayButtonAccessibility _accessibilityUpdatePlayButtonLabelForPlaying:]
+ -[QLOverlayPlayButtonAccessibility setPlaying:]
CStrings:
+ "pause.button"
+ "setPlaying:"
```
