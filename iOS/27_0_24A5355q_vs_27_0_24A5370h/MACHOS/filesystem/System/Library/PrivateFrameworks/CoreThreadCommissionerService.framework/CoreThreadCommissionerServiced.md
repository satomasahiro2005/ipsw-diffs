## CoreThreadCommissionerServiced

> `/System/Library/PrivateFrameworks/CoreThreadCommissionerService.framework/CoreThreadCommissionerServiced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6e0c0` | `0x6e934` | **`+0x874`** |
| `__TEXT.__oslogstring` | `0xabd4` | `0xae6e` | **`+0x29a`** |
| `__TEXT.__cstring` | `0xa163` | `0xa353` | **`+0x1f0`** |
| `__TEXT.__objc_methname` | `0x5ef5` | `0x6015` | **`+0x120`** |
| `__DATA_CONST.__cfstring` | `0x1a00` | `0x1aa0` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0x3720` | `0x37c0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x242c` | `0x2474` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0x15d0` | `0x1600` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x1328` | `0x1350` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x1730` | `0x1708` | **`-0x28`** |
| `__DATA.__objc_const` | `0x30d8` | `0x30f8` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x1855` | `0x1875` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1898` | `0x18b8` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xb00` | `0xb18` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x1a70` | `0x1a88` | **`+0x18`** |
| `__TEXT.__const` | `0x6d2` | `0x6e2` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xc8` | `0xcc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-431.0.2.0.0
+434.0.1.0.0

-  Functions: 1791
-  Symbols:   541
-  CStrings:  2767
+  Functions: 1803
+  Symbols:   544
+  CStrings:  2788
Symbols:
+ _CFUserNotificationDisplayNotice
+ _arc4random_uniform
+ _kCFPreferencesAnyHost
+ _objc_retain_x9
- _kCFPreferencesCurrentHost
CStrings:
+ " "
+ "%s:%d : current is past periodicity of self heal thread network timer, applying jitter delay in secs : %d"
+ "%s:%d: CredShare: Service %@ xpanId mismatch. Service xp: %@, Expected: %@"
+ "%s:%d:CredShare: Admin code expected, but empty."
+ "%s:%d:CredShare: Current state: '%@', Timeout: %u sec, Elapsed time: %.0f sec, Cached xpanId: %@, Requested xpanId: %@"
+ "%s:%d:CredShare: Displaying error dialog - Title: '%@', Message: '%@'"
+ "%s:%d:CredShare: Displaying success dialog - Title: '%@', Message: '%{private}@'"
+ "%s:%d:CredShare: Edge case - ePSKcState started but admin code missing. We should restart process to get admin code"
+ "%s:%d:CredShare: Invalid xpanId size %lu, expected %d"
+ "%s:%d:CredShare: Message missing ';ePSKcTimeout:' marker: '%@'"
+ "-[CTCSXPCService ctcsServerEnableCredentialSharingModeInternallyWithExtendedPANId:completion:]"
+ "-[CTCSXPCService ctcsServerEnableCredentialSharingModeWithExtendedPANId:completion:]"
+ "-[THThreadNetworkCredentialsKeychainBackingStore displayCredentialShareErrorDialogWithMessage:]_block_invoke"
+ "-[THThreadNetworkCredentialsKeychainBackingStore displayCredentialShareSuccessDialogWithMessage:]_block_invoke"
+ "-[THThreadNetworkCredentialsKeychainBackingStore enableCredentialSharingModeWithExtendedPANId:completion:]_block_invoke"
+ "-[THThreadNetworkCredentialsKeychainBackingStore findmDNSScanMatchingNetworkNameSupportingEPSKCwithExtendedPANId:completion:]_block_invoke"
+ "-[THThreadNetworkCredentialsStoreLocalClient enableCredentialSharingModeWithExtendedPANId:completion:]_block_invoke_2"
+ "-[THThreadNetworkCredentialsStoreLocalClient findmDNSScanMatchingNetworkNameSupportingEPSKCwithExtendedPANId:completion:]_block_invoke_2"
+ ";ePSKcTimeout:"
+ "@?16@0:8"
+ "CredShare: Failed to enable Credential Sharing Mode internally; Backing store is nil"
+ "CredShare: Invalid extended PAN ID size"
+ "CredShare: Service %@ passed all filters (xp matched, vn=%@, sb bit 11 set)"
+ "Failed to send EnableCS message to Border Router"
+ "Invalid dataset: ds is nil or empty, length: %lu, pointer: %p"
+ "Missing required fields (AdminCode, ePSKcState, or ePSKcTimeout)"
+ "Thread Administration One-Time Passcode"
+ "Thread Credential Sharing Error"
+ "Unable to find border router supporting EPSKC"
+ "_receivedEpskcXpanId"
+ "ctcsServerEnableCredentialSharingModeInternallyWithExtendedPANId:completion:"
+ "ctcsServerEnableCredentialSharingModeWithExtendedPANId:completion:"
+ "displayCredentialShareErrorDialogWithMessage:"
+ "displayCredentialShareSuccessDialogWithMessage:"
+ "enableCredentialSharingModeWithExtendedPANId:completion:"
+ "findmDNSScanMatchingNetworkNameSupportingEPSKCwithExtendedPANId:completion:"
+ "handleCredentialShareError:completion:"
+ "setCredentialSharingCompletion:"
+ "takeCredentialSharingCompletion"
+ "v32@0:8@\"NSData\"16@?<v@?@\"NSArray\"@\"NSError\">24"
- "%s:%d:CredShare: Current state: '%@', Timeout: %u sec, Elapsed time: %.0f sec"
- "%s:%d:CredShare: Message missing ';ePKScTimeout:' marker: '%@'"
- "-[CTCSXPCService ctcsServerEnableCredentialSharingModeInternallyWithCompletion:]"
- "-[CTCSXPCService ctcsServerEnableCredentialSharingModeWithCompletion:]"
- "-[THThreadNetworkCredentialsKeychainBackingStore enableCredentialSharingModeWithCompletion:]_block_invoke"
- "-[THThreadNetworkCredentialsKeychainBackingStore findmDNSScanMatchingNetworkNameSupportingEPSKCwithCompletion:]_block_invoke"
- "-[THThreadNetworkCredentialsStoreLocalClient enableCredentialSharingModeWithCompletion:]_block_invoke_2"
- "-[THThreadNetworkCredentialsStoreLocalClient findmDNSScanMatchingNetworkNameSupportingEPSKCwithCompletion:]_block_invoke_2"
- ";ePKScTimeout:"
- "CredShare: Service %@ passed all filters (vn=%@, sb bit 11 set)"
- "Don't find BR supporting EPSKC."
- "Failed to send EnableCS message"
- "Missing required fields (AdminCode, ePSKcState, or ePKScTimeout)"
- "ctcsServerEnableCredentialSharingModeInternallyWithCompletion:"
- "ctcsServerEnableCredentialSharingModeWithCompletion:"
- "enableCredentialSharingModeWithCompletion:"
- "findmDNSScanMatchingNetworkNameSupportingEPSKCwithCompletion:"
- "v24@0:8@?<v@?@\"NSString\"@\"NSError\">16"
- "v24@?0@\"NSString\"8@\"NSError\"16"
```
