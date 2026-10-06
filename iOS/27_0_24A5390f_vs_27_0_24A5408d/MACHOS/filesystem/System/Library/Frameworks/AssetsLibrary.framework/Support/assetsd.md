## assetsd

> `/System/Library/Frameworks/AssetsLibrary.framework/Support/assetsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1827c` | `0x18ecc` | **`+0xc50`** |
| `__TEXT.__oslogstring` | `0x3ff7` | `0x4264` | **`+0x26d`** |
| `__TEXT.__objc_methname` | `0x563c` | `0x5851` | **`+0x215`** |
| `__TEXT.__objc_stubs` | `0x4ac0` | `0x4ca0` | **`+0x1e0`** |
| `__DATA.__objc_const` | `0x2cd8` | `0x2dc8` | **`+0xf0`** |
| `__TEXT.__gcc_except_tab` | `0x554` | `0x624` | **`+0xd0`** |
| `__DATA.__objc_selrefs` | `0x1490` | `0x1508` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0xe14` | `0xe74` | **`+0x60`** |
| `__DATA.__objc_data` | `0xdc0` | `0xe10` | **`+0x50`** |
| `__DATA_CONST.__objc_intobj` | `0x78` | `0xa8` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x6e1` | `0x70b` | **`+0x2a`** |
| `__DATA_CONST.__const` | `0xf10` | `0xf38` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0xb60` | `0xb80` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x700` | `0x720` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x548` | `0x568` | **`+0x20`** |
| `__DATA_CONST.__objc_arrayobj` | `0x30` | `0x48` | **`+0x18`** |
| `__TEXT.__cstring` | `0x175e` | `0x1776` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x30` | `0x40` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xb40` | `0xb50` | **`+0x10`** |
| `__TEXT.__const` | `0x110` | `0x120` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x5b0` | `0x5b8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x160` | `0x168` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-910.33.102.0.0
+912.0.111.0.0

-  Functions: 358
-  Symbols:   416
-  CStrings:  1257
+  Functions: 366
+  Symbols:   421
+  CStrings:  1283
Symbols:
+ _NSURLIsSymbolicLinkKey
+ _OBJC_CLASS_$_PLAssetsdMigrationService
+ _OBJC_CLASS_$_PLPhotoLibraryPathManagerCore
+ _OBJC_CLASS_$_PLPhotoLibrarySearchCriteria
+ _PLIsErrorOrUnderlyingErrorFileNotFound
CStrings:
+ "Cannot stat File Provider cache file %@, error: %d"
+ "Failed to create enumerator for File Provider cache directory: %@"
+ "Failed to enumerate File Provider cache entry at URL: %@, error: %@"
+ "File Provider Storage"
+ "File Provider cache cleanup complete: removed %tu of %tu entries"
+ "File Provider cache cleanup: Failed to cleanup path %@. Error: %@"
+ "File Provider cache cleanup: Skipping file path cleanup %@"
+ "PLFileProviderCacheCleanupMaintenanceTask"
+ "Refusing to run File Provider cache cleanup, unexpected document storage URL: %@"
+ "Skipping File Provider cache cleanup, unable to resolve document storage URL: %@"
+ "URLByDeletingLastPathComponent"
+ "Unable to determine relationship of File Provider cache URL %@ to its parent %@: %@"
+ "_allKnownLibraryURLs"
+ "_cleanUpFileProviderCacheAtURL:transaction:"
+ "_isSaneFileProviderCacheRootURL:"
+ "_registeredCriticalMaintenanceTaskClasses"
+ "_shouldRemoveFileProviderCacheFileAtURL:"
+ "addObjectsFromArray:"
+ "allWellKnownAppDomainLibraryContainerIdentifiers"
+ "dateWithTimeIntervalSince1970:"
+ "deactivateFromOperationWithInvalidationError:asyncNodeCleanupBlock:"
+ "enabledFeatureDataclasses"
+ "findPhotoLibraryIdentifiersMatchingSearchCriteria:error:"
+ "getRelationship:ofDirectoryAtURL:toItemAtURL:error:"
+ "orderedSet"
+ "photosFileProviderManagerDocumentStorageURL:"
+ "setContainerIdentifier:"
+ "setDomain:"
- "_registeredCriticalMaintenaceTaskClasses"
- "deactivateWithInvalidationError:"
```
