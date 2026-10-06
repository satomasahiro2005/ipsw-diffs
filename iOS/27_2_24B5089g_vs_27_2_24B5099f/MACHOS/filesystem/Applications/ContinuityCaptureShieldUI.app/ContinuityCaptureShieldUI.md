## ContinuityCaptureShieldUI

> `/Applications/ContinuityCaptureShieldUI.app/ContinuityCaptureShieldUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9b3c` | `0x9c58` | **`+0x11c`** |
| `__TEXT.__objc_stubs` | `0x24a0` | `0x2560` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0x335a` | `0x3419` | **`+0xbf`** |
| `__DATA.__objc_selrefs` | `0xd78` | `0xdb0` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x258` | `0x268` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x460` | `0x470` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xdac` | `0xdbc` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x240` | `0x248` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2e8` | `0x2f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-764.40.5.0.0
+764.40.7.0.0

-  Functions: 204
-  Symbols:   159
-  CStrings:  854
+  Functions: 205
+  Symbols:   162
+  CStrings:  861
Symbols:
+ _OBJC_CLASS_$_UITraitHorizontalSizeClass
+ _OBJC_CLASS_$_UITraitVerticalSizeClass
+ _objc_unsafeClaimAutoreleasedReturnValue
Functions:
~ sub_1000029fc : 184 -> 284
+ sub_100002c88
CStrings:
+ "effectiveGeometry"
+ "horizontalSizeClass"
+ "interfaceOrientation"
+ "registerForTraitChanges:withAction:"
+ "setNeedsUpdateOfSupportedInterfaceOrientations"
+ "supportedInterfaceOrientations"
+ "verticalSizeClass"
```
