## MobileNotes

> `/private/var/staged_system_apps/MobileNotes.app/MobileNotes`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4cb94c` | `0x4ccc7c` | **`+0x1330`** |
| `__TEXT.__eh_frame` | `0x16cdc` | `0x17210` | **`+0x534`** |
| `__TEXT.__objc_methname` | `0x53c87` | `0x54107` | **`+0x480`** |
| `__TEXT.__objc_stubs` | `0x36ec0` | `0x370e0` | **`+0x220`** |
| `__TEXT.__oslogstring` | `0xe536` | `0xe376` | **`-0x1c0`** |
| `__TEXT.__unwind_info` | `0x10de8` | `0x10f50` | **`+0x168`** |
| `__DATA_CONST.__got` | `0x30c8` | `0x31b0` | **`+0xe8`** |
| `__TEXT.__objc_methlist` | `0x19e04` | `0x19edc` | **`+0xd8`** |
| `__DATA.__objc_const` | `0x29750` | `0x29820` | **`+0xd0`** |
| `__DATA.__objc_selrefs` | `0x11568` | `0x11610` | **`+0xa8`** |
| `__TEXT.__gcc_except_tab` | `0x36d4` | `0x377c` | **`+0xa8`** |
| `__TEXT.__objc_methtype` | `0xade9` | `0xae29` | **`+0x40`** |
| `__TEXT.__const` | `0x1df94` | `0x1dfc4` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0xa8e0` | `0xa8c0` | **`-0x20`** |
| `__DATA.__data` | `0x117a4` | `0x11794` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x7e40` | `0x7e30` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x10f4` | `0x1100` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x3f30` | `0x3f28` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x26c8` | `0x26d0` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x4dcc` | `0x4dd0` | **`+0x4`** |
| `__TEXT.__swift5_typeref` | `0x10758` | `0x10754` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__objc_classname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_replace`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2991.0.0.0.0
+2996.0.0.0.0

-  Functions: 23276
-  Symbols:   4345
-  CStrings:  16970
+  Functions: 23326
+  Symbols:   4343
+  CStrings:  16993
Symbols:
+ _$sScMs11GlobalActorsMc
+ _OBJC_CLASS_$_UITraitSplitViewControllerLayoutEnvironment
- _OBJC_CLASS_$_ICThumbnailDescription
- _kICSearchIndexingVersionKey
- _kICSpotlightClientStateDataKey
- _memset
CStrings:
+ "Cannot present Manage Shared Folder UI from Request Access deeplink: compact-column presenter not visible after didShow."
+ "Cannot present Manage Shared Note UI from Request Access deeplink: compact-column presenter not visible after didShow."
+ "T@?,C,N,V_compactNavigationDidShowViewControllerBlock"
+ "TB,N,GisExpandedSplitView,V_expandedSplitView"
+ "TB,N,V_modernResultsOnly"
+ "U"
+ "_compactNavigationDidShowViewControllerBlock"
+ "_expandedSplitView"
+ "_modernResultsOnly"
+ "compactNavigationDidShowViewControllerBlock"
+ "compactTopViewController"
+ "determineIfReindexIsNeededFromClientStateWithCompletionHandler:"
+ "expandedSplitView"
+ "hasAnyVisibleNoteIn:"
+ "hasVisibleNotesInFolder"
+ "ic_presentManageShareForFolder:onViewController:"
+ "ic_presentManageShareForFolderAfterCompactPush:"
+ "ic_presentManageShareForNote:onViewController:"
+ "ic_presentManageShareForNoteAfterCompactPush:"
+ "indexingScope"
+ "isExpandedSplitView"
+ "isWritingToolsAvailable"
+ "migrateSearchIndexVersionIfNeeded"
+ "modernResultsOnly"
+ "objectIDForShareRecordID:context:"
+ "reservedLayoutSize"
+ "selectContainerWithIdentifier:usingRootViewController:deferUntilDataLoaded:animated:dataRenderedBlock:"
+ "selectContainerWithIdentifier:usingRootViewController:deferUntilDataLoaded:animated:ensureSelectedNote:dataRenderedBlock:"
+ "setCompactNavigationDidShowViewControllerBlock:"
+ "setExpandedSplitView:"
+ "setIndexingScope:"
+ "setModernResultsOnly:"
+ "setReservedLayoutSize:"
+ "shouldDeferIndexingInMemoryConstrainedExtension"
+ "v16@?0@\"UIViewController\"8"
+ "v44@0:8@16B24B28B32@?36"
+ "v48@0:8@16B24B28B32B36@?40"
+ "waitForPendingChangeProcessing"
- "%@ no need to delete search indexing before reindexing. updating the indexing version to expected version"
- "App does not need to upgrade the search index although indexing version does not match. Current version = %lu, expected version = %lu. Directly updating the indexing version to expected version"
- "App needs to upgrade the search index because indexing version does not match. Current version = %lu, expected version = %lu"
- "Client State from CoreSpotlight: %@"
- "Client State from defaults: %@"
- "E"
- "Error fetching client state from CoreSpotlight: %@"
- "No client state found from CoreSpotlight."
- "No client state found from defaults."
- "Toggle Fakes Incompatible Devices"
- "clientStateFromCoreSpotlight not equal to clientStateFromDefaults"
- "fetchLastClientStateWithCompletionHandler:"
- "presentCloudSharingUIOnSplitViewControllerWithBlock:"
- "searchableIndex"
- "shouldShowWritingToolsButton"
```
