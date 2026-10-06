## InCallService

> `/System/Library/AccessibilityBundles/InCallService.axbundle/InCallService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4920` | `0x4d40` | **`+0x420`** |
| `__AUTH_CONST.__cfstring` | `0x1360` | `0x1540` | **`+0x1e0`** |
| `__AUTH_CONST.__objc_const` | `0x1710` | `0x1830` | **`+0x120`** |
| `__TEXT.__cstring` | `0xe3a` | `0xf25` | **`+0xeb`** |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x858` | `0x8d8` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x1c0` | `0x228` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x4e8` | `0x518` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x238` | `0x268` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0xa0` | `0xb8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x128` | `0x138` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x148` | `0x158` | **`+0x10`** |
| `__DATA.__bss` | `0x20` | `0x18` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x68` | `0x70` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__const` | `0x18` | `0x20` | **`+0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 163
-  Symbols:   504
-  CStrings:  172
+  Functions: 176
+  Symbols:   532
+  CStrings:  187
Symbols:
+ +[PHCarPlayNumberPadButtonAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PHCarPlayNumberPadButtonAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[PHCarPlayNumberPadButtonAccessibility _accessibilityKeyboardKeyAllowsTouchTyping]
+ -[PHCarPlayNumberPadButtonAccessibility _accessibilityNumberPadCharacter]
+ -[PHCarPlayNumberPadButtonAccessibility accessibilityLabel]
+ -[PHCarPlayNumberPadButtonAccessibility accessibilityPath]
+ -[PHCarPlayNumberPadButtonAccessibility accessibilityTraits]
+ -[PHCarPlayNumberPadButtonAccessibility accessibilityValue]
+ -[PHCarPlayNumberPadButtonAccessibility isAccessibilityElement]
+ GCC_except_table156
+ GCC_except_table170
+ _NSClassFromString
+ _OBJC_CLASS_$_PHCarPlayNumberPadButtonAccessibility
+ _OBJC_CLASS_$___PHCarPlayNumberPadButtonAccessibility_super
+ _OBJC_METACLASS_$_PHCarPlayNumberPadButtonAccessibility
+ _OBJC_METACLASS_$___PHCarPlayNumberPadButtonAccessibility_super
+ _UIAccessibilityTraitKeyboardKey
+ _UIAccessibilityTraitPlaysSound
+ __OBJC_$_CLASS_METHODS_PHCarPlayNumberPadButtonAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_PHCarPlayNumberPadButtonAccessibility
+ __OBJC_CLASS_RO_$_PHCarPlayNumberPadButtonAccessibility
+ __OBJC_CLASS_RO_$___PHCarPlayNumberPadButtonAccessibility_super
+ __OBJC_METACLASS_RO_$_PHCarPlayNumberPadButtonAccessibility
+ __OBJC_METACLASS_RO_$___PHCarPlayNumberPadButtonAccessibility_super
+ ___59-[PHCarPlayNumberPadButtonAccessibility accessibilityValue]_block_invoke
+ ___Block_byref_object_copy_
+ ___Block_byref_object_dispose_
+ ___block_descriptor_48_e8_32r_e5_v8?0lr32l8
+ _objc_release_x1
- GCC_except_table158
CStrings:
+ "2.key.hint"
+ "3.key.hint"
+ "4.key.hint"
+ "5.key.hint"
+ "6.key.hint"
+ "7.key.hint"
+ "8.key.hint"
+ "9.key.hint"
+ "PHCarPlayNumberPadButton"
+ "PHCarPlayNumberPadButtonAccessibility"
+ "TPNumberPadButton"
+ "character"
+ "number.pad.delete"
+ "number.pad.octothorpe"
+ "number.pad.star"
```
