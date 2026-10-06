## ClipUIServices

> `/System/Library/PrivateFrameworks/ClipUIServices.framework/ClipUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ed80` | `0x1eebc` | **`+0x13c`** |
| `__TEXT.__gcc_except_tab` | `0x1664` | `0x1698` | **`+0x34`** |
| `__AUTH_CONST.__objc_const` | `0x38a0` | `0x38c0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1b40` | `0x1b50` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x500` | `0x508` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2d8` | `0x2dc` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1038.7.0.0.0
+1038.8.1.0.0

-  Functions: 555
-  Symbols:   1469
+  Functions: 556
+  Symbols:   1471
Symbols:
+ -[CPSLaunchContentViewController cardStyle]
+ GCC_except_table108
+ GCC_except_table110
+ GCC_except_table112
+ GCC_except_table85
+ GCC_except_table88
+ GCC_except_table92
+ GCC_except_table97
+ GCC_except_table99
+ _OBJC_IVAR_$_CPSLaunchContentViewController._informationContainerTopConstraint
- GCC_except_table107
- GCC_except_table109
- GCC_except_table111
- GCC_except_table84
- GCC_except_table87
- GCC_except_table91
- GCC_except_table94
- GCC_except_table98
Functions:
~ -[CPSLaunchContentViewController updateViewConstraints] : 284 -> 548
~ -[CPSLaunchContentViewController setUpInformationSection] : 4584 -> 4588
+ -[CPSLaunchContentViewController allowsPullToDismiss]
~ -[CPSLaunchContentViewController .cxx_destruct] : 656 -> 676
```
