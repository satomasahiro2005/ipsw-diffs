## libcorecrypto_trace.dylib

> `/usr/lib/system/libcorecrypto_trace.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8c574` | `0x8cb38` | **`+0x5c4`** |
| `__AUTH_CONST.__const` | `0x23b8` | `0x2488` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x5bb3` | `0x5c76` | **`+0xc3`** |
| `__TEXT.__const` | `0x204b8` | `0x204f8` | **`+0x40`** |

### Other Changes

```diff

-2109.0.22.0.0
+2109.40.15.0.0

-  Functions: 2644
-  Symbols:   2971
-  CStrings:  558
+  Functions: 2649
+  Symbols:   2978
+  CStrings:  561
Symbols:
+ _ccmldsa44
+ _ccmldsa44_params
+ _ccmldsa_poly_bitpack_z_g1_17
+ _ccmldsa_poly_bitpack_z_g1_19
+ _ccmldsa_poly_bitunpack_z_g1_17
+ _ccmldsa_poly_bitunpack_z_g1_19
+ _ccmldsa_poly_simplebitpack_w1_4bit
+ _ccmldsa_poly_simplebitpack_w1_6bit
+ _rej_rnd_kat_44
+ _seed_kat_44
- _ccmldsa_poly_bitpack_z
- _ccmldsa_poly_bitunpack_z
- _ccmldsa_poly_simplebitpack_w1
CStrings:
+ "FIPSPOST_USER [%llu] %s:%d: FAILED: ccmldsa_sign (rejection, ML-DSA-44): %d\n"
+ "FIPSPOST_USER [%llu] %s:%d: FAILED: mismatch rejection sig (ML-DSA-44): %d\n"
+ "fipspost_post_mldsa_sign_rejection_kat_44"
```
