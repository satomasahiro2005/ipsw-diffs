## RemoteManagementModel

> `/System/Library/PrivateFrameworks/RemoteManagementModel.framework/RemoteManagementModel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55ed0` | `0x55e38` | **`-0x98`** |

### Other Changes

```diff

-621.0.0.502.1
+624.0.3.0.0
Functions:
~ ___79-[RMModelACMECredentialDeclaration loadFromDictionary:serializationType:error:]_block_invoke : 472 -> 468
~ +[RMModelClasses ensureClassForDeclarations:] : 572 -> 568
~ +[RMModelClasses hideDeclarationsWithTypes:] : 324 -> 320
~ +[RMModelClasses ensureClassForStatusItems:] : 572 -> 568
~ -[RMModelConfigurationBase assetReferencesFromKeyPaths:payloadObject:] : 512 -> 508
~ -[RMModelConfigurationBase _walkObject:keyPath:assetReference:result:processedIdentifiers:] : 1480 -> 1464
~ +[RMModelConfigurationBase combineMergeDictionary:other:] : 500 -> 496
~ -[RMModelConfigurationDynamic _enumerateDynamicSettings:usingBlock:] : 484 -> 480
~ +[RMModelConfigurationSchema loadDynamicSchemaFromFiles:] : 368 -> 364
~ +[RMModelConfigurationSchema _loadDynamicSchemaFromDirectory:into:] : 440 -> 436
~ -[RMModelConfigurationSchema _mergeSettings:withSettings:] : 900 -> 888
~ -[RMModelConfigurationSchema _parseAssetReferences:] : 488 -> 484
~ -[RMModelConfigurationSchema _parseDynamicSettings:] : 504 -> 500
~ -[NSData(RemoteManagementModel) RMModelHexString] : 268 -> 264
~ +[RMModelDiskManagementSettingsDeclaration combineConfigurations:] : 288 -> 284
~ -[RMModelManagementPropertiesDeclaration loadPayloadFromDictionary:serializationType:error:] : 468 -> 464
~ -[RMModelManagementPropertiesDeclaration serializePayloadWithType:] : 368 -> 364
~ +[RMModelManagementStatusSubscriptionsDeclaration combineConfigurations:] : 288 -> 284
~ +[RMModelPasscodeSettingsDeclaration combineConfigurations:] : 288 -> 284
~ -[RMModelPayloadBase mergeUnknownKeysFrom:parentKey:] : 488 -> 484
~ -[RMModelPayloadBase loadArrayFromDictionary:usingKey:forKeyPath:validator:isRequired:defaultValue:error:] : 772 -> 768
~ -[RMModelPayloadBase loadArrayFromDictionary:usingKey:forKeyPath:classType:nested:isRequired:defaultValue:serializationType:error:] : 1064 -> 1060
~ -[RMModelPayloadBase loadObjectsFromDictionary:forKeyPath:classType:serializationType:error:] : 596 -> 592
~ -[RMModelPayloadBase serializeArrayIntoDictionary:usingKey:value:itemSerializer:isRequired:defaultValue:] : 488 -> 484
~ -[RMModelPayloadBase serializeObjectsIntoDictionary:value:classType:serializationType:] : 592 -> 580
~ +[RMModelPayloadUtilities _walkObject:keyPath:fullKeyPath:] : 760 -> 756
~ ___79-[RMModelSCEPCredentialDeclaration loadFromDictionary:serializationType:error:]_block_invoke : 472 -> 468
~ +[RMModelSchemaParser loadSupportedOSFromDictionary:] : 1036 -> 1044
~ +[RMModelSchemaParser _parseEnrollmentTypes:] : 536 -> 532
~ +[RMModelSchemaParser _parseScopes:] : 536 -> 532
~ +[RMModelSchemaParser _parseVariants:] : 548 -> 544
~ +[RMModelSoftwareUpdateSettingsDeclaration combineConfigurations:] : 288 -> 284
~ +[RMModelStatusSchema loadDynamicSchemaFromFiles:] : 340 -> 336
~ +[RMModelStatusSchema _loadDynamicSchemaFromDirectory:into:] : 440 -> 436
```
