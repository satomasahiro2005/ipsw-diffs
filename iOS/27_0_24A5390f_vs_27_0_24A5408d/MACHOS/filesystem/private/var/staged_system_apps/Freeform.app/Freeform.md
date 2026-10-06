## Freeform

> `/private/var/staged_system_apps/Freeform.app/Freeform`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1454144` | `0x1465bd8` | **`+0x11a94`** |
| `__TEXT.__cstring` | `0xc5ca5` | `0xc6935` | **`+0xc90`** |
| `__TEXT.__unwind_info` | `0x43c98` | `0x443d8` | **`+0x740`** |
| `__TEXT.__eh_frame` | `0x57a8c` | `0x5813c` | **`+0x6b0`** |
| `__TEXT.__swift5_typeref` | `0x37aa2` | `0x37bc2` | **`+0x120`** |
| `__DATA.__bss` | `0x8b148` | `0x8b048` | **`-0x100`** |
| `__TEXT.__swift5_capture` | `0x11c50` | `0x11d50` | **`+0x100`** |
| `__DATA.__data` | `0x503d8` | `0x50478` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x56f98` | `0x57030` | **`+0x98`** |
| `__TEXT.__const` | `0x79b14` | `0x79b84` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x24165` | `0x241d5` | **`+0x70`** |
| `__TEXT.__objc_stubs` | `0x6c4a0` | `0x6c500` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x10f90` | `0x10fe0` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x3f30` | `0x3f74` | **`+0x44`** |
| `__TEXT.__objc_methname` | `0xc9109` | `0xc90c9` | **`-0x40`** |
| `__DATA.__objc_const` | `0x9c5d0` | `0x9c598` | **`-0x38`** |
| `__TEXT.__swift_as_ret` | `0x17ec` | `0x1820` | **`+0x34`** |
| `__DATA_CONST.__auth_got` | `0x87e0` | `0x8808` | **`+0x28`** |
| `__DATA.__objc_data` | `0x4d448` | `0x4d468` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x817d8` | `0x817b8` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x2078c` | `0x20770` | **`-0x1c`** |
| `__DATA.__objc_selrefs` | `0x253f8` | `0x25410` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x1444` | `0x145c` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x387fc` | `0x387e8` | **`-0x14`** |
| `__TEXT.__swift5_builtin` | `0xbcc` | `0xbe0` | **`+0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x6d10` | `0x6d08` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0x204` | `0x20c` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x4f78` | `0x4f70` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x38c8` | `0x38c4` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-653.0.0.0.3
+656.2.1.0.0

