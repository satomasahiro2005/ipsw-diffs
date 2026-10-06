## NotesAppMigrationExtension

> `/private/var/staged_system_apps/MobileNotes.app/Extensions/NotesAppMigrationExtension.appex/NotesAppMigrationExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x83124` | `0x84f58` | **`+0x1e34`** |
| `__TEXT.__eh_frame` | `0x3568` | `0x36a0` | **`+0x138`** |
| `__TEXT.__auth_stubs` | `0x2260` | `0x22e0` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0x2e60` | `0x2ec0` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x1ac8` | `0x1b28` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x2086` | `0x20d1` | **`+0x4b`** |
| `__TEXT.__swift5_typeref` | `0x1985` | `0x19cb` | **`+0x46`** |
| `__DATA_CONST.__auth_got` | `0x1138` | `0x1178` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x1092` | `0x10c2` | **`+0x30`** |
| `__DATA.__data` | `0x2390` | `0x23b8` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x3fa0` | `0x3fc8` | **`+0x28`** |
| `__DATA.__objc_const` | `0x5c0` | `0x5e0` | **`+0x20`** |
| `__TEXT.__const` | `0x58e4` | `0x5904` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x5a4` | `0x5c0` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0xbf8` | `0xc10` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x738` | `0x748` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1ad4` | `0x1ae0` | **`+0xc`** |
| `__DATA.__objc_data` | `0x280` | `0x288` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x748` | `0x750` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x40` | `0x48` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x6c` | `0x70` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-2998.0.0.0.0
+3001.2.1.0.0

-  Functions: 2166
+  Functions: 2183

-  CStrings:  619
+  CStrings:  622
CStrings:
+ "appMigrationImportedNoteCount"
+ "error importing archive in extension: %@"
+ "extension import finished: %ld/%ld"
+ "ic_save"
+ "importing from resolved root: %s"
+ "isEmpty"
+ "newLocalAccountInContext:"
+ "refreshAllObjects"
+ "workerManagedObjectContext"
- "copyItemAtURL:toURL:error:"
- "destination: %s"
- "error copying archive to group container: %@"
- "fileExistsAtPath:"
- "group container: %s"
- "removing existing import file"
```
