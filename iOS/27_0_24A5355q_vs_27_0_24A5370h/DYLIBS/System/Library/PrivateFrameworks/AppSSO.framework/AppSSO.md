## AppSSO

> `/System/Library/PrivateFrameworks/AppSSO.framework/AppSSO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2bb40` | `0x2baac` | **`-0x94`** |
| `__TEXT.__const` | `0x150` | `0x158` | **`+0x8`** |

### Other Changes

```diff

-635.0.0.0.0
+643.0.12.0.0
Functions:
~ -[SOConfigurationHost configurationForClientWithError:] : 540 -> 536
~ -[SODDMConfigurationHost allDeclarationKeysWithError:] : 764 -> 760
~ ___30-[SOExtension _setupExtension]_block_invoke_2 : 660 -> 656
~ -[SOExtension _otherVersionError:] : 604 -> 600
~ -[SOExtension authenticationMethods] : 500 -> 496
~ -[SOExtension removeExpiredEntriesFromCache:] : 452 -> 448
~ -[SOExtension checkAssociatedDomainsWithCache:] : 1820 -> 1816
~ -[SOExtension viewServiceDidTerminateWithError:] : 504 -> 500
~ -[SOExtensionManager unloadExtensions] : 416 -> 412
~ -[SOExtensionManager loadedExtensionWithBundleIdentifier:] : 544 -> 540
~ ___48-[SOExtensionManager _doBeginMatchingExtensions]_block_invoke_2 : 580 -> 576
~ -[SORequestQueue removeAllRequestsWithBlock:] : 740 -> 736
~ -[SORequestQueue removeRequestWithIdentifier:block:] : 808 -> 804
~ -[SOAuthorizationRequest completeWithHTTPAuthorizationHeaders:] : 700 -> 696
~ -[SOAuthorizationRequest completeWithAuthorizationResult:] : 840 -> 836
~ -[SOAuthorizationRequest _createSecKeyProxiesForSecKeys:error:] : 672 -> 668
~ -[SOConfigurationHost removedProfileForExtensionBundleIdentifier:] : 624 -> 620
~ -[SOConfigurationHost profilesWithExtensionBundleIdentifier:] : 556 -> 552
~ -[SOConfigurationHost validatedProfileForPlatformSSO] : 500 -> 496
~ -[SOConfigurationHost platformSSOProfile] : 824 -> 820
~ -[SOConfigurationHost findPlatformSSOProfile:] : 408 -> 404
~ -[SOConfigurationHost findProfileForExtension:profiles:] : 448 -> 444
~ -[SOConfigurationHost _removeNotSupportedUserProfiles:] : 584 -> 580
~ -[SOConfigurationHost hasAnyMDMProfileForExtension:] : 856 -> 852
~ -[SOConfigurationHost systemMDMProfileForExtension:] : 872 -> 868
~ +[SOConfigurationHost _loadProfilesFromArray:] : 748 -> 744
~ -[SOConfigurationHost _reloadConfigWithReason:] : 2356 -> 2348
~ -[SOConfigurationHost _mergeDDMProfiles:mdmProfiles:] : 888 -> 880
~ -[SOConfigurationHost _checkExtensionsExistenceForProfiles:] : 652 -> 648
~ -[SOConfigurationHost _checkAssociatedDomainForProfiles:] : 2496 -> 2488
~ -[SOConfigurationHost _extensionsLoaded:] : 1380 -> 1376
~ +[SOConfigurationHost maskRegistrationTokenInProfileList:] : 496 -> 492
~ +[SOAnalytics analyticsForMDMProfiles:reason:] : 384 -> 380
~ -[SOExtensionFinder _soExtensionsForExtensions:] : 332 -> 328
```
