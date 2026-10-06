## ClassroomKit

> `/System/Library/PrivateFrameworks/ClassroomKit.framework/ClassroomKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb1218` | `0xb4cd0` | **`+0x3ab8`** |
| `__TEXT.__oslogstring` | `0x42cb` | `0x4ab1` | **`+0x7e6`** |
| `__AUTH_CONST.__objc_const` | `0x26978` | `0x26fd8` | **`+0x660`** |
| `__TEXT.__objc_methlist` | `0x12c8c` | `0x130f4` | **`+0x468`** |
| `__TEXT.__cstring` | `0x8a75` | `0x8c09` | **`+0x194`** |
| `__AUTH.__objc_data` | `0x6fe0` | `0x7170` | **`+0x190`** |
| `__DATA_CONST.__objc_selrefs` | `0x6eb0` | `0x7038` | **`+0x188`** |
| `__AUTH_CONST.__cfstring` | `0x8ec0` | `0x9040` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0x3a30` | `0x3b20` | **`+0xf0`** |
| `__DATA_CONST.__const` | `0x2998` | `0x2a38` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x1860` | `0x18e0` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x6b8` | `0x720` | **`+0x68`** |
| `__DATA.__data` | `0x33c8` | `0x3428` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x12c0` | `0x12f0` | **`+0x30`** |
| `__DATA_CONST.__objc_classlist` | `0xf00` | `0xf28` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x1250` | `0x1270` | **`+0x20`** |
| `__DATA_CONST.__objc_superrefs` | `0xbf0` | `0xc10` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x300` | `0x318` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0x620` | `0x630` | **`+0x10`** |
| `__TEXT.__const` | `0x180` | `0x190` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x450` | `0x458` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x78` | `0x80` | **`+0x8`** |

### Other Changes

```diff

-142.0.0.0.0
+143.2.1.0.0

