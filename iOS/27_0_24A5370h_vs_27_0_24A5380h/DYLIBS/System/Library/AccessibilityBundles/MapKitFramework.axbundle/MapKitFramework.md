## MapKitFramework

> `/System/Library/AccessibilityBundles/MapKitFramework.axbundle/MapKitFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xabd4` | `0xb17c` | **`+0x5a8`** |
| `__AUTH_CONST.__cfstring` | `0x2940` | `0x29a0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x2011` | `0x2067` | **`+0x56`** |
| `__TEXT.__objc_methlist` | `0x1254` | `0x129c` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x700` | `0x730` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x420` | `0x430` | **`+0x10`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 349
-  Symbols:   1039
-  CStrings:  365
+  Functions: 355
+  Symbols:   1047
+  CStrings:  368
Symbols:
+ -[MKMapViewAccessibility _axIsHostedInLocationConsentSecureWindow]
+ -[MKMapViewAccessibility accessibilityLabel]
+ -[MKMapViewAccessibility accessibilityTraits]
+ -[MKMapViewAccessibility isAccessibilityElement]
+ -[UIButtonAccessibility__MapKit__UIKit _axIsDuplicateButtonInLocationConsentSecureWindow]
+ -[UIButtonAccessibility__MapKit__UIKit isAccessibilityElement]
+ GCC_except_table108
+ GCC_except_table135
+ GCC_except_table158
+ GCC_except_table175
+ _CGRectEqualToRect
+ _OBJC_CLASS_$_AXRemoteElement
+ _OBJC_CLASS_$_NSNumber
- GCC_except_table104
- GCC_except_table131
- GCC_except_table154
- GCC_except_table171
- _objc_retainAutoreleaseReturnValue
CStrings:
+ "AXIsDuplicateInLocationConsent"
+ "AXIsInLocationConsentWindow"
+ "_UIViewServiceSecureWindow"
```
