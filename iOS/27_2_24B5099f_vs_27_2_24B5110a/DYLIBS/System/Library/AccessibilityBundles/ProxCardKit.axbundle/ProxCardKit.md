## ProxCardKit

> `/System/Library/AccessibilityBundles/ProxCardKit.axbundle/ProxCardKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9c4` | `0xe2c` | **`+0x468`** |
| `__AUTH_CONST.__cfstring` | `0x360` | `0x4a0` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0x630` | `0x750` | **`+0x120`** |
| `__TEXT.__cstring` | `0x240` | `0x2e8` | **`+0xa8`** |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x1dc` | `0x274` | **`+0x98`** |
| `__DATA_CONST.__objc_selrefs` | `0x108` | `0x158` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x48` | `0x80` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0xa8` | `0xc0` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x58` | `0x68` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x20` | `0x28` | **`+0x8`** |

### Other Changes

```diff

-3050.3.5.0.0
+3050.3.8.0.0

-  Functions: 35
-  Symbols:   130
-  CStrings:  34
+  Functions: 46
+  Symbols:   164
+  CStrings:  44
Symbols:
+ +[PRXPasscodeEntryViewAccessibility _accessibilityPerformValidations:]
+ +[PRXPasscodeEntryViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[PRXPasscodeEntryViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[PRXPasscodeEntryViewAccessibility accessibilityActivate]
+ -[PRXPasscodeEntryViewAccessibility accessibilityAttributedValue]
+ -[PRXPasscodeEntryViewAccessibility accessibilityLabel]
+ -[PRXPasscodeEntryViewAccessibility accessibilityTraits]
+ -[PRXPasscodeEntryViewAccessibility accessibilityValue]
+ -[PRXPasscodeEntryViewAccessibility deleteBackward]
+ -[PRXPasscodeEntryViewAccessibility insertText:]
+ -[PRXPasscodeEntryViewAccessibility isAccessibilityElement]
+ _AXCFormattedString
+ _OBJC_CLASS_$_NSDictionary
+ _OBJC_CLASS_$_NSMutableAttributedString
+ _OBJC_CLASS_$_PRXPasscodeEntryViewAccessibility
+ _OBJC_CLASS_$_UIControl
+ _OBJC_CLASS_$___PRXPasscodeEntryViewAccessibility_super
+ _OBJC_METACLASS_$_PRXPasscodeEntryViewAccessibility
+ _OBJC_METACLASS_$___PRXPasscodeEntryViewAccessibility_super
+ _UIAccessibilitySpeechAttributeSpellOut
+ _UIAccessibilityValueChangedNotification
+ __AXTraitsRemoveTrait
+ __OBJC_$_CLASS_METHODS_PRXPasscodeEntryViewAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_PRXPasscodeEntryViewAccessibility
+ __OBJC_CLASS_RO_$_PRXPasscodeEntryViewAccessibility
+ __OBJC_CLASS_RO_$___PRXPasscodeEntryViewAccessibility_super
+ __OBJC_METACLASS_RO_$_PRXPasscodeEntryViewAccessibility
+ __OBJC_METACLASS_RO_$___PRXPasscodeEntryViewAccessibility_super
+ ___kCFBooleanTrue
+ ___stack_chk_fail
+ ___stack_chk_guard
+ _objc_alloc
+ _objc_opt_isKindOfClass
+ _objc_retain_x19
Functions:
~ ___50+[AXProxCardKitGlue accessibilityInitializeBundle]_block_invoke_3 : 152 -> 172
CStrings:
+ "%ld%ld"
+ "PRXPasscodeEntryView"
+ "PRXPasscodeEntryViewAccessibility"
+ "UIControl"
+ "deleteBackward"
+ "insertText:"
+ "numberOfDigits"
+ "passcode.entry.label"
+ "passcode.entry.value.format"
+ "text"
```
