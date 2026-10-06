## AVKit

> `/System/Library/AccessibilityBundles/AVKit.axbundle/AVKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbe10` | `0xbfb4` | **`+0x1a4`** |
| `__AUTH_CONST.__objc_const` | `0x38d0` | `0x39f0` | **`+0x120`** |
| `__AUTH.__objc_data` | `0xb40` | `0xbe0` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x3000` | `0x3080` | **`+0x80`** |
| `__TEXT.__cstring` | `0x2691` | `0x270e` | **`+0x7d`** |
| `__TEXT.__objc_methlist` | `0x12e8` | `0x1338` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x3f8` | `0x414` | **`+0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x770` | `0x788` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x328` | `0x338` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x528` | `0x538` | **`+0x10`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 381
-  Symbols:   1073
-  CStrings:  413
+  Functions: 387
+  Symbols:   1090
+  CStrings:  417
Symbols:
+ +[AVMobileGlassBackgroundViewAccessibility _accessibilityPerformValidations:]
+ +[AVMobileGlassBackgroundViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[AVMobileGlassBackgroundViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[AVMobileGlassBackgroundViewAccessibility _accessibilityObscuresScreen]
+ -[AVMobileGlassBackgroundViewAccessibility accessibilityViewIsModal]
+ GCC_except_table104
+ GCC_except_table149
+ GCC_except_table161
+ GCC_except_table163
+ GCC_except_table172
+ GCC_except_table180
+ GCC_except_table224
+ GCC_except_table262
+ GCC_except_table298
+ GCC_except_table311
+ GCC_except_table331
+ GCC_except_table351
+ GCC_except_table369
+ GCC_except_table64
+ GCC_except_table91
+ _OBJC_CLASS_$_AVMobileGlassBackgroundViewAccessibility
+ _OBJC_CLASS_$___AVMobileGlassBackgroundViewAccessibility_super
+ _OBJC_METACLASS_$_AVMobileGlassBackgroundViewAccessibility
+ _OBJC_METACLASS_$___AVMobileGlassBackgroundViewAccessibility_super
+ __OBJC_$_CLASS_METHODS_AVMobileGlassBackgroundViewAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_AVMobileGlassBackgroundViewAccessibility
+ __OBJC_CLASS_RO_$_AVMobileGlassBackgroundViewAccessibility
+ __OBJC_CLASS_RO_$___AVMobileGlassBackgroundViewAccessibility_super
+ __OBJC_METACLASS_RO_$_AVMobileGlassBackgroundViewAccessibility
+ __OBJC_METACLASS_RO_$___AVMobileGlassBackgroundViewAccessibility_super
+ ___92-[AVPictureInPicturePlatformAdapterAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke
- GCC_except_table103
- GCC_except_table148
- GCC_except_table160
- GCC_except_table162
- GCC_except_table171
- GCC_except_table179
- GCC_except_table223
- GCC_except_table261
- GCC_except_table292
- GCC_except_table305
- GCC_except_table319
- GCC_except_table339
- GCC_except_table363
- GCC_except_table90
CStrings:
+ "AVMobileGlassBackgroundView"
+ "AVMobileGlassBackgroundViewAccessibility"
+ "isRoutingVideoToHostedWindow"
+ "routingVideoToHostedWindow"
```
