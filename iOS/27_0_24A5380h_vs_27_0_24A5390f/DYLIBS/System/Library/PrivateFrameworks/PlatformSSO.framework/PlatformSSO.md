## PlatformSSO

> `/System/Library/PrivateFrameworks/PlatformSSO.framework/PlatformSSO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5adf0` | `0x5be94` | **`+0x10a4`** |
| `__TEXT.__oslogstring` | `0x2531` | `0x28f1` | **`+0x3c0`** |
| `__DATA_CONST.__objc_selrefs` | `0x2398` | `0x2400` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0x3534` | `0x358c` | **`+0x58`** |
| `__TEXT.__dlopen_cstrs` | `0x110` | `0x162` | **`+0x52`** |
| `__TEXT.__gcc_except_tab` | `0x13a8` | `0x13f8` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x3a00` | `0x3a40` | **`+0x40`** |
| `__TEXT.__cstring` | `0x8256` | `0x8296` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x8608` | `0x8640` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x1578` | `0x15a8` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x740` | `0x750` | **`+0x10`** |
| `__DATA_CONST.__const` | `0xf60` | `0xf50` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x38c` | `0x390` | **`+0x4`** |

### Other Changes

```diff

-643.0.21.0.0
+643.0.33.0.0

-  Functions: 2126
-  Symbols:   2648
-  CStrings:  1034
+  Functions: 2144
+  Symbols:   2656
+  CStrings:  1050
Symbols:
+ -[PODirectoryServices fullNameForUserName:]
+ -[POExtension _validateExtensionTeamIdentifier:]
+ -[POExtension initWithExtensionBundleIdentifier:teamIdentifier:delegate:]
+ -[POExtension initWithExtensionBundleIdentifier:teamIdentifier:extensionManager:delegate:]
+ -[POExtensionAgentProcess teamIdentifierForXPCConnection:]
+ -[POProfile extensionTeamIdentifier]
+ -[PORegistrationManager loadSSOExtensionWithExtensionBundleIdentifier:teamIdentifier:]
+ GCC_except_table100
+ GCC_except_table108
+ GCC_except_table114
+ GCC_except_table122
+ GCC_except_table129
+ GCC_except_table177
+ GCC_except_table30
+ GCC_except_table45
+ GCC_except_table5
+ GCC_except_table73
+ _AppSSOCoreLibraryCore.frameworkLibrary
+ _OBJC_IVAR_$_POProfile._extensionTeamIdentifier
+ _OUTLINED_FUNCTION_12
+ _SecTaskCopyTeamIdentifier
+ ___AppSSOCoreLibraryCore_block_invoke
+ ___getSOUtilsClass_block_invoke
+ _audit_stringAppSSOCore
+ _getSOUtilsClass.softClass
+ _objc_retainBlock
- GCC_except_table107
- GCC_except_table113
- GCC_except_table116
- GCC_except_table120
- GCC_except_table127
- GCC_except_table176
- GCC_except_table29
- GCC_except_table32
- GCC_except_table37
- GCC_except_table38
- GCC_except_table51
- GCC_except_table72
- GCC_except_table87
- GCC_except_table99
- ___54-[POExtensionAgentProcess isCallerCurrentSSOExtension]_block_invoke_2
- ___block_descriptor_57_e8_32s40s48s_e20_v24?0Q8"NSError"16ls32l8s40l8s48l8
- _isCallerCurrentSSOExtension.extensionIdentifier
- _isCallerCurrentSSOExtension.onceToken
CStrings:
+ ")#Y"
+ "Apple"
+ "Caller team identifier is not current extension"
+ "PlatformSSO extension bundle identifier mismatch: requested=%{public}@, loaded=%{public}@"
+ "PlatformSSO extension has no bundle path; cannot validate team identifier %{public}@"
+ "PlatformSSO extension signature check failed for %{public}@: %{public}@"
+ "PlatformSSO extension team identifier mismatch: requested=%{public}@, signed=%{public}@"
+ "SOUtils"
+ "Skipping local account password sync; AllowWebLoginPasswordSync is disabled for web login"
+ "The user is not a platform SSO user, skipping notification."
+ "User state is needs registration, key is invalid, or new user pending registration"
+ "ignoring PlatformSSO extension team identifier mismatch because extension signature validation is disabled"
+ "invalid team identifier of the extension, teamIdentifier=%{public}@, requiredTeamIdentifier=%{public}@"
+ "softlink:r:path:/System/Library/PrivateFrameworks/AppSSOCore.framework/AppSSOCore"
+ "teamIdentifier: CPCopyBundleIdentifierAndTeamFromAuditToken(): %{public}@"
+ "teamIdentifier: SecTaskCopyTeamIdentifier() failed %{public}@"
+ "teamIdentifier: SecTaskCreateWithAuditToken() failed"
+ "teamIdentifier: The entitlements are not validated."
- "(#Y"
- "User state is needs registration or key is invalid"
```
