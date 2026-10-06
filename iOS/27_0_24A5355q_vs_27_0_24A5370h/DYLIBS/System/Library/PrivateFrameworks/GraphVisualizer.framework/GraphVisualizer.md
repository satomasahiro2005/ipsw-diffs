## GraphVisualizer

> `/System/Library/PrivateFrameworks/GraphVisualizer.framework/GraphVisualizer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13528` | `0x13334` | **`-0x1f4`** |

### Other Changes

```text
Functions:
~ -[GVRank debugDescription] : 424 -> 420
~ -[GVRank neighborsOfNode:] : 360 -> 356
~ -[GVRank buildNodeIterators] : 316 -> 312
~ -[GVRank inCrossings] : 692 -> 688
~ -[GVRank outCrossings] : 692 -> 688
~ -[GVHorizontalRank breadth] : 288 -> 284
~ -[GVHorizontalRank length] : 268 -> 264
~ -[GVVerticalRank breadth] : 288 -> 284
~ -[GVVerticalRank length] : 268 -> 264
~ -[GVGraph copyWithZone:] : 484 -> 476
~ -[GVGraph updateSourceAndSinkSets] : 448 -> 444
~ -[GVGraph removeNode:] : 660 -> 652
~ -[GVGraph inNodesOf:] : 368 -> 364
~ -[GVGraph outNodesOf:] : 368 -> 364
~ -[GVGraph inEdgeCountOf:] : 328 -> 324
~ -[GVGraph outEdgeCountOf:] : 328 -> 324
~ __traverse_edges : 972 -> 968
~ -[GVGraph hasEdgeBetween::] : 452 -> 448
~ -[GVGraph hasEdgeFrom:to:] : 444 -> 440
~ -[GVGraph minimumSlack] : 320 -> 316
~ -[GVGraph bounds] : 568 -> 560
~ -[GVGraph addNodeGroup:identifier:margins:] : 1020 -> 1016
~ -[GVGraph debugDescription] : 1732 -> 1716
~ -[GVGraphPart reverseEdge:] : 836 -> 832
~ -[GVGraphPart _locateCycles:visistedNodes:nodesInStack:reverseList:] : 564 -> 560
~ -[GVGraphPart removeCycles] : 1004 -> 992
~ -[GVGraphPart initializeGroups] : 744 -> 736
~ -[GVGraphPart initializeRanks] : 860 -> 848
~ -[GVGraphPart smallestGroupContainingNode:] : 388 -> 384
~ -[GVGraphPart balanceRanks] : 4940 -> 4892
~ -[GVGraphPart buildRankMaxDims:] : 340 -> 336
~ -[GVGraphPart insertDummiesBetweenRanks:] : 1836 -> 1820
~ ___41-[GVGraphPart insertDummiesBetweenRanks:]_block_invoke : 368 -> 364
~ -[GVGraphPart assignRankCoordinates:separation:] : 508 -> 504
~ -[GVGraphPart currentOrderMap] : 312 -> 308
~ -[GVGraphPart applyOrderMap:] : 292 -> 288
~ -[GVGraphPart improveOrderUsingDirection:randomize:currentCrossings:] : 744 -> 736
~ -[GVGraphPart crossingsWithOrderMap:] : 896 -> 892
~ -[GVGraphPart assignGroupFrames] : 704 -> 700
~ -[GVIntegerMap debugDescription] : 528 -> 524
~ -[GVUIntegerMap maximum] : 292 -> 288
~ -[GVUIntegerMap debugDescription] : 528 -> 524
~ -[GVFloatArray enumerateIndicesAndValues:reverse:] : 404 -> 400
~ -[GVObjectArray _sortedValues] : 396 -> 392
~ -[GVObjectArray enumerateIndicesAndObjects:reverse:] : 404 -> 400
~ -[GVGroup initWithGroup:graph:] : 524 -> 520
~ -[GVGroup allNodes] : 288 -> 284
~ -[GVGroup indexCount] : 288 -> 284
~ -[GVGroup boundingBox] : 488 -> 484
~ -[GVGroup shiftIndexMinTo:] : 472 -> 468
~ -[GVGroup debugDescription] : 1228 -> 1224
~ -[GVLayout clearNodeState] : 356 -> 352
~ -[GVLayout doLayout:] : 2396 -> 2380
~ -[GVLayout buildRankObjectArray] : 1072 -> 1056
~ -[GVLayout optimizeOrder] : 800 -> 788
~ -[GVLayout buildGroupInfos] : 788 -> 784
~ -[GVLayout enforceGroupContiguity:] : 1368 -> 1356
~ -[GVLayout medianSort:withRespectTo:] : 612 -> 608
~ -[GVLayout weightedMedian:] : 488 -> 480
~ -[GVLayout assignNodePriorities] : 1136 -> 1120
~ -[GVLayout initializeNodeCoordinates] : 760 -> 752
~ -[GVLayout medianPosition:] : 460 -> 452
~ -[GVLayout packCut:] : 1256 -> 1240
~ -[GVLayout straighten] : 1544 -> 1524
~ -[GVLayout improveNodeCoordinatesWithinGroups:] : 2564 -> 2552
~ -[GVLayout assignRankCoordinates:] : 1856 -> 1844
~ -[GVLayout adjustCoordinatesForGroups] : 1680 -> 1672
~ -[GVLayout drawAllNodes:of:] : 304 -> 300
~ -[GVLayout drawAllGroups:of:] : 904 -> 900
~ -[GVLayout render:] : 560 -> 552
```
