## StoreDemoPlugin

> `/System/Library/SpringBoardPlugins/StoreDemoPlugin.servicebundle/StoreDemoPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb794` | `0xb8a8` | **`+0x114`** |
| `__TEXT.__objc_methname` | `0x2d8f` | `0x2e10` | **`+0x81`** |
| `__TEXT.__objc_stubs` | `0x2880` | `0x28c0` | **`+0x40`** |
| `__DATA.__objc_const` | `0xe70` | `0xea0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xd9c` | `0xdc4` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0xda0` | `0xdb8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x94` | `0x98` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1865.0.0.0.0
+1871.0.14.0.0

-  Functions: 304
+  Functions: 307

-  CStrings:  809
+  CStrings:  814
CStrings:
+ "T@\"NSDate\",&,N,V_lastStoreClosedDate"
+ "_lastStoreClosedDate"
+ "lastStoreClosedDate"
+ "newDateBySubtractingOneDay"
+ "setLastStoreClosedDate:"
```
