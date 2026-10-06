## JournalDataclassOwner

> `/System/Library/Accounts/DataclassOwners/JournalDataclassOwner.bundle/JournalDataclassOwner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xce0c` | `0xb378` | **`-0x1a94`** |
| `__TEXT.__oslogstring` | `0xcdd` | `0xb6d` | **`-0x170`** |
| `__TEXT.__auth_stubs` | `0xc60` | `0xb00` | **`-0x160`** |
| `__TEXT.__objc_stubs` | `0x5c0` | `0x480` | **`-0x140`** |
| `__DATA_CONST.__auth_got` | `0x638` | `0x588` | **`-0xb0`** |
| `__TEXT.__eh_frame` | `0x298` | `0x218` | **`-0x80`** |
| `__TEXT.__objc_methname` | `0x737` | `0x6c0` | **`-0x77`** |
| `__DATA_CONST.__got` | `0x1f0` | `0x198` | **`-0x58`** |
| `__DATA.__objc_selrefs` | `0x278` | `0x228` | **`-0x50`** |
| `__DATA.__data` | `0x4d0` | `0x498` | **`-0x38`** |
| `__TEXT.__const` | `0x7e8` | `0x7b8` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x2a8` | `0x278` | **`-0x30`** |
| `__DATA.__common` | `0x68` | `0x48` | **`-0x20`** |
| `__TEXT.__cstring` | `0x1c3` | `0x1a3` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0x27f` | `0x25f` | **`-0x20`** |
| `__DATA.__bss` | `0xb90` | `0xb80` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x1a8` | `0x198` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-77.0.0.0.0
+84.0.0.0.0

-  Functions: 200
-  Symbols:   153
-  CStrings:  178
+  Functions: 189
+  Symbols:   148
+  CStrings:  161
Symbols:
+ _objc_retain_x10
+ _swift_retain_x28
- _OBJC_CLASS_$_CKAsset
- _OBJC_CLASS_$_CKReference
- _OBJC_CLASS_$_NSFileManager
- _objc_retain_x9
- _swift_getAtKeyPath
- _swift_getKeyPath
- _swift_unknownObjectRelease
CStrings:
- "(actionUploadChanges) will upload %ld attachment records"
- "Failed to create partial record for the attachment: %@"
- "File attachment file does not exist: %{public}s"
- "Found %ld un-uploaded attachments"
- "No filePath for JournalEntryAssetFileAttachmentMO with id %{public}s, parentID %{public}s"
- "Will delete %ld attachment records"
- "asset"
- "defaultManager"
- "encryptedValues"
- "fileExistsAtPath:"
- "filePath"
- "id"
- "index"
- "initWithFileURL:"
- "initWithRecordID:action:"
- "parentJournalEntryAsset"
- "zoneID"
```
