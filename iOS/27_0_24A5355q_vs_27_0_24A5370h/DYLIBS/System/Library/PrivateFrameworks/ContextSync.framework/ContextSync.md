## ContextSync

> `/System/Library/PrivateFrameworks/ContextSync.framework/ContextSync`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xd06` | `0xd38` | **`+0x32`** |
| `__AUTH_CONST.__const` | `0x40` | `0x60` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x380` | `0x3a0` | **`+0x20`** |
| `__TEXT.__text` | `0x10138` | `0x10150` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x1017` | `0x102e` | **`+0x17`** |
| `__DATA_CONST.__objc_selrefs` | `0xb10` | `0xb18` | **`+0x8`** |
| `__TEXT.__const` | `0x88` | `0x90` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x410` | `0x418` | **`+0x8`** |

### Other Changes

```diff

-236.0.2.0.0
+239.0.2.0.0

-  Functions: 334
-  Symbols:   611
-  CStrings:  207
+  Functions: 335
+  Symbols:   614
+  CStrings:  209
Symbols:
+ GCC_except_table30
+ GCC_except_table32
+ GCC_except_table34
+ ___block_descriptor_32_e49_v32?0"BMDistributedContextSubscription"8Q16^B24l
- GCC_except_table31
Functions:
~ ___48-[BMDistributedContextService loadSubscriptions]_block_invoke : 1444 -> 1456
~ ___48-[BMDistributedContextService loadSubscriptions]_block_invoke.44 : 144 -> 156
+ ___48-[BMDistributedContextService loadSubscriptions]_block_invoke.48
~ -[BMDistributedContextService initializeSinksForRemoteDSLIdentifiers] : 476 -> 472
~ -[BMDistributedContextService updateSubscriptionsAfterUnlock] : 1112 -> 1104
~ -[BMDistributedContextService removeAllSubscriptionsForDeadRemoteDevice:] : 460 -> 456
~ -[BMDistributedContextService saveRemoteSubscription:fromDevice:] : 1692 -> 1680
~ -[BMDistributedContextService contextChanged:forSubscriptionWithIdentifier:] : 536 -> 532
~ -[BMDistributedContextService registerRemoteDSLSubscription:withRemoteIdentifier:withOptions:forDevices:] : 1096 -> 1100
~ -[BMDistributedContextService unregisterRemoteDSLSubscription:withRemoteIdentifier:forDevices:] : 928 -> 932
~ -[BMDistributedContextService idsDeviceForDeviceUUID:] : 348 -> 344
~ -[BMDistributedContextService devicesWithDeviceType:] : 848 -> 844
~ -[BMDistributedContextService sendIDSMessageWithContent:asWaking:toDevice:error:] : 2676 -> 2672
~ ___57-[BMDistributedContextService connection:devicesChanged:]_block_invoke : 744 -> 736
~ -[BMDistributedContextService logMetricsForSubscription:uponReboot:] : 572 -> 568
~ -[BMDistributedContextSubscribeMessage initWithMessageDictionary:fromRemoteDevice:localDevice:] : 1244 -> 1232
~ -[BMDistributedContextSubscribeMessage dictionaryRepresentation] : 928 -> 924
~ -[BMDistributedContextSubscribeMessage initWithSubscriptions:localDevice:messageIntent:] : 416 -> 412
~ -[BMDistributedContextSubscriptionManager saveToStorage] : 372 -> 368
~ +[BMDistributedContextSubscriptionManager loadFromStorage:withLocalDeviceID:] : 632 -> 628
~ +[BMDistributedContextSubscriptionManager loadAndMigrateStorageFromLegacyToV1:withLocalDeviceID:] : 1976 -> 1960
~ -[BMDistributedContextSubscriptionManager allSubscriptionIdentifiers] : 332 -> 328
~ -[BMDistributedContextSubscriptionManager deviceIdentifiersWithActiveSubscriptions] : 368 -> 364
~ -[BMDistributedContextSubscriptionManager subscriptionForIdentifier:fromSubscribingDevice:onSubscribedDevice:] : 488 -> 472
~ -[BMDistributedContextSubscriptionManager removeSubscriptionWithIdentifier:fromSubscribingDevice:onSubscribedDevice:] : 488 -> 484
~ -[BMDistributedContextSubscriptionManager removeAllSubscriptionsMadeBySubscribingDevice:] : 364 -> 360
~ -[BMDistributedContextSubscriptionManager subscribingDevicesForIdentifier:subscribedToDevice:] : 444 -> 440
~ -[BMDistributedContextSubscriptionManager subscriptionsWithIdentifier:subscribedToDevice:] : 408 -> 404
~ -[BMDistributedContextSubscriptionManager subscriptionsWithSubscribingDevice:] : 352 -> 348
~ -[BMDistributedContextSubscriptionManager subscriptionsWithSubscribedDevice:] : 352 -> 348
~ +[BMDistributedContextUtilities isSupportEnabledForBMDSL:useCase:withError:] : 592 -> 588
CStrings:
+ "Rebooted %@, unlocked %@, delivered notifications %@, reloaded %lu subscriptions"
+ "Subscription[%lu]: %@"
+ "v32@?0@\"BMDistributedContextSubscription\"8Q16^B24"
- "Rebooted %@, unlocked %@, delivered notifications %@, reloaded subscriptions %@"
```
