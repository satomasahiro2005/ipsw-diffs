## ToneKit

> `/System/Library/AccessibilityBundles/ToneKit.axbundle/ToneKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x698` | `0x864` | **`+0x1cc`** |
| `__AUTH_CONST.__objc_const` | `0x510` | `0x630` | **`+0x120`** |
| `__AUTH_CONST.__cfstring` | `0x1e0` | `0x2a0` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x1e7` | `0x294` | **`+0xad`** |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x154` | `0x19c` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x60` | `0x80` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x40` | `0x60` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x50` | `0x68` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x48` | `0x58` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xe0` | `0xf0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x18` | `0x20` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 24
-  Symbols:   109
-  CStrings:  21
+  Functions: 29
+  Symbols:   133
+  CStrings:  29
Symbols:
+ +[TKVibrationRecorderViewAccessibility _accessibilityPerformValidations:]
+ +[TKVibrationRecorderViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[TKVibrationRecorderViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[TKVibrationRecorderViewAccessibility _setLeftButtonIdentifier:enabled:rightButtonIdentifier:enabled:animated:]
+ _OBJC_CLASS_$_TKVibrationRecorderViewAccessibility
+ _OBJC_CLASS_$___TKVibrationRecorderViewAccessibility_super
+ _OBJC_METACLASS_$_TKVibrationRecorderViewAccessibility
+ _OBJC_METACLASS_$___TKVibrationRecorderViewAccessibility_super
+ _UIAccessibilityLayoutChangedNotification
+ _UIAccessibilityPostNotification
+ _UIAccessibilityScreenChangedNotification
+ __OBJC_$_CLASS_METHODS_TKVibrationRecorderViewAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_TKVibrationRecorderViewAccessibility
+ __OBJC_CLASS_RO_$_TKVibrationRecorderViewAccessibility
+ __OBJC_CLASS_RO_$___TKVibrationRecorderViewAccessibility_super
+ __OBJC_METACLASS_RO_$_TKVibrationRecorderViewAccessibility
+ __OBJC_METACLASS_RO_$___TKVibrationRecorderViewAccessibility_super
+ ___112-[TKVibrationRecorderViewAccessibility _setLeftButtonIdentifier:enabled:rightButtonIdentifier:enabled:animated:]_block_invoke
+ ___UIAccessibilitySafeClass
+ ___block_descriptor_32_e5_v8?0l
+ __dispatch_main_q
+ _dispatch_after
+ _dispatch_time
+ _objc_release_x22
CStrings:
+ "TKVibrationRecorderView"
+ "TKVibrationRecorderViewAccessibility"
+ "UIImage"
+ "UIView"
+ "_checkmarkImage"
+ "_setLeftButtonIdentifier:enabled:rightButtonIdentifier:enabled:animated:"
+ "i"
+ "v8@?0"
```
