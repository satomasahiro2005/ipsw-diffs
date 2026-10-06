## PassKitFramework

> `/System/Library/AccessibilityBundles/PassKitFramework.axbundle/PassKitFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x620` | `0x5e0` | **`-0x40`** |
| `__TEXT.__text` | `0x5c8` | `0x590` | **`-0x38`** |
| `__TEXT.__cstring` | `0x3ee` | `0x3b7` | **`-0x37`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  CStrings:  64
+  CStrings:  61
Functions:
~ ___55+[AXPassKitFrameworkGlue accessibilityInitializeBundle]_block_invoke : 1104 -> 1048
CStrings:
- "NSUInteger"
- "_modalGroupIndex"
- "_modallyPresentedGroupView"
```
