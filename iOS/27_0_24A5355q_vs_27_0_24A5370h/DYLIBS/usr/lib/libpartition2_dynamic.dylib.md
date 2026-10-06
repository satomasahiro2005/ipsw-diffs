## libpartition2_dynamic.dylib

> `/usr/lib/libpartition2_dynamic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb628` | `0xb638` | **`+0x10`** |

### Other Changes

```diff

-3689.0.0.0.1
+3695.0.0.0.0
Functions:
~ +[LPAPFSContainer allAPFSContainers] : 412 -> 408
~ +[LPAPFSContainer _containerWithPhysticalStoreRole:] : 564 -> 560
~ -[LPAPFSPhysicalStore parent] : 708 -> 704
~ +[LPAPFSVolume _loadMountPointTableForMode:] : 276 -> 284
~ +[LPAPFSVolume enumerateRoleMetadataUsingBlock:] : 84 -> 100
~ -[LPAPFSVolume snapshotMountPoints] : 732 -> 744
~ -[LPAPFSVolume unmountWithOptions:error:] : 2900 -> 2896
~ -[LPAPFSVolume snapshotsWithError:] : 380 -> 376
~ -[LPAPFSVolume deleteSnapshots:waitForDeletionFor:error:] : 1532 -> 1528
~ +[LPMedia snapshotNameForMediaForPath:] : 1672 -> 1668
~ -[LPMedia mountPoint] : 224 -> 240
~ ___44+[LPMedia(Private) contentTypeToSubclassMap]_block_invoke : 588 -> 584
~ +[LPPartitionMedia primaryMedia] : 348 -> 344
```
