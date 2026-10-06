## MailKit

> `/System/Library/PrivateFrameworks/MailKit.framework/MailKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14f10` | `0x14eb8` | **`-0x58`** |

### Other Changes

```diff

-3891.100.17.2.4
+3893.100.7.0.0
Functions:
~ ___33-[MEAppExtensionsController init]_block_invoke : 580 -> 576
~ -[MEAppExtensionsController hasSecurityExtensionsEnabled] : 376 -> 372
~ ___53-[MEAppExtensionsController _startMatchingExtensions]_block_invoke_2 : 1368 -> 1356
~ -[MEAppExtensionsController _extensionsNewlyMatchingFromNewExtensions:currentExtensions:forCriteria:] : 628 -> 624
~ -[MEAppExtensionsController _extensionsNoLongerMatchingFromNewExtensions:currentExtensions:forCriteria:] : 648 -> 644
~ -[MEAppExtensionsController _remoteEmailExtensionsForExtensions:enabledOnly:] : 992 -> 988
~ -[MEAppExtensionsController _logExtensionsStateWithReason:] : 604 -> 600
~ -[MEComposeExtensionsHelper dealloc] : 424 -> 420
~ ___78-[MEComposeExtensionsHelper _dispatchMailComposeSessionDidBeginForExtensions:]_block_invoke : 576 -> 572
~ ___99-[MEComposeExtensionsHelper dispatchEmailAddressTokenIconRequestsForMailMessage:completionHandler:]_block_invoke : 912 -> 908
~ ___99-[MEComposeExtensionsHelper dispatchEmailAddressTokenIconRequestsForMailMessage:completionHandler:]_block_invoke_2 : 584 -> 580
~ ___78-[MEComposeExtensionsHelper getAdditionalHeadersForMessage:completionHandler:]_block_invoke : 908 -> 904
~ ___51-[MEContentRuleListManager _handleExtensionsAdded:]_block_invoke : 384 -> 380
~ ___53-[MEContentRuleListManager _handleExtensionsRemoved:]_block_invoke_2 : 524 -> 520
~ -[MEContentRuleListManager _notifyObserversOfNewContentRuleList:] : 360 -> 356
~ -[MEContentRuleListManager _notifyObserversOfUpdatedContentRuleList:oldContentRuleList:] : 388 -> 380
~ -[MEContentRuleListManager _notifyObserversOfRemovedContentRuleList:] : 360 -> 356
~ -[MEMessage _sanitaizedHeadersForHeaders:] : 568 -> 564
~ -[MERemoteExtensionContext _createPrincipalObject] : 1668 -> 1664
```
