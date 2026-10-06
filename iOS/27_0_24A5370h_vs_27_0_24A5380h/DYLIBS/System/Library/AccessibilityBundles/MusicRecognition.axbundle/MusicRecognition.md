## MusicRecognition

> `/System/Library/AccessibilityBundles/MusicRecognition.axbundle/MusicRecognition`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x2d0` | `0x3f0` | **`+0x120`** |
| `__TEXT.__text` | `0x2ec` | `0x3bc` | **`+0xd0`** |
| `__AUTH.__objc_data` | `0x190` | `0x230` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x156` | `0x1ae` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0xa4` | `0xec` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x160` | `0x1a0` | **`+0x40`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x38` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x80` | `0x88` | **`+0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 13
-  Symbols:   67
-  CStrings:  14
+  Functions: 17
+  Symbols:   81
+  CStrings:  16
Symbols:
+ +[ActivityListeningViewAccessibility _accessibilityPerformValidations:]
+ +[ActivityListeningViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[ActivityListeningViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ +[AmbientListeningViewAccessibility _accessibilityPerformValidations:]
+ +[AmbientListeningViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[AmbientListeningViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[ActivityListeningViewAccessibility _accessibilityLoadAccessibilityInformation]
+ -[AmbientListeningViewAccessibility _accessibilityLoadAccessibilityInformation]
+ _OBJC_CLASS_$_ActivityListeningViewAccessibility
+ _OBJC_CLASS_$_AmbientListeningViewAccessibility
+ _OBJC_CLASS_$___ActivityListeningViewAccessibility_super
+ _OBJC_CLASS_$___AmbientListeningViewAccessibility_super
+ _OBJC_METACLASS_$_ActivityListeningViewAccessibility
+ _OBJC_METACLASS_$_AmbientListeningViewAccessibility
+ _OBJC_METACLASS_$___ActivityListeningViewAccessibility_super
+ _OBJC_METACLASS_$___AmbientListeningViewAccessibility_super
+ __OBJC_$_CLASS_METHODS_ActivityListeningViewAccessibility(SafeCategory)
+ __OBJC_$_CLASS_METHODS_AmbientListeningViewAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_ActivityListeningViewAccessibility
+ __OBJC_$_INSTANCE_METHODS_AmbientListeningViewAccessibility
+ __OBJC_CLASS_RO_$_ActivityListeningViewAccessibility
+ __OBJC_CLASS_RO_$_AmbientListeningViewAccessibility
+ __OBJC_CLASS_RO_$___ActivityListeningViewAccessibility_super
+ __OBJC_CLASS_RO_$___AmbientListeningViewAccessibility_super
+ __OBJC_METACLASS_RO_$_ActivityListeningViewAccessibility
+ __OBJC_METACLASS_RO_$_AmbientListeningViewAccessibility
+ __OBJC_METACLASS_RO_$___ActivityListeningViewAccessibility_super
+ __OBJC_METACLASS_RO_$___AmbientListeningViewAccessibility_super
- +[ListeningViewAccessibility _accessibilityPerformValidations:]
- +[ListeningViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[ListeningViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[ListeningViewAccessibility _accessibilityLoadAccessibilityInformation]
- _OBJC_CLASS_$_ListeningViewAccessibility
- _OBJC_CLASS_$___ListeningViewAccessibility_super
- _OBJC_METACLASS_$_ListeningViewAccessibility
- _OBJC_METACLASS_$___ListeningViewAccessibility_super
- __OBJC_$_CLASS_METHODS_ListeningViewAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_ListeningViewAccessibility
- __OBJC_CLASS_RO_$_ListeningViewAccessibility
- __OBJC_CLASS_RO_$___ListeningViewAccessibility_super
- __OBJC_METACLASS_RO_$_ListeningViewAccessibility
- __OBJC_METACLASS_RO_$___ListeningViewAccessibility_super
CStrings:
+ "ActivityListeningViewAccessibility"
+ "AmbientListeningViewAccessibility"
+ "MusicRecognition.ActivityListeningView"
+ "MusicRecognition.AmbientListeningView"
- "ListeningViewAccessibility"
- "MusicRecognition.ListeningView"
```
