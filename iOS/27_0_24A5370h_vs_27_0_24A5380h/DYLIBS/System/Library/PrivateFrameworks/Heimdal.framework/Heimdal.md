## Heimdal

> `/System/Library/PrivateFrameworks/Heimdal.framework/Heimdal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__data` | `—` | `0x1410` | **`+0x1410`** |
| `__DATA_DIRTY.__data` | `0x1320` | `0x90` | **`-0x1290`** |
| `__TEXT.__text` | `0x620a4` | `0x629e0` | **`+0x93c`** |
| `__TEXT.__cstring` | `0xf299` | `0xf30d` | **`+0x74`** |
| `__DATA.__data` | `0x2c38` | `0x2c50` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1608` | `0x1620` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xcc0` | `0xcd0` | **`+0x10`** |
| `__TEXT.__const` | `0x1090` | `0x10a0` | **`+0x10`** |

### Other Changes

```diff

-725.0.6.0.0
+725.0.8.0.0

-  Functions: 2504
-  Symbols:   1782
-  CStrings:  2244
+  Functions: 2511
+  Symbols:   1785
+  CStrings:  2249
Symbols:
+ _CCDesIsWeakKey
+ _CCDesSetOddParity
+ _krb5_string_to_key_derived
CStrings:
+ "KRB-CRED tickets count (%lu) does not match ticket-info count (%lu)"
+ "des3"
+ "des3-cbc-none"
+ "des3-cbc-sha1"
+ "hmac-sha1-des3"
```