-  Functions: 91522
-  Symbols:   7828
-  CStrings:  48719
+  Functions: 91619
+  Symbols:   7834
+  CStrings:  48742
Symbols:
+ _$s7SwiftUI31_IndefiniteSymbolEffectModifierVAA04ViewF0AAWP
+ _$s8PaperKit30FreehandWritingToolsControllerC06canceldE0yyF
+ _$s8PaperKit30FreehandWritingToolsControllerC07writingE9TextInputSo06UITextI0_So6UIViewCXcSgvg
+ _$s8PaperKit30FreehandWritingToolsControllerC16isCampoSupportedSbvg
+ _$sScG4next9isolationxSgScA_pSgYi_tYaF
+ _$sScG4next9isolationxSgScA_pSgYi_tYaFTu
+ _$sScG9cancelAllyyF
+ _swift_release_x11
- _$s7SwiftUI31_IndefiniteSymbolEffectModifierVAA04ViewF0AAMc
- _$ss17__CocoaDictionaryV8IteratorC7nextKeyyXlSgyF
CStrings:
+ "$__lazy_storage_$_editModeToolbarButtonToUndeleteSelectedItems"
+ "%@ and %ld others"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Freeform/src/freeform/Source/MediaLibrary/CRLMediaLibraryAssetBoardItemProvider.swift"
+ "1 or more boards you’re moving have the same name as an existing board in this location. Duplicate names will be appended with a number."
+ "1 or more folders you’re moving have the same name as an existing folder in this location. Duplicate names will be appended with a number."
+ "1 or more items you’re moving have the same name as an existing item in this location. Duplicate names will be appended with a number."
+ "<%{public}@> About to directly send ckZone modifications in %d batch(es)"
+ "<%{public}@> Enqueuing batch %d/%d, saves %{public}@, deletes %{public}@"
+ "<%{public}@> _directlyUploadZoneChanges per database result finished for %{public}@"
+ "<%{public}@> _directlyUploadZoneChanges to private db started for %{public}@"
+ "<%{public}@> _directlyUploadZoneChanges to shared db started for %{public}@"
+ "<%{public}@> sendZoneChangesTimeoutTask fired for batch %d/%d: %{public}@"
+ "A copy of the shared board will be moved."
+ "A copy of the shared board will be moved. You’ll lose access to the original and it will be deleted from all of your devices. To rejoin, use the link you were invited with."
+ "A copy of the shared folder will be moved."
+ "A copy of the shared folder will be moved. You’ll lose access to the original and it will be deleted from all of your devices. To rejoin, use the link you were invited with."
+ "Attempting to hideFromRecentlyDeleted but viewModel is nil for %{public}@"
+ "Board library command execution failed"
+ "Board library command execution failed with error %{public}@ <%@>"
+ "Can’t Move Folder"
+ "Can’t Move Folders"
+ "Command execution failed with error %{public}@ <%@>"
+ "Copies of the shared boards will be moved."
+ "Copies of the shared boards will be moved. You’ll lose access to the original boards and they will be deleted from all of your devices. To rejoin, use the links you were invited with."
+ "Copies of the shared folders will be moved."
+ "Copies of the shared folders will be moved. You’ll lose access to the original folders and they will be deleted from all of your devices. To rejoin, use the links you were invited with."
+ "Copies of the shared items will be moved."
+ "Copies of the shared items will be moved. You’ll lose access to the original items and they will be deleted from all of your devices. To rejoin, use the links you were invited with."
+ "Could not create CRLImageItemImporter for media library asset; inserting image without a thumbnail"
+ "Finished moving persisted cache into data model for %{public}@"
+ "Freeform is limited to 5 levels of folders."
+ "Hiding folder %{public}@ during hierarchy construction due to HFRD flag"
+ "It will be deleted from all of your devices. This action cannot be undone."
+ "It will be deleted from all of your devices. To rejoin this shared board, tap the link you were invited with."
+ "It will be deleted from all of your devices. To rejoin this shared folder, tap the link you were invited with."
+ "It will be permanently deleted from this device. This action cannot be undone."
+ "Move UI – first item name and count of other same-type items"
+ "Other people will no longer have access to it and it will be deleted from all of their devices. This action cannot be undone."
+ "Other people will no longer have access to them and they will be deleted from all of their devices. This action cannot be undone."
+ "Others will be able to recover or permanently delete subfolders and boards they belong to from the Recently Deleted folder for 30 days."
+ "Permanently Delete Boards?"
+ "Permanently Delete Folders?"
+ "Permanently Delete Items?"
+ "Remove from Folder"
+ "Setting hideFromRecentlyDeleted for a folder which does not yet have a directTTL set (likely inheritedly deleted): %{public}@"
+ "They include shared items. If you permanently delete these folders, other people will no longer have access to these items and they will be deleted from all of their devices. This action cannot be undone."
+ "They will be deleted from all of your devices. This action cannot be undone."
+ "They will be deleted from all of your devices. To rejoin these shared boards, tap the links you were invited with."
+ "They will be deleted from all of your devices. To rejoin these shared folders, tap the links you were invited with."
+ "They will be permanently deleted from this device. This action cannot be undone."
+ "This folder is unsupported and can’t be opened because it was edited in a newer version of Freeform and has unsupported features."
+ "This folder is unsupported because it was edited in a newer version of Freeform and has unsupported features. To open it, you’ll need to update iOS in Settings."
+ "This folder is unsupported because it was edited in a newer version of Freeform and has unsupported features. To open it, you’ll need to update iPadOS in Settings."
+ "You’ll no longer belong to these boards, but will still have access to them in Recently Deleted because you belong to a parent folder. To rejoin these shared boards, tap the links you were invited with."
+ "You’ll no longer belong to these folders, but will still have access to them in Recently Deleted because you belong to a parent folder. To rejoin these shared folders, tap the links you were invited with."
+ "You’ll no longer belong to these items, but will still have access to them in Recently Deleted because you belong to a parent folder. To rejoin these shared items, tap the links you were invited with."
+ "You’ll no longer belong to this board, but will still have access to it in Recently Deleted because you belong to a parent folder. To rejoin this shared board, tap the link you were invited with."
+ "You’ll no longer belong to this folder, but will still have access to it in Recently Deleted because you belong to a parent folder. To rejoin this shared folder, tap the link you were invited with."
+ "_executeSingleZoneModifyOperation(saves:deletes:uploadingZones:toDatabase:)"
+ "_setDisplayedShareIsOwnRoot:"
+ "beginEditingAtPoint:inputType:"
+ "cancelWritingTools"
+ "dismissPresentedManageShareUI()"
+ "effectiveTTL is server-derived, client may only clear a board's zone effectiveTTL to nil, never set it to a non-nil value"
+ "effectiveTTL is server-derived, client may only clear a folder's zone effectiveTTL to nil, never set it to a non-nil value"
+ "hideItemsFromRecentlyDeleted(foldersToHide:boardsToHide:)"
+ "importBoardItem(using:accessibilityLabel:)"
+ "isEraserInk"
+ "isProcessingPickerDidSelect"
+ "isWritingToolsCampoSupported"
+ "p_notifyObserversOfAzimuthChange"
+ "purgeDeleted should only be called within the Recently Deleted hierarchy"
+ "reportFailure(_:)"
+ "toolkitDidUpdateCurrentToolAzimuth"
- "1 or more boards you’re moving has the same name as an existing board in this location. Duplicate names will be appended with a number."
- "1 or more folders you’re moving has the same name as an existing folder in this location. Duplicate names will be appended with a number."
- "1 or more items you’re moving has the same name as an existing item in this location. Duplicate names will be appended with a number."
- "<%{public}@> About to directly send ckZone modifications, saves %{public}@, deletes %{public}@"
- "<%{public}@> Beginning Task for _sendZoneChanges for %{public}@"
- "<%{public}@> _sendZoneChanges called but no zoneChangesToSend generated"
- "<%{public}@> _sendZoneChanges called while an operation is ongoing, adding to pending queue: %{public}@"
- "<%{public}@> sendZoneChangesTask was cancelled, ignoring results: %{public}@"
- "<%{public}@> sendZoneChangesTimeoutTask fired for %{public}@"
- "Action decision - Alert title for permanently deleting multiple deleted boards title"
- "Action decision - Alert title for permanently deleting multiple deleted folders title"
- "Action decision - Alert title for permanently deleting multiple deleted items title"
- "Board library command execution failed with error %@"
- "Client should not be changing a board's zone effectiveTTL"
- "Client should not be changing a folder's effectiveTTL"
- "Command execution failed with error %@"
- "Depth Limit Reached"
- "Folders can only be nested 5 levels deep."
- "If you delete these shared boards, they will be deleted from all of your devices. To rejoin, tap the link you were invited with."
- "If you delete these shared folders, they will be deleted from all of your devices. To rejoin, tap the link you were invited with."
- "If you delete this shared board, it will be deleted from all of your devices. To rejoin, tap the link you were invited with."
- "If you delete this shared folder, it will be deleted from all of your devices. To rejoin, tap the link you were invited with."
- "Permanently Delete %lu Boards?"
- "Permanently Delete %lu Folders?"
- "Permanently Delete %lu Items?"
- "Remove from \"%@\""
- "Setting hideFromRecentlyDeleted for a folder which does not yet have a ttl set: %{public}@"
- "These boards will be deleted from all your devices. You can’t undo this action."
- "These boards will be permanently deleted. You can’t undo this action."
- "These folders will be deleted from all your devices. You can’t undo this action."
- "These folders will be permanently deleted. You can’t undo this action."
- "These items will be deleted from all your devices. You can’t undo this action."
- "These items will be permanently deleted. You can’t undo this action."
- "This board will be deleted from all your devices. You can’t undo this action."
- "This board will be permanently deleted. You can’t undo this action."
- "This folder can’t be opened because it was edited in a newer version of Freeform and has unsupported features. To open it, you’ll need to update iOS in Settings."
- "This folder can’t be opened because it was edited in a newer version of Freeform and has unsupported features. To open it, you’ll need to update iPadOS in Settings."
- "This folder will be deleted from all your devices. You can’t undo this action."
- "This folder will be permanently deleted. You can’t undo this action."
- "To open this folder, use Freeform on a newer iPad model."
- "To open this folder, use Freeform on a newer iPhone model."
- "beginEditingAtPoint:"
- "handleShowInEnclosingFolder()"
- "inflightZoneChanges"
- "mLastProcessedPathSource"
- "ongoingSendZoneChangesOperation"
- "pendingZoneChanges"
- "sendZoneChangesTask"
- "sendZoneChangesTimeoutTask"
- "sf_brightenedColor"
- "systemDarkBlueColor"
```
