## PlatformSSOCore

> `/System/Library/PrivateFrameworks/PlatformSSOCore.framework/PlatformSSOCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x97b10` | `0x982c0` | **`+0x7b0`** |
| `__TEXT.__oslogstring` | `0x1e67` | `0x1fd7` | **`+0x170`** |
| `__TEXT.__cstring` | `0xad28` | `0xae28` | **`+0x100`** |
| `__AUTH_CONST.__cfstring` | `0x7b20` | `0x7bc0` | **`+0xa0`** |
| `__TEXT.__const` | `0x19ac` | `0x1a04` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x62d8` | `0x6330` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x2d10` | `0x2d48` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x14d28` | `0x14d58` | **`+0x30`** |
| `__DATA.__data` | `0x1228` | `0x1250` | **`+0x28`** |
| `__AUTH_CONST.__objc_intobj` | `0x228` | `0x240` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2178` | `0x2190` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x9b0` | `0x9c0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x654` | `0x658` | **`+0x4`** |

### Other Changes

```diff

-643.0.47.0.0
+643.40.23.0.0

-  Functions: 3850
-  Symbols:   5836
-  CStrings:  1759
+  Functions: 3858
+  Symbols:   5854
+  CStrings:  1769
Symbols:
+ +[POCoreConfigurationUtil accountDisplayNameForDeviceConfiguration:loginConfiguration:]
+ +[POCoreConfigurationUtil alwaysUseLoginUIOverride]
+ +[POCoreConfigurationUtil shouldUsePlatformSSOLoginUIForDeviceConfiguration:]
+ -[PODeviceConfiguration alwaysUseLoginUI]
+ -[PODeviceConfiguration requiresPlatformSSOLoginUI]
+ -[PODeviceConfiguration setAlwaysUseLoginUI:]
+ -[PODeviceConfiguration supportsOpenID]
+ _OBJC_IVAR_$_PODeviceConfiguration._alwaysUseLoginUI
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
CStrings:
+ "%s IdP display name from the login configuration, the profile sets no AccountDisplayName on %@"
+ "%s Platform SSO login UI: %{public}@, alwaysUseLoginUI:%{public}@ openID:%{public}@ biometricRequired:%{public}@ loginType:%{public}@ on %@"
+ "%s Platform SSO login UI: always, set by local override on %@"
+ "%s no IdP display name in the device or login configuration on %@"
+ "+[POCoreConfigurationUtil accountDisplayNameForDeviceConfiguration:loginConfiguration:]"
+ "+[POCoreConfigurationUtil shouldUsePlatformSSOLoginUIForDeviceConfiguration:]"
+ "-[PODeviceConfiguration supportsOpenID]"
+ "AlwaysUseLoginUI"
+ "not required"
+ "required"
```
