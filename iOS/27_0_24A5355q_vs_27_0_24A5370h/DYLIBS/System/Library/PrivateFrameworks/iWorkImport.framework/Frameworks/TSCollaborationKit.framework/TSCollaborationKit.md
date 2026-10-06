## TSCollaborationKit

> `/System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSCollaborationKit.framework/TSCollaborationKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42d1c` | `0x431b8` | **`+0x49c`** |
| `__TEXT.__unwind_info` | `0x1e20` | `0x1dc8` | **`-0x58`** |
| `__AUTH_CONST.__auth_got` | `0x6f8` | `0x700` | **`+0x8`** |

### Other Changes

```diff

-  Symbols:   2303
+  Symbols:   2304
Symbols:
+ _objc_release_x28
Functions:
~ __ZNK4TSCK32CollaborationCommandHistoryArray18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZNK4TSCK39CollaborationCommandHistoryArraySegment18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZN4TSCK36CollaborationCommandHistory_ItemList25clear_transformer_entriesEv : 80 -> 92
~ __ZN4TSCK36CollaborationCommandHistory_ItemList5ClearEv : 144 -> 156
~ __ZNK4TSCK36CollaborationCommandHistory_ItemList18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 444 -> 452
~ __ZNK4TSCK36CollaborationCommandHistory_ItemList13IsInitializedEv : 124 -> 100
~ __ZNK4TSCK27CollaborationCommandHistory18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 560 -> 572
~ __ZNK4TSCK31CollaborationCommandHistoryItem18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 752 -> 768
~ sub_2b6283a78 -> sub_2b79d2aa4 : 300 -> 304
~ __ZN4TSCK42CollaborationCommandHistoryCoalescingGroup11clear_nodesEv : 80 -> 92
~ __ZN4TSCK42CollaborationCommandHistoryCoalescingGroup5ClearEv : 132 -> 144
~ __ZNK4TSCK42CollaborationCommandHistoryCoalescingGroup18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 348 -> 352
~ __ZNK4TSCK42CollaborationCommandHistoryCoalescingGroup13IsInitializedEv : 104 -> 88
~ __ZNK4TSCK46CollaborationCommandHistoryCoalescingGroupNode18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZNK4TSCK68CollaborationCommandHistoryOriginatingCommandAcknowledgementObserver18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 400 -> 408
~ __ZNK4TSCK33DocumentSupportCollaborationState18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 400 -> 408
~ __ZNK4TSCK38SetAnnotationAuthorColorCommandArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 712 -> 728
~ __ZNK4TSCK49SetActivityAuthorShareParticipantIDCommandArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 488 -> 496
~ __ZNK4TSCK15IdOperationArgs18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZNK4TSCK18AddIdOperationArgs18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 384 -> 392
~ __ZNK4TSCK21RemoveIdOperationArgs18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 384 -> 392
~ __ZNK4TSCK24RearrangeIdOperationArgs18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 536 -> 548
~ __ZNK4TSCK24IdPlacementOperationArgs18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 536 -> 548
~ __ZNK4TSCK28ActivityCommitCommandArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 616 -> 628
~ __ZNK4TSCK50ExecuteTestBetweenRollbackAndReapplyCommandArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZNK4TSCK40CreateLocalStorageSnapshotCommandArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 292 -> 296
~ __ZNK4TSCK34BlockDiffsAtCurrentRevisionCommand18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZNK4TSCK16TransformerEntry18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 456 -> 464
~ __ZN4TSCK50CollaborationAppliedCommandDocumentRevisionMapping34clear_remaining_command_operationsEv : 80 -> 92
~ __ZN4TSCK50CollaborationAppliedCommandDocumentRevisionMapping5ClearEv : 192 -> 204
~ __ZNK4TSCK50CollaborationAppliedCommandDocumentRevisionMapping18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 884 -> 904
~ __ZN4TSCK62CollaborationDocumentSessionState_AcknowledgementObserverEntry31clear_acknowledgement_observersEv : 80 -> 92
~ __ZN4TSCK62CollaborationDocumentSessionState_AcknowledgementObserverEntry5ClearEv : 144 -> 156
~ __ZNK4TSCK62CollaborationDocumentSessionState_AcknowledgementObserverEntry18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 444 -> 452
~ __ZNK4TSCK62CollaborationDocumentSessionState_AcknowledgementObserverEntry13IsInitializedEv : 144 -> 120
~ __ZN4TSCK33CollaborationDocumentSessionState30clear_rsvp_command_queue_itemsEv : 80 -> 92
~ __ZN4TSCK33CollaborationDocumentSessionState45clear_collaborator_cursor_transformer_entriesEv : 80 -> 92
~ __ZN4TSCK33CollaborationDocumentSessionState56clear_acknowledged_commands_pending_resume_process_diffsEv : 80 -> 92
~ __ZN4TSCK33CollaborationDocumentSessionState55clear_unprocessed_commands_pending_resume_process_diffsEv : 80 -> 92
~ __ZN4TSCK33CollaborationDocumentSessionState61clear_transformer_from_unprocessed_command_operations_entriesEv : 80 -> 92
~ __ZN4TSCK33CollaborationDocumentSessionState64clear_skipped_acknowledged_commands_pending_resume_process_diffsEv : 80 -> 92
~ __ZN4TSCK33CollaborationDocumentSessionState5ClearEv : 556 -> 652
~ __ZNK4TSCK33CollaborationDocumentSessionState18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 3228 -> 3300
~ sub_2b629368c -> sub_2b79e2864 : 300 -> 304
~ __ZNK4TSCK33CollaborationDocumentSessionState12ByteSizeLongEv : 1372 -> 1380
~ __ZNK4TSCK33CollaborationDocumentSessionState13IsInitializedEv : 588 -> 480
~ __ZNK4TSCK26OperationStorageEntryArray18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZN4TSCK33OperationStorageEntryArraySegment14clear_elementsEv : 80 -> 92
~ __ZN4TSCK33OperationStorageEntryArraySegment5ClearEv : 156 -> 168
~ __ZNK4TSCK33OperationStorageEntryArraySegment18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 788 -> 804
~ __ZNK4TSCK16OperationStorage18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 1076 -> 1100
~ __ZNK4TSCK20OutgoingCommandQueue18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZNK4TSCK27OutgoingCommandQueueSegment18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZNK4TSCK24CommandAssetChunkArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 768 -> 784
~ __ZNK4TSCK53AssetUploadStatusCommandArchive_AssetUploadStatusInfo18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 276 -> 280
~ __ZN4TSCK31AssetUploadStatusCommandArchive5ClearEv : 144 -> 156
~ __ZNK4TSCK31AssetUploadStatusCommandArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 444 -> 452
~ __ZNK4TSCK41AssetUnmaterializedOnServerCommandArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 320 -> 324
~ __ZNK4TSCK41AssetUnmaterializedOnServerCommandArchive12ByteSizeLongEv : 228 -> 236
~ __ZNK4TSCK25CollaboratorCursorArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 272 -> 276
~ __ZN4TSCK36ActivityStreamActivityCounterArchive5ClearEv : 164 -> 188
~ __ZNK4TSCK21ActivityStreamArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 1072 -> 1096
~ __ZNK4TSCK27ActivityStreamActivityArray18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZNK4TSCK34ActivityStreamActivityArraySegment18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZN4TSCK15ActivityArchive44clear_cursor_collection_persistence_wrappersEv : 80 -> 92
~ __ZN4TSCK15ActivityArchive5ClearEv : 220 -> 232
~ __ZNK4TSCK15ActivityArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 1676 -> 1712
~ __ZNK4TSCK15ActivityArchive13IsInitializedEv : 168 -> 144
~ __ZNK4TSCK21ActivityAuthorArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 444 -> 448
~ __ZNK4TSCK21ActivityAuthorArchive12ByteSizeLongEv : 416 -> 424
~ __ZN4TSCK30CommandActivityBehaviorArchive29clear_selection_path_storagesEv : 80 -> 92
~ __ZN4TSCK30CommandActivityBehaviorArchive5ClearEv : 160 -> 172
~ __ZNK4TSCK30CommandActivityBehaviorArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 784 -> 800
~ __ZNK4TSCK30CommandActivityBehaviorArchive13IsInitializedEv : 128 -> 104
~ __ZN4TSCK31ActivityCursorCollectionArchive5ClearEv : 220 -> 232
~ __ZNK4TSCK31ActivityCursorCollectionArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 1056 -> 1080
~ __ZNK4TSCK31ActivityCursorCollectionArchive13IsInitializedEv : 204 -> 180
~ __ZNK4TSCK49ActivityCursorCollectionPersistenceWrapperArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZNK4TSCK36CommentActivityNavigationInfoArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 456 -> 464
~ __ZNK4TSCK50ActivityAuthorCacheArchive_ShareParticipantIDCache18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 292 -> 296
~ __ZNK4TSCK40ActivityAuthorCacheArchive_PublicIDCache18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 292 -> 296
~ __ZNK4TSCK37ActivityAuthorCacheArchive_IndexCache18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 384 -> 392
~ __ZNK4TSCK41ActivityAuthorCacheArchive_FirstJoinCache18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 400 -> 408
~ __ZN4TSCK26ActivityAuthorCacheArchive13clear_authorsEv : 80 -> 92
~ __ZN4TSCK26ActivityAuthorCacheArchive34clear_author_identifiers_to_removeEv : 80 -> 92
~ __ZN4TSCK26ActivityAuthorCacheArchive5ClearEv : 344 -> 416
~ __ZNK4TSCK26ActivityAuthorCacheArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 1344 -> 1372
~ __ZNK4TSCK26ActivityAuthorCacheArchive13IsInitializedEv : 264 -> 216
~ sub_2b62a96e8 -> sub_2b79f89d8 : 136 -> 128
~ sub_2b62a9770 -> sub_2b79f8a58 : 136 -> 128
~ __ZNK4TSCK26ActivityOnlyCommandArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZN4TSCK31ActivityNotificationItemArchive16clear_activitiesEv : 80 -> 92
~ __ZN4TSCK31ActivityNotificationItemArchive5ClearEv : 168 -> 180
~ __ZNK4TSCK31ActivityNotificationItemArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 732 -> 748
~ __ZNK4TSCK31ActivityNotificationItemArchive13IsInitializedEv : 172 -> 148
~ __ZNK4TSCK71ActivityNotificationParticipantCacheArchive_UniqueIdentifierAndAttempts18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 384 -> 392
~ __ZN4TSCK43ActivityNotificationParticipantCacheArchive24clear_notification_itemsEv : 80 -> 92
~ __ZN4TSCK43ActivityNotificationParticipantCacheArchive5ClearEv : 264 -> 288
~ __ZNK4TSCK43ActivityNotificationParticipantCacheArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 824 -> 840
~ __ZNK4TSCK43ActivityNotificationParticipantCacheArchive13IsInitializedEv : 176 -> 152
~ __ZN4TSCK32ActivityNotificationQueueArchive36clear_unprocessed_notification_itemsEv : 80 -> 92
~ __ZN4TSCK32ActivityNotificationQueueArchive32clear_pending_participant_cachesEv : 80 -> 92
~ __ZN4TSCK32ActivityNotificationQueueArchive29clear_sent_participant_cachesEv : 80 -> 92
~ __ZN4TSCK32ActivityNotificationQueueArchive5ClearEv : 204 -> 240
~ __ZNK4TSCK32ActivityNotificationQueueArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 652 -> 664
~ __ZNK4TSCK32ActivityNotificationQueueArchive13IsInitializedEv : 208 -> 160
~ __ZNK4TSCK40ActivityStreamTransformationStateArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 996 -> 1016
~ __ZNK4TSCK54ActivityStreamActivityCounterArchive_ActionTypeCounter18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 376 -> 384
~ __ZNK4TSCK54ActivityStreamActivityCounterArchive_CursorTypeCounter18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 376 -> 384
~ __ZNK4TSCK36ActivityStreamActivityCounterArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 472 -> 480
~ __ZNK4TSCK72ActivityStreamRemovedAuthorAuditorPendingStateArchive_DateToAuditAndType18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 384 -> 392
~ __ZN4TSCK53ActivityStreamRemovedAuthorAuditorPendingStateArchive32clear_current_author_identifiersEv : 80 -> 92
~ __ZN4TSCK53ActivityStreamRemovedAuthorAuditorPendingStateArchive5ClearEv : 164 -> 188
~ __ZNK4TSCK53ActivityStreamRemovedAuthorAuditorPendingStateArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 472 -> 480
~ __ZNK4TSCK53ActivityStreamRemovedAuthorAuditorPendingStateArchive13IsInitializedEv : 132 -> 104
~ sub_2b62b20cc -> sub_2b7a0144c : 136 -> 128
~ sub_2b62b55a0 -> sub_2b7a04918 : 72 -> 80
~ sub_2b62b56ec -> sub_2b7a04a6c : 128 -> 144
~ sub_2b62b582c -> sub_2b7a04bbc : 128 -> 144
~ sub_2b62b596c -> sub_2b7a04d0c : 152 -> 160
~ sub_2b62b5a04 -> sub_2b7a04dac : 128 -> 144
~ sub_2b62b5a84 -> sub_2b7a04e3c : 128 -> 144
~ sub_2b62b5d30 -> sub_2b7a050f8 : 128 -> 144
~ sub_2b62b5e70 -> sub_2b7a05248 : 148 -> 152
~ sub_2b62b5f04 -> sub_2b7a052e0 : 128 -> 144
~ sub_2b62b6044 -> sub_2b7a05430 : 272 -> 276
~ sub_2b62b6158 -> sub_2b7a05548 : 128 -> 144
~ sub_2b62b6298 -> sub_2b7a05698 : 128 -> 144
~ sub_2b62b6318 -> sub_2b7a05728 : 128 -> 144
~ sub_2b62b6398 -> sub_2b7a057b8 : 128 -> 144
~ sub_2b62b6418 -> sub_2b7a05848 : 128 -> 144
~ sub_2b62b6498 -> sub_2b7a058d8 : 128 -> 144
~ sub_2b62b68d8 -> sub_2b7a05d28 : 128 -> 144
~ sub_2b62b6a18 -> sub_2b7a05e78 : 148 -> 156
~ sub_2b62b6aac -> sub_2b7a05f14 : 148 -> 156
~ sub_2b62b6cc0 -> sub_2b7a06130 : 128 -> 144
~ sub_2b62ba790 -> sub_2b7a09c10 : 576 -> 572
~ sub_2b62ba9d0 -> sub_2b7a09e4c : 488 -> 484
~ __ZNK7TSCKSOS30FixCorruptedDataCommandArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 388 -> 392
~ __ZNK7TSCKSOS30FixCorruptedDataCommandArchive12ByteSizeLongEv : 240 -> 248
~ __ZN7TSCKSOS37RemoveAuthorIdentifiersCommandArchive24clear_author_identifiersEv : 80 -> 92
~ __ZN7TSCKSOS37RemoveAuthorIdentifiersCommandArchive5ClearEv : 148 -> 160
~ __ZNK7TSCKSOS37RemoveAuthorIdentifiersCommandArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 496 -> 504
~ __ZNK7TSCKSOS37RemoveAuthorIdentifiersCommandArchive13IsInitializedEv : 144 -> 120
~ __ZNK7TSCKSOS33ResetActivityStreamCommandArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ sub_2b62bdbdc -> sub_2b7a0d06c : 860 -> 872
```
