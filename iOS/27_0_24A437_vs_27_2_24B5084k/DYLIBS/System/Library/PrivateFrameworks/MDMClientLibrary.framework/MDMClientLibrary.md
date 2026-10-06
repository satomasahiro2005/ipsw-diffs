## MDMClientLibrary

> `/System/Library/PrivateFrameworks/MDMClientLibrary.framework/MDMClientLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e750` | `0x1e938` | **`+0x1e8`** |
| `__TEXT.__oslogstring` | `0x30b8` | `0x313f` | **`+0x87`** |
| `__AUTH_CONST.__cfstring` | `0x3320` | `0x3380` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x11b8` | `0x1178` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x1db4` | `0x1df4` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x50c` | `0x4d8` | **`-0x34`** |
| `__DATA_CONST.__objc_selrefs` | `0x13b0` | `0x13d8` | **`+0x28`** |
| `__TEXT.__cstring` | `0x2475` | `0x245f` | **`-0x16`** |
| `__AUTH_CONST.__objc_const` | `0x3a10` | `0x3a18` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x3c8` | `0x3d0` | **`+0x8`** |

### Other Changes

```diff

-113.2.5.0.0
+113.40.17.0.0

-  Functions: 685
-  Symbols:   1666
-  CStrings:  644
+  Functions: 688
+  Symbols:   1669
+  CStrings:  648
Symbols:
+ +[MDMCheckInRequest responseFromTransaction:]
+ +[MDMMAIDBearerTokenAuthenticator _createMissingAltDSIDErrorWithAccountID:]
+ -[MDMClientCore executeDeclarativeManagementRequestForEndpoint:requestData:completion:]
+ -[MDMCloudConfiguration organizationID]
+ -[MDMCloudConfiguration organizationType]
+ -[MDMConfigurationBase _nameForChannelType:]
+ GCC_except_table108
+ GCC_except_table112
+ GCC_except_table15
+ GCC_except_table23
+ GCC_except_table43
+ GCC_except_table89
+ ___87-[MDMClientCore executeDeclarativeManagementRequestForEndpoint:requestData:completion:]_block_invoke
+ ___block_descriptor_56_e8_32s40bs_e5_v8?0ls32l8s40l8
+ _kCCOrganizationIDKey
+ _kCCOrganizationTypeKey
+ _kMDMChannelStringDevice
+ _kMDMChannelStringUser
- +[MDMProvisioningProfileTrust manualTrustSignerIdentities:]
- +[MDMProvisioningProfileTrust signerIdentitiesFromProvisioningProfileUUID:]
- GCC_except_table106
- GCC_except_table110
- GCC_except_table17
- GCC_except_table21
- GCC_except_table25
- GCC_except_table27
- GCC_except_table47
- GCC_except_table87
- ___59+[MDMProvisioningProfileTrust manualTrustSignerIdentities:]_block_invoke
- ___75+[MDMProvisioningProfileTrust signerIdentitiesFromProvisioningProfileUUID:]_block_invoke
- ___block_descriptor_40_e8_32bs_e57_v32?0"MDMHTTPTransaction"8"NSDictionary"16"NSError"24ls32l8
- ___block_descriptor_40_e8_32s_e22_v24?0^v8"NSString"16ls32l8
- ___block_descriptor_48_e8_32s40r_e9_B16?0^v8ls32l8r40l8
CStrings:
+ "DMC_MISSING_ALT_DSID_%@"
+ "Device"
+ "Failed to execute DeclarativeManagement request. Error: %{public}@"
+ "MDMConfigurationBase: dataWithContentsOfFile (%@) failed with error: %{public}@"
+ "Not exchanging MAID for bearer token, RM account %{public}@ has no altDSID"
+ "Not exchanging MAID for bearer token, no RM account with ID %{public}@: %{public}@"
+ "Refreshing MDM details. Channel: %{public}@"
+ "User"
- "MDMProvisioningProfileTrust could not find provisioning profile for UUID %{public}@ with error: %{public}@"
- "MDMProvisioningProfileTrust failed to manually trust signer identities: %{public}@"
- "Refreshing MDM details."
- "v32@?0@\"MDMHTTPTransaction\"8@\"NSDictionary\"16@\"NSError\"24"
```
