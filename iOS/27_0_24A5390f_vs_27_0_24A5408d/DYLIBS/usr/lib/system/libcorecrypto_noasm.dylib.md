## libcorecrypto_noasm.dylib

> `/usr/lib/system/libcorecrypto_noasm.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x875bc` | `0x86a5c` | **`-0xb60`** |
| `__DATA_CONST.__const` | `0x1ec8` | `0x2108` | **`+0x240`** |
| `__TEXT.__cstring` | `0x5818` | `0x5940` | **`+0x128`** |
| `__TEXT.__unwind_info` | `0x1c38` | `0x1c10` | **`-0x28`** |
| `__TEXT.__const` | `0x201e8` | `0x20208` | **`+0x20`** |

### Other Changes

```diff

-2109.0.17.0.0
+2109.0.22.0.0

-  Functions: 2486
-  Symbols:   2788
-  CStrings:  529
+  Functions: 2474
+  Symbols:   2778
+  CStrings:  534
Symbols:
+ _rej_rnd_kat
- _ccapsic_client_check_intersect_response
- _ccapsic_client_check_intersect_response_ws
- _ccapsic_client_generate_match_response
- _ccapsic_client_init
- _ccapsic_client_init_internal
- _ccapsic_client_state_sizeof
- _ccapsic_server_determine_intersection
- _ccapsic_server_encode_element
- _ccapsic_server_encode_element_ws
- _ccapsic_server_init
- _ccapsic_server_state_sizeof
CStrings:
+ "FIPSPOST_USER [%llu] %s:%d: FAILED: ccmldsa_import_privkey: %d\n"
+ "FIPSPOST_USER [%llu] %s:%d: FAILED: ccmldsa_import_pubkey: %d\n"
+ "FIPSPOST_USER [%llu] %s:%d: FAILED: ccmldsa_sign (rejection): %d\n"
+ "FIPSPOST_USER [%llu] %s:%d: FAILED: mismatch rejection sig: %d\n"
+ "fipspost_post_mldsa_sign_rejection_kat"
```
