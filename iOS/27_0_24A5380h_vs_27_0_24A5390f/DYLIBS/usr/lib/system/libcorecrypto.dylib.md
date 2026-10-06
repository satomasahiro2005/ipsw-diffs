## libcorecrypto.dylib

> `/usr/lib/system/libcorecrypto.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8c538` | `0x8c894` | **`+0x35c`** |
| `__TEXT.__cstring` | `0x5530` | `0x5818` | **`+0x2e8`** |

### Other Changes

```diff

-2109.0.11.0.0
+2109.0.17.0.0

-  Functions: 2641
-  Symbols:   2966
-  CStrings:  519
+  Functions: 2640
+  Symbols:   2968
+  CStrings:  529
Symbols:
+ _ccmldsa_keygen_pairwise_check
+ _ccmlkem_kem_pairwise_check
Functions:
~ _OUTLINED_FUNCTION_0 : 56 -> 20
~ _OUTLINED_FUNCTION_2 : 12 -> 28
~ _OUTLINED_FUNCTION_1 : 20 -> 36
~ _OUTLINED_FUNCTION_1 : 36 -> 16
~ _OUTLINED_FUNCTION_1 : 16 -> 28
~ _OUTLINED_FUNCTION_1 : 28 -> 20
~ _OUTLINED_FUNCTION_1 : 20 -> 16
- _OUTLINED_FUNCTION_1
- _OUTLINED_FUNCTION_3
~ _OUTLINED_FUNCTION_3 : 32 -> 36
~ _ccmlkem_kem_keypair_from_seed : 1144 -> 448
~ _ccgcm_init : 112 -> 120
~ _OUTLINED_FUNCTION_4 : 24 -> 36
- _OUTLINED_FUNCTION_4
~ _ccpoly1305_update_internal : 260 -> 252
+ sub_1d31414a0
- sub_1d280a7c0
+ _ccmlkem_kem_pairwise_check
~ _ccsigma_session_clear : 76 -> 84
+ _ccmldsa_keygen_pairwise_check
~ _fipspost_post_mlkem : 1136 -> 1384
~ _ccaes_ecb_decrypt : 856 -> 864
~ _fipspost_post_mldsa : 1140 -> 1420
~ _cc_impl_name : 44 -> 52
~ _ccmldsa_keygen_internal : 1384 -> 996
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
