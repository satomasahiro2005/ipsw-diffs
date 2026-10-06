## DebugHierarchyFoundation

> `/System/Library/PrivateFrameworks/DebugHierarchyFoundation.framework/DebugHierarchyFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13478` | `0x133c0` | **`-0xb8`** |

### Same-size Content Changes

- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_selrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ +[DebugHierarchyObjectProtocolHelper enumerateAdditionalGroupsAndObjectsOfObject:withType:withBlock:] : 828 -> 820
~ -[DebugHierarchyMetaDataAction performInContext:] : 1056 -> 1052
~ -[DebugHierarchyPropertyActionLegacyV1 performInContext:withObject:] : 964 -> 960
~ -[DebugHierarchyRequest initWithDictionary:] : 1000 -> 992
~ -[DebugHierarchyRequest dictionaryRepresentation] : 1208 -> 1200
~ -[NSPointerArray(DBGAdditions) dbg_indexOfObjectIdenticalTo:] : 288 -> 284
~ -[DebugHierarchyRuntimeInfo initWithSerializedRepresentation:] : 320 -> 316
~ -[DebugHierarchyRuntimeInfo _reindexAllTypes] : 248 -> 244
~ -[DebugHierarchyRuntimeInfo _recursivelyIndexRuntimeType:] : 328 -> 324
~ -[DebugHierarchyRuntimeInfo serializedRepresentation] : 352 -> 348
~ -[DebugHierarchyRuntimeInfo _topLevelTypes] : 364 -> 360
~ -[DebugHierarchyRuntimeInfo mergeWith:] : 264 -> 260
~ -[DebugHierarchyRuntimeInfo _recursivelyMergeInRuntimeType:] : 440 -> 436
~ -[DebugHierarchyRuntimeInfo debugDescription] : 508 -> 504
~ -[DebugHierarchyRuntimeInfo _describeTreeWithRoot:depth:description:] : 448 -> 444
~ -[DebugHierarchyRequestExecutionContext _addDebugHierarchyObjectDict:toGroupWithID:asDirectChild:belowParent:] : 1320 -> 1316
~ -[DebugHierarchyRequestExecutionContext addProperties:toObject:] : 608 -> 596
~ -[DebugHierarchyRequestExecutionContext _collectRuntimeInformationForObjectType:] : 1016 -> 1012
~ -[DebugHierarchyCrawler crawlEntryPointClasses] : 796 -> 792
~ -[DebugHierarchyCrawler _entryPointClasses] : 356 -> 352
~ -[DebugHierarchyRequestExecutor _v1RecursivelyMakePropertyDescriptionCompatibleWithGroup:] : 1152 -> 1148
~ -[DebugHierarchyRequestExecutor _executeRequestActionsWithKnownObjects] : 604 -> 596
~ -[DebugHierarchyPropertyAction performInContext:withObject:] : 812 -> 808
~ -[DebugHierarchyPropertyAction isTargetingObject:] : 1028 -> 1012
~ -[DebugHierarchyPropertyAction _fetchValuesForPropertiesWithNames:onObject:inContext:] : 548 -> 544
~ -[DebugHierarchyRuntimeType initWithDictionaryRepresentation:] : 648 -> 640
~ -[DebugHierarchyRuntimeType dictionaryRepresentation] : 920 -> 912
~ ___77+[DebugHierarchyRequest(TargetHubAdditions) _requestWithV1RequestDictionary:]_block_invoke : 484 -> 480
~ +[DebugHierarchyRequestActionExecutor objectTargetedActionsFromActions:] : 340 -> 336
~ +[DebugHierarchyRequestActionExecutor _executeStandaloneActions:inContext:] : 260 -> 256
~ +[DebugHierarchyRequestActionExecutor _executeObjectActions:withObject:inContext:] : 288 -> 284
~ -[DebugHierarchyRequestActionExecutor allObjectActionsTargetIdentifiers:] : 376 -> 372
~ +[DebugHierarchyLogEntry formattedSummaryOfLogs:] : 360 -> 356
~ _DBGSerializePropertyDescriptionsAsJSON : 424 -> 420
~ _DBGDeserializePropertyDictionariesFromJSON : 424 -> 420
```
