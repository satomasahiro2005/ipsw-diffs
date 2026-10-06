## BiometricSupport

> `/System/Library/PrivateFrameworks/BiometricSupport.framework/BiometricSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ea48` | `0x4ebc8` | **`+0x180`** |
| `__TEXT.__const` | `0x1394` | `0x13ec` | **`+0x58`** |
| `__DATA.__data` | `0xc08` | `0xc30` | **`+0x28`** |
| `__TEXT.__cstring` | `0x6fb1` | `0x6fcf` | **`+0x1e`** |
| `__TEXT.__oslogstring` | `0x3733` | `0x3734` | **`+0x1`** |

### Other Changes

```diff

-575.0.0.0.0
+576.0.0.0.0

-  Functions: 2015
-  Symbols:   2744
-  CStrings:  1234
+  Functions: 2018
+  Symbols:   2756
+  CStrings:  1235
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
Functions:
~ _OUTLINED_FUNCTION_43 : 16 -> 24
~ _OUTLINED_FUNCTION_24 : 28 -> 12
~ _OUTLINED_FUNCTION_24 : 28 -> 12
+ _OUTLINED_FUNCTION_24
~ _OUTLINED_FUNCTION_22 : 12 -> 20
~ _OUTLINED_FUNCTION_22 : 8 -> 56
~ _OUTLINED_FUNCTION_40 : 24 -> 12
+ _OUTLINED_FUNCTION_42
~ _OUTLINED_FUNCTION_19 : 36 -> 16
~ _OUTLINED_FUNCTION_20 : 12 -> 36
~ _OUTLINED_FUNCTION_21 : 56 -> 12
~ _OUTLINED_FUNCTION_23 : 12 -> 8
~ _OUTLINED_FUNCTION_26 : 20 -> 28
~ _OUTLINED_FUNCTION_27 : 28 -> 20
~ _OUTLINED_FUNCTION_28 : 12 -> 28
~ _OUTLINED_FUNCTION_31 : 32 -> 12
~ _OUTLINED_FUNCTION_33 : 36 -> 32
~ _OUTLINED_FUNCTION_34 : 16 -> 36
~ _OUTLINED_FUNCTION_35 : 36 -> 16
~ _OUTLINED_FUNCTION_36 : 12 -> 36
~ _OUTLINED_FUNCTION_37 : 20 -> 12
~ _OUTLINED_FUNCTION_38 : 28 -> 20
~ _OUTLINED_FUNCTION_39 : 12 -> 28
- _OUTLINED_FUNCTION_42
~ _aks_kext_get_options : 204 -> 188
~ _aks_get_internal_info_for_key : 384 -> 376
+ _aks_get_convenience_bio_state
+ _aks_get_sks_heap_stats
CStrings:
+ "AssertMacros: %s (value = 0x%lx), version: BiometricKit-576~458, %s file: %s, line: %d\n\n"
+ "aks_get_convenience_bio_state"
- "AssertMacros: %s (value = 0x%lx), version: BiometricKit-575~90, %s file: %s, line: %d\n\n"
```
