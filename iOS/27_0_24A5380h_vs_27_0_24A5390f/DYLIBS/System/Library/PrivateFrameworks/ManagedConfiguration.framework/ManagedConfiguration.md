## ManagedConfiguration

> `/System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf5c40` | `0xf61fc` | **`+0x5bc`** |
| `__TEXT.__oslogstring` | `0x925b` | `0x94c9` | **`+0x26e`** |
| `__AUTH_CONST.__cfstring` | `0x19580` | `0x19640` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x1865d` | `0x186d0` | **`+0x73`** |
| `__TEXT.__const` | `0x14c4` | `0x152c` | **`+0x68`** |
| `__AUTH_CONST.__objc_const` | `0xd740` | `0xd770` | **`+0x30`** |
| `__DATA.__data` | `0xc78` | `0xca0` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xb28c` | `0xb2b4` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x5d90` | `0x5db0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x4e10` | `0x4e18` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3258` | `0x3250` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x990` | `0x994` | **`+0x4`** |

### Other Changes

```diff

-2483.0.1.0.0
+2483.0.5.0.0

-  Functions: 5790
-  Symbols:   9672
-  CStrings:  4597
+  Functions: 5797
+  Symbols:   9690
+  CStrings:  4611
Symbols:
+ -[MCPasscodeManager _simplePasscodeTypeDescription:]
+ -[MCPasscodeManager _unlockScreenTypeDescription:]
+ -[MCPasscodeManager currentUnlockScreenTypeWithOutSimpleType:]
+ -[MCPasscodeManager recoveryPasscodeUnlockScreenTypeWithOutSimpleType:]
+ -[MCPasscodeManager unlockScreenTypeForSharedDataVolume:withOutSimpleType:]
+ -[MCPasscodeManager unlockScreenTypeForUser:withOutSimpleType:]
+ -[MCPasscodeManager unlockScreenTypeWithPublicPasscodeDict:isRecovery:deviceHandle:outSimplePasscodeType:]
+ -[MCProfileConnection(Misc) isAutoCapitalizationAllowed]
+ -[MCSingleAppModeConfiguration allowAutoCapitalization]
+ -[MCSingleAppModeConfiguration setAllowAutoCapitalization:]
+ GCC_except_table290
+ _MCFeatureAutoCapitalizationAllowed
+ _MCFixPermissionOfManagedConfigurationFile
+ _MCFixPermissionOfManagedConfigurationFileFM
+ _MCFixPermissionsOfManagedConfigurationDirectoryAndContents
+ _MCFixPermissionsOfManagedConfigurationDirectoryAndContentsFM
+ _OBJC_IVAR_$_MCSingleAppModeConfiguration._allowAutoCapitalization
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
- -[MCPasscodeManager currentUnlockSimplePasscodeType]
- -[MCPasscodeManager recoveryPasscodeUnlockSimplePasscodeType]
- -[MCPasscodeManager unlockScreenTypeWithPublicPasscodeDict:isRecovery:deviceHandle:]
- -[MCPasscodeManager unlockSimplePasscodeTypeForSharedDataVolume:]
- -[MCPasscodeManager unlockSimplePasscodeTypeForUser:]
- -[MCPasscodeManager unlockSimplePasscodeTypeWithPublicPasscodeDict:isRecovery:deviceHandle:]
- GCC_except_table289
- _MCFixPermissionOfSystemGroupContainerFile
- _MCFixPermissionOfSystemGroupContainerFileFM
- _MCFixPermissionsOfSystemGroupContainerDirectoryAndContents
- _MCFixPermissionsOfSystemGroupContainerDirectoryAndContentsFM
CStrings:
+ "Failed to decode System Metadata: %{public}@"
+ "Failed to decode User Metadata: %{public}@"
+ "Failed to load System Metadata: %{public}@"
+ "Invalide simple passcode type value %{public}d. Defaulting to %{public}@"
+ "Invalide unlock screen and simple type state. Defaulting to %{public}@ and %{public}@"
+ "Invalide unlock screen value %{public}d. Defaulting to %{public}@"
+ "Not Simple"
+ "Numeric Long"
+ "Retrieved unlock screen type %{public}@ and simple type %{public}@ for generation %{public}@. Public Dictionary Exists: %{public}@. Is Empty: %{public}@. Generation Exists: %{public}@. Is Recovery: %{public}@"
+ "Retrieving unlock screen type and simple type for generation %{public}@. Public Dictionary Exists: %{public}@. Is Empty: %{public}@. Generation Exists: %{public}@. Is Recovery: %{public}@"
+ "Simple"
+ "Simple 4 Digit"
+ "Simple 6 Digit"
+ "aks_get_convenience_bio_state"
+ "allowAutoCapitalization"
- "Unable to retrieve unlock simple type for generation %{public}@, but retrieved simple unlock screen. Defaulting to Simple 4 Digits"
```