-  Functions: 6365
-  Symbols:   12271
-  CStrings:  1624
+  Functions: 6469
+  Symbols:   12431
+  CStrings:  1669
Symbols:
+ +[CRKASMCredentialStoreFactory instructorCredentialStoreUsingLoginKeychain]
+ +[CRKASMCredentialStoreFactory instructorCredentialStoreUsingModernKeychain]
+ +[CRKASMCredentialStoreFactory instructorManifestServiceNames]
+ +[CRKASMCredentialStoreFactory makeCredentialStoreWithRole:keychainOverride:accessGroupOverride:]
+ +[CRKASMCredentialStoreFactory makeInstructorCredentialStoreWithKeychainOverride:accessGroupOverride:]
+ +[CRKASMRosterProviderConfiguration instructorRosterUsingLoginKeychainConfiguration]
+ +[CRKASMRosterProviderConfiguration instructorRosterUsingModernKeychainConfiguration]
+ +[CRKConcreteKeychain modernKeychain]
+ +[CRKIdentityConfiguration defaultCreatesDataProtectionKey]
+ +[CRKMigrateKeychainItemsToModernKeychainRequest allowlistedClassForResultObject]
+ +[CRKMigrateKeychainItemsToModernKeychainRequest supportsSecureCoding]
+ +[CRKMigrateKeychainItemsToModernKeychainResultObject supportsSecureCoding]
+ +[CRKPropertyListConverter propertyListSafeValue:]
+ +[CRKRemovePersistentIDsFromLoginKeychainRequest supportsSecureCoding]
+ +[NSXPCConnection(CRKAdditions) crk_keychainMigrationServiceConnection]
+ -[CRKASMCredentialStore ingestMigratedCredentialsFromStore:modernPersistentIDsByLegacyID:]
+ -[CRKASMCredentialStore removeStoredManifests]
+ -[CRKASMRosterProviderFactory makeInstructorRosterProviderUsingLoginKeychain]
+ -[CRKASMRosterProviderFactory makeInstructorRosterProviderUsingModernKeychain]
+ -[CRKAnnotatedCredentialStore deleteStoredManifestReturningError:]
+ -[CRKAnnotatedCredentialStore ingestMigratedManifestFromStore:modernPersistentIDsByLegacyID:]
+ -[CRKConcreteCertificate publicKeyHash]
+ -[CRKConcreteKeychain addItem:ofClass:toAccessGroup:]
+ -[CRKConcreteKeychain alwaysAccessibleAttribute]
+ -[CRKConcreteKeychain isUsingLegacyKeychain]
+ -[CRKConcreteKeychain isUsingModernKeychain]
+ -[CRKConcreteKeychain removeCertificate:error:]
+ -[CRKConcreteKeychain removeKeyWithApplicationLabel:keyClass:error:]
+ -[CRKConcreteKeychain removePasswordForService:error:]
+ -[CRKConcreteKeychain removePrivateKeyWithApplicationLabel:error:]
+ -[CRKConcreteKeychain removePublicKeyWithApplicationLabel:error:]
+ -[CRKConcretePrivateKey algorithmID]
+ -[CRKConcretePrivateKey applicationLabel]
+ -[CRKConcretePrivateKey publicKey]
+ -[CRKDevice lastStudentError]
+ -[CRKDevice setLastStudentError:]
+ -[CRKIdentityConfiguration createsDataProtectionKey]
+ -[CRKIdentityConfiguration setCreatesDataProtectionKey:]
+ -[CRKInMemoryCertificate publicKeyHash]
+ -[CRKInMemoryKeychain removeCertificate:error:]
+ -[CRKInMemoryKeychain removePasswordForService:error:]
+ -[CRKInMemoryKeychain removePrivateKeyWithApplicationLabel:error:]
+ -[CRKInMemoryKeychain removePublicKeyWithApplicationLabel:error:]
+ -[CRKInMemoryPrivateKey algorithmID]
+ -[CRKInMemoryPrivateKey applicationLabel]
+ -[CRKInMemoryPrivateKey publicKey]
+ -[CRKKeychainMigrationServiceProxy .cxx_destruct]
+ -[CRKKeychainMigrationServiceProxy _performMigrationRequest:completion:]
+ -[CRKKeychainMigrationServiceProxy _performRemovalRequest:completion:]
+ -[CRKKeychainMigrationServiceProxy connectionProvider]
+ -[CRKKeychainMigrationServiceProxy init]
+ -[CRKKeychainMigrationServiceProxy performMigrationRequest:completion:]
+ -[CRKKeychainMigrationServiceProxy performRemovalRequest:completion:]
+ -[CRKMigrateKeychainItemsToModernKeychainRequest .cxx_destruct]
+ -[CRKMigrateKeychainItemsToModernKeychainRequest certificatePersistentIDs]
+ -[CRKMigrateKeychainItemsToModernKeychainRequest encodeWithCoder:]
+ -[CRKMigrateKeychainItemsToModernKeychainRequest identityPersistentIDs]
+ -[CRKMigrateKeychainItemsToModernKeychainRequest initWithCoder:]
+ -[CRKMigrateKeychainItemsToModernKeychainRequest migratesInstructorASMCredentialStore]
+ -[CRKMigrateKeychainItemsToModernKeychainRequest setCertificatePersistentIDs:]
+ -[CRKMigrateKeychainItemsToModernKeychainRequest setIdentityPersistentIDs:]
+ -[CRKMigrateKeychainItemsToModernKeychainRequest setMigratesInstructorASMCredentialStore:]
+ -[CRKMigrateKeychainItemsToModernKeychainResultObject .cxx_destruct]
+ -[CRKMigrateKeychainItemsToModernKeychainResultObject encodeWithCoder:]
+ -[CRKMigrateKeychainItemsToModernKeychainResultObject initWithCoder:]
+ -[CRKMigrateKeychainItemsToModernKeychainResultObject modernPersistentIDsByLegacyPersistentID]
+ -[CRKMigrateKeychainItemsToModernKeychainResultObject setModernPersistentIDsByLegacyPersistentID:]
+ -[CRKNoOpKeychain removeCertificate:error:]
+ -[CRKNoOpKeychain removePasswordForService:error:]
+ -[CRKNoOpKeychain removePrivateKeyWithApplicationLabel:error:]
+ -[CRKNoOpKeychain removePublicKeyWithApplicationLabel:error:]
+ -[CRKRemovePersistentIDsFromLoginKeychainRequest .cxx_destruct]
+ -[CRKRemovePersistentIDsFromLoginKeychainRequest encodeWithCoder:]
+ -[CRKRemovePersistentIDsFromLoginKeychainRequest initWithCoder:]
+ -[CRKRemovePersistentIDsFromLoginKeychainRequest persistentIDs]
+ -[CRKRemovePersistentIDsFromLoginKeychainRequest setPersistentIDs:]
+ -[NSError(CRKAdditions) dictionaryValue]
+ -[NSError(CRKAdditions) initWithDictionary:]
+ GCC_except_table22
+ _CRKClassroomModernKeychainAccessGroup
+ _CRKConfigureInterfaceForKeychainMigrationService
+ _CRKDeviceLastStudentErrorKey
+ _CRKItemNotFoundError
+ _CRKKeychainMigrationServiceXPCInterface
+ _OBJC_CLASS_$_CRKKeychainMigrationServiceProxy
+ _OBJC_CLASS_$_CRKMigrateKeychainItemsToModernKeychainRequest
+ _OBJC_CLASS_$_CRKMigrateKeychainItemsToModernKeychainResultObject
+ _OBJC_CLASS_$_CRKPropertyListConverter
+ _OBJC_CLASS_$_CRKRemovePersistentIDsFromLoginKeychainRequest
+ _OBJC_IVAR_$_CRKDevice._lastStudentError
+ _OBJC_IVAR_$_CRKIdentityConfiguration._createsDataProtectionKey
+ _OBJC_IVAR_$_CRKKeychainMigrationServiceProxy._connectionProvider
+ _OBJC_IVAR_$_CRKMigrateKeychainItemsToModernKeychainRequest._certificatePersistentIDs
+ _OBJC_IVAR_$_CRKMigrateKeychainItemsToModernKeychainRequest._identityPersistentIDs
+ _OBJC_IVAR_$_CRKMigrateKeychainItemsToModernKeychainRequest._migratesInstructorASMCredentialStore
+ _OBJC_IVAR_$_CRKMigrateKeychainItemsToModernKeychainResultObject._modernPersistentIDsByLegacyPersistentID
+ _OBJC_IVAR_$_CRKRemovePersistentIDsFromLoginKeychainRequest._persistentIDs
+ _OBJC_METACLASS_$_CRKKeychainMigrationServiceProxy
+ _OBJC_METACLASS_$_CRKMigrateKeychainItemsToModernKeychainRequest
+ _OBJC_METACLASS_$_CRKMigrateKeychainItemsToModernKeychainResultObject
+ _OBJC_METACLASS_$_CRKPropertyListConverter
+ _OBJC_METACLASS_$_CRKRemovePersistentIDsFromLoginKeychainRequest
+ _SecCertificateCopyAttributeDictionary
+ _SecKeyCopyAttributes
+ _SecKeyCopyPublicKey
+ _SecKeyCreateRandomKey
+ _SecKeyGetAlgorithmId
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSError_$_CRKAdditions
+ __OBJC_$_CLASS_METHODS_CRKMigrateKeychainItemsToModernKeychainRequest
+ __OBJC_$_CLASS_METHODS_CRKMigrateKeychainItemsToModernKeychainResultObject
+ __OBJC_$_CLASS_METHODS_CRKPropertyListConverter
+ __OBJC_$_CLASS_METHODS_CRKRemovePersistentIDsFromLoginKeychainRequest
+ __OBJC_$_INSTANCE_METHODS_CRKKeychainMigrationServiceProxy
+ __OBJC_$_INSTANCE_METHODS_CRKMigrateKeychainItemsToModernKeychainRequest
+ __OBJC_$_INSTANCE_METHODS_CRKMigrateKeychainItemsToModernKeychainResultObject
+ __OBJC_$_INSTANCE_METHODS_CRKRemovePersistentIDsFromLoginKeychainRequest
+ __OBJC_$_INSTANCE_VARIABLES_CRKKeychainMigrationServiceProxy
+ __OBJC_$_INSTANCE_VARIABLES_CRKMigrateKeychainItemsToModernKeychainRequest
+ __OBJC_$_INSTANCE_VARIABLES_CRKMigrateKeychainItemsToModernKeychainResultObject
+ __OBJC_$_INSTANCE_VARIABLES_CRKRemovePersistentIDsFromLoginKeychainRequest
+ __OBJC_$_PROP_LIST_CRKKeychainMigrationServiceProxy
+ __OBJC_$_PROP_LIST_CRKMigrateKeychainItemsToModernKeychainRequest
+ __OBJC_$_PROP_LIST_CRKMigrateKeychainItemsToModernKeychainResultObject
+ __OBJC_$_PROP_LIST_CRKRemovePersistentIDsFromLoginKeychainRequest
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CRKKeychainMigrationServiceInterface
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CRKKeychainMigrationServiceInterface
+ __OBJC_CATEGORY_PROTOCOLS_$_NSError_$_CRKAdditions
+ __OBJC_CLASS_PROTOCOLS_$_CRKKeychainMigrationServiceProxy
+ __OBJC_CLASS_RO_$_CRKKeychainMigrationServiceProxy
+ __OBJC_CLASS_RO_$_CRKMigrateKeychainItemsToModernKeychainRequest
+ __OBJC_CLASS_RO_$_CRKMigrateKeychainItemsToModernKeychainResultObject
+ __OBJC_CLASS_RO_$_CRKPropertyListConverter
+ __OBJC_CLASS_RO_$_CRKRemovePersistentIDsFromLoginKeychainRequest
+ __OBJC_LABEL_PROTOCOL_$_CRKKeychainMigrationServiceInterface
+ __OBJC_METACLASS_RO_$_CRKKeychainMigrationServiceProxy
+ __OBJC_METACLASS_RO_$_CRKMigrateKeychainItemsToModernKeychainRequest
+ __OBJC_METACLASS_RO_$_CRKMigrateKeychainItemsToModernKeychainResultObject
+ __OBJC_METACLASS_RO_$_CRKPropertyListConverter
+ __OBJC_METACLASS_RO_$_CRKRemovePersistentIDsFromLoginKeychainRequest
+ __OBJC_PROTOCOL_$_CRKKeychainMigrationServiceInterface
+ __OBJC_PROTOCOL_REFERENCE_$_CRKKeychainMigrationServiceInterface
+ ___40-[CRKKeychainMigrationServiceProxy init]_block_invoke
+ ___50+[CRKPropertyListConverter propertyListSafeValue:]_block_invoke
+ ___50-[CRKConcreteKeychain removeItemWithPersistentID:]_block_invoke
+ ___69-[CRKKeychainMigrationServiceProxy performRemovalRequest:completion:]_block_invoke
+ ___70-[CRKKeychainMigrationServiceProxy _performRemovalRequest:completion:]_block_invoke
+ ___70-[CRKKeychainMigrationServiceProxy _performRemovalRequest:completion:]_block_invoke_2
+ ___70-[CRKKeychainMigrationServiceProxy _performRemovalRequest:completion:]_block_invoke_3
+ ___70-[CRKKeychainMigrationServiceProxy _performRemovalRequest:completion:]_block_invoke_4
+ ___71-[CRKKeychainMigrationServiceProxy performMigrationRequest:completion:]_block_invoke
+ ___72-[CRKKeychainMigrationServiceProxy _performMigrationRequest:completion:]_block_invoke
+ ___72-[CRKKeychainMigrationServiceProxy _performMigrationRequest:completion:]_block_invoke_2
+ ___72-[CRKKeychainMigrationServiceProxy _performMigrationRequest:completion:]_block_invoke_3
+ ___72-[CRKKeychainMigrationServiceProxy _performMigrationRequest:completion:]_block_invoke_4
+ ___block_descriptor_32_e18_B16?0"NSNumber"8l
+ ___block_descriptor_32_e25_v32?0"NSNumber"8Q16^B24l
+ ___block_descriptor_40_e8_32bs_e73_v24?0"CRKMigrateKeychainItemsToModernKeychainResultObject"8"NSError"16ls32l8
+ ___block_descriptor_48_e8_32s40bs_e73_v24?0"CRKMigrateKeychainItemsToModernKeychainResultObject"8"NSError"16ls32l8s40l8
+ _kSecAttrApplicationLabel
+ _kSecAttrKeyClassPublic
+ _kSecAttrPublicKeyHash
+ _kSecUseDataProtectionKeychain
- +[CRKASMCredentialStoreFactory makeCredentialStoreWithRole:keychainOverride:]
- -[CRKConcreteKeychain addItem:toAccessGroup:]
CStrings:
+ "B16@?0@\"NSNumber\"8"
+ "Encountered multiple errors when removing keychain item with persistent ID %@"
+ "Failed to add identity to keychain."
+ "KEYCHAIN: Added certificate \"%{private, mask.hash}@\" (pubKeyHash %{private, mask.hash}@) -> persistent ID %{public}@"
+ "KEYCHAIN: Added identity \"%{private, mask.hash}@\" (pubKeyHash %{private, mask.hash}@) -> persistent ID %{public}@"
+ "KEYCHAIN: Adding certificate %{private, mask.hash}@ to access group %{public}@"
+ "KEYCHAIN: Adding identity %{private, mask.hash}@ to access group %{public}@"
+ "KEYCHAIN: Adding private key to access group %{public}@"
+ "KEYCHAIN: Calling SecItemAdd with query: %{public}@"
+ "KEYCHAIN: Calling SecItemCopyMatching with query: %{public}@"
+ "KEYCHAIN: Calling SecItemDelete with query %{public}@"
+ "KEYCHAIN: Creating certificate with data: %{public}@"
+ "KEYCHAIN: Creating data protection key"
+ "KEYCHAIN: Creating identity with certificate %{private, mask.hash}@ and private key %{private, mask.hash}@"
+ "KEYCHAIN: Creating identity with configuration"
+ "KEYCHAIN: Creating legacy key"
+ "KEYCHAIN: Creating private key (%lu bytes)"
+ "KEYCHAIN: Removing item with persistent ID %{public}@"
+ "KEYCHAIN: Removing key with application label %{public}@, key class %{public}@"
+ "KEYCHAIN: Retieving certificate with persistent ID %{public}@"
+ "KEYCHAIN: Retieving identity with persistent ID %{public}@"
+ "KEYCHAIN: Retieving private key with persistent ID %{public}@"
+ "KEYCHAIN: Retrieved certificate \"%{private, mask.hash}@\" (pubKeyHash %{private, mask.hash}@) for persistent ID %{public}@"
+ "KEYCHAIN: Retrieved identity \"%{private, mask.hash}@\" (pubKeyHash %{private, mask.hash}@) for persistent ID %{public}@"
+ "KEYCHAIN: SecIdentityCopyCertificate failed with status %{public}@"
+ "KEYCHAIN: SecIdentityCopyCertificate succeeded"
+ "KEYCHAIN: SecIdentityCopyPrivateKey failed with status %{public}@"
+ "KEYCHAIN: SecIdentityCopyPrivateKey succeeded"
+ "KEYCHAIN: SecItemDelete (certificate) failed: %{public}@"
+ "KEYCHAIN: SecItemDelete (key, class %{public}@) failed: %{public}@"
+ "KEYCHAIN: SecItemDelete (password, service %{public}@) status: %d"
+ "Keychain removal error %ld: %{public}@."
+ "No modern persistent ID found for a migrated credential; dropping its manifest entry"
+ "certificatePersistentIDs"
+ "code"
+ "com.apple.ClassroomKit.KeychainMigrationService"
+ "createsDataProtectionKey"
+ "domain"
+ "identityPersistentIDs"
+ "itemName"
+ "lastStudentError"
+ "migratesInstructorASMCredentialStore"
+ "modernPersistentIDsByLegacyPersistentID"
+ "persistentIDs"
+ "v24@?0@\"CRKMigrateKeychainItemsToModernKeychainResultObject\"8@\"NSError\"16"
+ "v32@?0@\"NSNumber\"8Q16^B24"
- "Could not remove keychain item with persistentID %@. Error (ignored): %{public}@."
```
