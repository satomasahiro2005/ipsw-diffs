## Spotlight

> `/System/Library/AccessibilityBundles/Spotlight.axbundle/Spotlight`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7ac` | `0x1b0` | **`-0x5fc`** |
| `__AUTH_CONST.__objc_const` | `0x2d0` | `0x90` | **`-0x240`** |
| `__DATA_DIRTY.__objc_data` | `0x190` | `0x50` | **`-0x140`** |
| `__AUTH_CONST.__cfstring` | `0x180` | `0x80` | **`-0x100`** |
| `__TEXT.__cstring` | `0x137` | `0x62` | **`-0xd5`** |
| `__TEXT.__objc_methlist` | `0xd4` | `0x14` | **`-0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0xf0` | `0x48` | **`-0xa8`** |
| `__DATA_CONST.__const` | `0xb8` | `0x40` | **`-0x78`** |
| `__TEXT.__oslogstring` | `0x51` | `—` | **`-0x51`** |
| `__TEXT.__unwind_info` | `0xa0` | `0x70` | **`-0x30`** |
| `__DATA_CONST.__got` | `0x38` | `0x18` | **`-0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x8` | **`-0x20`** |
| `__TEXT.__const` | `0x18` | `—` | **`-0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x8` | `—` | **`-0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 20
-  Symbols:   88
-  CStrings:  20
+  Functions: 5
+  Symbols:   34
+  CStrings:  6
Symbols:
- +[SPUISearchBarWindowAccessibility _accessibilityPerformValidations:]
- +[SPUISearchBarWindowAccessibility(SafeCategory) safeCategoryBaseClass]
- +[SPUISearchBarWindowAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[SPUISecureWindowAccessibility _accessibilityPerformValidations:]
- +[SPUISecureWindowAccessibility(SafeCategory) safeCategoryBaseClass]
- +[SPUISecureWindowAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[SPUISearchBarWindowAccessibility _accessibilityIgnoresStatusBarFrame]
- -[SPUISearchBarWindowAccessibility _accessibilityLoadAccessibilityInformation]
- -[SPUISearchBarWindowAccessibility accessibilityElementsHidden]
- -[SPUISearchBarWindowAccessibility dealloc]
- -[SPUISearchBarWindowAccessibility init]
- -[SPUISecureWindowAccessibility accessibilityElementsHidden]
- _AXLogCommon
- _AXPerformBlockAsynchronouslyOnMainThread
- _OBJC_CLASS_$_AXSpringBoardServer
- _OBJC_CLASS_$_SPUISearchBarWindowAccessibility
- _OBJC_CLASS_$_SPUISecureWindowAccessibility
- _OBJC_CLASS_$_UIAccessibilitySafeCategory
- _OBJC_CLASS_$_UIWindow
- _OBJC_CLASS_$___SPUISearchBarWindowAccessibility_super
- _OBJC_CLASS_$___SPUISecureWindowAccessibility_super
- _OBJC_METACLASS_$_SPUISearchBarWindowAccessibility
- _OBJC_METACLASS_$_SPUISecureWindowAccessibility
- _OBJC_METACLASS_$_UIAccessibilitySafeCategory
- _OBJC_METACLASS_$___SPUISearchBarWindowAccessibility_super
- _OBJC_METACLASS_$___SPUISecureWindowAccessibility_super
- __NSConcreteStackBlock
- __OBJC_$_CLASS_METHODS_SPUISearchBarWindowAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_SPUISecureWindowAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_SPUISearchBarWindowAccessibility
- __OBJC_$_INSTANCE_METHODS_SPUISecureWindowAccessibility
- __OBJC_CLASS_RO_$_SPUISearchBarWindowAccessibility
- __OBJC_CLASS_RO_$_SPUISecureWindowAccessibility
- __OBJC_CLASS_RO_$___SPUISearchBarWindowAccessibility_super
- __OBJC_CLASS_RO_$___SPUISecureWindowAccessibility_super
- __OBJC_METACLASS_RO_$_SPUISearchBarWindowAccessibility
- __OBJC_METACLASS_RO_$_SPUISecureWindowAccessibility
- __OBJC_METACLASS_RO_$___SPUISearchBarWindowAccessibility_super
- __OBJC_METACLASS_RO_$___SPUISecureWindowAccessibility_super
- ___78-[SPUISearchBarWindowAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke
- ___UIAccessibilityCastAsClass
- ___block_descriptor_40_e8_32s_e18_v16?0"NSString"8ls32l8
- ___block_descriptor_40_e8_32s_e25_v24?0q8"NSDictionary"16ls32l8
- ___block_descriptor_40_e8_32s_e5_v8?0ls32l8
- __os_log_debug_impl
- __os_log_impl
- _abort
- _objc_msgSendSuper2
- _objc_release
- _objc_release_x20
- _objc_release_x21
- _objc_retainAutoreleasedReturnValue
- _objc_retain_x2
- _os_log_type_enabled
Functions:
~ ___48+[AXSpotlightGlue accessibilityInitializeBundle]_block_invoke_3 : 92 -> 4
CStrings:
- "SPUISearchBarWindow"
- "SPUISearchBarWindowAccessibility"
- "SPUISecureWindow"
- "SPUISecureWindowAccessibility"
- "Spotlight register: %@"
- "Spotlight visible change: %@"
- "Spotlight visible status: %d"
- "UIWindow"
- "actionHandlerIdentifier"
- "isSpotlightVisible"
- "isVisible"
- "v16@?0@\"NSString\"8"
- "v24@?0q8@\"NSDictionary\"16"
- "v8@?0"
```
