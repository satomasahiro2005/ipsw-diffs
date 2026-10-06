## SpringBoardHome

> `/System/Library/AccessibilityBundles/SpringBoardHome.axbundle/SpringBoardHome`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x215b4` | `0x217b4` | **`+0x200`** |
| `__AUTH_CONST.__cfstring` | `0x5dc0` | `0x5e20` | **`+0x60`** |
| `__TEXT.__cstring` | `0x4f91` | `0x4fc8` | **`+0x37`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  CStrings:  837
+  CStrings:  840
Functions:
~ +[SBHIconManagerAccessibility _accessibilityPerformValidations:] : 476 -> 540
~ ___92-[SBHIconManagerAccessibility pushExpandedIcon:location:context:animated:completionHandler:]_block_invoke : 596 -> 672
~ +[SBRootFolderViewAccessibility _accessibilityPerformValidations:] : 660 -> 756
~ -[SBRootFolderViewAccessibility automationElements] : 964 -> 1240
CStrings:
+ "SBHomeScreenController"
+ "contentVisibility"
+ "sbWindowScene"
```
