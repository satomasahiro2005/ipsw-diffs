## AccountSubscriber

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/XPCServices/AccountSubscriber.xpc/AccountSubscriber`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13a80` | `0x145e0` | **`+0xb60`** |
| `__TEXT.__objc_stubs` | `0x2100` | `0x2280` | **`+0x180`** |
| `__TEXT.__cstring` | `0x10e9` | `0x11e9` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x1e36` | `0x1f31` | **`+0xfb`** |
| `__TEXT.__oslogstring` | `0xfd0` | `0x10a8` | **`+0xd8`** |
| `__DATA_CONST.__cfstring` | `0xd20` | `0xdc0` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x220` | `0x290` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x8d8` | `0x940` | **`+0x68`** |
| `__DATA.__objc_selrefs` | `0x978` | `0x9d0` | **`+0x58`** |
| `__DATA_CONST.__got` | `0x3f8` | `0x440` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x3f8` | `0x420` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x86c` | `0x88c` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x390` | `0x3a0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1d8` | `0x1e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-624.2.3.0.0
+624.40.12.0.0

-  Functions: 299
-  Symbols:   300
-  CStrings:  555
+  Functions: 310
+  Symbols:   318
+  CStrings:  574
Symbols:
+ _AccountPropertyCommunicationServiceRules
+ _AccountPropertyMailAllowAppSheet
+ _AccountPropertyMailAllowMailRecentsSyncing
+ _AccountPropertyMailAllowMove
+ _AccountPropertyMailEnableMailDrop
+ _AccountPropertyRemoteManagementProfileTransferDate
+ _AccountPropertyRemoteManagementTransferredFromProfileIdentifier
+ _MCRemoteManagementTransferProfileAccount
+ _OBJC_CLASS_$_NSDate
+ _OBJC_CLASS_$_RMFeatureFlags
+ _RMModelAccountMailDeclaration_IncomingServer_AuthenticationMethod_CRAMMD5
+ _RMModelAccountMailDeclaration_IncomingServer_AuthenticationMethod_HTTPMD5
+ _RMModelAccountMailDeclaration_IncomingServer_AuthenticationMethod_NTLM
+ _RMModelStatusAccountListExchange_ProtocolType_EAS
+ _RemoteManagementManagingOwnerIdentifier
+ _kDAAccountEmailAddress
+ _kMCAccountProfileUUIDKey
+ _kMCCommunicationServiceRulesAccountProperty
CStrings:
+ "Account cannot be saved: %{public}@ %{public}@"
+ "AudioCall"
+ "DefaultServiceHandlers"
+ "Failed to record failure for %{public}@: %{public}@"
+ "No existing DDM-managed account for key %{public}@, checking for profile transfer candidate"
+ "No supported protocol in EnabledProtocolTypes: %{public}@"
+ "Only EAS is supported on this device"
+ "RemoteManagementProfileTransferDate"
+ "RemoteManagementTransferredFromProfileIdentifier"
+ "Skipping configuration %{public}@ after failed profile transfer: %{public}@"
+ "_remotemanagement_communicationServiceRules"
+ "_remotemanagement_mailAllowAppSheet"
+ "_remotemanagement_mailAllowMailRecentsSyncing"
+ "_remotemanagement_mailAllowMove"
+ "_remotemanagement_mailEnableMailDrop"
+ "_transferProfileManagedAccountWithIdentifier:error:"
+ "canSaveAccount:withCompletionHandler:"
+ "copy"
+ "date"
+ "denialErrorForSavingAccount:accountStore:"
+ "isAccountTakeoverEnabled"
+ "payloadAudioCall"
+ "payloadDefaultServiceHandlers"
+ "removeSearchSettings:"
+ "searchSettings"
+ "setStatusProtocolType:"
- "EmailAuthCRAMMD5"
- "EmailAuthHTTPMD5"
- "EmailAuthNTLM"
- "Only EAS is supported on iOS"
- "Profile account transfer to DDM"
- "createNotImplementedErrorForFeature:"
- "transferProfileAccount: not implemented on this platform for account %{public}@"
```
