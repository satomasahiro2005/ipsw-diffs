## com.apple.MobileSoftwareUpdate.CleanupPreparePathService

> `/System/Library/PrivateFrameworks/MobileSoftwareUpdate.framework/XPCServices/com.apple.MobileSoftwareUpdate.CleanupPreparePathService.xpc/com.apple.MobileSoftwareUpdate.CleanupPreparePathService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__got` | `0x2e0` | `0x2f8` | **`+0x18`** |
| `__TEXT.__text` | `0x29a08` | `0x29a1c` | **`+0x14`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2718.0.2.0.0
+2718.0.5.0.0
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/MobileSoftwareUpdate/install/TempContent/Objects/MobileSoftwareUpdate.build/CleanupPreparePathService.build/Objects-normal/arm64e/common-855ff3e0594266b8bf39e992d8b834f5.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/MobileSoftwareUpdate/install/TempContent/Objects/MobileSoftwareUpdate.build/CleanupPreparePathService.build/Objects-normal/arm64e/common-f356305c0f01cdc643ddd2bd6717b958.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/MobileSoftwareUpdate/install/TempContent/Objects/MobileSoftwareUpdate.build/CleanupPreparePathService.build/Objects-normal/arm64e/common-4e1279833aea10e74fdbfc26932a0f10.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/MobileSoftwareUpdate/install/TempContent/Objects/MobileSoftwareUpdate.build/CleanupPreparePathService.build/Objects-normal/arm64e/common-83263c96618a1efacaa59ffa50b136f8.o
Functions:
~ _handle_message : 504 -> 508
~ ___MSUCleanupPreparePath_block_invoke : 232 -> 228
~ _checkpoint_history_add : 2816 -> 2824
~ _checkpoint_nvram_store_by_id : 272 -> 276
~ _ramrod_get_mount_path : 212 -> 220
```
