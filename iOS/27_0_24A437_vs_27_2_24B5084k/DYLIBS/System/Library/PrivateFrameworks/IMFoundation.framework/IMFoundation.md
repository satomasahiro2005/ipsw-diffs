## IMFoundation

> `/System/Library/PrivateFrameworks/IMFoundation.framework/IMFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a000` | `0x4a114` | **`+0x114`** |
| `__TEXT.__oslogstring` | `0x3cfb` | `0x3d44` | **`+0x49`** |
| `__TEXT.__gcc_except_tab` | `0x182c` | `0x1868` | **`+0x3c`** |
| `__AUTH_CONST.__auth_got` | `0xca0` | `0xca8` | **`+0x8`** |
| `__TEXT.__const` | `0x278` | `0x280` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1940` | `0x1948` | **`+0x8`** |

### Other Changes

```diff

-1138.100.1.0.0
+1138.200.11.0.0

-  Functions: 2487
-  Symbols:   1532
-  CStrings:  1648
+  Functions: 2488
+  Symbols:   1533
+  CStrings:  1649
Symbols:
+ _object_getClassName
Functions:
~ _JWEncodeCodableObject : 60 -> 248
+ sub_19ff85eb0
CStrings:
+ "JWEncodeCodableObject: exception encoding object of class %{public}s: %@"
```
