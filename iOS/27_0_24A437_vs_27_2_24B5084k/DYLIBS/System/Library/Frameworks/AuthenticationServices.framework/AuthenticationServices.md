## AuthenticationServices

> `/System/Library/Frameworks/AuthenticationServices.framework/AuthenticationServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1431ec` | `0x1439e8` | **`+0x7fc`** |
| `__DATA_CONST.__const` | `0x19c8` | `0x1a40` | **`+0x78`** |
| `__TEXT.__cstring` | `0xb558` | `0xb5a8` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x11d4` | `0x1220` | **`+0x4c`** |
| `__DATA_CONST.__objc_selrefs` | `0x4cb8` | `0x4d00` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0x10150` | `0x10190` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x8064` | `0x809c` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x5d00` | `0x5d28` | **`+0x28`** |
| `__TEXT.__oslogstring` | `0x356b` | `0x357b` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x700` | `0x708` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1090` | `0x1098` | **`+0x8`** |

### Other Changes

```diff

-625.1.29.10.29
+625.2.4.1.0

-  Functions: 8182
-  Symbols:   6515
-  CStrings:  1352
+  Functions: 8193
+  Symbols:   6529
+  CStrings:  1355
Symbols:
+ -[ASPasskeyCredentialIdentity _initWithFoundationCredentialIdentity:]
+ -[_ASWebsiteNameProvider _updateFetchingSuspended:]
+ -[_ASWebsiteNameProvider resumeFetching]
+ -[_ASWebsiteNameProvider suspendFetching]
+ GCC_except_table13
+ GCC_except_table19
+ GCC_except_table33
+ GCC_except_table46
+ GCC_except_table52
+ GCC_except_table54
+ GCC_except_table62
+ GCC_except_table64
+ GCC_except_table65
+ GCC_except_table68
+ GCC_except_table74
+ GCC_except_table75
+ GCC_except_table76
+ _OBJC_CLASS_$_NSThread
+ _OBJC_IVAR_$__ASAgentCredentialExchangeListener._extensionManager
+ _OBJC_IVAR_$__ASWebsiteNameFetchOperation._request
+ _OBJC_IVAR_$__ASWebsiteNameProvider._fetchingSuspended
+ ___105-[ASCredentialIdentityStore getCredentialIdentitiesForService:credentialIdentityTypes:completionHandler:]_block_invoke
+ ___105-[ASCredentialIdentityStore getCredentialIdentitiesForService:credentialIdentityTypes:completionHandler:]_block_invoke_2
+ ___38-[_ASWebsiteNameFetchOperation cancel]_block_invoke
+ ___51-[_ASWebsiteNameProvider _updateFetchingSuspended:]_block_invoke
+ ___block_descriptor_32_e54_"<ASCredentialIdentity>"16?0"SFCredentialIdentity"8l
+ ___block_descriptor_40_e8_32s_e23_B32?0"NSUUID"816^B24ls32l8
+ ___block_descriptor_41_ea8_32s_e5_v8?0ls32l8
+ ___block_descriptor_48_e8_32s40s_e34_"NSExtension"16?0"NSExtension"8ls32l8s40l8
+ ___block_descriptor_64_ea8_32s40s48s56bs_e5_v8?0ls32l8s56l8s40l8s48l8
- GCC_except_table15
- GCC_except_table22
- GCC_except_table23
- GCC_except_table48
- GCC_except_table49
- GCC_except_table50
- GCC_except_table51
- GCC_except_table56
- GCC_except_table66
- GCC_except_table70
- GCC_except_table71
- GCC_except_table72
- _OBJC_IVAR_$__ASPasswordManagerIconController._fetchingSuspended
- ___71-[_ASWebsiteNameProvider fetchOperation:finishedWithResult:completion:]_block_invoke_2
- ___block_descriptor_32_e34_"NSExtension"16?0"NSExtension"8l
- ___block_descriptor_64_ea8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
CStrings:
+ "@\"<ASCredentialIdentity>\"16@?0@\"SFCredentialIdentity\"8"
+ "B32@?0@\"NSUUID\"8@16^B24"
+ "Ignoring credential identity with unexpected type: %ld"
+ "Not persisting cancelled fetch for %{sensitive}@"
+ "\xf0!"
- "Skipping touch icon fetch while suspended; domain=%{sensitive, mask.hash}@"
- "\xf01"
```
