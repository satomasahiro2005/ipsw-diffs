## AccessibilityUIUtilities

> `/System/Library/PrivateFrameworks/AccessibilityUIUtilities.framework/AccessibilityUIUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x61628` | `0x61578` | **`-0xb0`** |
| `__AUTH_CONST.__objc_dictobj` | `—` | `0x50` | **`+0x50`** |
| `__TEXT.__cstring` | `0x5b8e` | `0x5bd2` | **`+0x44`** |
| `__AUTH_CONST.__const` | `0xaa0` | `0xae0` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0x6920` | `0x6940` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0xa150` | `0xa130` | **`-0x20`** |
| `__DATA_CONST.__const` | `0xdb0` | `0xdd0` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x60` | `0x80` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x11e8` | `0x11f8` | **`+0x10`** |
| `__AUTH.__data` | `0x5b8` | `0x5b0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1960` | `0x1968` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x578` | `0x574` | **`-0x4`** |

### Other Changes

```diff

-3232.3.0.0.0
+3234.5.0.0.0

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  Functions: 2397
-  Symbols:   4606
-  CStrings:  1058
+  Functions: 2399
+  Symbols:   4611
+  CStrings:  1060
Symbols:
+ -[AXUISettingsInstructionsView preferredHeightForWidth:inTableView:]
+ GCC_except_table1826
+ GCC_except_table1834
+ GCC_except_table1847
+ GCC_except_table1850
+ GCC_except_table1857
+ GCC_except_table1882
+ _AnalyticsSendEventLazy
+ _OBJC_CLASS_$_NSConstantDictionary
+ ___58-[AccessibilityAirPodSettingsController loudNoiseToggled:]_block_invoke
+ ___78-[AccessibilityAirPodSettingsController confirmationViewAcceptedForSpecifier:]_block_invoke
+ ___block_descriptor_32_e19_"NSDictionary"8?0l
+ _swift_arrayInitWithCopy
- -[AXUISettingsInstructionsView setNeedsLayout]
- GCC_except_table1824
- GCC_except_table1832
- GCC_except_table1845
- GCC_except_table1848
- GCC_except_table1855
- GCC_except_table1880
- _OBJC_IVAR_$_AXUISettingsInstructionsView._marginConstraints
CStrings:
+ "@\"NSDictionary\"8@?0"
+ "com.apple.accessibility.loudSoundReductionToggled"
```
