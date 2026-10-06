## AppAttestInternal

> `/System/Library/PrivateFrameworks/AppAttestInternal.framework/AppAttestInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x69a70` | `0x6a460` | **`+0x9f0`** |
| `__TEXT.__unwind_info` | `0x1080` | `0x1078` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-151.0.0.0.0
+153.0.0.0.0
Functions:
~ ___45+[FeatureFlagsManager isModernizationEnabled]_block_invoke : 228 -> 240
~ ___35+[FeatureFlagsManager isMacEnabled]_block_invoke : 228 -> 240
~ ___52+[FeatureFlagsManager isExtensionAttestationEnabled]_block_invoke : 228 -> 240
~ ___46+[AppAttestTaskCreator createForDefaultAttest]_block_invoke : 260 -> 272
~ ___54+[AppAttestTaskCreator createForWebAuthAttestKeychain]_block_invoke : 552 -> 576
~ ___53+[AppAttestTaskCreator createForDeviceAttestKeychain]_block_invoke : 552 -> 576
~ -[PinnedUrlDelegate URLSession:didReceiveChallenge:completionHandler:] : 864 -> 888
~ ___sendServerRequestWithError_block_invoke : 860 -> 872
~ _AppAttest_WebAuthentication_AttestKey : 1080 -> 1092
~ ___AppAttest_WebAuthentication_AttestKey_block_invoke : 1404 -> 1424
~ _resolveAppUUIDKeychain : 5188 -> 5428
~ _saveAppUUIDKeychain : 828 -> 852
~ _encodeKeyToCOSE : 1364 -> 1400
~ _fetchPublicKey : 1172 -> 1220
~ _generateCOSEForKeySize : 1008 -> 1032
~ _generateEnvironmentByAppSigning : 1804 -> 1888
~ _resolveAppAttestApplicationIdentifiersForApplicationRecord : 924 -> 948
~ _extractApplicationIdentifiers : 2140 -> 2164
~ _generateAttestationObject : 1316 -> 1352
~ _generateAssertionObject : 756 -> 768
~ _saveCredentialKeychain : 656 -> 680
~ _loadCredentialKeychain : 708 -> 732
~ _deleteCredentialKeychainWithLabel : 524 -> 548
~ _getAllCredentialKeychainLabelsWithShouldExit : 532 -> 544
~ _saveAssertionCounterKeychain : 752 -> 776
~ _loadAssertionCounterKeychain : 788 -> 812
~ _deleteAssertionCounterKeychainWithLabel : 524 -> 548
~ _getAllAssertionCounterKeychainLabelsWithShouldExit : 532 -> 544
~ _getApplicationIdentifierHashFromKeychainLabel : 356 -> 368
~ _getAllAppUUIDKeychainLabelsWithShouldExit : 1812 -> 1876
~ _listKeychainItems : 1056 -> 1048
~ _removeAllKeychainItemsForMissingAppsWithShouldExit : 1064 -> 1116
~ _listOfInstalledAppHashesWithShouldExit : 896 -> 952
~ _listOfAllowlistedDaemonHashesWithShouldExit : 996 -> 1048
~ _listOfInstalledExtensionHashesWithShouldExit : 880 -> 916
~ ___removeAllKeychainItemsForMissingAppsWithShouldExit_block_invoke : 1940 -> 2048
~ ___removeAllKeychainItemsForMissingAppsWithShouldExit_block_invoke.130 : 804 -> 840
~ ___removeAllKeychainItemsForMissingAppsWithShouldExit_block_invoke.133 : 804 -> 840
~ -[AppAttestEligibilityManager isEligibleClientFor:] : 816 -> 864
~ -[AppAttestEligibilityManager isEligibleApplicationFor:] : 512 -> 536
~ -[AppAttestEligibilityManager isEligibleApplicationExtensionFor:] : 2484 -> 2580
~ -[AppAttestEligibilityManager isEligibleDaemonFor:] : 1344 -> 1416
~ -[AppAttestEligibilityManager isEligibleForPrivService:] : 660 -> 696
~ -[AppAttestEligibilityManager containsValidEntitlements] : 1320 -> 1368
~ -[AppAttestEligibilityManager fetchEntitlementForAuditToken:withKey:] : 1032 -> 1056
~ -[AppAttestEligibilityManager meetsSecurityControlsForAuditToken:] : 1668 -> 1752
~ -[AppAttestEligibilityManager fetchBundleRecordFor:] : 732 -> 756
~ _AppAttest_DeviceAttestation_AttestKey : 3756 -> 3852
~ ___AppAttest_DeviceAttestation_AttestKey_block_invoke : 1996 -> 2052
~ _fetchAlwaysAccessibleKeysEntitlement : 680 -> 692
~ _fetchOptInEntitlements : 984 -> 1020
~ _fetchCdHash : 424 -> 444
~ _AppAttest_AppAttestation_IsEligibleApplication : 320 -> 332
~ _AppAttest_AppAttestation_IsSupportedAndEligibleApplication : 460 -> 484
~ _CreateKey : 2120 -> 2144
~ _AttestKey : 3812 -> 3932
~ _AppAttest_AppAttestation_Assert : 768 -> 780
~ _Assert : 2552 -> 2600
~ _Sign : 2672 -> 2756
~ _GetKey : 1892 -> 1952
~ ___AttestKey_block_invoke : 2936 -> 3032
~ sub_225f6f940 -> sub_226e812f4 : 380 -> 368
~ sub_225f70714 -> sub_226e820bc : 44 -> 32
~ sub_225f7093c -> sub_226e822d8 : 44 -> 32
~ sub_225f71140 -> sub_226e82ad0 : 172 -> 176
~ sub_225f71a08 -> sub_226e8339c : 312 -> 316
~ sub_225f71c88 -> sub_226e83620 : 476 -> 484
~ sub_225f71e64 -> sub_226e83804 : 308 -> 316
~ sub_225f71f98 -> sub_226e83940 : 400 -> 416
~ sub_225f72128 -> sub_226e83ae0 : 348 -> 356
~ sub_225f723d8 -> sub_226e83d98 : 72 -> 76
~ sub_225f729ac -> sub_226e84370 : 476 -> 480
~ sub_225f72d20 -> sub_226e846e8 : 236 -> 256
~ sub_225f79d50 -> sub_226e8b72c : 344 -> 340
~ sub_225f7bdfc -> sub_226e8d7d4 : 1696 -> 1684
~ sub_225f7c830 -> sub_226e8e1fc : 596 -> 604
~ sub_225f806dc -> sub_226e920b0 : 280 -> 276
~ sub_225f80f10 -> sub_226e928e0 : 244 -> 268
~ sub_225f81004 -> sub_226e929ec : 492 -> 500
~ sub_225f86030 -> sub_226e97a20 : 256 -> 276
~ sub_225fa5c3c -> sub_226eb7640 : 380 -> 376
~ sub_225fa5db8 -> sub_226eb77b8 : 236 -> 256
~ sub_225fa9fd4 -> sub_226ebb9e8 : 244 -> 252
~ sub_225faeab0 -> sub_226ec04cc : 96 -> 92
~ sub_225fb35b8 -> sub_226ec4fd0 : 412 -> 388
~ sub_225fb6fb4 -> sub_226ec89b4 : 1044 -> 1036
~ sub_225fbcb5c -> sub_226ece554 : 1400 -> 1392
CStrings:
+ "AppAttest (%@-153) - %@"
- "AppAttest (%@-151) - %@"
```
