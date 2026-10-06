## MediaStream

> `/System/Library/PrivateFrameworks/MediaStream.framework/MediaStream`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15710` | `0x15be4` | **`+0x4d4`** |
| `__DATA_CONST.__got` | `0x5b0` | `0x5d0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x788` | `0x7a0` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x22b0` | `0x22a8` | **`-0x8`** |
| `__DATA.__bss` | `0x28` | `0x30` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x170` | `0x168` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x19c4` | `0x19cc` | **`+0x8`** |

### Other Changes

```diff

-910.21.101.0.0
+910.27.103.0.0

-  Functions: 612
-  Symbols:   1342
+  Functions: 614
+  Symbols:   1348
Symbols:
+ -[MSASConnection cancelMigrationToCPLForAlbumWithGUID:personID:clientVersion:completionBlock:]
+ -[MSASConnection completeMigrationToCPLForAlbumWithGUID:personID:clientVersion:sourceAssetCount:destinationAssetCount:completionBlock:]
+ -[MSASConnection failMigrationToCPLForAlbumWithGUID:migrationError:personID:clientVersion:completionBlock:]
+ -[MSASConnection initiateMigrationToCPLForAlbumWithGUID:personID:isSilentMigration:clientVersion:sourceAssetCount:completionBlock:]
+ -[MSASConnection refreshContentOfAlbumWithGUID:resetSync:personID:completionBlock:]
+ -[MSASConnection unarchiveMigrationToCPLForAlbumWithGUID:personID:clientVersion:completionBlock:]
+ GCC_except_table446
+ GCC_except_table452
+ GCC_except_table457
+ GCC_except_table462
+ GCC_except_table522
+ GCC_except_table571
+ ___107-[MSASConnection failMigrationToCPLForAlbumWithGUID:migrationError:personID:clientVersion:completionBlock:]_block_invoke
+ ___131-[MSASConnection initiateMigrationToCPLForAlbumWithGUID:personID:isSilentMigration:clientVersion:sourceAssetCount:completionBlock:]_block_invoke
+ ___135-[MSASConnection completeMigrationToCPLForAlbumWithGUID:personID:clientVersion:sourceAssetCount:destinationAssetCount:completionBlock:]_block_invoke
+ ___83-[MSASConnection refreshContentOfAlbumWithGUID:resetSync:personID:completionBlock:]_block_invoke
+ ___94-[MSASConnection cancelMigrationToCPLForAlbumWithGUID:personID:clientVersion:completionBlock:]_block_invoke
+ ___97-[MSASConnection unarchiveMigrationToCPLForAlbumWithGUID:personID:clientVersion:completionBlock:]_block_invoke
+ _kMSASClientVersionKey
+ _kMSASDestinationAssetCountKey
+ _kMSASModelRefreshContentOfAlbumWithGUIDWithCompletionFn
+ _kMSASSourceAssetCountKey
- -[MSASConnection cancelMigrationToCPLForAlbumWithGUID:personID:completionBlock:]
- -[MSASConnection completeMigrationToCPLForAlbumWithGUID:personID:completionBlock:]
- -[MSASConnection failMigrationToCPLForAlbumWithGUID:migrationError:personID:completionBlock:]
- -[MSASConnection initiateMigrationToCPLForAlbumWithGUID:personID:isSilentMigration:completionBlock:]
- -[MSASConnection unarchiveMigrationToCPLForAlbumWithGUID:personID:completionBlock:]
- GCC_except_table440
- GCC_except_table450
- GCC_except_table455
- GCC_except_table460
- GCC_except_table520
- GCC_except_table569
- ___100-[MSASConnection initiateMigrationToCPLForAlbumWithGUID:personID:isSilentMigration:completionBlock:]_block_invoke
- ___80-[MSASConnection cancelMigrationToCPLForAlbumWithGUID:personID:completionBlock:]_block_invoke
- ___82-[MSASConnection completeMigrationToCPLForAlbumWithGUID:personID:completionBlock:]_block_invoke
- ___83-[MSASConnection unarchiveMigrationToCPLForAlbumWithGUID:personID:completionBlock:]_block_invoke
- ___93-[MSASConnection failMigrationToCPLForAlbumWithGUID:migrationError:personID:completionBlock:]_block_invoke
```
