## CoreIDCred

> `/System/Library/PrivateFrameworks/CoreIDCred.framework/CoreIDCred`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x2bbc` | `0x317c` | **`+0x5c0`** |
| `__TEXT.__text` | `0x3ec00` | `0x3e7f8` | **`-0x408`** |
| `__TEXT.__objc_methlist` | `0x204c` | `0x20ec` | **`+0xa0`** |
| `__AUTH.__data` | `0x90` | `—` | **`-0x90`** |
| `__AUTH_CONST.__const` | `0x1b80` | `0x1c08` | **`+0x88`** |
| `__DATA.__data` | `0xd40` | `0xcd0` | **`-0x70`** |
| `__AUTH_CONST.__auth_got` | `0x7e0` | `0x798` | **`-0x48`** |
| `__DATA_CONST.__got` | `0x318` | `0x2e0` | **`-0x38`** |
| `__TEXT.__unwind_info` | `0x1510` | `0x1548` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x3740` | `0x3768` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0xc48` | `0xc70` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x668` | `0x650` | **`-0x18`** |
| `__TEXT.__swift5_typeref` | `0xcf3` | `0xcdf` | **`-0x14`** |
| `__TEXT.__swift5_reflstr` | `0x334` | `0x324` | **`-0x10`** |
| `__TEXT.__constg_swiftt` | `0x800` | `0x7f4` | **`-0xc`** |

### Other Changes

```diff

-9.38.0.0.0
+9.42.0.0.0

-  Functions: 2111
-  Symbols:   1691
-  CStrings:  425
+  Functions: 2145
+  Symbols:   1707
+  CStrings:  444
Symbols:
+ -[DCCredentialStore deleteCredential:reason:completion:]
+ -[DCCredentialStore deletePIIDataFromSyncableKeyStoreForIdentifier:keystoreType:piiDataType:credentialIdentifier:reason:completion:]
+ -[DCCredentialStore resetCredentialOperationLogForCredential:completion:]
+ -[DCCredentialStore retrieveCredentialOperationLogsWithCompletion:]
+ -[DCCredentialStoreClient deleteCredential:reason:completion:]
+ -[DCCredentialStoreClient deletePIIDataFromSyncableKeyStoreForIdentifier:keystoreType:piiDataType:credentialIdentifier:reason:completion:]
+ -[DCCredentialStoreClient resetCredentialOperationLogForCredential:completion:]
+ -[DCCredentialStoreClient retrieveCredentialOperationLogsWithCompletion:]
+ -[DCCredentialStoreClient storePIIDataInSyncableKeyStoreForIdentifier:data:keystoreType:piiDataType:credentialIdentifier:reason:completion:]
+ ___132-[DCCredentialStore deletePIIDataFromSyncableKeyStoreForIdentifier:keystoreType:piiDataType:credentialIdentifier:reason:completion:]_block_invoke
+ ___138-[DCCredentialStoreClient deletePIIDataFromSyncableKeyStoreForIdentifier:keystoreType:piiDataType:credentialIdentifier:reason:completion:]_block_invoke
+ ___138-[DCCredentialStoreClient deletePIIDataFromSyncableKeyStoreForIdentifier:keystoreType:piiDataType:credentialIdentifier:reason:completion:]_block_invoke_2
+ ___140-[DCCredentialStoreClient storePIIDataInSyncableKeyStoreForIdentifier:data:keystoreType:piiDataType:credentialIdentifier:reason:completion:]_block_invoke
+ ___140-[DCCredentialStoreClient storePIIDataInSyncableKeyStoreForIdentifier:data:keystoreType:piiDataType:credentialIdentifier:reason:completion:]_block_invoke_2
+ ___56-[DCCredentialStore deleteCredential:reason:completion:]_block_invoke
+ ___62-[DCCredentialStoreClient deleteCredential:reason:completion:]_block_invoke
+ ___67-[DCCredentialStore retrieveCredentialOperationLogsWithCompletion:]_block_invoke
+ ___73-[DCCredentialStore resetCredentialOperationLogForCredential:completion:]_block_invoke
+ ___73-[DCCredentialStoreClient retrieveCredentialOperationLogsWithCompletion:]_block_invoke
+ ___73-[DCCredentialStoreClient retrieveCredentialOperationLogsWithCompletion:]_block_invoke_2
+ ___79-[DCCredentialStoreClient resetCredentialOperationLogForCredential:completion:]_block_invoke
+ ___swift_memcpy40_8
+ _type_layout_string 10CoreIDCred15DocumentRequestV
- _swift_cvw_initStructMetadataWithLayoutString
- _swift_cvw_initWithTake
- _swift_getEnumTagSinglePayloadGeneric
- _swift_getSingletonMetadata
- _swift_storeEnumTagSinglePayloadGeneric
- _symbolic _____Sg 10Foundation6LocaleV6RegionV
- _symbolic _____Sg_ABt 10Foundation6LocaleV6RegionV
CStrings:
+ "DCCredentialStore deleteCredential:reason:"
+ "DCCredentialStore deletePIIDataFromSyncableKeyStoreForIdentifier:reason:"
+ "DCCredentialStore resetCredentialOperationLogForCredential"
+ "DCCredentialStore retrieveCredentialOperationLogs"
+ "DCCredentialStoreClient deleteCredential:reason:"
+ "DCCredentialStoreClient deleteCredential:reason: returned successfully"
+ "DCCredentialStoreClient deleteCredential:reason: returned with error %{public}@"
+ "DCCredentialStoreClient deletePIIDataFromSyncableKeyStoreForIdentifier:reason:"
+ "DCCredentialStoreClient deletePIIDataFromSyncableKeyStoreForIdentifier:reason: returned successfully"
+ "DCCredentialStoreClient deletePIIDataFromSyncableKeyStoreForIdentifier:reason: returned with error %{public}@"
+ "DCCredentialStoreClient resetCredentialOperationLogForCredential"
+ "DCCredentialStoreClient resetCredentialOperationLogForCredential returned successfully"
+ "DCCredentialStoreClient resetCredentialOperationLogForCredential returned with error %{public}@"
+ "DCCredentialStoreClient retrieveCredentialOperationLogs"
+ "DCCredentialStoreClient retrieveCredentialOperationLogs returned successfully"
+ "DCCredentialStoreClient retrieveCredentialOperationLogs returned with error %{public}@"
+ "DCCredentialStoreClient storePIIDataInSyncableKeyStoreForIdentifier:reason:"
+ "DCCredentialStoreClient storePIIDataInSyncableKeyStoreForIdentifier:reason: returned successfully"
+ "DCCredentialStoreClient storePIIDataInSyncableKeyStoreForIdentifier:reason: returned with error %{public}@"
```
