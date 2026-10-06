## JournalShareExtension

> `/private/var/staged_system_apps/Journal.app/PlugIns/JournalShareExtension.appex/JournalShareExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf8f78` | `0xf6c04` | **`-0x2374`** |
| `__DATA.__objc_data` | `0x7f88` | `0x7c88` | **`-0x300`** |
| `__DATA.__bss` | `0x66f0` | `0x6510` | **`-0x1e0`** |
| `__TEXT.__oslogstring` | `0x24bd` | `0x22dd` | **`-0x1e0`** |
| `__DATA_CONST.__const` | `0x4e98` | `0x4ce0` | **`-0x1b8`** |
| `__TEXT.__objc_methname` | `0x695d` | `0x6a8d` | **`+0x130`** |
| `__TEXT.__eh_frame` | `0x4c68` | `0x4b40` | **`-0x128`** |
| `__TEXT.__cstring` | `0x25c4` | `0x24b4` | **`-0x110`** |
| `__TEXT.__swift5_typeref` | `0x2b2c` | `0x2bf4` | **`+0xc8`** |
| `__TEXT.__swift5_capture` | `0xf3c` | `0xe94` | **`-0xa8`** |
| `__TEXT.__objc_stubs` | `0x4da0` | `0x4e20` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x2818` | `0x2798` | **`-0x80`** |
| `__TEXT.__objc_methtype` | `0x1b05` | `0x1b67` | **`+0x62`** |
| `__DATA.__objc_selrefs` | `0x1a80` | `0x1ae0` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x4050` | `0x40b0` | **`+0x60`** |
| `__DATA.__data` | `0x5dc0` | `0x5d68` | **`-0x58`** |
| `__TEXT.__objc_methlist` | `0x1464` | `0x14bc` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0x3d6c` | `0x3d28` | **`-0x44`** |
| `__DATA_CONST.__auth_got` | `0x2030` | `0x2060` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x1a21` | `0x19f1` | **`-0x30`** |
| `__DATA.__objc_const` | `0x47a8` | `0x47c8` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0xe28` | `0xe08` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x12e0` | `0x1300` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x1e8c` | `0x1e70` | **`-0x1c`** |
| `__TEXT.__const` | `0x6214` | `0x6224` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0x1495` | `0x1485` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x3c0` | `0x3b0` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x35c` | `0x368` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x168` | `0x170` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x1e8` | `0x1f0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x25c` | `0x258` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-89.0.0.0.0
+94.0.0.0.0

-  Functions: 3152
-  Symbols:   502
-  CStrings:  1716
+  Functions: 3137
+  Symbols:   505
+  CStrings:  1714
Symbols:
+ _MKMapItemTypeIdentifier
+ _NSItemProviderErrorDomain
+ _OBJC_CLASS_$_HKCategoryType
+ _OBJC_CLASS_$_LPMapMetadata
+ _OBJC_CLASS_$_MKMapItemIdentifier
+ _OBJC_CLASS_$_MKMapItemRequest
+ _kCGImageSourceShouldCache
+ _swift_continuation_resume
- _CGSizeEqualToSize
- _OBJC_CLASS_$_HKSampleType
- _swift_bridgeObjectRetain_n
- _swift_release_x10
- _swift_task_future_wait_throwing
CStrings:
+ "EntryUndoManager.redo()"
+ "EntryViewModel: reducing textLength stored property value of (%ld) to Int16.max (%hd)"
+ "Failed to fetch string: %@"
+ "MindfulnessManager - Pause Session"
+ "MindfulnessManager - Stop Session"
+ "Process is being suspended while logging mindfulness session"
+ "Unhandled itemProvider: %@"
+ "_canvasIdleTracker"
+ "_coordinate"
+ "_firstLocalizedCategoryName"
+ "_mindfulnessManager"
+ "addressComponents"
+ "addressRepresentations"
+ "category"
+ "city"
+ "cityName"
+ "didShowMindfulMinuteHealthPermission"
+ "didShowStateOfMindHealthPermission"
+ "getMapItemWithCompletionHandler:"
+ "initWithIdentifierString:"
+ "initWithMapItemIdentifier:"
+ "initWithObject:"
+ "invalidateLayoutWithContext:"
+ "isRedoing"
+ "isUndoing"
+ "keyPathsForValuesAffectingDidShowMindfulMinuteHealthPermission"
+ "keyPathsForValuesAffectingDidShowStateOfMindHealthPermission"
+ "keyPathsForValuesAffectingHasSeenBothHealthTCCs"
+ "persistentStoreCoordinator"
+ "prepareForDisplayWithCompletionHandler:"
+ "redo"
+ "setDidShowMindfulMinuteHealthPermission:"
+ "setDidShowStateOfMindHealthPermission:"
+ "setGroupsByEvent:"
+ "setPersistentStoreCoordinator:"
+ "setTextLength:"
+ "street"
+ "v16@?0@\"UIImage\"8"
+ "v24@?0@\"MKMapItem\"8@\"NSError\"16"
- "(purgeCache) Infinite loop, exiting"
- "(purgeCache) unable to get assetId from an asset"
- "(removeUndoablyDeletedAssets) assets.count: %ld assetsToRemove.count: %ld from entry %{public}s. Removing ids: %{public}s"
- "An unknown exception occurred."
- "Couldn't create a HKCategoryType of type .mindfulSession"
- "Couldn't create a HKSampleType for %s"
- "Delete data from url error: %@"
- "Deleting %s attachment directory: %s"
- "Error deleting %s attachments directory %s: %@"
- "Failed to fetch image file URL: %@"
- "Failed to fetch string: %s"
- "Failed to parse image properties from the passed data / image source."
- "JournalEntryAssetMO"
- "Move Asset undo/redo button label"
- "Sleep task was canceled"
- "The mindful minutes flag is turned off, or the user hasn't seen the mindfulMinutes TCC yet so no mindfulness sessions will be recorded"
- "_placeholderLabel"
- "assetsFileManager"
- "attachmentIdsMissingFile"
- "authorizationStatusForType:"
- "backgroundingSemaphore"
- "canvasIdleTracker"
- "categoryTypeForIdentifier:"
- "com.apple.journal.mindfulnessManager"
- "didShowMindfulMinuteHealthPermissionKey"
- "didShowStateOfMindHealthPermissionKey"
- "initWithData:"
- "isUndoablyDeleted"
- "loadItemForTypeIdentifier:options:completionHandler:"
- "mindfulnessManager"
- "removeAssetsObject:"
- "setAttributedPlaceholder:"
- "setBundleDate:"
- "setBundleEndDate:"
- "setBundleId:"
- "setHasSeenBothHealthTCCs:"
- "setIsRemovedFromCloud:"
- "setParentContext:"
- "stateOfMindType"
- "undoManager"
- "v24@?0@\"<NSSecureCoding>\"8@\"NSError\"16"
```
