## backupd

> `/System/Library/PrivateFrameworks/MobileBackup.framework/backupd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x247be4` | `0x248204` | **`+0x620`** |
| `__TEXT.__gcc_except_tab` | `0x9d54` | `0xa0b0` | **`+0x35c`** |
| `__TEXT.__cstring` | `0x687bb` | `0x68a90` | **`+0x2d5`** |
| `__TEXT.__oslogstring` | `0x313eb` | `0x316b3` | **`+0x2c8`** |
| `__TEXT.__objc_methname` | `0x3776a` | `0x3781a` | **`+0xb0`** |
| `__TEXT.__objc_stubs` | `0x28100` | `0x281a0` | **`+0xa0`** |
| `__DATA_CONST.__cfstring` | `0x1aee0` | `0x1aea0` | **`-0x40`** |
| `__DATA.__objc_const` | `0x23780` | `0x237b8` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x15ea4` | `0x15ed4` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x7dc0` | `0x7de8` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x65e6` | `0x65c4` | **`-0x22`** |
| `__DATA.__objc_selrefs` | `0xb7b8` | `0xb7d0` | **`+0x18`** |
| `__TEXT.__objc_classname` | `0x2140` | `0x2156` | **`+0x16`** |
| `__DATA_CONST.__auth_ptr` | `0x298` | `0x2a0` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0xca0` | `0xca8` | **`+0x8`** |
| `__DATA_CONST.__objc_catlist` | `0xd0` | `0xd8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6200` | `0x61f8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3039.2.2.0.0
+3039.40.8.0.0

-  CStrings:  18402
+  CStrings:  18418
CStrings:
+ "-[NSString(MBFollowUpNameSpacing) mb_fetchFollowUpIdentifier:accountIdentifier:]"
+ "=ckrestore-engine= Failed to fetch app for bundleID %@: %@"
+ "=ckrestore-engine= No app to uninstall for %@"
+ "=ckrestore-engine= Not installing app for %@ as it doesn't reside on the intended volume"
+ "=diag= Aborting directory node enumeration, too many dirents under %{public}s"
+ "=diag= Aborting readdir_r, too many dirents under %{public}s"
+ "=diag= Failed to enumerate directory nodes under %{public}s"
+ "=diag= Failed to find the file using getattrlistbulk (%u)"
+ "=diag= getattrlistbulk found file entry (%u) for %@: %@"
+ "=drive-domain-delegate= Not creating safe harbour for %@ with invalid container type (%@)"
+ "=pc= open_dprotected_np could not open file at %s: %{errno}d"
+ "=scheduler= No device record found:%@ (dateOfLastBackup): %@"
+ "Creating the sync zone for account %{public}@(%{public}@) id:%{public}@ gid:%{public}@ gn:%{public}@"
+ "MBFollowUpNameSpacing"
+ "getattrlist"
+ "mb_fetchFollowUpIdentifier:accountIdentifier:"
+ "mb_followUpItemWithFollowUpIdentifier:account:"
+ "mb_nameSpacedIdentifierForFollowUpIdentifier:accountIdentifier:"
+ "outAccountIdentifier"
+ "outFollowUpIdentifier"
+ "setTimeoutIntervalForResource:"
+ "v32@0:8^@16^@24"
- "=ckrestore-engine= Failed to find user app %@: %@"
- "Creating the sync zone for account %{public}@(%{public}@)"
- "MB_PREBUDDY_PERCENT_BACKED_UP_DISABLED_CATEGORIES"
- "MB_PREBUDDY_PERCENT_BACKED_UP_DISABLED_CATEGORIES_ETA"
- "runEncodingTask:reply:"
- "v32@0:8@\"MBFileEncodingTask\"16@?<v@?@\"NSError\">24"
```
