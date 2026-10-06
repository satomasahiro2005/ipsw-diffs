## mstreamd

> `/System/Library/PrivateFrameworks/MediaStream.framework/Support/mstreamd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbdec` | `0xc0d0` | **`+0x2e4`** |
| `__TEXT.__objc_methname` | `0x348d` | `0x3552` | **`+0xc5`** |
| `__DATA_CONST.__got` | `0x5a0` | `0x5c0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2220` | `0x2240` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xca0` | `0xca8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-910.21.101.0.0
+910.27.103.0.0

-  Functions: 186
-  Symbols:   280
-  CStrings:  689
+  Functions: 187
+  Symbols:   284
+  CStrings:  690
Symbols:
+ _kMSASClientVersionKey
+ _kMSASDestinationAssetCountKey
+ _kMSASModelRefreshContentOfAlbumWithGUIDWithCompletionFn
+ _kMSASSourceAssetCountKey
Functions:
~ sub_100008954 : 11176 -> 11780
+ sub_10000ca28
CStrings:
+ "cancelMigrationToCPLForAlbumWithGUID:personID:clientVersion:completionBlock:"
+ "completeMigrationToCPLForAlbumWithGUID:personID:clientVersion:sourceAssetCount:destinationAssetCount:completionBlock:"
+ "failMigrationToCPLForAlbumWithGUID:migrationError:personID:clientVersion:completionBlock:"
+ "initiateMigrationToCPLForAlbumWithGUID:personID:isSilentMigration:clientVersion:sourceAssetCount:completionBlock:"
+ "refreshContentOfAlbumWithGUID:resetSync:personID:info:completionBlock:"
+ "unarchiveMigrationToCPLForAlbumWithGUID:personID:clientVersion:completionBlock:"
- "cancelMigrationToCPLForAlbumWithGUID:personID:completionBlock:"
- "completeMigrationToCPLForAlbumWithGUID:personID:completionBlock:"
- "failMigrationToCPLForAlbumWithGUID:migrationError:personID:completionBlock:"
- "initiateMigrationToCPLForAlbumWithGUID:personID:isSilentMigration:completionBlock:"
- "unarchiveMigrationToCPLForAlbumWithGUID:personID:completionBlock:"
```
