## ptpcamerad

> `/usr/libexec/ptpcamerad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x460e` | `0x4666` | **`+0x58`** |
| `__DATA.__objc_const` | `0x1ed0` | `0x1f00` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x1734` | `0x174c` | **`+0x18`** |
| `__TEXT.__text` | `0x1b76c` | `0x1b780` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0x13b8` | `0x13c8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1cc` | `0x1d0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2116.0.0.0.0
+2118.0.0.0.0

-  Functions: 512
+  Functions: 514

-  CStrings:  1333
+  CStrings:  1337
CStrings:
+ "TB,N,V_sessionCloseCalled"
+ "_sessionCloseCalled"
+ "sessionCloseCalled"
+ "setSessionCloseCalled:"
```
