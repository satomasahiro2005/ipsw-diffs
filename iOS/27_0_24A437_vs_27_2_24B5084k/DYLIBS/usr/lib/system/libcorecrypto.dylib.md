## libcorecrypto.dylib

> `/usr/lib/system/libcorecrypto.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8bd78` | `0x8c2fc` | **`+0x584`** |
| `__AUTH_CONST.__const` | `0x23b8` | `0x2488` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x5940` | `0x5a03` | **`+0xc3`** |
| `__TEXT.__const` | `0x204a8` | `0x204e8` | **`+0x40`** |

### Other Changes

```diff

-2109.0.22.0.0
+2109.40.15.0.0

-  Functions: 2638
-  Symbols:   2958
-  CStrings:  534
+  Functions: 2644
+  Symbols:   2965
+  CStrings:  537
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
