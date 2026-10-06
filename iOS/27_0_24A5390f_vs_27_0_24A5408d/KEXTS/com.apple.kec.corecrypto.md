## com.apple.kec.corecrypto

> `com.apple.kec.corecrypto`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x6a0fc` | `0x6db98` | **`+0x3a9c`** |
| `__TEXT.__cstring` | `0x4214` | `0x4479` | **`+0x265`** |
| `__TEXT.__const` | `0x10140` | `0x10180` | **`+0x40`** |

### Other Changes

```diff

-2109.0.17.0.0
-  Functions: 1942
+2109.0.22.0.0
+  Functions: 1949

-  CStrings:  347
+  CStrings:  368
CStrings:
+ "FIPSPOST_KEXT [%llu] %s:%d: FAILED: ccmldsa_import_privkey: %d\n"
+ "FIPSPOST_KEXT [%llu] %s:%d: FAILED: ccmldsa_import_pubkey: %d\n"
+ "FIPSPOST_KEXT [%llu] %s:%d: FAILED: ccmldsa_sign (rejection): %d\n"
+ "FIPSPOST_KEXT [%llu] %s:%d: FAILED: mismatch rejection sig: %d\n"
+ "cckem_decapsulate"
+ "cckem_encapsulate"
+ "cckem_generate_key"
+ "cckem_generate_key_with_seed"
+ "cckem_mlkem1024"
+ "cckem_mlkem768"
+ "ccmldsa65"
+ "ccmldsa87"
+ "ccmldsa_generate_key"
+ "ccmldsa_generate_key_with_seed"
+ "ccmldsa_sign"
+ "ccmldsa_sign_prehashed"
+ "ccmldsa_sign_with_context"
+ "ccmldsa_verify"
+ "ccmldsa_verify_prehashed"
+ "ccmldsa_verify_with_context"
+ "fipspost_post_mldsa_sign_rejection_kat"
```
