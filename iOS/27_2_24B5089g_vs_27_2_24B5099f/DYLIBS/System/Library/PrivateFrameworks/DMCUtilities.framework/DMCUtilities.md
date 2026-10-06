## DMCUtilities

> `/System/Library/PrivateFrameworks/DMCUtilities.framework/DMCUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36938` | `0x37628` | **`+0xcf0`** |
| `__TEXT.__oslogstring` | `0x5a74` | `0x5bf5` | **`+0x181`** |
| `__DATA_CONST.__objc_selrefs` | `0x26d0` | `0x2790` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x3004` | `0x309c` | **`+0x98`** |
| `__AUTH_CONST.__objc_const` | `0x4640` | `0x46d0` | **`+0x90`** |
| `__TEXT.__gcc_except_tab` | `0x5fc` | `0x654` | **`+0x58`** |
| `__DATA_DIRTY.__objc_data` | `0xa0` | `0xf0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xe40` | `0xe88` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x4460` | `0x44a0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x3b2d` | `0x3b61` | **`+0x34`** |
| `__AUTH_CONST.__objc_intobj` | `0x168` | `0x198` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1318` | `0x1340` | **`+0x28`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x18` | `0x30` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x28` | `0x38` | **`+0x10`** |
| `__TEXT.__const` | `0x1a8` | `0x1b8` | **`+0x10`** |
| `__DATA.__bss` | `0x928` | `0x930` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x710` | `0x718` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1a0` | `0x1a8` | **`+0x8`** |
| `__DATA.__data` | `0x300` | `0x2f9` | **`-0x7`** |

### Other Changes

```diff

-113.40.17.0.0
+113.40.20.0.0

+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

-  Functions: 1441
-  Symbols:   2841
-  CStrings:  1044
+  Functions: 1460
+  Symbols:   2863
+  CStrings:  1052
Symbols:
+ +[DMCAppNetworkAccessCheck _stateForBundleID:]
+ +[DMCAppNetworkAccessCheck _stateForPolicy:]
+ +[DMCAppNetworkAccessCheck allCapabilities]
+ +[DMCAppNetworkAccessCheck appBundleIdentifierForCapability:]
+ +[DMCAppNetworkAccessCheck displayNameForBundleIdentifier:]
+ +[DMCAppNetworkAccessCheck stateForCapability:]
+ +[DMCRatchet _armRatchetForOperation:completion:]
+ +[DMCRatchet _requireBiometricsForOperation:completion:]
+ +[DMCRatchet _responseForPolicy:result:error:]
+ +[DMCRatchet isAuthorizedForOperation:policy:completion:]
+ -[ACAccountStore(DeviceManagementClient) _dmc_accountsWithType:error:criteria:]
+ -[ACAccountStore(DeviceManagementClient) _dmc_logConflictingAccounts:matchedOn:value:]
+ -[ACAccountStore(DeviceManagementClient) dmc_conflictingAccountsWithAltDSID:error:]
+ -[ACAccountStore(DeviceManagementClient) dmc_conflictingAccountsWithUsername:error:]
+ _OBJC_CLASS_$_DMCAppNetworkAccessCheck
+ _OBJC_CLASS_$_LSApplicationRecord
+ _OBJC_METACLASS_$_DMCAppNetworkAccessCheck
+ __OBJC_$_CLASS_METHODS_DMCAppNetworkAccessCheck
+ __OBJC_CLASS_RO_$_DMCAppNetworkAccessCheck
+ __OBJC_METACLASS_RO_$_DMCAppNetworkAccessCheck
+ ___49+[DMCRatchet _armRatchetForOperation:completion:]_block_invoke
+ ___56+[DMCRatchet _requireBiometricsForOperation:completion:]_block_invoke
+ ___83-[ACAccountStore(DeviceManagementClient) dmc_conflictingAccountsWithAltDSID:error:]_block_invoke
+ ___83-[ACAccountStore(DeviceManagementClient) dmc_conflictingAccountsWithAltDSID:error:]_block_invoke_2
+ ___84-[ACAccountStore(DeviceManagementClient) dmc_conflictingAccountsWithUsername:error:]_block_invoke
+ ___block_descriptor_48_e8_32bs40r_e34_v24?0"NSDictionary"8"NSError"16lr40l8s32l8
+ ___getLAContextClass_block_invoke
+ _getLAContextClass
+ _getLAContextClass.softClass
- +[DMCRatchet _responseFromRatchetResult:error:]
- +[DMCRatchet isAuthorizedForOperation:completion:]
- GCC_except_table32
- ___50+[DMCRatchet isAuthorizedForOperation:completion:]_block_invoke
- ___88-[ACAccountStore(DeviceManagementClient) dmc_conflictingAccountsExistWithAltDSID:error:]_block_invoke
- ___88-[ACAccountStore(DeviceManagementClient) dmc_conflictingAccountsExistWithAltDSID:error:]_block_invoke_2
- ___89-[ACAccountStore(DeviceManagementClient) dmc_conflictingAccountsExistWithUsername:error:]_block_invoke
CStrings:
+ "App network access policy for %{public}@. Cellular: %ld, Wi-Fi: %ld, satellite: %ld, managed: %d, restricted: %d"
+ "Conflicting account with %{public}@ (%{public}@) exists (%lu total). Identifier: %@, type: %{public}@, owning bundle ID: %{public}@, primary: %d"
+ "DMCRatchet is authorized because LAContext is unavailable"
+ "Failed to load record for app: %{public}@ with error: %{public}@."
+ "LAContext"
+ "No app network access policy exists for %{public}@ yet."
+ "No app network access policy returned for %{public}@."
+ "Unable to read app network access policy for %{public}@: %{public}@"
+ "com.apple.AppStore"
+ "com.apple.mobilesafari"
- "Conflicting account with altDSID (%{public}@) exists. Identifier: %@, type: %{public}@"
- "Conflicting account with username (%{public}@) exists. Identifier: %@, type: %{public}@"
```
