## MobileNotes

> `/private/var/staged_system_apps/MobileNotes.app/MobileNotes`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ccc7c` | `0x4d0f24` | **`+0x42a8`** |
| `__TEXT.__oslogstring` | `0xe376` | `0xeaf6` | **`+0x780`** |
| `__TEXT.__objc_methname` | `0x54107` | `0x542e7` | **`+0x1e0`** |
| `__TEXT.__objc_stubs` | `0x370e0` | `0x37280` | **`+0x1a0`** |
| `__DATA.__objc_const` | `0x29820` | `0x29968` | **`+0x148`** |
| `__TEXT.__eh_frame` | `0x17210` | `0x172b8` | **`+0xa8`** |
| `__DATA_CONST.__cfstring` | `0xa8c0` | `0xa960` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x1d1a8` | `0x1d238` | **`+0x90`** |
| `__TEXT.__cstring` | `0x1c29b` | `0x1c32b` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x19edc` | `0x19f64` | **`+0x88`** |
| `__DATA.__objc_selrefs` | `0x11610` | `0x11690` | **`+0x80`** |
| `__TEXT.__ustring` | `0xcec` | `0xd68` | **`+0x7c`** |
| `__TEXT.__const` | `0x1dfc4` | `0x1e034` | **`+0x70`** |
| `__DATA.__data` | `0x11794` | `0x117f4` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x377c` | `0x37d0` | **`+0x54`** |
| `__DATA.__objc_data` | `0xf708` | `0xf758` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x10f50` | `0x10f90` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0x4ceb` | `0x4d0b` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x75c` | `0x77c` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x8e4` | `0x904` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x31b0` | `0x31c8` | **`+0x18`** |
| `__DATA_CONST.__objc_intobj` | `0x318` | `0x330` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x4dd0` | `0x4de8` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x7e30` | `0x7e40` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1100` | `0x110c` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x3f28` | `0x3f30` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x26d0` | `0x26d8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xc90` | `0xc98` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_replace`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-2996.0.0.0.0
+2998.0.0.0.0

-  Functions: 23326
-  Symbols:   4343
-  CStrings:  16993
+  Functions: 23349
+  Symbols:   4348
+  CStrings:  17038
Symbols:
+ _$s10AppIntents11EntityQueryP22displayRepresentations3forSDy0C0_2IDQZAA21DisplayRepresentationVGSayAHG_tYaKFTq
+ _$s10AppIntents11EntityQueryPAAE22displayRepresentations3forSDy0C0_2IDQZAA21DisplayRepresentationVGSayAHG_tYaKF
+ _$s10AppIntents11EntityQueryPAAE22displayRepresentations3forSDy0C0_2IDQZAA21DisplayRepresentationVGSayAHG_tYaKFTu
+ _$s10Foundation17URLResourceValuesV8fileSizeSiSgvg
+ _ICTTAttributeNameGeneratedByWritingTools
+ _NSCommentDocumentAttribute
- _$s10Foundation3URLV11descriptionSSvg
CStrings:
+ "AIGC=1"
+ "Composition completed but no MOV file produced for note ID: %@ attachmentID: %@. Directory contents: %s"
+ "Composition produced a zero-byte MOV %s for note ID: %@ attachmentID: %@. Import would produce empty media."
+ "Composition produced an empty directory for note ID: %@ attachmentID: %@. Nothing to import."
+ "Could not find attachment with ID %@ in note %@. Note has %ld attachments."
+ "Exiting because the database could not be opened. Exit code: %d"
+ "ICRequestShareAccessAlertPresenter"
+ "MOV file for note ID: %@ attachmentID: %@: %s (%ld bytes)"
+ "MOV file is empty (%ld bytes) for note ID: %@ attachmentID: %@. Imported media will be empty."
+ "No composed MOV file found in directory for note ID: %@ attachmentID: %@. Directory contents: %s"
+ "Notes can’t access its data."
+ "Notes can’t be opened right now."
+ "Request Access deeplink couldn't resolve shareRecordID %@"
+ "T@\"NSManagedObject<ICFolderObject>\",R,&,N"
+ "TB,N,V_aigcMarkerDetected"
+ "TB,N,V_disablesIntegratedSuggestions"
+ "This could be because the note was deleted or is not shared with you."
+ "Unable to open database due to error: %@"
+ "Unable to open database due to low disk space. Error: %@"
+ "Your local storage is almost full. Make some space, then try again."
+ "_aigcMarkerDetected"
+ "_didPresentDatabaseOpenErrorAlert"
+ "_disablesIntegratedSuggestions"
+ "aigcMarkerDetected"
+ "audioModel returned nil when creating subattachment for note ID: %@ attachmentID: %@"
+ "call recording composition error: %@ for note ID: %@ attachmentID: %@"
+ "call recording import complete for note ID: %@ attachmentID: %@. Duration: %fs"
+ "call recording import succeeded but media URL is nil for note ID: %@ attachmentID: %@. Subattachment count: %ld"
+ "call transcription unsupported for note ID: %@ attachmentID: %@. Locale: %s"
+ "composition completed for note ID: %@ attachmentID: %@"
+ "composition produced MOV %s (%ld bytes) for note ID: %@ attachmentID: %@"
+ "could not check contents of call recording directory: %@"
+ "could not create subattachment for call recording with note ID: %@ attachmentID: %@. Error: %@"
+ "could not download speech model for call transcription for note ID: %@ attachmentID: %@. Error: %@"
+ "could not remove call recording source file for note ID: %@ attachmentID: %@: %@"
+ "created subattachment for call recording. %s"
+ "databaseOpenError"
+ "databaseOpenFailedDueToLowDiskSpace"
+ "did not parse directory name for call recording: %s"
+ "disablesIntegratedSuggestions"
+ "failed to import call recording metadata from %s: %@"
+ "found call recording file and attachment for note ID: %@ attachmentID: %@"
+ "grammarCheckingType"
+ "importAndDeleteCallRecordingFilesIfNeeded found %ld recording directories"
+ "isSharedViaAccessRequests"
+ "no existing note found during import, creating new call note for note ID: %@ attachmentID: %@"
+ "noteResult.managedObjectContext is unexpectedly nil, not creating ICAddNoteUndoTarget"
+ "objectNotFoundAlertMessage"
+ "objectNotFoundAlertTitle"
+ "presentDatabaseOpenErrorAlertIfNeeded"
+ "presentObjectNotFoundAlertFromViewController:"
+ "re-importing call recording for existing note (missing media) with note ID: %@ attachmentID: %@"
+ "resetSearchController"
+ "reusing existing subattachment without media for note ID: %@ attachmentID: %@"
+ "setAigcMarkerDetected:"
+ "setDisablesIntegratedSuggestions:"
+ "setGrammarCheckingType:"
+ "setStylesTitle:"
+ "skipping import for in-progress recording with note ID: %@ attachmentID: %@"
+ "skipping offline call transcription for note ID: %@ attachmentID: %@. Feature flag enabled: %{bool}d, has media URL: %{bool}d, supports call transcription: %{bool}d"
+ "useAILabeling"
- "Request Access deeplink timed out without resolving shareRecordID %@"
- "T@\"NSManagedObject<ICFolderObject>\",R,C,N"
- "call recording composition error: %@"
- "call recording feature flag not enabled"
- "call transcription not supported for %s"
- "call transcription unsupported."
- "could not check contents of call recording directory"
- "could not create subattachment for call recording with note ID: %@ attachmentID: %@"
- "could not download speech model for call transcription"
- "could not remove call recording:%@"
- "did not parse directory name for call recording"
- "failed to import call recording metadata: %@"
- "found call recording attachment during import for note ID: %@ attachmentID: %@"
- "found call recording file for note ID: %@ attachmentID: %@"
- "importing call recording source file for existing note with note ID: %@ attachmentID: %@"
- "no media on attachment"
```
