## PencilKit

> `/System/Library/AccessibilityBundles/PencilKit.axbundle/PencilKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x1ef0` | `0x2010` | **`+0x120`** |
| `__TEXT.__text` | `0x426c` | `0x435c` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x13ae` | `0x145f` | **`+0xb1`** |
| `__AUTH.__objc_data` | `0xa0` | `0x140` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x1940` | `0x19c0` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x9f8` | `0xa30` | **`+0x38`** |
| `__DATA_CONST.__objc_classlist` | `0x1b8` | `0x1c8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2e0` | `0x2e8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xa0` | `0xa8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x240` | `0x248` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 173
-  Symbols:   545
-  CStrings:  218
+  Functions: 177
+  Symbols:   558
+  CStrings:  222
Symbols:
+ +[PKSqueezePaletteIntelligenceLightFactoryAccessibility _accessibilityPerformValidations:]
+ +[PKSqueezePaletteIntelligenceLightFactoryAccessibility makeIntelligenceButtonWithConfiguration:primaryAction:]
+ +[PKSqueezePaletteIntelligenceLightFactoryAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PKSqueezePaletteIntelligenceLightFactoryAccessibility(SafeCategory) safeCategoryTargetClassName]
+ GCC_except_table121
+ _OBJC_CLASS_$_PKSqueezePaletteIntelligenceLightFactoryAccessibility
+ _OBJC_CLASS_$___PKSqueezePaletteIntelligenceLightFactoryAccessibility_super
+ _OBJC_METACLASS_$_PKSqueezePaletteIntelligenceLightFactoryAccessibility
+ _OBJC_METACLASS_$___PKSqueezePaletteIntelligenceLightFactoryAccessibility_super
+ __OBJC_$_CLASS_METHODS_PKSqueezePaletteIntelligenceLightFactoryAccessibility(SafeCategory)
+ __OBJC_CLASS_RO_$_PKSqueezePaletteIntelligenceLightFactoryAccessibility
+ __OBJC_CLASS_RO_$___PKSqueezePaletteIntelligenceLightFactoryAccessibility_super
+ __OBJC_METACLASS_RO_$_PKSqueezePaletteIntelligenceLightFactoryAccessibility
+ __OBJC_METACLASS_RO_$___PKSqueezePaletteIntelligenceLightFactoryAccessibility_super
- GCC_except_table117
CStrings:
+ "PKSqueezePaletteIntelligenceLightFactory"
+ "PKSqueezePaletteIntelligenceLightFactoryAccessibility"
+ "makeIntelligenceButtonWithConfiguration:primaryAction:"
+ "squeeze.visualintelligence"
```
