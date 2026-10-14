## ScreenshotServicesService

> `/System/Library/AccessibilityBundles/ScreenshotServicesService.axbundle/ScreenshotServicesService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x990` | `0xab0` | **`+0x120`** |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x330` | `0x378` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x940` | `0x980` | **`+0x40`** |
| `__TEXT.__text` | `0x17a4` | `0x17dc` | **`+0x38`** |
| `__TEXT.__cstring` | `0x6cb` | `0x6e4` | **`+0x19`** |
| `__DATA_CONST.__objc_classlist` | `0x88` | `0x98` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f0` | `0x1f8` | **`+0x8`** |

### Other Changes

```diff

-3050.3.5.0.0
+3050.3.8.0.0

-  Functions: 64
-  Symbols:   219
-  CStrings:  86
+  Functions: 68
+  Symbols:   233
+  CStrings:  88
Symbols:
+ +[SSSDittoDebugViewAccessibility _accessibilityPerformValidations:]
+ +[SSSDittoDebugViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[SSSDittoDebugViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[SSSDittoDebugViewAccessibility accessibilityElementsHidden]
+ GCC_except_table56
+ _OBJC_CLASS_$_SSSDittoDebugViewAccessibility
+ _OBJC_CLASS_$___SSSDittoDebugViewAccessibility_super
+ _OBJC_METACLASS_$_SSSDittoDebugViewAccessibility
+ _OBJC_METACLASS_$___SSSDittoDebugViewAccessibility_super
+ __OBJC_$_CLASS_METHODS_SSSDittoDebugViewAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_SSSDittoDebugViewAccessibility
+ __OBJC_CLASS_RO_$_SSSDittoDebugViewAccessibility
+ __OBJC_CLASS_RO_$___SSSDittoDebugViewAccessibility_super
+ __OBJC_METACLASS_RO_$_SSSDittoDebugViewAccessibility
+ __OBJC_METACLASS_RO_$___SSSDittoDebugViewAccessibility_super
- GCC_except_table52
CStrings:
+ "SSSDittoDebugView"
+ "UIView"
```
