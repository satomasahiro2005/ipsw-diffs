## ProactiveHarvesting

> `/System/Library/PrivateFrameworks/ProactiveHarvesting.framework/ProactiveHarvesting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3bf1c` | `0x3be78` | **`-0xa4`** |

### Other Changes

```diff

-1331.0.1.0.0
+1334.0.1.0.0
Functions:
~ -[HVQueues deleteContentWithRequest:error:] : 852 -> 848
~ ___47-[HVQueues informObserversToDeleteWithRequest:]_block_invoke : 448 -> 444
~ -[HVDonationReceiver donateInteractions:bundleIdentifier:error:] : 984 -> 980
~ ___49-[HVQueues informObserversThatContentIsAvailable]_block_invoke : 436 -> 432
~ -[HVConsumerCoordinator _consumersForOneDataSource:guardedData:] : 384 -> 380
~ ___53-[HVConsumerCoordinator contentAvailableFromSources:]_block_invoke_2 : 444 -> 440
~ -[HVDataSourceContentState initWithDataSource:basePath:] : 1692 -> 1684
~ ___95-[HVQueue dequeueContent:dataSourceContentState:minimumLevelOfService:inMemoryItemsOnly:error:]_block_invoke : 1468 -> 1456
~ ___137-[HVConsumerCoordinator _consumeContentFromAllDataSources:minimumLevelOfService:inMemoryItemsOnly:guardedData:shouldContinueBlock:error:]_block_invoke_2 : 4928 -> 4952
~ -[HVDataSourceContentState sha256] : 760 -> 756
~ -[HVQueue _writeEventsToDisk:guardedData:] : 924 -> 920
~ -[HVContentState hash] : 292 -> 288
~ -[HVPBDataSourceContentState writeTo:] : 448 -> 440
~ -[HVPBContentStateEntry writeTo:] : 308 -> 304
~ -[HVPBContentState writeTo:] : 332 -> 328
~ +[HVSearchableItemHelper searchableItemIsOutgoing:] : 488 -> 484
~ ___44-[HVQueue dequeuedContentConsumedWithError:]_block_invoke : 1540 -> 1532
~ +[HVSearchableItemHelper messageIdHeaderValuesFromHeaders:] : 468 -> 464
~ +[HVSearchableItemHelper mailItemIsSPAM:emailHeaders:mailboxIdentifiers:] : 2140 -> 2156
~ ___43-[HVHtmlParser _consumeHtmlDataEnumerator:]_block_invoke : 536 -> 548
~ -[HVHtmlParser _tagEnd] : 620 -> 616
~ ___49-[HVSpotlightDeletionRequest matchesBloomFilter:]_block_invoke_2 : 376 -> 372
~ ___49-[HVSpotlightDeletionRequest matchesBloomFilter:]_block_invoke_3 : 376 -> 372
~ -[HVPBContentStateEntry copyWithZone:] : 356 -> 352
~ -[HVPBContentStateEntry mergeFrom:] : 332 -> 328
~ +[HVSearchableItemHelper mailItemIsRecent:emailHeaders:] : 1144 -> 1140
~ -[HVContentAdmission _refreshBundleIdentifierDenyListsWithLearnFromDenyList:configurableDenyList:] : 632 -> 628
~ ___98-[HVContentAdmission _refreshBundleIdentifierDenyListsWithLearnFromDenyList:configurableDenyList:]_block_invoke : 536 -> 532
~ ___53-[HVContentAdmission _migrateIfNeededWithCompletion:]_block_invoke_2 : 1644 -> 1636
~ ___40-[HVContentAdmission _clearTestSettings]_block_invoke : 432 -> 428
~ ___56-[HVConsumerCoordinator deleteContentWithRequest:error:]_block_invoke : 1300 -> 1284
~ -[HVConsumerCoordinator _statsForConsumers:] : 776 -> 772
~ -[HVQueues statsWithError:] : 1052 -> 1044
~ -[HVQueues(TestHelpers) waitForObserversWithTimeout:] : 796 -> 792
~ ___53-[HVQueues(TestHelpers) waitForObserversWithTimeout:]_block_invoke_2 : 380 -> 376
~ -[HVDonationReceiver donateSearchableItems:bundleIdentifier:error:] : 1576 -> 1568
~ ___64+[HVBiomeConversions _mailContentEventFromSearchableItem:error:]_block_invoke : 488 -> 484
~ -[HVPBContentState copyWithZone:] : 380 -> 376
~ -[HVPBContentState mergeFrom:] : 336 -> 332
~ -[_HVNSStringEncodingEnumerator nextObject] : 492 -> 488
~ -[HVPBDataSourceContentState dictionaryRepresentation] : 664 -> 656
~ -[HVPBDataSourceContentState copyWithZone:] : 504 -> 496
~ -[HVPBDataSourceContentState mergeFrom:] : 440 -> 432
```
