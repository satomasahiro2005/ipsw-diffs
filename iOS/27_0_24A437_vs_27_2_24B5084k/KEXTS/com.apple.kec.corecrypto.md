## com.apple.kec.corecrypto

> `com.apple.kec.corecrypto`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x6ecb0` | `0x6f138` | **`+0x488`** |
| `__TEXT.__cstring` | `0x4479` | `0x453c` | **`+0xc3`** |
| `__TEXT.__const` | `0x10180` | `0x101e0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x3fb8` | `0x3fd8` | **`+0x20`** |

### Other Changes

```diff

-2109.0.22.0.0
-  Functions: 1948
+2109.40.15.0.0
+  Functions: 1955

-  CStrings:  368
+  CStrings:  371
CStrings:
+ "FIPSPOST_KEXT [%llu] %s:%d: FAILED: ccmldsa_sign (rejection, ML-DSA-44): %d\n"
+ "FIPSPOST_KEXT [%llu] %s:%d: FAILED: mismatch rejection sig (ML-DSA-44): %d\n"
+ "fipspost_post_mldsa_sign_rejection_kat_44"
```
