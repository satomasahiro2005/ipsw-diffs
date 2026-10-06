## CommunicationsUI

> `/System/Library/AccessibilityBundles/CommunicationsUI.axbundle/CommunicationsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__objc_data` | `—` | `0x190` | **`+0x190`** |
| `__AUTH_CONST.__objc_const` | `0x2d0` | `0x3f0` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x190` | `0xa0` | **`-0xf0`** |
| `__TEXT.__text` | `0x3c4` | `0x448` | **`+0x84`** |
| `__TEXT.__cstring` | `0x16d` | `0x1cf` | **`+0x62`** |
| `__TEXT.__objc_methlist` | `0xbc` | `0x104` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x180` | `0x1c0` | **`+0x40`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x38` | **`+0x10`** |
| `__DATA.__bss` | `0x10` | `0x8` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xa8` | `0xb0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x8` | `0x10` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `—` | `0x8` | **`+0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 15
-  Symbols:   69
-  CStrings:  15
+  Functions: 19
+  Symbols:   84
+  CStrings:  17
Symbols:
+ +[ContactAvatarTileForegroundUIViewAccessibility _accessibilityPerformValidations:]
+ +[ContactAvatarTileForegroundUIViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[ContactAvatarTileForegroundUIViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[ContactAvatarTileForegroundUIViewAccessibility isAccessibilityElement]
+ _AXDoesRequestingClientDeserveAutomation
+ _OBJC_CLASS_$_ContactAvatarTileForegroundUIViewAccessibility
+ _OBJC_CLASS_$___ContactAvatarTileForegroundUIViewAccessibility_super
+ _OBJC_METACLASS_$_ContactAvatarTileForegroundUIViewAccessibility
+ _OBJC_METACLASS_$___ContactAvatarTileForegroundUIViewAccessibility_super
+ __OBJC_$_CLASS_METHODS_ContactAvatarTileForegroundUIViewAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_ContactAvatarTileForegroundUIViewAccessibility
+ __OBJC_CLASS_RO_$_ContactAvatarTileForegroundUIViewAccessibility
+ __OBJC_CLASS_RO_$___ContactAvatarTileForegroundUIViewAccessibility_super
+ __OBJC_METACLASS_RO_$_ContactAvatarTileForegroundUIViewAccessibility
+ __OBJC_METACLASS_RO_$___ContactAvatarTileForegroundUIViewAccessibility_super
Functions:
~ ___55+[AXCommunicationsUIGlue accessibilityInitializeBundle]_block_invoke_3 : 92 -> 112
CStrings:
+ "CommunicationsUI.ContactAvatarTileForegroundUIView"
+ "ContactAvatarTileForegroundUIViewAccessibility"
```
