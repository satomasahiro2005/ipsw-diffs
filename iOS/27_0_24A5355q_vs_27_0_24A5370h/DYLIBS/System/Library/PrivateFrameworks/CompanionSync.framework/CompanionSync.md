## CompanionSync

> `/System/Library/PrivateFrameworks/CompanionSync.framework/CompanionSync`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x99448` | `0x99330` | **`-0x118`** |
| `__TEXT.__unwind_info` | `0x2980` | `0x2988` | **`+0x8`** |

### Other Changes

```text
Functions:
~ -[SYObjectChangeSet changesBetween:and:] : 956 -> 952
~ ___34-[SYObjectChangeSet applyToStore:]_block_invoke : 576 -> 564
~ __obfuscatedDescription : 576 -> 588
~ -[SYSyncBatch dictionaryRepresentation] : 556 -> 552
~ -[SYSyncBatch writeTo:] : 372 -> 368
~ -[SYSyncBatch copyWithZone:] : 420 -> 416
~ -[SYSyncBatch mergeFrom:] : 384 -> 380
~ -[SYChangeMessage dictionaryRepresentation] : 460 -> 456
~ -[SYChangeMessage writeTo:] : 308 -> 304
~ -[SYChangeMessage copyWithZone:] : 356 -> 352
~ -[SYChangeMessage mergeFrom:] : 332 -> 328
~ -[SYLogServiceState dictionaryRepresentation] : 1244 -> 1240
~ -[SYLogServiceState writeTo:] : 580 -> 576
~ -[SYLogServiceState copyWithZone:] : 668 -> 664
~ -[SYLogServiceState mergeFrom:] : 624 -> 620
~ -[SYStoreResetSessionOwner _sendBufferedChanges:] : 420 -> 416
~ -[SYStoreResetSessionOwner syncSession:enqueueChanges:error:] : 592 -> 588
~ ___67-[SYStoreIncomingSessionOwner syncSession:applyChanges:completion:]_block_invoke_2 : 432 -> 428
~ -[SYLegacyStore handleChangeMessage:] : 2060 -> 2056
~ -[SYLegacyStore remoteStoreAllObjects:fromPeer:clock:] : 948 -> 944
~ -[SYLegacyStore performFullSyncToCurrentDBVersion] : 1532 -> 1528
~ -[SYLegacyStore(BatchedSyncSupport) _sendBatchChunk:withState:then:] : 704 -> 700
~ -[SYService _wrapUpCurrentSession:] : 1404 -> 1400
~ ___33-[SYPersistentStore _fixPeerInfo]_block_invoke : 864 -> 860
~ -[SYPersistentStore _decodeIndexSet:] : 352 -> 348
~ ___38-[SYPersistentStore logChanges:error:]_block_invoke : 748 -> 744
~ -[SYLogSessionState dictionaryRepresentation] : 1424 -> 1416
~ -[SYLogSessionState writeTo:] : 880 -> 872
~ -[SYLogSessionState copyWithZone:] : 996 -> 988
~ -[SYLogSessionState mergeFrom:] : 920 -> 912
~ -[SYSendingSession _processNextState] : 680 -> 676
~ ___34-[SYSendingSession _installTimers]_block_invoke.23 : 916 -> 912
~ -[SYSendingSession _sentMessageWithIdentifier:userInfo:] : 524 -> 520
~ -[SYSendingSession _peerProcessedMessageWithIdentifier:userInfo:] : 536 -> 532
~ -[SYVectorClock(Additions) initWithJSONRepresentation:] : 752 -> 748
~ -[SYVectorClock(Additions) clockForPeerID:] : 384 -> 380
~ ___38-[_SYDeviceMonitor _rebuildDeviceList]_block_invoke : 356 -> 352
~ ___35-[_SYDeviceMonitor removeNRDevice:]_block_invoke : 376 -> 372
~ ___38-[_SYDeviceMonitor deviceForNRDevice:]_block_invoke : 320 -> 316
~ ___39-[_SYDeviceMonitor deviceForPairingID:]_block_invoke : 320 -> 316
~ ___43-[_SYDeviceMonitor currentTargetableDevice]_block_invoke : 288 -> 284
~ +[SYDevice deviceForIDSDeviceID:fromList:] : 472 -> 468
~ -[SYDevice _updateCachedStateForProperty:] : 272 -> 268
~ -[NMSObfuscatableDescription _descriptionObfuscated:] : 552 -> 548
~ -[SYReceivingSession _processNextState] : 812 -> 808
~ -[SYLogServiceState(Convenience) cocoaTransportOptions] : 384 -> 380
~ -[SYLogSessionState(Convenience) cocoaTransportOptions] : 384 -> 380
~ -[SYMessengerSyncEngine cancelMessagesReturningFailures:] : 552 -> 548
~ -[_SYOutputStreamer _completeAllItemsWithError:] : 492 -> 488
~ -[_SYInputStreamer _completeAllItemsWithError:] : 568 -> 564
~ -[SYRejectedVersion writeTo:] : 200 -> 196
~ -[NMSMessageCenter _checkForSwitch] : 696 -> 692
~ -[SYBatchSyncChunk writeTo:] : 372 -> 368
~ -[SYBatchSyncChunk copyWithZone:] : 420 -> 416
~ -[SYBatchSyncChunk mergeFrom:] : 384 -> 380
~ -[SYFileTransferSyncEngine cancelMessagesReturningFailures:] : 564 -> 560
~ -[_SYMessageTimerTable cancelAllTimers] : 244 -> 240
~ __EnqueueOnNewGroup : 476 -> 472
~ -[SYStatisticStore(DatabaseTidying) _LOCKED_pruneMessageLogForServices:] : 516 -> 512
~ -[SYStatisticStore(DatabaseTidying) _LOCKED_pruneFileTransferLogForServices:] : 516 -> 512
~ -[SYVectorClock dictionaryRepresentation] : 404 -> 400
~ -[SYVectorClock writeTo:] : 276 -> 272
~ -[SYVectorClock copyWithZone:] : 316 -> 312
~ -[SYVectorClock mergeFrom:] : 260 -> 256
~ -[SYSyncAllObjects writeTo:] : 372 -> 368
~ -[SYSyncAllObjects copyWithZone:] : 420 -> 416
~ -[SYSyncAllObjects mergeFrom:] : 384 -> 380
~ ___31+[SYQueueDumper registerQueue:]_block_invoke_2 : 508 -> 504
```
