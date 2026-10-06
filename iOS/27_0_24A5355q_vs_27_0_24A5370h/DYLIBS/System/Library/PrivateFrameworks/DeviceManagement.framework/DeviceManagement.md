## DeviceManagement

> `/System/Library/PrivateFrameworks/DeviceManagement.framework/DeviceManagement`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x392cc` | `0x39260` | **`-0x6c`** |

### Other Changes

```diff

-258.0.0.0.0
+259.0.0.0.0
Functions:
~ ___79-[DMFPolicyMonitor requestCommunicationPoliciesForBundleIdentifiers:withError:]_block_invoke.134 : 252 -> 248
~ ___56-[DMFEmergencyModeMonitor emergencyModeStatusWithError:]_block_invoke.65 : 408 -> 404
~ -[DMFBatchRequestOperation activityTransactionOperationDidStart:] : 444 -> 440
~ -[DMFCommunicationPolicyMonitor init] : 444 -> 440
~ -[DMFEffectivePolicy policyForIdentifier:excludableIdentifiers:] : 648 -> 644
~ -[DMFEffectivePolicy hasRestrictivePolicies] : 312 -> 308
~ +[DMFPrioritizedPolicy prioritizedPoliciesForAppPolicy:appCategoryPolicy:bundleIdentifiers:categoryPolicy:categoryIdentifiers:webPolicy:webCategoryPolicy:webDomains:] : 1528 -> 1508
~ -[DMFFetchApplicationsResultObject description] : 416 -> 412
~ -[DMFFetchAppsResultObject description] : 376 -> 372
~ -[DMFFetchCertificatesResultObject description] : 400 -> 396
~ -[DMFFetchManagedBooksResultObject description] : 400 -> 396
~ -[DMFFetchProfilesResultObject description] : 400 -> 396
~ -[DMFFetchProvisioningProfilesResultObject description] : 400 -> 396
~ -[DMFFetchSafariBookmarksResultObject description] : 356 -> 352
~ -[DMFFetchSafariBookmarksResultObject _appendDescriptionOfBookmark:toString:level:] : 488 -> 484
~ -[DMFFetchUsersResultObject description] : 400 -> 396
~ ___42-[DMFPolicyMonitor initWithXPCConnection:]_block_invoke : 428 -> 424
~ ___54-[DMFPolicyMonitor requestPoliciesForTypes:withError:]_block_invoke.128 : 288 -> 284
~ ___66-[DMFPolicyMonitor requestPoliciesForBundleIdentifiers:withError:]_block_invoke.131 : 252 -> 248
~ ___57-[DMFPolicyMonitor allExpiredScreenTimeBudgetsWithError:]_block_invoke.139 : 240 -> 236
~ _DMFObjectDescriptionWithProperties : 828 -> 824
~ ___74-[DMFWebsitePolicyMonitor hasAnyRestrictivePoliciesWithCompletionHandler:]_block_invoke : 392 -> 388
~ -[DMFWebsitePolicyMonitor hasAnyRestrictivePoliciesWithError:] : 424 -> 420
```
