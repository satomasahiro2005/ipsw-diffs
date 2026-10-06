## Pasteboard

> `/System/Library/PrivateFrameworks/Pasteboard.framework/Pasteboard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2731c` | `0x27638` | **`+0x31c`** |
| `__DATA_CONST.__const` | `0x1470` | `0x1520` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0xdf0` | `0xe48` | **`+0x58`** |
| `__TEXT.__cstring` | `0x1b4a` | `0x1b8c` | **`+0x42`** |
| `__AUTH_CONST.__cfstring` | `0x1180` | `0x11c0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x2280` | `0x22a0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1538` | `0x1550` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x804` | `0x818` | **`+0x14`** |

### Other Changes

```diff

-9127.0.66.0.0
+9127.0.71.0.0

-  Functions: 1057
-  Symbols:   1792
-  CStrings:  310
+  Functions: 1062
+  Symbols:   1802
+  CStrings:  312
Symbols:
+ -[PBItemRepresentation _loadWithContext:completionBlock:synchronous:]
+ -[PBItemRepresentation loadDataWithContext:completion:synchronous:]
+ -[PBItemRepresentation loadFileCopyWithContext:completion:synchronous:]
+ -[PBItemRepresentation loadOpenInPlaceWithContext:completion:synchronous:]
+ -[PBItemRepresentation performProgressTrackingWithLoaderBlock:onCancelCallback:synchronous:]
+ _PBMetadataAppIntentsPayloadKey
+ _PBMetadataUnmatchedAppEntityPayloadsKey
+ _PBPerformCallback
+ ___67-[PBItemRepresentation loadDataWithContext:completion:synchronous:]_block_invoke
+ ___67-[PBItemRepresentation loadDataWithContext:completion:synchronous:]_block_invoke_2
+ ___67-[PBItemRepresentation loadDataWithContext:completion:synchronous:]_block_invoke_3
+ ___67-[PBItemRepresentation loadDataWithContext:completion:synchronous:]_block_invoke_4
+ ___69-[PBItemRepresentation _loadWithContext:completionBlock:synchronous:]_block_invoke
+ ___69-[PBItemRepresentation _loadWithContext:completionBlock:synchronous:]_block_invoke_2
+ ___69-[PBItemRepresentation _loadWithContext:completionBlock:synchronous:]_block_invoke_3
+ ___69-[PBItemRepresentation _loadWithContext:completionBlock:synchronous:]_block_invoke_4
+ ___69-[PBItemRepresentation _loadWithContext:completionBlock:synchronous:]_block_invoke_5
+ ___69-[PBItemRepresentation _loadWithContext:completionBlock:synchronous:]_block_invoke_6
+ ___69-[PBItemRepresentation _loadWithContext:completionBlock:synchronous:]_block_invoke_7
+ ___71-[PBItemRepresentation loadFileCopyWithContext:completion:synchronous:]_block_invoke
+ ___71-[PBItemRepresentation loadFileCopyWithContext:completion:synchronous:]_block_invoke_2
+ ___71-[PBItemRepresentation loadFileCopyWithContext:completion:synchronous:]_block_invoke_3
+ ___74-[PBItemRepresentation loadOpenInPlaceWithContext:completion:synchronous:]_block_invoke
+ ___74-[PBItemRepresentation loadOpenInPlaceWithContext:completion:synchronous:]_block_invoke_2
+ ___74-[PBItemRepresentation loadOpenInPlaceWithContext:completion:synchronous:]_block_invoke_3
+ ___92-[PBItemRepresentation performProgressTrackingWithLoaderBlock:onCancelCallback:synchronous:]_block_invoke
+ ___92-[PBItemRepresentation performProgressTrackingWithLoaderBlock:onCancelCallback:synchronous:]_block_invoke_2
+ ___92-[PBItemRepresentation performProgressTrackingWithLoaderBlock:onCancelCallback:synchronous:]_block_invoke_3
+ ____coordinatedFileAccess_block_invoke_3
+ ___block_descriptor_41_e8_32bs_e5_v8?0ls32l8
+ ___block_descriptor_48_e8_32s40bs_e15_v16?0"NSURL"8ls32l8s40l8
+ ___block_descriptor_49_e8_32bs40bs_e5_v8?0ls32l8s40l8
+ ___block_descriptor_49_e8_32bs40r_e5_v8?0lr40l8s32l8
+ ___block_descriptor_49_e8_32s40bs_e91_v48?0"NSData"8"PBSecurityScopedURLWrapper"16"PBResponseMetadata"24"NSError"32?<v?>40ls32l8s40l8
+ ___block_descriptor_49_e8_32s40r_e14_v16?0?<v?>8ls32l8r40l8
+ ___block_descriptor_57_e8_32s40bs48bs_e5_v8?0ls40l8s32l8s48l8
+ ___block_descriptor_57_e8_32s40s48bs_e91_v48?0"NSData"8"PBSecurityScopedURLWrapper"16"PBResponseMetadata"24"NSError"32?<v?>40ls32l8s48l8s40l8
+ ___block_descriptor_65_e8_32s40bs48r56r_e5_v8?0lr48l8s40l8s32l8r56l8
+ ___block_descriptor_65_e8_32s40s48bs56bs_e15_v16?0"NSURL"8ls32l8s48l8s40l8s56l8
+ ___block_descriptor_65_e8_32s40s48bs56bs_e27_v24?0"NSURL"8"NSError"16ls32l8s48l8s40l8s56l8
+ ___block_descriptor_73_e8_32s40bs48bs56bs64r_e91_v48?0"NSData"8"PBSecurityScopedURLWrapper"16"PBResponseMetadata"24"NSError"32?<v?>40ls32l8r64l8s40l8s48l8s56l8
+ ___block_descriptor_73_e8_32s40s48bs56bs64r_e33_"NSProgress"16?0?<v??<v?>>8ls32l8s40l8r64l8s48l8s56l8
+ ___block_descriptor_73_e8_32s40s48s56bs64bs_e27_v24?0"NSURL"8"NSError"16ls32l8s40l8s56l8s48l8s64l8
+ ___block_descriptor_81_e8_32s40s48s56s64bs72bs_e5_v8?0ls64l8s32l8s40l8s48l8s56l8s72l8
- -[PBItemRepresentation _loadWithContext:completionBlock:]
- -[PBItemRepresentation performProgressTrackingWithLoaderBlock:onCancelCallback:]
- GCC_except_table46
- ___55-[PBItemRepresentation loadDataWithContext:completion:]_block_invoke
- ___55-[PBItemRepresentation loadDataWithContext:completion:]_block_invoke_2
- ___55-[PBItemRepresentation loadDataWithContext:completion:]_block_invoke_3
- ___55-[PBItemRepresentation loadDataWithContext:completion:]_block_invoke_4
- ___57-[PBItemRepresentation _loadWithContext:completionBlock:]_block_invoke
- ___57-[PBItemRepresentation _loadWithContext:completionBlock:]_block_invoke_2
- ___57-[PBItemRepresentation _loadWithContext:completionBlock:]_block_invoke_3
- ___57-[PBItemRepresentation _loadWithContext:completionBlock:]_block_invoke_4
- ___57-[PBItemRepresentation _loadWithContext:completionBlock:]_block_invoke_5
- ___57-[PBItemRepresentation _loadWithContext:completionBlock:]_block_invoke_6
- ___57-[PBItemRepresentation _loadWithContext:completionBlock:]_block_invoke_7
- ___59-[PBItemRepresentation loadFileCopyWithContext:completion:]_block_invoke
- ___59-[PBItemRepresentation loadFileCopyWithContext:completion:]_block_invoke_2
- ___59-[PBItemRepresentation loadFileCopyWithContext:completion:]_block_invoke_3
- ___62-[PBItemRepresentation loadOpenInPlaceWithContext:completion:]_block_invoke
- ___62-[PBItemRepresentation loadOpenInPlaceWithContext:completion:]_block_invoke_2
- ___62-[PBItemRepresentation loadOpenInPlaceWithContext:completion:]_block_invoke_3
- ___80-[PBItemRepresentation performProgressTrackingWithLoaderBlock:onCancelCallback:]_block_invoke
- ___80-[PBItemRepresentation performProgressTrackingWithLoaderBlock:onCancelCallback:]_block_invoke_2
- ___80-[PBItemRepresentation performProgressTrackingWithLoaderBlock:onCancelCallback:]_block_invoke_3
- ___block_descriptor_48_e8_32bs40bs_e5_v8?0ls32l8s40l8
- ___block_descriptor_48_e8_32s40bs_e91_v48?0"NSData"8"PBSecurityScopedURLWrapper"16"PBResponseMetadata"24"NSError"32?<v?>40ls32l8s40l8
- ___block_descriptor_48_e8_32s40r_e14_v16?0?<v?>8ls32l8r40l8
- ___block_descriptor_56_e8_32s40bs48bs_e5_v8?0ls40l8s32l8s48l8
- ___block_descriptor_56_e8_32s40s48bs_e91_v48?0"NSData"8"PBSecurityScopedURLWrapper"16"PBResponseMetadata"24"NSError"32?<v?>40ls32l8s48l8s40l8
- ___block_descriptor_64_e8_32s40bs48r56r_e5_v8?0lr48l8s40l8s32l8r56l8
- ___block_descriptor_64_e8_32s40s48bs56bs_e15_v16?0"NSURL"8ls32l8s48l8s40l8s56l8
- ___block_descriptor_64_e8_32s40s48bs56bs_e27_v24?0"NSURL"8"NSError"16ls32l8s48l8s40l8s56l8
- ___block_descriptor_72_e8_32s40bs48bs56bs64r_e91_v48?0"NSData"8"PBSecurityScopedURLWrapper"16"PBResponseMetadata"24"NSError"32?<v?>40ls32l8r64l8s40l8s48l8s56l8
- ___block_descriptor_72_e8_32s40s48bs56bs64r_e33_"NSProgress"16?0?<v??<v?>>8ls32l8s40l8r64l8s48l8s56l8
- ___block_descriptor_72_e8_32s40s48s56bs64bs_e27_v24?0"NSURL"8"NSError"16ls32l8s40l8s56l8s48l8s64l8
CStrings:
+ "com.apple.Pasteboard.appIntentsPayload"
+ "unmatchedAppEntityPayloads"
```
