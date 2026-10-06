## ANEStorageMaintainer

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/XPCServices/ANEStorageMaintainer.xpc/ANEStorageMaintainer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7800` | `0x7990` | **`+0x190`** |
| `__TEXT.__objc_stubs` | `0xec0` | `0xf20` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0xf94` | `0xfe6` | **`+0x52`** |
| `__DATA_CONST.__cfstring` | `0x2c0` | `0x300` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x4d8` | `0x4f8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x3b4` | `0x3c4` | **`+0x10`** |
| `__TEXT.__cstring` | `0x1e3` | `0x1e8` | **`+0x5`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-382.11.0.0.0
+382.12.0.0.0

-  Functions: 96
-  Symbols:   380
-  CStrings:  318
+  Functions: 97
+  Symbols:   384
+  CStrings:  324
Symbols:
+ +[_ANEStorageHelper isPath:safelyWithinDirectory:]
+ GCC_except_table10
+ GCC_except_table6
+ _objc_msgSend$containsObject:
+ _objc_msgSend$hasSuffix:
+ _objc_msgSend$stringByAppendingString:
- GCC_except_table5
- GCC_except_table9
Functions:
+ +[_ANEStorageHelper isPath:safelyWithinDirectory:]
CStrings:
+ ".."
+ "/"
+ "containsObject:"
+ "hasSuffix:"
+ "isPath:safelyWithinDirectory:"
+ "stringByAppendingString:"
```
