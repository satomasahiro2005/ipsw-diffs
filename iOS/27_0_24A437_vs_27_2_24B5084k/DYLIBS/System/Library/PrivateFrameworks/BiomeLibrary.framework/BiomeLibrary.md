## BiomeLibrary

> `/System/Library/PrivateFrameworks/BiomeLibrary.framework/BiomeLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7584dc` | `0x75a8a4` | **`+0x23c8`** |
| `__AUTH_CONST.__cfstring` | `0x4b4c0` | `0x4b940` | **`+0x480`** |
| `__TEXT.__cstring` | `0x4e9fa` | `0x4ed07` | **`+0x30d`** |
| `__DATA_CONST.__const` | `0x1ebc8` | `0x1ee88` | **`+0x2c0`** |
| `__AUTH_CONST.__objc_const` | `0xa2f50` | `0xa30a0` | **`+0x150`** |
| `__TEXT.__const` | `0x47d8` | `0x4868` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x50564` | `0x505d4` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x129d8` | `0x12a38` | **`+0x60`** |
| `__AUTH.__objc_data` | `0xb210` | `0xb260` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0xb990` | `0xb940` | **`-0x50`** |
| `__AUTH_CONST.__const` | `0x9b38` | `0x9b78` | **`+0x40`** |
| `__DATA_CONST.__objc_arraydata` | `0xb278` | `0xb2b0` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0xf678` | `0xf6a0` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x8220` | `0x823c` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x3a0` | `0x3b0` | **`+0x10`** |

### Other Changes

