## SpringBoardUIServices

> `/System/Library/AccessibilityBundles/SpringBoardUIServices.axbundle/SpringBoardUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a38` | `0x4a90` | **`+0x58`** |
| `__AUTH_CONST.__cfstring` | `0x14e0` | `0x1500` | **`+0x20`** |
| `__TEXT.__cstring` | `0x116b` | `0x117b` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x4d8` | `0x4e0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xb3c` | `0xb44` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x290` | `0x298` | **`+0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  Functions: 206
-  Symbols:   617
-  CStrings:  190
+  Functions: 207
+  Symbols:   618
+  CStrings:  191
Symbols:
+ -[SBUIPasscodeLockViewBaseAccessibility resetForSuccess]
+ GCC_except_table123
+ GCC_except_table162
- GCC_except_table122
- GCC_except_table161
Functions:
~ -[SBUISystemApertureElementSourceAccessibility _handleSceneResizeAction:] : 588 -> 584
~ -[SBUISystemApertureElementSourceAccessibility traverseTreeForElementsFromView:] : 444 -> 440
~ +[SBUIPasscodeLockViewBaseAccessibility _accessibilityPerformValidations:] : 540 -> 568
+ -[SBUIPasscodeLockViewBaseAccessibility resetForSuccess]
CStrings:
+ "resetForSuccess"
```
