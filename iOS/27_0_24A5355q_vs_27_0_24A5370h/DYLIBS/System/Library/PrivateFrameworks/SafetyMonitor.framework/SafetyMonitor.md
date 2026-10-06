## SafetyMonitor

> `/System/Library/PrivateFrameworks/SafetyMonitor.framework/SafetyMonitor`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x712cc` | `0x71240` | **`-0x8c`** |

### Other Changes

```diff

-1109.0.3.0.0
+1114.0.0.0.0
Functions:
~ sub_297e2e6c8 -> sub_29ae2f6c8 : 220 -> 216
~ sub_297e2e7a4 -> sub_29ae2f7a0 : 228 -> 224
~ -[SMSessionEndMessage initWithURL:] : 3136 -> 3132
~ ___57-[SMEligibilityChecker checkReceiverEligibility:handler:]_block_invoke.22 : 1072 -> 1068
~ -[SMEligibilityChecker checkConversationEligibility:handler:] : 1188 -> 1184
~ ___61-[SMEligibilityChecker checkConversationEligibility:handler:]_block_invoke.32 : 564 -> 560
~ ___101-[SMEligibilityChecker resolveEndpointsForDestinations:service:requiredCapabilities:completionBlock:]_block_invoke_2 : 324 -> 320
~ -[SMDeviceConfigurationChecker effectivePairedDevice] : 316 -> 312
~ +[SMDeepLinkURLFactory resolvePayloadTypeFromURL:] : 1536 -> 1532
~ -[SMSessionStartMessage initWithURL:] : 5640 -> 5636
~ -[SMConversation initWithReceiverHandles:identifier:displayName:] : 524 -> 520
~ -[SMConversation initWithDictionary:] : 496 -> 492
~ -[SMConversation outputToDictionary] : 564 -> 560
~ -[SMHandle canonicalizedHandle] : 468 -> 464
~ _conversationHandlesValid : 344 -> 340
~ -[SMMessage initWithURL:] : 2296 -> 2292
~ +[SMMessage messageTypeFromURL:] : 476 -> 472
~ +[SMMessage messageIDFromURL:] : 516 -> 512
~ +[SMMessage sessionIDFromURL:] : 516 -> 512
~ -[SMCache initWithDictionary:] : 1228 -> 1220
~ -[SMCache outputToDictionary] : 1272 -> 1264
~ -[SMCache identifierHash] : 720 -> 712
~ -[SMCache logCacheForSessionID:role:deviceType:transaction:hashString:] : 2316 -> 2308
~ -[SMCache shiftLocationsOnQueue:handler:] : 2264 -> 2256
~ -[SMSessionConfigurationEnumerationOptions initWithBatchSize:fetchLimit:sortBySessionStartDate:ascending:sessionTypes:timeInADayInterval:pickOneConfigInTimeInADayInterval:dateInterval:startBoundingBoxLocation:destinationBoundingBoxLocation:boundingBoxRadius:sessionIdentifier:] : 1028 -> 1024
~ __SMMultiErrorCreate : 1036 -> 1032
~ -[SMKeyReleaseMessage initWithURL:] : 5268 -> 5264
~ -[SMAppDeletionManager _notifyObserversForMessagesAppInstalled] : 276 -> 272
~ -[SMAppDeletionManager _notifyObserversForMessagesAppUninstalled] : 276 -> 272
~ -[SMAppDeletionManager _applicationsDidInstall:] : 316 -> 312
~ -[SMAppDeletionManager _applicationsDidUninstall:] : 316 -> 312
~ -[SMSafetyMonitorManager initWithRestorationIdentifier:] : 728 -> 724
~ sub_297e84730 -> sub_29ae8569c : 1192 -> 1212
~ sub_297e84efc -> sub_29ae85e7c : 280 -> 276
~ sub_297e874a4 -> sub_29ae88420 : 2184 -> 2196
~ sub_297e971f8 -> sub_29ae98180 : 1704 -> 1708
~ sub_297e97934 -> sub_29ae988c0 : 1888 -> 1876
~ sub_297e98f38 -> sub_29ae99eb8 : 900 -> 896
~ ___swift_closure_destructor : 140 -> 148
~ sub_297e9e17c -> sub_29ae9f100 : 1140 -> 1124
```
