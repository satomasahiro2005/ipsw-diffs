## libVinylNonUpdater.dylib

> `/usr/lib/libVinylNonUpdater.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59e2c` | `0x59f10` | **`+0xe4`** |
| `__TEXT.__const` | `0x73cc` | `0x7424` | **`+0x58`** |
| `__DATA.__data` | `0xc70` | `0xc98` | **`+0x28`** |
| `__TEXT.__cstring` | `0xc9ea` | `0xca08` | **`+0x1e`** |
| `__TEXT.__unwind_info` | `0x1f78` | `0x1f80` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 1698
-  Symbols:   3137
-  CStrings:  1554
+  Functions: 1701
+  Symbols:   3148
+  CStrings:  1555
Symbols:
+ ___der_key_last_mesa_auth
+ ___der_key_last_mesa_unlock
+ ___der_key_last_passcode_auth
+ ___der_key_last_passcode_unlock
+ ___der_key_sks_heap_stats
+ _aks_get_convenience_bio_state
+ _der_key_last_mesa_auth
+ _der_key_last_mesa_unlock
+ _der_key_last_passcode_auth
+ _der_key_last_passcode_unlock
+ _der_key_sks_heap_stats
Functions:
~ _OUTLINED_FUNCTION_22 : 12 -> 20
~ _OUTLINED_FUNCTION_23 : 32 -> 12
+ _OUTLINED_FUNCTION_24
+ _firebloom_cp_prime_size
~ _aks_kext_get_options : 204 -> 188
~ _aks_get_internal_info_for_key : 384 -> 376
+ _aks_get_convenience_bio_state
CStrings:
+ "aks_get_convenience_bio_state"
```
