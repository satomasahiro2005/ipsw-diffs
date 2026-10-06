## DeviceRecoveryBrainSupport

> `/System/Library/PrivateFrameworks/DeviceRecoveryBrainSupport.framework/DeviceRecoveryBrainSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b648` | `0x1b62c` | **`-0x1c`** |

### Same-size Content Changes

- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_selrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-142.0.0.0.0
+144.0.0.0.0
Functions:
~ _DRENVRAMValueToString : 452 -> 448
~ _DREGetNVRAMAll : 564 -> 560
~ -[DeviceRecoveryBrain filesInDirectory:withPrefix:extension:excludeSymlinks:] : 920 -> 912
~ -[DeviceRecoveryBrain scanForTestFiles] : 1304 -> 1300
~ -[DeviceRecoveryBrain recoverTestFiles] : 2048 -> 2044
~ -[DeviceRecoveryBrainSpaceManager freeSpaceOnMainContainerTillThreshold:] : 1632 -> 1628
~ -[DeviceRecoveryBrainSpaceManager cleanupUpdateVolume] : 1136 -> 1128
~ -[DeviceRecoveryBrainSpaceManager cleanupMobileAssets] : 1536 -> 1528
~ +[LPStaticAPFSContainer allAPFSContainers] : 412 -> 408
~ +[LPStaticAPFSContainer _containerWithPhysticalStoreRole:] : 564 -> 560
~ -[LPStaticAPFSPhysicalStore parent] : 708 -> 704
~ +[LPStaticAPFSVolume _loadMountPointTableForMode:] : 276 -> 284
~ +[LPStaticAPFSVolume enumerateRoleMetadataUsingBlock:] : 84 -> 100
~ -[LPStaticAPFSVolume snapshotMountPoints] : 732 -> 744
~ -[LPStaticAPFSVolume unmountWithOptions:error:] : 2900 -> 2896
~ -[LPStaticAPFSVolume snapshotsWithError:] : 380 -> 376
~ -[LPStaticAPFSVolume deleteSnapshots:waitForDeletionFor:error:] : 1532 -> 1528
~ +[LPStaticMedia snapshotNameForMediaForPath:] : 1672 -> 1668
~ -[LPStaticMedia mountPoint] : 224 -> 240
~ ___50+[LPStaticMedia(Private) contentTypeToSubclassMap]_block_invoke : 588 -> 584
~ +[LPStaticPartitionMedia primaryMedia] : 348 -> 344
```
