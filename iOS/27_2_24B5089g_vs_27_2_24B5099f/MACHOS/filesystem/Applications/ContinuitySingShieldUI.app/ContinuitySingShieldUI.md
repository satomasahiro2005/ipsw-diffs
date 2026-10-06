## ContinuitySingShieldUI

> `/Applications/ContinuitySingShieldUI.app/ContinuitySingShieldUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xae40` | `0xb14c` | **`+0x30c`** |
| `__TEXT.__objc_stubs` | `0x2800` | `0x28e0` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x378c` | `0x386a` | **`+0xde`** |
| `__DATA.__objc_selrefs` | `0xe88` | `0xec8` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x2c4` | `0x2e0` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x290` | `0x2a0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x480` | `0x490` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xed4` | `0xee4` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x250` | `0x258` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x348` | `0x350` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-764.40.5.0.0
+764.40.7.0.0

-  Functions: 231
-  Symbols:   168
-  CStrings:  919
+  Functions: 232
+  Symbols:   171
+  CStrings:  927
Symbols:
+ _OBJC_CLASS_$_UITraitHorizontalSizeClass
+ _OBJC_CLASS_$_UITraitVerticalSizeClass
+ _objc_unsafeClaimAutoreleasedReturnValue
CStrings:
+ "didMoveToParentViewController:"
+ "effectiveGeometry"
+ "horizontalSizeClass"
+ "interfaceOrientation"
+ "registerForTraitChanges:withAction:"
+ "setNeedsUpdateOfSupportedInterfaceOrientations"
+ "supportedInterfaceOrientations"
+ "verticalSizeClass"
```
