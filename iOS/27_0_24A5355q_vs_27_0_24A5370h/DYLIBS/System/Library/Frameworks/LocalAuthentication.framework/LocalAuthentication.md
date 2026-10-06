## LocalAuthentication

> `/System/Library/Frameworks/LocalAuthentication.framework/LocalAuthentication`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34354` | `0x34318` | **`-0x3c`** |

### Other Changes

```diff

-2305.0.0.0.1
+2319.0.16.502.1
Functions:
~ -[LAEnvironmentState initWithCoreState:] : 572 -> 568
~ -[LAEnvironment _notifyObserversAboutUpdateFrom:] : 580 -> 576
~ +[LAClient _performInvalidationBlocks:] : 244 -> 240
~ +[LARatchetManager optionsForRatchetArmOptions:] : 436 -> 432
~ -[LAAuthenticationRequirement encodeWithACLCoder:] : 268 -> 264
~ -[LABiometryFallbackRequirement encodeWithACLCoder:] : 268 -> 264
~ -[_LAKeyStore removeItemsWithCompletion:] : 512 -> 508
~ +[LAACLBuilder customACL:] : 1724 -> 1716
~ -[_LAKeyStoreBackendFake fetchItemWithQuery:error:] : 1444 -> 1432
~ -[LAAuthenticationMethod forEachObserverWithProtocol:selector:invoke:] : 348 -> 344
~ -[LAContext _notifyObserversAfterInvalidation] : 444 -> 440
~ -[LADomainStateBiometry initWithResult:] : 532 -> 528
~ -[LADomainStateCompanion initWithResult:] : 596 -> 592
~ -[LADomainStateCompanion _resolveCombinedStateHash] : 424 -> 420
~ sub_1c5cf3d40 -> sub_1c64e8cfc : 172 -> 180
```
