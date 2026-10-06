## VisualLogger

> `/System/Library/PrivateFrameworks/VisualLogger.framework/VisualLogger`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7066e0` | `0x700b3c` | **`-0x5ba4`** |
| `__TEXT.__gcc_except_tab` | `0x65958` | `0x648b8` | **`-0x10a0`** |
| `__TEXT.__const` | `0x67530` | `0x671f0` | **`-0x340`** |
| `__TEXT.__unwind_info` | `0x1c310` | `0x1c060` | **`-0x2b0`** |
| `__AUTH_CONST.__const` | `0x32750` | `0x32640` | **`-0x110`** |
| `__DATA.__bss` | `0x27e0` | `0x2740` | **`-0xa0`** |
| `__DATA.__common` | `0x298` | `0x338` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x50` | `0x98` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x1458` | `0x1478` | **`+0x20`** |
| `__AUTH.__data` | `—` | `0x18` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x18` | `—` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0xe00` | `0xdf8` | **`-0x8`** |
| `__TEXT.__cstring` | `0x1674b` | `0x1674e` | **`+0x3`** |

### Other Changes

```diff

-9.26.5.12.5
+9.26.6.16.5

-  Functions: 16951
+  Functions: 16895

-  CStrings:  2204
+  CStrings:  2205
CStrings:
+ " : "
+ "(null)"
+ "-"
- " : %.*s"
- "%s: %s:%d"
```
