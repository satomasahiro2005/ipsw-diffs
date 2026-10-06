## libcorecrypto_noasm.dylib

> `/usr/lib/system/libcorecrypto_noasm.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x85464` | `0x8743c` | **`+0x1fd8`** |
| `__TEXT.__cstring` | `0x5f9d` | `0x5530` | **`-0xa6d`** |
| `__DATA_CONST.__const` | `0x21b0` | `0x1ec8` | **`-0x2e8`** |
| `__AUTH_CONST.__const` | `0x1980` | `0x1a70` | **`+0xf0`** |
| `__TEXT.__eh_frame` | `0x3a0` | `0x488` | **`+0xe8`** |
| `__AUTH.__data` | `0x118` | `0x148` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1c20` | `0x1c40` | **`+0x20`** |

### Other Changes

```diff

-2097.0.0.0.0
+2109.0.7.0.0

-  Functions: 2460
-  Symbols:   2760
-  CStrings:  553
+  Functions: 2487
+  Symbols:   2786
+  CStrings:  519
Symbols:
+ _OUTLINED_FUNCTION_8
+ _cc_free
+ _cckeccak_absorb_and_pad_internal
+ _cckeccak_f1600_masked_c
+ _cckeccak_oneshot_masked
+ _cckeccak_squeeze_internal
+ _cckeccak_theta
+ _cckem_mlkem1024_decapsulate_unmasked
+ _cckem_mlkem1024_unmasked
+ _cckem_mlkem1024_unmasked_info
+ _cckem_mlkem768_decapsulate_unmasked
+ _cckem_mlkem768_unmasked
+ _cckem_mlkem768_unmasked_info
+ _ccmlkem_decompress_coefficient
+ _ccmlkem_hash_g_masked
+ _ccmlkem_indcpa_decrypt_masked_ws
+ _ccmlkem_indcpa_encrypt_masked_ws
+ _ccmlkem_kem_decapsulate_masked
+ _ccmlkem_poly_compress_encode
+ _ccmlkem_poly_compress_encode_d1
+ _ccmlkem_poly_compress_encode_d10
+ _ccmlkem_poly_compress_encode_d11
+ _ccmlkem_poly_compress_encode_d1_masked
+ _ccmlkem_poly_compress_encode_d4
+ _ccmlkem_poly_compress_encode_d5
+ _ccmlkem_poly_decode_d12
+ _ccmlkem_poly_decode_decompress
+ _ccmlkem_poly_decode_decompress_d1
+ _ccmlkem_poly_decode_decompress_d10
+ _ccmlkem_poly_decode_decompress_d11
+ _ccmlkem_poly_decode_decompress_d1_masked
+ _ccmlkem_poly_decode_decompress_d4
+ _ccmlkem_poly_decode_decompress_d5
+ _ccmlkem_poly_encode_d12
+ _ccmlkem_polyvec_compress_encode
+ _ccmlkem_polyvec_decode_d12
+ _ccmlkem_polyvec_decode_decompress
+ _ccmlkem_polyvec_encode_d12
+ _ccspake_mac_nistkdf_cmac_aes128_sha256
+ _ccspake_mac_nistkdf_cmac_aes128_sha256_decl
+ _ccspake_mac_nistkdf_cmac_compute
+ _ccspake_mac_nistkdf_derive
+ _fipspost_post_run_all
+ _fipspost_run_post
- _ccmlkem_poly_compress
- _ccmlkem_poly_compress_d1
- _ccmlkem_poly_compress_d10
- _ccmlkem_poly_compress_d11
- _ccmlkem_poly_compress_d4
- _ccmlkem_poly_compress_d5
- _ccmlkem_poly_decode
- _ccmlkem_poly_decompress
- _ccmlkem_poly_decompress_d1
- _ccmlkem_poly_decompress_d10
- _ccmlkem_poly_decompress_d11
- _ccmlkem_poly_decompress_d4
- _ccmlkem_poly_decompress_d5
- _ccmlkem_poly_encode
- _ccmlkem_polyvec_compress
- _ccmlkem_polyvec_decode
- _ccmlkem_polyvec_decompress
- _ccmlkem_polyvec_encode
CStrings:
+ "27.0"
+ "FIPSPOST_USER [%llu] %s:%d: FAILED: %s: %d\n"
+ "FIPSPOST_USER [%llu] %s:%d: FAILED: ccmlkem_kem_decapsulate_masked: %d\n"
+ "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - %s\n"
+ "fipspost_post_aes_ecb"
+ "fipspost_post_ecdh"
+ "fipspost_post_ecdsa"
+ "fipspost_post_indicator"
+ "fipspost_post_mldsa"
+ "fipspost_post_mlkem"
+ "fipspost_post_rsa_enc_dec"
+ "fipspost_post_rsa_sig"
+ "fipspost_run_post"
- "26.0"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_aes_cbc: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_aes_ccm: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_aes_cmac: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_aes_ecb: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_aes_gcm: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_aes_xts: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_drbg_ctr: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_drbg_hmac: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_ecdh: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_ecdsa: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_ffdh: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_hkdf: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_hmac: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_indicator: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_integrity: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_kdf_ctr: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_kdf_ctr_cmac: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_mldsa: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_mlkem: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_pbkdf: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_rsa_enc_dec: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_rsa_sig: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: FAILED: fipspost_post_shake: %d\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_aes_cbc\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_aes_ccm\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_aes_cmac\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_aes_ecb\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_aes_gcm\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_aes_xts\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_drbg_ctr\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_drbg_hmac\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_ecdh\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_ecdsa\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_ffdh\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_hkdf\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_hmac\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_indicator\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_integrity\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_kdf_ctr\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_kdf_ctr_cmac\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_mldsa\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_mlkem\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_pbkdf\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_rsa_enc_dec\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_rsa_sig\n"
- "FIPSPOST_USER [%llu] %s:%d: PASSED: (%u ms) - fipspost_post_shake\n"
```
