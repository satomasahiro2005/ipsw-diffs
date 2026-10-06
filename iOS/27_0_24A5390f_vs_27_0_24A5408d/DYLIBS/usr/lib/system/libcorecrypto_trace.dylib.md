## libcorecrypto_trace.dylib

> `/usr/lib/system/libcorecrypto_trace.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8d054` | `0x8c4a0` | **`-0xbb4`** |
| `__DATA_CONST.__const` | `0x1ec8` | `0x2108` | **`+0x240`** |
| `__TEXT.__cstring` | `0x5a8b` | `0x5bb3` | **`+0x128`** |
| `__TEXT.__unwind_info` | `0x1d60` | `0x1d30` | **`-0x30`** |
| `__TEXT.__const` | `0x20498` | `0x204b8` | **`+0x20`** |

### Other Changes

```diff

-2109.0.17.0.0
+2109.0.22.0.0

-  Functions: 2645
-  Symbols:   2981
-  CStrings:  553
+  Functions: 2633
+  Symbols:   2971
+  CStrings:  558
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
