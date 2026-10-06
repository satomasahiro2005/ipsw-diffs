## MobileTimer

> `/System/Library/AccessibilityBundles/MobileTimer.axbundle/MobileTimer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8bdc` | `0x8c24` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x24c0` | `0x2500` | **`+0x40`** |
| `__TEXT.__cstring` | `0x179e` | `0x17b4` | **`+0x16`** |
| `__DATA_CONST.__objc_selrefs` | `0x758` | `0x760` | **`+0x8`** |

### Other Changes

```diff

-3050.3.1.0.0
+3050.3.5.0.0

-  CStrings:  319
+  CStrings:  321
Functions:
~ +[MTATimerRecentViewAccessibility _accessibilityPerformValidations:] : 156 -> 188
~ -[MTATimerRecentViewAccessibility accessibilityLabel] : 268 -> 308
CStrings:
+ "MTTimerDuration"
+ "title"
```
