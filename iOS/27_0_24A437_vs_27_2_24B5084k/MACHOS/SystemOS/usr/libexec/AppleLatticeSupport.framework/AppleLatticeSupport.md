## AppleLatticeSupport

> `/usr/libexec/AppleLatticeSupport.framework/AppleLatticeSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x1c9` | `0x1ea` | **`+0x21`** |
| `__AUTH_CONST.__objc_const` | `0x110` | `0x128` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x98` | `0xb0` | **`+0x18`** |
| `__TEXT.__text` | `0x11b0` | `0x11c4` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0xa0` | `0xa8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xf8` | `0x100` | **`+0x8`** |

### Same-size Content Changes

- `__AUTH.__objc_data`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_dictobj`
- `__DATA_CONST.__const`
- `__TEXT.__cstring`

### Other Changes

```diff

-187.0.1.0.0
+197.0.0.502.1

-  Functions: 27
-  Symbols:   130
-  CStrings:  69
+  Functions: 28
+  Symbols:   133
+  CStrings:  71
Symbols:
+ +[AppleLatticeServiceRef serviceModuleName]
+ GCC_except_table12
+ GCC_except_table21
+ GCC_except_table24
+ GCC_except_table4
+ __OBJC_$_CLASS_METHODS_AppleLatticeServiceRef
+ __OBJC_$_CLASS_PROP_LIST_AppleLatticeServiceRef
- GCC_except_table0
- GCC_except_table11
- GCC_except_table20
- GCC_except_table23
Functions:
+ +[AppleLatticeServiceRef serviceModuleName]
CStrings:
+ "T@\"NSString\",R"
+ "serviceModuleName"
```
