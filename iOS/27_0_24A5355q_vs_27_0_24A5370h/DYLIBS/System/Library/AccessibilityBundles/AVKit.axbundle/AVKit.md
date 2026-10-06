## AVKit

> `/System/Library/AccessibilityBundles/AVKit.axbundle/AVKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbcdc` | `0xbe10` | **`+0x134`** |
| `__AUTH_CONST.__objc_const` | `0x37b0` | `0x38d0` | **`+0x120`** |
| `__AUTH_CONST.__cfstring` | `0x2f40` | `0x3000` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0xf00` | `0xfa0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x2612` | `0x2691` | **`+0x7f`** |
| `__TEXT.__objc_methlist` | `0x12a0` | `0x12e8` | **`+0x48`** |
| `__DATA_CONST.__objc_classlist` | `0x318` | `0x328` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x518` | `0x528` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x768` | `0x770` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x148` | `0x150` | **`+0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

+  - /System/Library/PrivateFrameworks/AccessibilitySharedSupport.framework/AccessibilitySharedSupport

-  Functions: 377
-  Symbols:   1058
-  CStrings:  407
+  Functions: 381
+  Symbols:   1073
+  CStrings:  413
Symbols:
+ +[AVMobileGlassPlaybackControlButtonAccessibility _accessibilityPerformValidations:]
+ +[AVMobileGlassPlaybackControlButtonAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[AVMobileGlassPlaybackControlButtonAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[AVMobileGlassPlaybackControlButtonAccessibility setImageName:]
+ GCC_except_table292
+ GCC_except_table305
+ GCC_except_table319
+ GCC_except_table325
+ GCC_except_table339
+ GCC_except_table345
+ GCC_except_table363
+ _AXSSAccessibilityDescriptionForSymbolName
+ _OBJC_CLASS_$_AVMobileGlassPlaybackControlButtonAccessibility
+ _OBJC_CLASS_$___AVMobileGlassPlaybackControlButtonAccessibility_super
+ _OBJC_METACLASS_$_AVMobileGlassPlaybackControlButtonAccessibility
+ _OBJC_METACLASS_$___AVMobileGlassPlaybackControlButtonAccessibility_super
+ __OBJC_$_CLASS_METHODS_AVMobileGlassPlaybackControlButtonAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_AVMobileGlassPlaybackControlButtonAccessibility
+ __OBJC_CLASS_RO_$_AVMobileGlassPlaybackControlButtonAccessibility
+ __OBJC_CLASS_RO_$___AVMobileGlassPlaybackControlButtonAccessibility_super
+ __OBJC_METACLASS_RO_$_AVMobileGlassPlaybackControlButtonAccessibility
+ __OBJC_METACLASS_RO_$___AVMobileGlassPlaybackControlButtonAccessibility_super
- GCC_except_table288
- GCC_except_table301
- GCC_except_table315
- GCC_except_table321
- GCC_except_table335
- GCC_except_table341
- GCC_except_table359
CStrings:
+ "AVMobileGlassPlaybackControlButtonAccessibility"
+ "backward.end.fill"
+ "forward.end.fill"
+ "setImageName:"
+ "skip.to.next"
+ "skip.to.previous"
```
