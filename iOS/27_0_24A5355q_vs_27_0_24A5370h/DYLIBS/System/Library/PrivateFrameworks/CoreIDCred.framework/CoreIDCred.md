## CoreIDCred

> `/System/Library/PrivateFrameworks/CoreIDCred.framework/CoreIDCred`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f750` | `0x3ec00` | **`-0xb50`** |
| `__TEXT.__oslogstring` | `0x2ccc` | `0x2bbc` | **`-0x110`** |
| `__TEXT.__objc_methlist` | `0x20ac` | `0x204c` | **`-0x60`** |
| `__TEXT.__unwind_info` | `0x1568` | `0x1510` | **`-0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0xc88` | `0xc48` | **`-0x40`** |
| `__DATA_CONST.__const` | `0xa10` | `0x9e8` | **`-0x28`** |

### Other Changes

```diff

-9.31.0.0.0
+9.34.0.0.0

-  Functions: 2135
-  Symbols:   1706
-  CStrings:  429
+  Functions: 2111
+  Symbols:   1691
+  CStrings:  425
Symbols:
- -[DCCredentialStore deletePIITokenFromSyncableKeyStoreForIdentifier:credentialIdentifier:completion:]
- -[DCCredentialStore deletePIITokenFromSyncableKeyStoreForIdentifier:credentialIdentifier:keystoreType:completion:]
- -[DCCredentialStore retrievePIITokenFromSyncableKeyStoreForIdentifier:completion:]
- -[DCCredentialStore retrievePIITokenFromSyncableKeyStoreForIdentifier:keystoreType:credentialIdentifier:completion:]
- -[DCCredentialStore storePIITokenInSyncableKeyStoreForIdentifier:data:credentialIdentifier:completion:]
- -[DCCredentialStore storePIITokenInSyncableKeyStoreForIdentifier:data:credentialIdentifier:keystoreType:completion:]
- -[DCCredentialStore updatePIITokenInSyncableKeyStoreForIdentifier:attributesToUpdate:credentialIdentifier:completion:]
- -[DCCredentialStore updatePIITokenInSyncableKeyStoreForIdentifier:attributesToUpdate:credentialIdentifier:keystoreType:completion:]
- ___101-[DCCredentialStore deletePIITokenFromSyncableKeyStoreForIdentifier:credentialIdentifier:completion:]_block_invoke
- ___114-[DCCredentialStore deletePIITokenFromSyncableKeyStoreForIdentifier:credentialIdentifier:keystoreType:completion:]_block_invoke
- ___116-[DCCredentialStore retrievePIITokenFromSyncableKeyStoreForIdentifier:keystoreType:credentialIdentifier:completion:]_block_invoke
- ___116-[DCCredentialStore storePIITokenInSyncableKeyStoreForIdentifier:data:credentialIdentifier:keystoreType:completion:]_block_invoke
- ___118-[DCCredentialStore updatePIITokenInSyncableKeyStoreForIdentifier:attributesToUpdate:credentialIdentifier:completion:]_block_invoke
- ___131-[DCCredentialStore updatePIITokenInSyncableKeyStoreForIdentifier:attributesToUpdate:credentialIdentifier:keystoreType:completion:]_block_invoke
- ___block_descriptor_80_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
CStrings:
- "DCCredentialStore deletePIITokenFromSyncableKeyStoreForIdentifier"
- "DCCredentialStore retrievePIITokenFromSyncableKeyStoreForIdentifier"
- "DCCredentialStore storePIITokenInSyncableKeyStoreForIdentifier"
- "DCCredentialStore updatePIITokenInSyncableKeyStoreForIdentifier"
```
