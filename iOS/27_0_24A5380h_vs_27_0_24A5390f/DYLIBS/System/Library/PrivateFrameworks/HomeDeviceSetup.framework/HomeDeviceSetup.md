## HomeDeviceSetup

> `/System/Library/PrivateFrameworks/HomeDeviceSetup.framework/HomeDeviceSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x726a4` | `0x72750` | **`+0xac`** |
| `__AUTH_CONST.__objc_const` | `0x77d0` | `0x7878` | **`+0xa8`** |
| `__AUTH.__objc_data` | `0x728` | `0x778` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x342c` | `0x3444` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x840` | `0x848` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x98` | `0xa0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2d98` | `0x2da0` | **`+0x8`** |

### Other Changes

```diff

-405.0.3.0.0
+405.0.7.0.0

-  Functions: 3075
-  Symbols:   3325
+  Functions: 3076
+  Symbols:   3333
Symbols:
+ +[HDSHPCommon currentProductType]
+ _MGGetProductType
+ _OBJC_CLASS_$_HDSHPCommon
+ _OBJC_METACLASS_$_HDSHPCommon
+ __OBJC_$_CLASS_METHODS_HDSHPCommon
+ __OBJC_$_CLASS_PROP_LIST_HDSHPCommon
+ __OBJC_CLASS_RO_$_HDSHPCommon
+ __OBJC_METACLASS_RO_$_HDSHPCommon
```
