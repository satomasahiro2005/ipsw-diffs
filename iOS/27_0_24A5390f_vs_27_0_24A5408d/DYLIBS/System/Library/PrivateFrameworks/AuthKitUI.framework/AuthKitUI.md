## AuthKitUI

> `/System/Library/PrivateFrameworks/AuthKitUI.framework/AuthKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xddc04` | `0xde0ac` | **`+0x4a8`** |
| `__AUTH_CONST.__objc_const` | `0x186d8` | `0x18768` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x2f48` | `0x2fa8` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x6008` | `0x6068` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x886c` | `0x88c4` | **`+0x58`** |
| `__AUTH_CONST.__cfstring` | `0x50e0` | `0x5100` | **`+0x20`** |
| `__TEXT.__cstring` | `0x57dd` | `0x57ed` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1c88` | `0x1c98` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x768` | `0x770` | **`+0x8`** |

### Other Changes

```diff

-555.0.0.0.0
+559.0.0.0.0

-  Functions: 3368
-  Symbols:   5815
-  CStrings:  1311
+  Functions: 3374
+  Symbols:   5824
+  CStrings:  1312
Symbols:
+ -[AKAuthorizationInputPaneViewController _scopeIconImageNamed:]
+ -[AKAuthorizationPaneViewController currentScreen]
+ -[AKModalSignInViewController disablePasswordAutoFill]
+ -[AKModalSignInViewController setDisablePasswordAutoFill:]
+ -[AKProximityAuthViewController childSetupContentHeightConstraint]
+ -[AKProximityAuthViewController setChildSetupContentHeightConstraint:]
+ GCC_except_table170
+ GCC_except_table98
+ _OBJC_IVAR_$_AKModalSignInViewController._disablePasswordAutoFill
+ _OBJC_IVAR_$_AKProximityAuthViewController._childSetupContentHeightConstraint
+ _kCBBrightnessBoostFactor
- GCC_except_table169
- GCC_except_table97
CStrings:
+ "CBBrightnessBoostFactor"
```
