## MobileCalSettings

> `/System/Library/PreferenceBundles/MobileCalSettings.bundle/MobileCalSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x100d4` | `0x102d4` | **`+0x200`** |
| `__TEXT.__objc_stubs` | `0x2b60` | `0x2c00` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x41af` | `0x4229` | **`+0x7a`** |
| `__DATA.__objc_selrefs` | `0x10b8` | `0x10e8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x1134` | `0x114c` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0xa00` | `0xa10` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x508` | `0x510` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x428` | `0x430` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3d8` | `0x3e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-29917.0.102.0.0
+29917.1.6.0.0

-  Functions: 309
-  Symbols:   335
-  CStrings:  947
+  Functions: 311
+  Symbols:   337
+  CStrings:  953
Symbols:
+ _CalInterfaceIsLeftToRight
+ _OBJC_CLASS_$_EKUIListViewCell
CStrings:
+ "adjustedSeparatorInsets"
+ "applySeparatorInsetToCell:"
+ "safeAreaInsets"
+ "safeAreaInsetsDidChange"
+ "setSeparatorInset:"
+ "visibleCells"
```
