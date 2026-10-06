## BiometricSupport

> `/System/Library/PrivateFrameworks/BiometricSupport.framework/BiometricSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ed9c` | `0x4ee4c` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x6fdc` | `0x7043` | **`+0x67`** |
| `__TEXT.__const` | `0x13ec` | `0x1444` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x3735` | `0x377a` | **`+0x45`** |
| `__TEXT.__objc_methlist` | `0x291c` | `0x294c` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x3f48` | `0x3f70` | **`+0x28`** |
| `__DATA.__data` | `0xc30` | `0xc58` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1070` | `0x1090` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1ba0` | `0x1bb8` | **`+0x18`** |
| `__DATA.__bss` | `0x51` | `0x61` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1060` | `0x105c` | **`-0x4`** |

### Other Changes

```diff

-577.0.0.0.0
+578.40.6.0.0

-  Functions: 2020
-  Symbols:   2759
-  CStrings:  1236
+  Functions: 2033
+  Symbols:   2773
+  CStrings:  1240
Symbols:
+ -[BiometricKitXPCExportedObject getDeviceProperties:replyBlock:]
+ -[BiometricKitXPCServer addDeviceSpecificProperties:]
+ -[BiometricKitXPCServer getDeviceProperties:withClient:]
+ GCC_except_table188
+ GCC_except_table194
+ GCC_except_table196
+ GCC_except_table203
+ GCC_except_table208
+ GCC_except_table213
+ GCC_except_table221
+ GCC_except_table227
+ GCC_except_table230
+ GCC_except_table238
+ GCC_except_table248
+ GCC_except_table253
+ __MergedGlobals
+ ___der_key_state_abs_last_mesa_auth
+ ___der_key_state_abs_last_mesa_unlock
+ ___der_key_state_abs_last_passcode_auth
+ ___der_key_state_abs_last_passcode_unlock
+ ___der_key_state_abs_lock_time
+ _der_key_state_abs_last_mesa_auth
+ _der_key_state_abs_last_mesa_unlock
+ _der_key_state_abs_last_passcode_auth
+ _der_key_state_abs_last_passcode_unlock
+ _der_key_state_abs_lock_time
- GCC_except_table186
- GCC_except_table193
- GCC_except_table195
- GCC_except_table202
- GCC_except_table204
- GCC_except_table209
- GCC_except_table219
- GCC_except_table226
- GCC_except_table228
- GCC_except_table235
- GCC_except_table246
- GCC_except_table251
CStrings:
+ "-[BiometricKitXPCExportedObject getDeviceProperties:replyBlock:]"
+ "AssertMacros: %s (value = 0x%lx), version: BiometricKit-578.40.6~32, %s file: %s, line: %d\n\n"
+ "deviceProperties"
+ "devicePropertiesDict"
+ "getDeviceProperties: (client:%@) -> err:0x%x deviceProperties:%@\n"
- "AssertMacros: %s (value = 0x%lx), version: BiometricKit-577~3209, %s file: %s, line: %d\n\n"
```
