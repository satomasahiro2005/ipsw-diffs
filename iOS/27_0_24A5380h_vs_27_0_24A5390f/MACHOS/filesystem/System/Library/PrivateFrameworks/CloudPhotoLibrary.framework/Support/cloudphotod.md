## cloudphotod

> `/System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/Support/cloudphotod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cc1a0` | `0x1cca40` | **`+0x8a0`** |
| `__TEXT.__objc_methname` | `0x2ad01` | `0x2ad81` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x12690` | `0x126d8` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x10914` | `0x1094c` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x6db8` | `0x6df0` | **`+0x38`** |
| `__TEXT.__cstring` | `0x1c0c2` | `0x1c0f2` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xb050` | `0xb070` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1cb20` | `0x1cb40` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x8d70` | `0x8d88` | **`+0x18`** |
| `__DATA.__bss` | `0xec78` | `0xec88` | **`+0x10`** |
| `__DATA.__objc_const` | `0x1ee98` | `0x1eea8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-910.27.103.0.0
+910.33.102.0.0

-  Functions: 10150
+  Functions: 10165

-  CStrings:  11463
+  CStrings:  11469
CStrings:
+ "Failed to upload records to update %@: %@"
+ "Will upload these records: %@"
+ "ckRecordForCollectionShareSettingsWithZoneID:usingFetchedRecords:userID:"
+ "ckRecordForLibraryShareSettingsWithZoneID:usingFetchedRecords:userID:"
+ "engine.transport.cloudkit.transportupdate"
+ "isApprovedRequester"
+ "recordIDsToFetchToUpdateScopeFromScopeChange:currentUserID:"
+ "recordsToUpdateFromScopeChange:usingFetchedRecords:currentUserID:"
+ "setIsApprovedRequester:"
+ "shareRecordID"
+ "updateNonSharePropertiesOnCKShare:"
- "_bestErrorForUnderlyingError:scopeProvider:"
- "_isCKErrorForRejectedRecord:"
- "_rejectionReasonFromPartialError:identifier:"
- "ckRecordForCollectionShareSettingsWithZoneID:userID:"
- "ckRecordForLibraryShareSettingsWithZoneID:userID:"
```
