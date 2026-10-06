## com.apple.kec.corecrypto

> `com.apple.kec.corecrypto`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x6db84` | `0x6fe68` | **`+0x22e4`** |
| `__TEXT.__cstring` | `0x4d8c` | `0x4567` | **`-0x825`** |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x250` | **`+0x250`** |
| `__DATA_CONST.__const` | `0x42a8` | `0x4218` | **`-0x90`** |

### Other Changes

```diff

-2097.0.0.0.0
-  Functions: 1960
+2109.0.7.0.0
+  Functions: 1993

-  CStrings:  470
+  CStrings:  443
CStrings:
+ "27.0"
+ "FIPSPOST_KEXT [%llu] %s:%d: FAILED: %s: %d\n"
+ "FIPSPOST_KEXT [%llu] %s:%d: FAILED: ccmlkem_kem_decapsulate_masked: %d\n"
+ "FIPSPOST_KEXT [%llu] %s:%d: PASSED: (%u ms) - %s\n"
+ "fipspost_post_aes_ecb"
+ "fipspost_post_ecdh"
+ "fipspost_post_ecdsa"
+ "fipspost_post_indicator"
+ "fipspost_post_rsa_sig"
+ "fipspost_run_post"
- "26.0"
- "FIPSPOST_KEXT [%llu] %s:%d: FAILED: fipspost_post_aes_cbc: %d\n"
- "FIPSPOST_KEXT [%llu] %s:%d: FAILED: fipspost_post_aes_ccm: %d\n"
- "FIPSPOST_KEXT [%llu] %s:%d: FAILED: fipspost_post_aes_cmac: %d\n"
- "FIPSPOST_KEXT [%llu] %s:%d: FAILED: fipspost_post_aes_ecb: %d\n"
- "FIPSPOST_KEXT [%llu] %s:%d: FAILED: fipspost_post_aes_gcm: %d\n"
- "FIPSPOST_KEXT [%llu] %s:%d: FAILED: fipspost_post_aes_xts: %d\n"
- "FIPSPOST_KEXT [%llu] %s:%d: FAILED: fipspost_post_drbg_ctr: %d\n"
- "FIPSPOST_KEXT [%llu] %s:%d: FAILED: fipspost_post_drbg_hmac: %d\n"
- "FIPSPOST_KEXT [%llu] %s:%d: FAILED: fipspost_post_ecdh: %d\n"
- "FIPSPOST_KEXT [%llu] %s:%d: FAILED: fipspost_post_ecdsa: %d\n"
- "FIPSPOST_KEXT [%llu] %s:%d: FAILED: fipspost_post_hkdf: %d\n"
- "FIPSPOST_KEXT [%llu] %s:%d: FAILED: fipspost_post_hmac: %d\n"
- "FIPSPOST_KEXT [%llu] %s:%d: FAILED: fipspost_post_indicator: %d\n"
- "FIPSPOST_KEXT [%llu] %s:%d: FAILED: fipspost_post_integrity: %d\n"
- "FIPSPOST_KEXT [%llu] %s:%d: FAILED: fipspost_post_kdf_ctr: %d\n"
- "FIPSPOST_KEXT [%llu] %s:%d: FAILED: fipspost_post_kdf_ctr_cmac: %d\n"
- "FIPSPOST_KEXT [%llu] %s:%d: FAILED: fipspost_post_pbkdf: %d\n"
- "FIPSPOST_KEXT [%llu] %s:%d: FAILED: fipspost_post_rsa_sig: %d\n"
- "FIPSPOST_KEXT [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_aes_cbc\n"
- "FIPSPOST_KEXT [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_aes_ccm\n"
- "FIPSPOST_KEXT [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_aes_cmac\n"
- "FIPSPOST_KEXT [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_aes_ecb\n"
- "FIPSPOST_KEXT [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_aes_gcm\n"
- "FIPSPOST_KEXT [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_aes_xts\n"
- "FIPSPOST_KEXT [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_drbg_ctr\n"
- "FIPSPOST_KEXT [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_drbg_hmac\n"
- "FIPSPOST_KEXT [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_ecdh\n"
- "FIPSPOST_KEXT [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_ecdsa\n"
- "FIPSPOST_KEXT [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_hkdf\n"
- "FIPSPOST_KEXT [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_hmac\n"
- "FIPSPOST_KEXT [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_indicator\n"
- "FIPSPOST_KEXT [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_integrity\n"
- "FIPSPOST_KEXT [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_kdf_ctr\n"
- "FIPSPOST_KEXT [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_kdf_ctr_cmac\n"
- "FIPSPOST_KEXT [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_pbkdf\n"
- "FIPSPOST_KEXT [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_rsa_sig\n"
```
