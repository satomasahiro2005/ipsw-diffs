## MediaGroupsDaemon

> `/System/Library/PrivateFrameworks/MediaGroupsDaemon.framework/MediaGroupsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23af0` | `0x23a74` | **`-0x7c`** |

### Other Changes

```text
Functions:
~ -[MGRemoteQueryClientHandlerQuery handleCompleteResponse:jsonPayload:] : 1088 -> 1080
~ -[MGRemoteQueryClientBrowser _applyUpdates] : 736 -> 728
~ -[MGRemoteQueryServer _clientFind:] : 568 -> 564
~ -[MGRemoteQueryServer _unsafe_transactionCount] : 260 -> 256
~ -[MGRemoteQueryServerHandlerQuery _requestParse] : 644 -> 640
~ ___41-[MGRemoteQueryClientManager _setupQuery]_block_invoke_2 : 632 -> 640
~ -[MGRemoteQueryClientManager _targetAdd:] : 760 -> 756
~ -[MGRemoteQueryClientManager _targetValidate:] : 604 -> 600
~ ___59-[MGRemoteQueryClientManager browser:invalidatedWithError:]_block_invoke : 440 -> 436
~ -[MGRemoteQueryClientManager _queryAdd:] : 932 -> 928
~ -[MGRemoteQueryClientManager _queryRemove:] : 632 -> 628
~ -[MGRemoteQueryClientManager _clientRemove:] : 536 -> 532
~ -[MGRemoteQueryClientManager _clientForTask:includeOthers:] : 632 -> 624
~ -[MGRemoteQueryClientManager _clientForTarget:withQuery:] : 484 -> 480
~ -[MGRemoteQueryClientManager _clientsWithQuery:] : 560 -> 556
~ -[MGRemoteQueryClientManager _clientsForTarget:] : 388 -> 384
~ -[MGRemoteQueryClientManager _watchdogFired:] : 492 -> 488
~ -[MGGroupsQueryAgent setGroupsByMediator:] : 660 -> 656
~ -[MGGroupsQueryAgent _prepareWithGroups:currentIdentifier:] : 2808 -> 2804
~ ___52-[MGGroupsQueryAgent _queryOperation:didFindGroups:]_block_invoke : 1080 -> 1076
~ _MGGroupIdentifierCopyApplyingHashing : 688 -> 684
~ __MGRelevantComponentsForGroupIdentifierComponents : 572 -> 568
~ _MGClassForGroupIdentifier : 744 -> 740
~ ___41-[MGRemoteQueryServerManager _setupQuery]_block_invoke_2 : 748 -> 752
~ -[NSDictionary(MGRemoteQueryCoding) rq_coded] : 444 -> 440
~ -[NSDictionary(MGRemoteQueryCoding) rq_arrayOfDecodedClass:forKey:] : 408 -> 404
~ -[NSArray(MGRemoteQueryCoding) rq_coded] : 332 -> 328
~ ___MGLogForCategory_block_invoke : 108 -> 112
~ -[MGRemoteQueryServerTransaction _handlerForRequest:] : 460 -> 456
~ ___38-[MGDaemon setTopologyRequestHandler:]_block_invoke : 596 -> 592
~ -[MGDaemon groupsQueryAgent:didFindResults:forQuery:] : 536 -> 532
~ ___53-[MGDaemon groupsQueryAgent:didFindResults:forQuery:]_block_invoke : 816 -> 812
~ -[MGDaemon createGroupWithType:name:members:completion:] : 1260 -> 1256
~ ___39-[MGDaemon _fetchGroupInfo:completion:]_block_invoke.159 : 660 -> 656
~ ___66-[MGDaemon startOutstandingQueryWithPredicate:handler:completion:]_block_invoke : 404 -> 400
```
