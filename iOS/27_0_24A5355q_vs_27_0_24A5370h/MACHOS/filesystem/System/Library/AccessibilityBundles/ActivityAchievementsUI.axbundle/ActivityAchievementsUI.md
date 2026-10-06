## ActivityAchievementsUI

> `/System/Library/AccessibilityBundles/ActivityAchievementsUI.axbundle/ActivityAchievementsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4d4` | `0x6f0` | **`+0x21c`** |
| `__DATA.__objc_const` | `0x2d0` | `0x3f0` | **`+0x120`** |
| `__DATA.__objc_data` | `0x190` | `0x230` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x176` | `0x1fe` | **`+0x88`** |
| `__DATA_CONST.__cfstring` | `0x1a0` | `0x220` | **`+0x80`** |
| `__TEXT.__objc_classname` | `0xb6` | `0x128` | **`+0x72`** |
| `__TEXT.__auth_stubs` | `0xd0` | `0x140` | **`+0x70`** |
| `__DATA_CONST.__const` | `0xe0` | `0x128` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0xc4` | `0x10c` | **`+0x48`** |
| `__DATA_CONST.__auth_got` | `0x70` | `0xb0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x90` | `0xb8` | **`+0x28`** |
| `__TEXT.__objc_methname` | `0x2d5` | `0x2fc` | **`+0x27`** |
| `__TEXT.__objc_stubs` | `0x1e0` | `0x200` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `—` | `0x14` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0xc0` | `0xd0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x28` | `0x38` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x38` | **`+0x10`** |
| `__TEXT.__const` | `—` | `0x10` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x10` | `0x18` | **`+0x8`** |

### Other Changes

```diff

-1029.0.0.0.0
+1032.0.0.0.0

-  Functions: 17
-  Symbols:   88
-  CStrings:  54
+  Functions: 23
+  Symbols:   117
+  CStrings:  61
Symbols:
+ +[AAUIAchievementDetailTransitionAnimatorAccessibility _accessibilityPerformValidations:]
+ +[AAUIAchievementDetailTransitionAnimatorAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[AAUIAchievementDetailTransitionAnimatorAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[AAUIAchievementDetailTransitionAnimatorAccessibility animateTransition:]
+ GCC_except_table17
+ _AXPerformBlockOnMainThreadAfterDelay
+ _AXPerformSafeBlock
+ _OBJC_CLASS_$_AAUIAchievementDetailTransitionAnimatorAccessibility
+ _OBJC_CLASS_$___AAUIAchievementDetailTransitionAnimatorAccessibility_super
+ _OBJC_METACLASS_$_AAUIAchievementDetailTransitionAnimatorAccessibility
+ _OBJC_METACLASS_$___AAUIAchievementDetailTransitionAnimatorAccessibility_super
+ _UIAccessibilityLayoutChangedNotification
+ _UIAccessibilityPostNotification
+ __Block_object_dispose
+ __NSConcreteStackBlock
+ __OBJC_$_CLASS_METHODS_AAUIAchievementDetailTransitionAnimatorAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_AAUIAchievementDetailTransitionAnimatorAccessibility
+ __OBJC_CLASS_RO_$_AAUIAchievementDetailTransitionAnimatorAccessibility
+ __OBJC_CLASS_RO_$___AAUIAchievementDetailTransitionAnimatorAccessibility_super
+ __OBJC_METACLASS_RO_$_AAUIAchievementDetailTransitionAnimatorAccessibility
+ __OBJC_METACLASS_RO_$___AAUIAchievementDetailTransitionAnimatorAccessibility_super
+ __Unwind_Resume
+ ___74-[AAUIAchievementDetailTransitionAnimatorAccessibility animateTransition:]_block_invoke
+ ___74-[AAUIAchievementDetailTransitionAnimatorAccessibility animateTransition:]_block_invoke_2
+ ___block_descriptor_56_e8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
+ ___objc_personality_v0
+ _objc_msgSend$transitionDuration:
+ _objc_release_x8
+ _objc_retain_x20
Functions:
~ ___61+[AXActivityAchievementsUIGlue accessibilityInitializeBundle]_block_invoke_4 : 92 -> 112
CStrings:
+ "AAUIAchievementDetailTransitionAnimator"
+ "AAUIAchievementDetailTransitionAnimatorAccessibility"
+ "__AAUIAchievementDetailTransitionAnimatorAccessibility_super"
+ "animateTransition:"
+ "d"
+ "transitionDuration:"
+ "v"
```
