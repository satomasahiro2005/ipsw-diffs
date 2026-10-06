## PlatformSSO

> `/System/Library/PrivateFrameworks/PlatformSSO.framework/PlatformSSO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c530` | `0x5d028` | **`+0xaf8`** |
| `__AUTH_CONST.__objc_const` | `0x8670` | `0x8828` | **`+0x1b8`** |
| `__TEXT.__objc_methlist` | `0x35bc` | `0x36bc` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x2961` | `0x2a41` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x82e6` | `0x8376` | **`+0x90`** |
| `__AUTH.__objc_data` | `0xa00` | `0xa50` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x2428` | `0x2460` | **`+0x38`** |
| `__DATA_CONST.__const` | `0xf78` | `0xfa0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x3a80` | `0x3aa0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x15c8` | `0x15e8` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x394` | `0x3a4` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1454` | `0x1464` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x108` | `0x110` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xc8` | `0xd0` | **`+0x8`** |

### Other Changes

```diff

-643.40.23.0.0
+643.40.27.0.0

-  Functions: 2154
-  Symbols:   2671
-  CStrings:  1053
+  Functions: 2179
+  Symbols:   2703
+  CStrings:  1058
Symbols:
+ +[POSoftwareUpdateCredentialPolicy credentialsWanted]
+ +[POSoftwareUpdateCredentialPolicy harvestPassword:forUserId:]
+ -[POAgentAuthenticationProcess keychainAccess]
+ -[POAgentAuthenticationProcess setKeychainAccess:]
+ -[POAgentProcess configurationManagerForUserName:]
+ -[POAgentProcess keychainAccess]
+ -[POAgentProcess setKeychainAccess:]
+ -[POAgentProcess updateLocalAccountPassword:oldPasswordContext:passwordContext:completion:]
+ -[POAgentProcess updateLocalAccountPassword:oldPasswordContextData:passwordContextData:completion:]
+ -[POAuthPluginProcess updateLocalAccountPassword:oldPasswordContext:passwordContext:completion:]
+ -[POConfigurationManager keychainAccess]
+ -[POConfigurationManager setKeychainAccess:]
+ -[PODirectoryServices .cxx_destruct]
+ -[PODirectoryServices init]
+ -[PODirectoryServices keychainAccess]
+ -[PODirectoryServices setKeychainAccess:]
+ -[PORegistrationManager setUserAuthPluginProcess:]
+ -[PORegistrationManager storeCredentialContext:]
+ -[PORegistrationManager updatePasswordHint]
+ -[POServiceConnection updateLocalAccountPassword:oldPasswordContextData:passwordContextData:completion:]
+ GCC_except_table101
+ GCC_except_table112
+ GCC_except_table116
+ GCC_except_table121
+ GCC_except_table124
+ GCC_except_table180
+ GCC_except_table31
+ GCC_except_table57
+ GCC_except_table74
+ _OBJC_CLASS_$_POKeychainAccess
+ _OBJC_CLASS_$_POSoftwareUpdateCredentialPolicy
+ _OBJC_IVAR_$_POAgentAuthenticationProcess._keychainAccess
+ _OBJC_IVAR_$_POAgentProcess._keychainAccess
+ _OBJC_IVAR_$_POConfigurationManager._keychainAccess
+ _OBJC_IVAR_$_PODirectoryServices._keychainAccess
+ _OBJC_METACLASS_$_POSoftwareUpdateCredentialPolicy
+ _OUTLINED_FUNCTION_13
+ __OBJC_$_CLASS_METHODS_POSoftwareUpdateCredentialPolicy
+ __OBJC_$_CLASS_PROP_LIST_POSoftwareUpdateCredentialPolicy
+ __OBJC_$_INSTANCE_VARIABLES_PODirectoryServices
+ __OBJC_CLASS_RO_$_POSoftwareUpdateCredentialPolicy
+ __OBJC_METACLASS_RO_$_POSoftwareUpdateCredentialPolicy
+ ___104-[POServiceConnection updateLocalAccountPassword:oldPasswordContextData:passwordContextData:completion:]_block_invoke
+ ___48-[PORegistrationManager storeCredentialContext:]_block_invoke
+ ___block_descriptor_56_e8_32s40s48bs_e20_v24?0Q8"NSError"16ls32l8s40l8s48l8
- -[PORegistrationManager storeCredentialAndUpdatePasswordHint]
- GCC_except_table100
- GCC_except_table110
- GCC_except_table115
- GCC_except_table123
- GCC_except_table129
- GCC_except_table178
- GCC_except_table30
- GCC_except_table45
- GCC_except_table73
- GCC_except_table86
- _OBJC_CLASS_$_NSURLRequest
- ___61-[PORegistrationManager storeCredentialAndUpdatePasswordHint]_block_invoke
CStrings:
+ "\v"
+ "-[POAuthPluginProcess updateLocalAccountPassword:oldPasswordContext:passwordContext:completion:]"
+ "Falling back to password-authorized local account password change"
+ "No usable old credential was supplied; using the stashed credential"
+ "Password update fallback result: %{public}@"
+ "The new credential context cannot be externalized"
+ "\xf0\xd1"
- "\n"
- "\xf0\xc1"
```
