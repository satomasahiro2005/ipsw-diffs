## IOAccelMemoryInfo

> `/System/Library/PrivateFrameworks/IOAccelMemoryInfo.framework/IOAccelMemoryInfo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x53f8` | `0x5398` | **`-0x60`** |

### Other Changes

```diff
Symbols:
+ __ZNSt3__127__tree_balance_after_insertB9fqe220106IPNS_16__tree_node_baseIPvEEEEvT_S5_
+ __ZNSt3__13setIiNS_4lessIiEENS_9allocatorIiEEE6insertB9fqe220106ERKi
+ __ZNSt3__16__treeIiNS_4lessIiEENS_9allocatorIiEEE14__tree_deleterclB9fqe220106EPNS_11__tree_nodeIiPvEE
- __ZNSt3__127__tree_balance_after_insertB9fqe220100IPNS_16__tree_node_baseIPvEEEEvT_S5_
- __ZNSt3__13setIiNS_4lessIiEENS_9allocatorIiEEE6insertB9fqe220100ERKi
- __ZNSt3__16__treeIiNS_4lessIiEENS_9allocatorIiEEE14__tree_deleterclB9fqe220100EPNS_11__tree_nodeIiPvEE
Functions:
~ +[IOAccelMemoryInfo collectDataWithCompletionQueue:completionBlock:] : 1208 -> 1204
~ ___68+[IOAccelMemoryInfo collectDataWithCompletionQueue:completionBlock:]_block_invoke_3 : 660 -> 656
~ ___68+[IOAccelMemoryInfo collectDataWithCompletionQueue:completionBlock:]_block_invoke_4 : 1892 -> 1872
~ +[IOAccelMemoryInfo newKernelAllocationList:] : 1772 -> 1768
~ +[IOAccelMemoryInfo validateDictionary:] : 732 -> 728
~ __ZL13validateArrayP12NSDictionaryP8NSStringP10objc_classbb : 572 -> 564
~ -[IOAccelMemoryInfo processIDs] : 312 -> 308
~ -[IOAccelMemoryInfo blamedProcesses] : 460 -> 456
~ -[IOAccelMemoryInfo blamedProcessesForProcess:] : 492 -> 488
~ -[IOAccelMemoryInfo mappings] : 612 -> 608
~ -[IOAccelMemoryInfo openglObjects] : 1016 -> 1012
~ -[IOAccelMemoryInfo openclObjects] : 724 -> 720
~ -[IOAccelMemoryInfo formattedDescriptions] : 588 -> 580
~ __ZL22validateAllocationListP7NSArray : 236 -> 232
~ __ZL26addIdentifiersInEntryToSetP12NSMutableSetP12NSDictionary : 252 -> 248
~ __ZL17createMergedEntryP12NSDictionaryS0_ : 1464 -> 1452
```
