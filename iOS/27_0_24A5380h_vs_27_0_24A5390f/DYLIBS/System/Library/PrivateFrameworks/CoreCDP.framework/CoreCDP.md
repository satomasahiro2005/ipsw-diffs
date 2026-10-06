## CoreCDP

> `/System/Library/PrivateFrameworks/CoreCDP.framework/CoreCDP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f4c8` | `0x4f648` | **`+0x180`** |
| `__TEXT.__const` | `0x1424` | `0x147c` | **`+0x58`** |
| `__DATA.__data` | `0x1150` | `0x1178` | **`+0x28`** |
| `__TEXT.__cstring` | `0x65a4` | `0x65c2` | **`+0x1e`** |

### Other Changes

```diff

-444.0.0.0.0
+445.0.0.0.0

-  Functions: 2398
-  Symbols:   3873
-  CStrings:  1638
+  Functions: 2401
+  Symbols:   3885
+  CStrings:  1639
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
```
