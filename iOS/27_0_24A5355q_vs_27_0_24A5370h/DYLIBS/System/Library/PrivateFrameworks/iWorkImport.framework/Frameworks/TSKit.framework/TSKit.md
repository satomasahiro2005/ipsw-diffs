## TSKit

> `/System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSKit.framework/TSKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa3974` | `0xa3d80` | **`+0x40c`** |
| `__TEXT.__unwind_info` | `0x3f98` | `0x3f30` | **`-0x68`** |
| `__AUTH_CONST.__auth_got` | `0x10b0` | `0x10a8` | **`-0x8`** |

### Other Changes

```diff

-  Symbols:   3636
+  Symbols:   3635
Symbols:
- _objc_retain_x25
Functions:
~ sub_2b64ef698 -> sub_2b7c3e698 : 224 -> 228
~ sub_2b64f01d4 -> sub_2b7c3f1d8 : 344 -> 336
~ sub_2b64f31d4 -> sub_2b7c421d0 : 168 -> 176
~ sub_2b64f327c -> sub_2b7c42280 : 296 -> 300
~ sub_2b64f341c -> sub_2b7c42424 : 64 -> 80
~ sub_2b64f345c -> sub_2b7c42474 : 96 -> 116
~ sub_2b64f3c90 -> sub_2b7c42cbc : 732 -> 752
~ sub_2b64f3f6c -> sub_2b7c42fac : 136 -> 148
~ sub_2b64f40b0 -> sub_2b7c430fc : 420 -> 424
~ sub_2b64f4d30 -> sub_2b7c43d80 : 972 -> 968
~ sub_2b64f66a4 -> sub_2b7c456f0 : 444 -> 440
~ sub_2b64f8368 -> sub_2b7c473b0 : 368 -> 364
~ sub_2b64f99cc -> sub_2b7c48a10 : 244 -> 240
~ sub_2b64fbb94 -> sub_2b7c4abd4 : 752 -> 748
~ sub_2b64ff220 -> sub_2b7c4e25c : 384 -> 376
~ sub_2b650b41c -> sub_2b7c5a450 : 6216 -> 6212
~ sub_2b6510604 -> sub_2b7c5f634 : 564 -> 560
~ sub_2b65109bc -> sub_2b7c5f9e8 : 568 -> 556
~ sub_2b6510cb4 -> sub_2b7c5fcd4 : 160 -> 156
~ sub_2b6510d8c -> sub_2b7c5fda8 : 180 -> 176
~ sub_2b6510ef8 -> sub_2b7c5ff10 : 112 -> 108
~ sub_2b6511184 -> sub_2b7c60198 : 540 -> 528
~ sub_2b6511784 -> sub_2b7c6078c : 524 -> 528
~ sub_2b651248c -> sub_2b7c61498 : 296 -> 300
~ sub_2b65125b4 -> sub_2b7c615c4 : 516 -> 520
~ sub_2b6512de4 -> sub_2b7c61df8 : 920 -> 916
~ sub_2b6513588 -> sub_2b7c62598 : 1148 -> 1144
~ sub_2b6514130 -> sub_2b7c6313c : 264 -> 260
~ sub_2b6514238 -> sub_2b7c63240 : 1100 -> 1092
~ sub_2b65146a8 -> sub_2b7c636a8 : 616 -> 612
~ sub_2b6516018 -> sub_2b7c65014 : 508 -> 500
~ sub_2b6518200 -> sub_2b7c671f4 : 524 -> 520
~ sub_2b6518638 -> sub_2b7c67628 : 60 -> 72
~ sub_2b651ed54 -> sub_2b7c6dd50 : 536 -> 532
~ sub_2b65207c4 -> sub_2b7c6f7bc : 316 -> 308
~ sub_2b6523720 -> sub_2b7c72710 : 304 -> 300
~ sub_2b6523c30 -> sub_2b7c72c1c : 568 -> 564
~ __ZN3TSK8TreeNode14clear_childrenEv : 80 -> 92
~ __ZN3TSK8TreeNode5ClearEv : 200 -> 212
~ __ZNK3TSK8TreeNode18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 488 -> 496
~ sub_2b6526a40 -> sub_2b7c75a48 : 300 -> 304
~ __ZNK3TSK8TreeNode13IsInitializedEv : 124 -> 100
~ __ZNK3TSK23LocalCommandHistoryItem18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 400 -> 408
~ __ZNK3TSK24LocalCommandHistoryArray18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZNK3TSK31LocalCommandHistoryArraySegment18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZNK3TSK19LocalCommandHistory18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 456 -> 464
~ __ZN3TSK15DocumentArchive26clear_activity_log_entriesEv : 80 -> 92
~ __ZN3TSK15DocumentArchive5ClearEv : 344 -> 356
~ __ZN3TSK24FormattingSymbolsArchive5ClearEv : 1800 -> 1812
~ __ZNK3TSK15DocumentArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 1624 -> 1648
~ __ZNK3TSK15DocumentArchive13IsInitializedEv : 244 -> 220
~ __ZNK3TSK24FormattingSymbolsArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 2236 -> 2240
~ sub_2b652f63c -> sub_2b7c7e670 : 300 -> 304
~ __ZNK3TSK24FormattingSymbolsArchive12ByteSizeLongEv : 3896 -> 4040
~ __ZNK3TSK22DocumentSupportArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 1968 -> 2012
~ __ZNK3TSK16ViewStateArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 448 -> 456
~ __ZNK3TSK14CommandArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 688 -> 696
~ __ZN3TSK19CommandGroupArchive14clear_commandsEv : 80 -> 92
~ __ZN3TSK19CommandGroupArchive5ClearEv : 228 -> 240
~ __ZNK3TSK19CommandGroupArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 708 -> 720
~ __ZNK3TSK19CommandGroupArchive13IsInitializedEv : 164 -> 140
~ __ZN3TSK31InducedCommandCollectionArchive22clear_induced_commandsEv : 80 -> 92
~ __ZN3TSK31InducedCommandCollectionArchive5ClearEv : 188 -> 200
~ __ZNK3TSK31InducedCommandCollectionArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 740 -> 756
~ __ZNK3TSK31InducedCommandCollectionArchive13IsInitializedEv : 184 -> 160
~ __ZNK3TSK34PropagatedCommandCollectionArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 672 -> 684
~ __ZNK3TSK23FinalCommandPairArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 672 -> 684
~ __ZN3TSK23CommandContainerArchive14clear_commandsEv : 80 -> 92
~ __ZN3TSK23CommandContainerArchive5ClearEv : 124 -> 136
~ __ZNK3TSK23CommandContainerArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 292 -> 296
~ __ZNK3TSK23CommandContainerArchive13IsInitializedEv : 104 -> 88
~ __ZNK3TSK30ProgressiveCommandGroupArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZN3TSK19CustomFormatArchive5ClearEv : 212 -> 224
~ __ZNK3TSK19FormatStructArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 4884 -> 4984
~ __ZNK3TSK19FormatStructArchive12ByteSizeLongEv : 1880 -> 1888
~ __ZNK3TSK29CustomFormatArchive_Condition18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 512 -> 520
~ __ZNK3TSK19CustomFormatArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 780 -> 796
~ sub_2b653e21c -> sub_2b7c8d3f4 : 104 -> 88
~ __ZN3TSK23CustomFormatListArchive11clear_uuidsEv : 80 -> 92
~ __ZN3TSK23CustomFormatListArchive5ClearEv : 164 -> 188
~ __ZNK3TSK23CustomFormatListArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 472 -> 480
~ __ZNK3TSK23CustomFormatListArchive13IsInitializedEv : 156 -> 120
~ __ZNK3TSK23AnnotationAuthorArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 448 -> 452
~ __ZNK3TSK23AnnotationAuthorArchive12ByteSizeLongEv : 416 -> 424
~ __ZNK3TSK29DeprecatedChangeAuthorArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 292 -> 296
~ __ZN3TSK30AnnotationAuthorStorageArchive23clear_annotation_authorEv : 80 -> 92
~ __ZN3TSK30AnnotationAuthorStorageArchive5ClearEv : 124 -> 136
~ __ZNK3TSK30AnnotationAuthorStorageArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 292 -> 296
~ __ZNK3TSK30AnnotationAuthorStorageArchive13IsInitializedEv : 104 -> 88
~ __ZN3TSK20SelectionPathArchive5ClearEv : 124 -> 136
~ __ZNK3TSK42CommandBehaviorSelectionPathStorageArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 864 -> 884
~ __ZNK3TSK42CommandBehaviorSelectionPathStorageArchive13IsInitializedEv : 284 -> 244
~ __ZNK3TSK20SelectionPathArchive13IsInitializedEv : 104 -> 88
~ __ZNK3TSK22CommandBehaviorArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 400 -> 408
~ __ZN3TSK31CommandSelectionBehaviorArchive36clear_additional_selection_behaviorsEv : 80 -> 92
~ __ZN3TSK31CommandSelectionBehaviorArchive5ClearEv : 160 -> 172
~ __ZNK3TSK31CommandSelectionBehaviorArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 872 -> 892
~ __ZNK3TSK31CommandSelectionBehaviorArchive13IsInitializedEv : 124 -> 100
~ __ZN3TSK31SelectionPathTransformerArchive28clear_selection_transformersEv : 80 -> 92
~ __ZN3TSK31SelectionPathTransformerArchive5ClearEv : 124 -> 136
~ __ZNK3TSK31SelectionPathTransformerArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 292 -> 296
~ __ZNK3TSK31SelectionPathTransformerArchive13IsInitializedEv : 104 -> 88
~ __ZN3TSK20SelectionPathArchive24clear_ordered_selectionsEv : 80 -> 92
~ __ZNK3TSK20SelectionPathArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 292 -> 296
~ __ZNK3TSK24DocumentSelectionArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZNK3TSK18NullCommandArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZNK3TSK25GroupCommitCommandArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 304 -> 308
~ __ZNK3TSK38UpgradeDocPostProcessingCommandArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZNK3TSK44InducedCommandCollectionCommitCommandArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 240 -> 244
~ __ZNK3TSK39ChangeDocumentPackageTypeCommandArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 536 -> 548
~ __ZNK3TSK32AIGeneratedContentCommandArchive18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 560 -> 572
~ __ZNK3TSK12RangeAddress18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 440 -> 448
~ __ZNK3TSK9Operation18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 1536 -> 1568
~ __ZN3TSK20OperationTransformer5ClearEv : 132 -> 144
~ __ZNK3TSK20OperationTransformer18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 348 -> 352
~ __ZN3TSK24OutgoingCommandQueueItem21clear_large_data_listEv : 80 -> 92
~ __ZN3TSK24OutgoingCommandQueueItem5ClearEv : 268 -> 292
~ __ZNK3TSK24OutgoingCommandQueueItem18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 936 -> 952
~ __ZNK3TSK24OutgoingCommandQueueItem13IsInitializedEv : 196 -> 160
~ __ZNK3TSK42OutgoingCommandQueueItemUUIDToDataMapEntry18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 400 -> 408
~ __ZN3TSK24NativeContentDescription27clear_drawable_descriptionsEv : 80 -> 92
~ __ZN3TSK24NativeContentDescription5ClearEv : 292 -> 304
~ __ZNK3TSK24NativeContentDescription18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 404 -> 408
~ __ZNK3TSK24NativeContentDescription13IsInitializedEv : 104 -> 88
~ __ZNK3TSK28StructuredTextImportSettings18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 1160 -> 1176
~ __ZNK3TSK28StructuredTextImportSettings12ByteSizeLongEv : 696 -> 728
~ __ZN3TSK38OperationStorageCommandOperationsEntry5ClearEv : 152 -> 164
~ __ZNK3TSK38OperationStorageCommandOperationsEntry18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 588 -> 596
~ __ZN3TSK21OperationStorageEntry5ClearEv : 160 -> 172
~ __ZNK3TSK21OperationStorageEntry18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 720 -> 732
~ __ZNK3TSK53DataReferenceRecord_ContainerUUIDToReferencedDataPair18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 544 -> 556
~ __ZN3TSK19DataReferenceRecord32clear_unbounded_referenced_datasEv : 80 -> 92
~ __ZN3TSK19DataReferenceRecord5ClearEv : 204 -> 240
~ __ZNK3TSK19DataReferenceRecord18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 652 -> 664
~ __ZNK3TSK19DataReferenceRecord13IsInitializedEv : 208 -> 160
~ __ZNK3TSK23PencilAnnotationUIState18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 776 -> 788
~ sub_2b65584c0 -> sub_2b7ca77d4 : 72 -> 80
~ sub_2b6558508 -> sub_2b7ca7824 : 128 -> 144
~ sub_2b655874c -> sub_2b7ca7a78 : 152 -> 160
~ sub_2b65587e4 -> sub_2b7ca7b18 : 128 -> 144
~ sub_2b6558a44 -> sub_2b7ca7d88 : 128 -> 144
~ sub_2b6558b84 -> sub_2b7ca7ed8 : 128 -> 144
~ sub_2b6558c04 -> sub_2b7ca7f68 : 128 -> 144
~ sub_2b6558e04 -> sub_2b7ca8178 : 148 -> 152
~ sub_2b6558e98 -> sub_2b7ca8210 : 272 -> 276
~ sub_2b6558fac -> sub_2b7ca8328 : 128 -> 144
~ sub_2b65590ec -> sub_2b7ca8478 : 128 -> 144
~ sub_2b655916c -> sub_2b7ca8508 : 128 -> 144
~ sub_2b655936c -> sub_2b7ca8718 : 128 -> 144
~ sub_2b65594ac -> sub_2b7ca8868 : 128 -> 144
~ sub_2b655c834 -> sub_2b7cabc00 : 512 -> 508
~ sub_2b655cce8 -> sub_2b7cac0b0 : 376 -> 372
~ sub_2b655d8d0 -> sub_2b7cacc94 : 232 -> 228
~ sub_2b655d9b8 -> sub_2b7cacd78 : 140 -> 132
~ sub_2b65601d8 -> sub_2b7caf590 : 320 -> 316
~ sub_2b6560958 -> sub_2b7cafd0c : 400 -> 396
~ sub_2b6561138 -> sub_2b7cb04e8 : 436 -> 432
~ sub_2b65612f4 -> sub_2b7cb06a0 : 404 -> 400
~ sub_2b6561488 -> sub_2b7cb0830 : 392 -> 388
~ sub_2b6561610 -> sub_2b7cb09b4 : 660 -> 656
~ sub_2b65618a4 -> sub_2b7cb0c44 : 792 -> 788
~ sub_2b6562298 -> sub_2b7cb1634 : 424 -> 420
~ sub_2b6562440 -> sub_2b7cb17d8 : 620 -> 616
~ sub_2b6562ed8 -> sub_2b7cb226c : 260 -> 256
~ sub_2b6562fdc -> sub_2b7cb236c : 700 -> 696
~ sub_2b6563a84 -> sub_2b7cb2e10 : 352 -> 348
~ sub_2b6563be4 -> sub_2b7cb2f6c : 288 -> 284
~ sub_2b65640e8 -> sub_2b7cb346c : 572 -> 568
~ sub_2b6564420 -> sub_2b7cb37a0 : 776 -> 768
~ sub_2b6564728 -> sub_2b7cb3aa0 : 592 -> 588
~ sub_2b656db88 -> sub_2b7cbcefc : 1624 -> 1628
~ sub_2b656e570 -> sub_2b7cbd8e8 : 284 -> 300
~ sub_2b656e68c -> sub_2b7cbda14 : 1492 -> 1496
~ sub_2b657312c -> sub_2b7cc24b8 : 992 -> 988
~ __ZNK17TSKUIDStructTract10intersectsERKS_ : 244 -> 252
~ __ZNK17TSKUIDStructTract8containsERKS_ : 236 -> 244
~ sub_2b65777fc -> sub_2b7cc6b94 : 28 -> 24
~ sub_2b657c730 -> sub_2b7ccbac4 : 1192 -> 1188
~ sub_2b657d288 -> sub_2b7ccc618 : 372 -> 368
~ sub_2b657d5d8 -> sub_2b7ccc964 : 292 -> 288
~ sub_2b657dd9c -> sub_2b7ccd124 : 276 -> 272
~ sub_2b657e8dc -> sub_2b7ccdc60 : 348 -> 344
~ sub_2b657f524 -> sub_2b7cce8a4 : 360 -> 356
~ sub_2b657f68c -> sub_2b7ccea08 : 356 -> 352
~ sub_2b657f7f0 -> sub_2b7cceb68 : 356 -> 352
~ sub_2b657f954 -> sub_2b7ccecc8 : 340 -> 336
~ sub_2b657faa8 -> sub_2b7ccee18 : 340 -> 336
~ sub_2b657fc88 -> sub_2b7cceff4 : 452 -> 448
~ sub_2b65800dc -> sub_2b7ccf444 : 500 -> 496
~ sub_2b65802d0 -> sub_2b7ccf634 : 436 -> 432
~ sub_2b6580588 -> sub_2b7ccf8e8 : 436 -> 432
~ sub_2b6583128 -> sub_2b7cd2484 : 1020 -> 964
~ sub_2b658405c -> sub_2b7cd3380 : 2508 -> 2488
~ sub_2b6584a28 -> sub_2b7cd3d38 : 1916 -> 1892
~ sub_2b6586868 -> sub_2b7cd5b60 : 944 -> 952
~ sub_2b6588678 -> sub_2b7cd7978 : 1064 -> 1196
~ sub_2b6589ac4 -> sub_2b7cd8e48 : 640 -> 772
~ sub_2b658c1bc -> sub_2b7cdb5c4 : 32 -> 36
```
