## AppleKeyStore

> `/System/Library/PrivateFrameworks/AppleKeyStore.framework/AppleKeyStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x62b78` | `0x62d38` | **`+0x1c0`** |
| `__TEXT.__const` | `0x11073` | `0x110d3` | **`+0x60`** |
| `__TEXT.__cstring` | `0x348f` | `0x34ef` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x24f0` | `0x2520` | **`+0x30`** |
| `__DATA.__data` | `0x14a8` | `0x14d0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1740` | `0x1748` | **`+0x8`** |

### Other Changes

```diff

-2383.0.14.0.1
+2383.0.22.0.2

-  Functions: 2836
-  Symbols:   2647
-  CStrings:  754
+  Functions: 2840
+  Symbols:   2659
+  CStrings:  757
Symbols:
+ ___der_key_last_mesa_auth
+ ___der_key_last_mesa_unlock
+ ___der_key_last_passcode_auth
+ ___der_key_last_passcode_unlock
+ ___der_key_sks_heap_stats
+ _aks_get_convenience_bio_state
+ _aks_get_sks_heap_stats
+ _der_key_last_mesa_auth
+ _der_key_last_mesa_unlock
+ _der_key_last_passcode_auth
+ _der_key_last_passcode_unlock
+ _der_key_sks_heap_stats
CStrings:
+ "aks_get_convenience_bio_state"
+ "convenienceBioEnabled"
+ "convenienceBioToken"
```
