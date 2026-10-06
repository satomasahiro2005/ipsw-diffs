## Bridge

> `/System/Library/AccessibilityBundles/Bridge.axbundle/Bridge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x1cf0` | `0x1e10` | **`+0x120`** |
| `__AUTH.__objc_data` | `0xff0` | `0x1090` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x854` | `0x89c` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x1020` | `0x1060` | **`+0x40`** |
| `__TEXT.__cstring` | `0xc7e` | `0xcb3` | **`+0x35`** |
| `__TEXT.__text` | `0x2e40` | `0x2e74` | **`+0x34`** |
| `__DATA_CONST.__objc_classlist` | `0x198` | `0x1a8` | **`+0x10`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 146
-  Symbols:   486
-  CStrings:  144
+  Functions: 150
+  Symbols:   501
+  CStrings:  146
Symbols:
+ +[COSAppInstallButtonAccessibility _accessibilityPerformValidations:]
+ +[COSAppInstallButtonAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[COSAppInstallButtonAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[COSAppInstallButtonAccessibility accessibilityLabel]
+ GCC_except_table104
+ _OBJC_CLASS_$_COSAppInstallButtonAccessibility
+ _OBJC_CLASS_$___COSAppInstallButtonAccessibility_super
+ _OBJC_METACLASS_$_COSAppInstallButtonAccessibility
+ _OBJC_METACLASS_$___COSAppInstallButtonAccessibility_super
+ _UIAXStringForAllChildren
+ __OBJC_$_CLASS_METHODS_COSAppInstallButtonAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_COSAppInstallButtonAccessibility
+ __OBJC_CLASS_RO_$_COSAppInstallButtonAccessibility
+ __OBJC_CLASS_RO_$___COSAppInstallButtonAccessibility_super
+ __OBJC_METACLASS_RO_$_COSAppInstallButtonAccessibility
+ __OBJC_METACLASS_RO_$___COSAppInstallButtonAccessibility_super
- GCC_except_table100
CStrings:
+ "COSAppInstallButton"
+ "COSAppInstallButtonAccessibility"
```
