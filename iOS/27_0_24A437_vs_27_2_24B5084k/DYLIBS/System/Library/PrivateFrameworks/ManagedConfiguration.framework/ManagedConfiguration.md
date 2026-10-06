## ManagedConfiguration

> `/System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf7134` | `0xf7284` | **`+0x150`** |
| `__TEXT.__cstring` | `0x186ab` | `0x1878f` | **`+0xe4`** |
| `__AUTH_CONST.__cfstring` | `0x19640` | `0x19720` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x9798` | `0x96c3` | **`-0xd5`** |
| `__DATA_CONST.__const` | `0x4e40` | `0x4dd8` | **`-0x68`** |
| `__TEXT.__const` | `0x152c` | `0x1584` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0xb33c` | `0xb2ec` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x3288` | `0x3250` | **`-0x38`** |
| `__DATA.__data` | `0xca0` | `0xcc8` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x2130` | `0x2110` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0xd808` | `0xd7e8` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x5e18` | `0x5e00` | **`-0x18`** |
| `__TEXT.__gcc_except_tab` | `0x1040` | `0x1048` | **`+0x8`** |

### Other Changes

```diff

-2483.2.6.0.0
+2483.40.14.0.0

-  Functions: 5817
-  Symbols:   9720
-  CStrings:  4621
+  Functions: 5814
+  Symbols:   9726
+  CStrings:  4629
Symbols:
+ -[MCNotifier sendAllowCloudSyncChangedNotification]
+ -[MCProfileConnection _allowCloudSyncDidChange:]
+ GCC_except_table45
+ GCC_except_table53
+ GCC_except_table93
+ _MCAllowCloudSyncChangedNotification
+ _MCRemoteManagementTransferProfileAccount
+ _MCSendAllowCloudSyncChangedNotification
+ _MCTakeoverErrorDomain
+ ___48-[MCProfileConnection _allowCloudSyncDidChange:]_block_invoke
+ ___48-[MCProfileConnection _allowCloudSyncDidChange:]_block_invoke_2
+ ___MCRemoteManagementTransferProfileAccount_block_invoke
+ ___block_descriptor_64_e8_32s40s48r56r_e20_v20?0B8"NSError"12lr48l8r56l8s32l8s40l8
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
- -[MCProfileConnection(Profiles) provisiongProfileUUIDsForSignerIdentity:]
- -[MCProfileConnection(Profiles) removeTrustedCodeSigningIdentities:]
- -[MCProfileConnection(Profiles) signerIdentityForBundleID:]
- -[MCProfileConnection(Profiles) syncTrustedCodeSigningIdentitiesWithOutError:]
- -[MCProfileConnection(Profiles) verifiedTrustedCodeSigningIdentities]
- GCC_except_table102
- GCC_except_table116
- GCC_except_table89
- GCC_except_table99
- ___59-[MCProfileConnection(Profiles) signerIdentityForBundleID:]_block_invoke
- ___69-[MCProfileConnection(Profiles) verifiedTrustedCodeSigningIdentities]_block_invoke
- ___73-[MCProfileConnection(Profiles) provisiongProfileUUIDsForSignerIdentity:]_block_invoke
- ___78-[MCProfileConnection(Profiles) syncTrustedCodeSigningIdentitiesWithOutError:]_block_invoke
- ___block_descriptor_40_e8_32r_e27_v24?0"NSSet"8"NSError"16lr32l8
- ___block_descriptor_40_e8_32s_e17_v16?0"NSError"8ls32l8
- ___block_descriptor_48_e8_32s40r_e27_v24?0"NSSet"8"NSError"16ls32l8r40l8
- ___block_descriptor_48_e8_32s40r_e30_v24?0"NSString"8"NSError"16ls32l8r40l8
CStrings:
+ "Account %{public}@ already owned by %{public}@; nothing to transfer"
+ "Account %{public}@ is not profile-managed; nothing to transfer"
+ "Account %{public}@ not found for profile-managed account transfer"
+ "ERROR_ACCOUNT_TAKEOVER_ACCOUNT_NOT_FOUND_P_ID"
+ "ERROR_ACCOUNT_TAKEOVER_INVALID_INPUT"
+ "ERROR_ACCOUNT_TAKEOVER_NOT_PROFILE_MANAGED_P_ID"
+ "ERROR_ACCOUNT_TAKEOVER_SAVE_FAILED_P_ID"
+ "MCTakeoverErrorDomain"
+ "Missing required arguments for profile-managed account transfer"
+ "Profile-managed account transfer save %{public}@ did not succeed (%{public}@); restoring account"
+ "Received allow cloud sync changed notification"
+ "Received enabling restrictions changed notification"
+ "Save profile-managed account transfer %{public}@ completed: %{public}@"
+ "Sending allow cloud sync changed notification."
+ "Transferring profile-managed account %{public}@ from profile %{public}@ to owner %{public}@"
+ "com.apple.managedconfiguration.allowcloudsyncchanged"
+ "timed out"
- "MCProfileConnection+Profiles XPC failed to get provisioning profile UUIDs for signer identity '%{public}@' with error: %{public}@"
- "MCProfileConnection+Profiles XPC failed to get signer identity for bundle ID '%{public}@' with error: %{public}@"
- "MCProfileConnection+Profiles XPC failed to get trusted code signing identities with error: %{public}@"
- "MCProfileConnection+Profiles XPC failed to sync trusted code signing identities with error: %{public}@"
- "MCProfileConnection+Profiles failed to get provisioning profile UUIDs for signer identity '%{public}@' with error: %{public}@"
- "MCProfileConnection+Profiles failed to get signer identity for bundle ID '%{public}@' with error: %{public}@"
- "MCProfileConnection+Profiles failed to get trusted code signing identities with error: %{public}@"
- "MCProfileConnection+Profiles failed to sync trusted code signing identities with error: %{public}@"
- "v24@?0@\"NSSet\"8@\"NSError\"16"
```
