## ContactsFoundation

> `/System/Library/PrivateFrameworks/ContactsFoundation.framework/ContactsFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x4190` | `0x3460` | **`-0xd30`** |
| `__DATA_DIRTY.__objc_data` | `0x2e68` | `0x3b98` | **`+0xd30`** |
| `__DATA_DIRTY.__data` | `0x2f8` | `0x320` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x33a0` | `0x33c0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x38d8` | `0x38f8` | **`+0x20`** |
| `__AUTH.__data` | `0x4c8` | `0x4b0` | **`-0x18`** |
| `__TEXT.__text` | `0x9ce34` | `0x9ce20` | **`-0x14`** |
| `__DATA.__data` | `0x1d98` | `0x1da8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x7214` | `0x7224` | **`+0x10`** |

### Other Changes

```diff

-1430.200.21.0.0
+1430.200.41.0.0

-  Functions: 5265
-  Symbols:   8757
-  CStrings:  1913
+  Functions: 5266
+  Symbols:   8758
+  CStrings:  1914
Symbols:
+ GCC_except_table31
+ ___22+[CNFuture _joinMany:]_block_invoke_5
+ ___block_descriptor_32_e20_16?0"<CNFuture>"8l
- GCC_except_table30
- GCC_except_table32
Functions:
~ +[CNFuture _joinMany:] : 552 -> 568
~ ___22+[CNFuture _joinMany:]_block_invoke : 504 -> 12
~ ___22+[CNFuture _joinMany:]_block_invoke_2 : 188 -> 456
~ ___22+[CNFuture _joinMany:]_block_invoke_3 : 480 -> 188
~ ___22+[CNFuture _joinMany:]_block_invoke_4 : 124 -> 480
+ ___22+[CNFuture _joinMany:]_block_invoke_5
CStrings:
+ "@16@?0@\"<CNFuture>\"8"
```