```diff

-436.6.0.0.0
+441.22.0.1.0

-  Functions: 28727
-  Symbols:   53071
-  CStrings:  9772
+  Functions: 28751
+  Symbols:   53117
+  CStrings:  9808
Symbols:
+ +[BMSafariSearchEngine columns]
+ +[BMSafariSearchEngine eventWithData:dataVersion:]
+ +[BMSafariSearchEngine latestDataVersion]
+ +[BMSafariSearchEngine protoFields]
+ +[BMSafariSearchEngine validKeyPaths]
+ +[_BMSafariLibraryNode SearchEngine]
+ +[_BMSafariLibraryNode configurationForSearchEngine]
+ +[_BMSafariLibraryNode storeConfigurationForSearchEngine]
+ +[_BMSafariLibraryNode syncPolicyForSearchEngine]
+ -[BMAppInFocus initWithLaunchReason:type:starting:absoluteTimestamp:bundleID:parentBundleID:extensionHostID:shortVersionString:exactVersionString:dyldPlatform:isNativeArchitecture:displayType:transitionReason:]
+ -[BMAppInFocus transitionReason]
+ -[BMAppInFocus(Deprecation) initWithLaunchReason:type:starting:absoluteTimestamp:bundleID:parentBundleID:extensionHostID:shortVersionString:exactVersionString:dyldPlatform:isNativeArchitecture:displayType:]
+ -[BMCarKeyProvisioningData initWithOwnerPairingUrl:carBrand:alreadyProvisioned:carModel:carIdentifier:pairingCode:userIdentifier:provisioningCodeExpiration:spotlightUniqueIdentifier:spotlightDomainIdentifier:spotlightBundleIdentifier:dateSent:cccManufacturer:cccBrand:supportedTransports:sourceLanguage:messageIdentifier:]
+ -[BMCarKeyProvisioningData messageIdentifier]
+ -[BMCarKeyProvisioningData(Deprecation) initWithOwnerPairingUrl:carBrand:alreadyProvisioned:carModel:carIdentifier:pairingCode:userIdentifier:provisioningCodeExpiration:spotlightUniqueIdentifier:spotlightDomainIdentifier:spotlightBundleIdentifier:dateSent:cccManufacturer:cccBrand:supportedTransports:sourceLanguage:]
+ -[BMGeneratedImageFailureReason blockingSafetyModel]
+ -[BMGeneratedImageFailureReason blocklistCategory]
+ -[BMGeneratedImageFailureReason failureReason]
+ -[BMGeneratedImageFailureReason initWithTimestamp:identifier:userInterfaceLanguage:userSetRegionFormat:reason:feature:userPrompt:rewrittenPrompt:safetyCategory:blocklistCategory:blockingSafetyModel:failureReason:]
+ -[BMGeneratedImageFailureReason rewrittenPrompt]
+ -[BMGeneratedImageFailureReason safetyCategory]
+ -[BMGeneratedImageFailureReason userPrompt]
+ -[BMGeneratedImageFailureReason(Deprecation) initWithTimestamp:identifier:userInterfaceLanguage:userSetRegionFormat:reason:feature:]
+ -[BMSafariSearchEngine .cxx_destruct]
+ -[BMSafariSearchEngine dataVersion]
+ -[BMSafariSearchEngine description]
+ -[BMSafariSearchEngine initByReadFrom:]
+ -[BMSafariSearchEngine initWithJSONDictionary:error:]
+ -[BMSafariSearchEngine initWithSearchEngineIdentifier:]
+ -[BMSafariSearchEngine isEqual:]
+ -[BMSafariSearchEngine jsonDictionary]
+ -[BMSafariSearchEngine searchEngineIdentifier]
+ -[BMSafariSearchEngine serialize]
+ -[BMSafariSearchEngine writeTo:]
+ _BMAppInFocusTransitionReasonColumn
+ _BMCarKeyProvisioningDataMessageIdentifierColumn
+ _BMGeneratedImageFailureReasonBlockingSafetyModelAsString
+ _BMGeneratedImageFailureReasonBlockingSafetyModelColumn
+ _BMGeneratedImageFailureReasonBlockingSafetyModelDecode
+ _BMGeneratedImageFailureReasonBlockingSafetyModelFromString
+ _BMGeneratedImageFailureReasonBlockingSafetyModelFromString.sortedStrings
+ _BMGeneratedImageFailureReasonBlocklistCategoryAsString
+ _BMGeneratedImageFailureReasonBlocklistCategoryColumn
+ _BMGeneratedImageFailureReasonBlocklistCategoryDecode
+ _BMGeneratedImageFailureReasonBlocklistCategoryFromString
+ _BMGeneratedImageFailureReasonBlocklistCategoryFromString.sortedEnums
+ _BMGeneratedImageFailureReasonBlocklistCategoryFromString.sortedStrings
+ _BMGeneratedImageFailureReasonFailureReasonAsString
+ _BMGeneratedImageFailureReasonFailureReasonColumn
+ _BMGeneratedImageFailureReasonFailureReasonDecode
+ _BMGeneratedImageFailureReasonFailureReasonFromString
+ _BMGeneratedImageFailureReasonFailureReasonFromString.sortedEnums
+ _BMGeneratedImageFailureReasonFailureReasonFromString.sortedStrings
+ _BMGeneratedImageFailureReasonRewrittenPromptColumn
+ _BMGeneratedImageFailureReasonSafetyCategoryAsString
+ _BMGeneratedImageFailureReasonSafetyCategoryColumn
+ _BMGeneratedImageFailureReasonSafetyCategoryDecode
+ _BMGeneratedImageFailureReasonSafetyCategoryFromString
+ _BMGeneratedImageFailureReasonSafetyCategoryFromString.sortedEnums
+ _BMGeneratedImageFailureReasonSafetyCategoryFromString.sortedStrings
+ _BMGeneratedImageFailureReasonUserPromptColumn
+ _BMSafariSearchEngineIdentifier
+ _BMSafariSearchEngineSearchEngineIdentifierColumn
+ _NSSelectorFromString
+ _OBJC_CLASS_$_BMSafariSearchEngine
+ _OBJC_IVAR_$_BMAppInFocus._transitionReason
+ _OBJC_IVAR_$_BMCarKeyProvisioningData._messageIdentifier
+ _OBJC_IVAR_$_BMGeneratedImageFailureReason._blockingSafetyModel
+ _OBJC_IVAR_$_BMGeneratedImageFailureReason._blocklistCategory
+ _OBJC_IVAR_$_BMGeneratedImageFailureReason._failureReason
+ _OBJC_IVAR_$_BMGeneratedImageFailureReason._rewrittenPrompt
+ _OBJC_IVAR_$_BMGeneratedImageFailureReason._safetyCategory
+ _OBJC_IVAR_$_BMGeneratedImageFailureReason._userPrompt
+ _OBJC_IVAR_$_BMSafariSearchEngine._dataVersion
+ _OBJC_IVAR_$_BMSafariSearchEngine._searchEngineIdentifier
+ _OBJC_METACLASS_$_BMSafariSearchEngine
+ __OBJC_$_CLASS_METHODS_BMSafariSearchEngine
+ __OBJC_$_CLASS_PROP_LIST_BMSafariSearchEngine
+ __OBJC_$_INSTANCE_METHODS_BMGeneratedImageFailureReason(Deprecation)
+ __OBJC_$_INSTANCE_METHODS_BMSafariSearchEngine
+ __OBJC_$_INSTANCE_VARIABLES_BMSafariSearchEngine
+ __OBJC_$_PROP_LIST_BMSafariSearchEngine
+ __OBJC_CLASS_PROTOCOLS_$_BMSafariSearchEngine
+ __OBJC_CLASS_RO_$_BMSafariSearchEngine
+ __OBJC_METACLASS_RO_$_BMSafariSearchEngine
+ ___BMGeneratedImageFailureReasonBlockingSafetyModelFromString_block_invoke
+ ___BMGeneratedImageFailureReasonBlocklistCategoryFromString_block_invoke
+ ___BMGeneratedImageFailureReasonFailureReasonFromString_block_invoke
+ ___BMGeneratedImageFailureReasonSafetyCategoryFromString_block_invoke
+ _objc_opt_respondsToSelector
- +[BMSiriHomeHistory columns]
- +[BMSiriHomeHistory eventWithData:dataVersion:]
- +[BMSiriHomeHistory latestDataVersion]
- +[BMSiriHomeHistory protoFields]
- +[BMSiriHomeHistory validKeyPaths]
- +[_BMSiriRemembersLibraryNode HomeHistory]
- +[_BMSiriRemembersLibraryNode configurationForHomeHistory]
- +[_BMSiriRemembersLibraryNode storeConfigurationForHomeHistory]
- +[_BMSiriRemembersLibraryNode syncPolicyForHomeHistory]
- -[BMAppInFocus initWithLaunchReason:type:starting:absoluteTimestamp:bundleID:parentBundleID:extensionHostID:shortVersionString:exactVersionString:dyldPlatform:isNativeArchitecture:displayType:]
- -[BMCarKeyProvisioningData initWithOwnerPairingUrl:carBrand:alreadyProvisioned:carModel:carIdentifier:pairingCode:userIdentifier:provisioningCodeExpiration:spotlightUniqueIdentifier:spotlightDomainIdentifier:spotlightBundleIdentifier:dateSent:cccManufacturer:cccBrand:supportedTransports:sourceLanguage:]
- -[BMGeneratedImageFailureReason initWithTimestamp:identifier:userInterfaceLanguage:userSetRegionFormat:reason:feature:]
- -[BMSiriHomeHistory .cxx_destruct]
- -[BMSiriHomeHistory _entitiesJSONArray]
- -[BMSiriHomeHistory dataVersion]
- -[BMSiriHomeHistory description]
- -[BMSiriHomeHistory entities]
- -[BMSiriHomeHistory initByReadFrom:]
- -[BMSiriHomeHistory initWithInteraction:entities:]
- -[BMSiriHomeHistory initWithJSONDictionary:error:]
- -[BMSiriHomeHistory interaction]
- -[BMSiriHomeHistory isEqual:]
- -[BMSiriHomeHistory jsonDictionary]
- -[BMSiriHomeHistory serialize]
- -[BMSiriHomeHistory writeTo:]
- _BMSiriHomeHistoryEntitiesColumn
- _BMSiriHomeHistoryInteractionColumn
- _BMSiriRemembersHomeHistoryIdentifier
- _OBJC_CLASS_$_BMSiriHomeHistory
- _OBJC_IVAR_$_BMSiriHomeHistory._dataVersion
- _OBJC_IVAR_$_BMSiriHomeHistory._entities
- _OBJC_IVAR_$_BMSiriHomeHistory._interaction
- _OBJC_METACLASS_$_BMSiriHomeHistory
- __OBJC_$_CLASS_METHODS_BMSiriHomeHistory
- __OBJC_$_CLASS_PROP_LIST_BMSiriHomeHistory
- __OBJC_$_INSTANCE_METHODS_BMGeneratedImageFailureReason
- __OBJC_$_INSTANCE_METHODS_BMSiriHomeHistory
- __OBJC_$_INSTANCE_VARIABLES_BMSiriHomeHistory
- __OBJC_$_PROP_LIST_BMSiriHomeHistory
- __OBJC_CLASS_PROTOCOLS_$_BMSiriHomeHistory
- __OBJC_CLASS_RO_$_BMSiriHomeHistory
- __OBJC_METACLASS_RO_$_BMSiriHomeHistory
- ___28+[BMSiriHomeHistory columns]_block_invoke
- ___28+[BMSiriHomeHistory columns]_block_invoke_2
CStrings:
+ "!D"
+ "AppleProducts"
+ "BMAppInFocus with launchReason: %@, type: %@, starting: %@, absoluteTimestamp: %@, bundleID: %@, parentBundleID: %@, extensionHostID: %@, shortVersionString: %@, exactVersionString: %@, dyldPlatform: %@, isNativeArchitecture: %@, displayType: %@, transitionReason: %@"
+ "BMCarKeyProvisioningData with ownerPairingUrl: %@, carBrand: %@, alreadyProvisioned: %@, carModel: %@, carIdentifier: %@, pairingCode: %@, userIdentifier: %@, provisioningCodeExpiration: %@, spotlightUniqueIdentifier: %@, spotlightDomainIdentifier: %@, spotlightBundleIdentifier: %@, dateSent: %@, cccManufacturer: %@, cccBrand: %@, supportedTransports: %@, sourceLanguage: %@, messageIdentifier: %@"
+ "BMGeneratedImageFailureReason with timestamp: %@, identifier: %@, userInterfaceLanguage: %@, userSetRegionFormat: %@, reason: %@, feature: %@, userPrompt: %@, rewrittenPrompt: %@, safetyCategory: %@, blocklistCategory: %@, blockingSafetyModel: %@, failureReason: %@"
+ "BMSafariSearchEngine with searchEngineIdentifier: %@"
+ "CustomWords"
+ "Desecration"
+ "Drugs"
+ "E701EAE3-5E66-458A-84C1-A611E4B3C2E3"
+ "ErrorUnableToSignInWithUserName"
+ "ExternalGeneratorNetworkFailure"
+ "ExternalGeneratorRateLimited"
+ "Harassment"
+ "Hate"
+ "IdentityEditing"
+ "MapsAndFlags"
+ "Minor"
+ "ModelsDownloading"
+ "MultimodalGuardrail"
+ "NOT ALL {bundleID, parentBundleID, extensionHostID} IN $installed"
+ "Offensive"
+ "PCCNoNodesAvailable"
+ "Photorealism"
+ "PixelGuardrail"
+ "PublicFigure"
+ "Racy"
+ "Safari.SearchEngine"
+ "SearchEngine"
+ "SelfHarm"
+ "Suggestive"
+ "Terrorism"
+ "TextGuardrail"
+ "Toxic"
+ "ViolenceAndGore"
+ "blockingSafetyModel"
+ "blocklistCategory"
+ "recoversFromFutureDatedEvents"
+ "rewrittenPrompt"
+ "safetyCategory"
+ "searchEngineIdentifier"
+ "setRecoversFromFutureDatedEvents:"
+ "transitionReason"
+ "userPrompt"
- "!\""
- "2A547182-AF14-4DCE-BF23-C42E38DBEC9B"
- "BMAppInFocus with launchReason: %@, type: %@, starting: %@, absoluteTimestamp: %@, bundleID: %@, parentBundleID: %@, extensionHostID: %@, shortVersionString: %@, exactVersionString: %@, dyldPlatform: %@, isNativeArchitecture: %@, displayType: %@"
- "BMCarKeyProvisioningData with ownerPairingUrl: %@, carBrand: %@, alreadyProvisioned: %@, carModel: %@, carIdentifier: %@, pairingCode: %@, userIdentifier: %@, provisioningCodeExpiration: %@, spotlightUniqueIdentifier: %@, spotlightDomainIdentifier: %@, spotlightBundleIdentifier: %@, dateSent: %@, cccManufacturer: %@, cccBrand: %@, supportedTransports: %@, sourceLanguage: %@"
- "BMGeneratedImageFailureReason with timestamp: %@, identifier: %@, userInterfaceLanguage: %@, userSetRegionFormat: %@, reason: %@, feature: %@"
- "BMSiriHomeHistory with interaction: %@, entities: %@"
- "HomeHistory"
- "Siri.Remembers.HomeHistory"
```
