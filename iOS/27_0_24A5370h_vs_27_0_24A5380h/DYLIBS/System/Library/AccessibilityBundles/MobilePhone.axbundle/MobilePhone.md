## MobilePhone

> `/System/Library/AccessibilityBundles/MobilePhone.axbundle/MobilePhone`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ae8` | `0x4f08` | **`+0x420`** |
| `__AUTH_CONST.__cfstring` | `0x18c0` | `0x1aa0` | **`+0x1e0`** |
| `__DATA_DIRTY.__objc_data` | `0xc30` | `0xd70` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0x1988` | `0x1aa8` | **`+0x120`** |
| `__TEXT.__cstring` | `0x118b` | `0x1275` | **`+0xea`** |
| `__AUTH.__objc_data` | `0x140` | `0xa0` | **`-0xa0`** |
| `__TEXT.__objc_methlist` | `0x89c` | `0x91c` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x178` | `0x1e0` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x518` | `0x540` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x210` | `0x238` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x6c` | `0x84` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x158` | `0x168` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x158` | `0x168` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x68` | `0x70` | **`+0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 148
-  Symbols:   498
-  CStrings:  213
+  Functions: 161
+  Symbols:   523
+  CStrings:  228
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
+ GCC_except_table101
+ GCC_except_table52
+ GCC_except_table84
+ GCC_except_table86
+ _AXFormatInteger
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
+ ___block_descriptor_48_e8_32r_e5_v8?0lr32l8
- GCC_except_table72
- GCC_except_table74
- GCC_except_table89
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
+ "voicemailViewController"
- "_voicemailViewController"
```
