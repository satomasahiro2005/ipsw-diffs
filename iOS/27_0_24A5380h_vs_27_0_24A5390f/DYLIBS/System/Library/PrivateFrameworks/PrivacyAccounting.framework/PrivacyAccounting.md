## PrivacyAccounting

> `/System/Library/PrivateFrameworks/PrivacyAccounting.framework/PrivacyAccounting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c44c` | `0x1c6b8` | **`+0x26c`** |
| `__TEXT.__oslogstring` | `0x93f` | `0x9dc` | **`+0x9d`** |
| `__AUTH_CONST.__const` | `0x5c0` | `0x600` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0xde0` | `0xe00` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0xb8` | `0xd8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x10ec` | `0x10fc` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xa90` | `0xaa0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x300` | `0x308` | **`+0x8`** |

### Other Changes

```diff

-148.0.0.0.0
+149.0.0.0.0

-  Functions: 866
-  Symbols:   1737
-  CStrings:  200
+  Functions: 873
+  Symbols:   1738
+  CStrings:  206
Symbols:
+ ___NSDictionary0__struct
CStrings:
+ ""
+ "PAAccess"
+ "PAAccess was created with nil accessor"
+ "PAApplication"
+ "PAApplication could not be resolved from TCC identity type %d"
+ "nil PAAccess passed to log:; caller passed a nil access"
```
