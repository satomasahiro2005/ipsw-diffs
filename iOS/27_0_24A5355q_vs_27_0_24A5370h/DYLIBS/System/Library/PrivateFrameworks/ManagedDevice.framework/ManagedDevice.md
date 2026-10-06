## ManagedDevice

> `/System/Library/PrivateFrameworks/ManagedDevice.framework/ManagedDevice`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__ustring` | `0xb64` | `0x9d8` | **`-0x18c`** |
| `__TEXT.__text` | `0x2a2dc` | `0x2a1ac` | **`-0x130`** |
| `__AUTH_CONST.__cfstring` | `0x66c0` | `0x65c0` | **`-0x100`** |
| `__TEXT.__cstring` | `0x49d0` | `0x4920` | **`-0xb0`** |

### Other Changes

```diff

-20.0.0.0.0
+22.0.0.0.0

-  - /System/Library/Frameworks/CoreLocation.framework/CoreLocation

-  CStrings:  883
+  CStrings:  875
Functions:
~ -[MDFBatchRequestOperation activityTransactionOperationDidStart:] : 444 -> 440
~ -[MDFEffectivePolicy policyForIdentifier:excludableIdentifiers:] : 648 -> 644
~ -[MDFEffectivePolicy hasRestrictivePolicies] : 312 -> 308
~ +[MDFPrioritizedPolicy prioritizedPoliciesForAppPolicy:appCategoryPolicy:bundleIdentifiers:categoryPolicy:categoryIdentifiers:webPolicy:webCategoryPolicy:webDomains:] : 1528 -> 1508
~ -[MDFFetchApplicationsResultObject description] : 416 -> 412
~ -[MDFFetchAppsResultObject description] : 376 -> 372
~ -[MDFFetchManagedBooksResultObject description] : 400 -> 396
~ -[MDFFetchProfilesResultObject description] : 400 -> 396
~ ___42-[MDFPolicyMonitor initWithXPCConnection:]_block_invoke : 428 -> 424
~ ___54-[MDFPolicyMonitor requestPoliciesForTypes:withError:]_block_invoke.128 : 288 -> 284
~ ___66-[MDFPolicyMonitor requestPoliciesForBundleIdentifiers:withError:]_block_invoke.131 : 252 -> 248
~ ___79-[MDFPolicyMonitor requestCommunicationPoliciesForBundleIdentifiers:withError:]_block_invoke.134 : 252 -> 248
~ ___57-[MDFPolicyMonitor allExpiredScreenTimeBudgetsWithError:]_block_invoke.139 : 240 -> 236
~ _MDFObjectDescriptionWithProperties : 828 -> 824
~ __MDFErrorDescriptionsWithCodeAndUserInfo : 5300 -> 5068
CStrings:
- "Could not play lost mode sound."
- "The device cannot be put in lost mode."
- "The device cannot be taken out of lost mode."
- "The device is in lost mode."
- "The device is not in lost mode."
- "The device’s location cannot be determined."
- "The device’s location cannot be requested at this time because audit information cannot be saved."
- "The device’s location cannot be requested at this time."
```
