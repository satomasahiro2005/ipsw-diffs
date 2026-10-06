## MDMClientLibrary

> `/System/Library/PrivateFrameworks/MDMClientLibrary.framework/MDMClientLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methlist` | `0x1da4` | `0x1db4` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x13a8` | `0x13b0` | **`+0x8`** |
| `__TEXT.__text` | `0x1e714` | `0x1e710` | **`-0x4`** |

### Other Changes

```diff

-105.0.0.0.0
+107.0.0.0.0

-  Functions: 684
-  Symbols:   1667
+  Functions: 685
+  Symbols:   1668
Symbols:
+ +[MDMCloudConfiguration isTeslaEnrolledWithCloudConfig:]
Functions:
~ +[MDMManagedMediaReader attributesByAppIDExcludeDDMApps:] : 560 -> 556
~ +[MDMManagedMediaReader _metadataByBundleIDExcludeDDMApps:] : 684 -> 680
~ -[MDMBearerTokenAuthenticator authTokensWithCallbackURL:authParams:completionHandler:] : 752 -> 748
+ +[MDMCloudConfiguration isTeslaEnrolledWithCloudConfig:]
~ +[MDMConfiguration hasIncompleteMigration] : 340 -> 344
~ +[MDMESSODetails essoDetailsWithJSONDictionary:] : 1568 -> 1564
~ +[MDMManagedMediaReader managedBooks] : 656 -> 648
~ +[MDMManagedMediaReader managedAppIDsWithFlags:excludeDDMApps:] : 480 -> 476
~ -[MDMOAuth2Authenticator authTokensWithCallbackURL:authParams:completionHandler:] : 924 -> 920
~ +[MDMOptionsUtilities validatedMDMOptionsFromOptionsDictionary:] : 440 -> 436
~ +[MDMProvisioningProfileTrust _signerIdentitiesFromProvisioningProfile:] : 628 -> 624
~ ___71+[MDMProvisioningProfileTrust _enumerateProvisioningProfilesWithBlock:]_block_invoke : 428 -> 424
~ -[MDMProvisioningProfileTrust uiTrustAndVerifyProvisioningProfiles:developer:completion:] : 592 -> 588
~ ___87-[MDMProvisioningProfileTrust _uiSetTrustForProvisioningProfiles:developer:completion:]_block_invoke : 692 -> 688
~ -[MDMProvisioningProfileTrust updateTrustedCodeSigningIdentities:validateBundleIDs:validateManagedApps:] : 2468 -> 2444
~ ___104-[MDMProvisioningProfileTrust updateTrustedCodeSigningIdentities:validateBundleIDs:validateManagedApps:]_block_invoke_2 : 208 -> 204
~ +[MDMProvisioningProfileTrust _appSignerIdentitiesFromBundleIDs:] : 356 -> 352
```
