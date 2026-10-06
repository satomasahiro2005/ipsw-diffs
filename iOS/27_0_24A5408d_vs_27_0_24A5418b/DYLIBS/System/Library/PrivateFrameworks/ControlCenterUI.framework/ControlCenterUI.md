## ControlCenterUI

> `/System/Library/PrivateFrameworks/ControlCenterUI.framework/ControlCenterUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbb298` | `0xbb3e0` | **`+0x148`** |
| `__AUTH_CONST.__objc_const` | `0x11190` | `0x111d0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xb500` | `0xb538` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x6928` | `0x6948` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2d58` | `0x2d60` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x740` | `0x744` | **`+0x4`** |

### Other Changes

```diff

-704.0.1.0.0
+704.0.2.0.0

-  Functions: 5045
-  Symbols:   5619
+  Functions: 5048
+  Symbols:   5623
Symbols:
+ -[CCUIModuleInstance presentationInterfaceOrientation]
+ -[CCUIModuleInstance setPresentationInterfaceOrientation:]
+ -[CCUIModuleInstanceManager presentationInterfaceOrientationForContentModuleContext:]
+ _OBJC_IVAR_$_CCUIModuleInstance._presentationInterfaceOrientation
```
