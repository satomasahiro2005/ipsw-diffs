## libcorecrypto_noasm.dylib

> `/usr/lib/system/libcorecrypto_noasm.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x87290` | `0x875bc` | **`+0x32c`** |
| `__TEXT.__cstring` | `0x5530` | `0x5818` | **`+0x2e8`** |

### Other Changes

```diff

-2109.0.11.0.0
+2109.0.17.0.0

-  Functions: 2487
-  Symbols:   2786
-  CStrings:  519
+  Functions: 2486
+  Symbols:   2788
+  CStrings:  529
Symbols:
+ _ccmldsa_keygen_pairwise_check
+ _ccmlkem_kem_pairwise_check
CStrings:
+ "FIPSPOST_USER [%llu] %s:%d: FAILED: [PCT] CCMLDSA_KEYGEN_PAIRWISE_CHECK: unexpected FAILURE: %d\n"
+ "FIPSPOST_USER [%llu] %s:%d: FAILED: [PCT] CCMLDSA_KEYGEN_PAIRWISE_CHECK: unexpected SUCCESS\n"
+ "FIPSPOST_USER [%llu] %s:%d: FAILED: [PCT] CCMLKEM_KEM_PAIRWISE_CHECK: unexpected FAILURE: %d\n"
+ "FIPSPOST_USER [%llu] %s:%d: FAILED: [PCT] CCMLKEM_KEM_PAIRWISE_CHECK: unexpected SUCCESS\n"
+ "FIPSPOST_USER [%llu] %s:%d: [PCT] CCMLDSA_KEYGEN_PAIRWISE_CHECK: FORCEFAIL\n"
+ "FIPSPOST_USER [%llu] %s:%d: [PCT] CCMLDSA_KEYGEN_PAIRWISE_CHECK: expected SUCCESS\n"
+ "FIPSPOST_USER [%llu] %s:%d: [PCT] CCMLKEM_KEM_PAIRWISE_CHECK: FORCEFAIL\n"
+ "FIPSPOST_USER [%llu] %s:%d: [PCT] CCMLKEM_KEM_PAIRWISE_CHECK: expected SUCCESS\n"
+ "fipspost_post_mldsa_pairwise"
+ "fipspost_post_mlkem_pairwise"
```
