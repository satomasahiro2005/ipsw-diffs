## Heimdal

> `/System/Library/PrivateFrameworks/Heimdal.framework/Heimdal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6257c` | `0x620a4` | **`-0x4d8`** |
| `__DATA_DIRTY.__data` | `0x14a0` | `0x1320` | **`-0x180`** |
| `__DATA.__data` | `0x2c50` | `0x2c38` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x15f0` | `0x1608` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xcd0` | `0xcc0` | **`-0x10`** |
| `__TEXT.__const` | `0x10a0` | `0x1090` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x98` | `0xa0` | **`+0x8`** |
| `__TEXT.__cstring` | `0xf298` | `0xf299` | **`+0x1`** |

### Other Changes

```diff

-720.0.0.0.0
+725.0.6.0.0

-  Functions: 2510
-  Symbols:   1785
-  CStrings:  2247
+  Functions: 2504
+  Symbols:   1782
+  CStrings:  2244
Symbols:
- _CCDesIsWeakKey
- _CCDesSetOddParity
- _krb5_string_to_key_derived
CStrings:
+ "Failed to create SecCertificate from signer cert"
- "des3"
- "des3-cbc-none"
- "des3-cbc-sha1"
- "hmac-sha1-des3"
```
