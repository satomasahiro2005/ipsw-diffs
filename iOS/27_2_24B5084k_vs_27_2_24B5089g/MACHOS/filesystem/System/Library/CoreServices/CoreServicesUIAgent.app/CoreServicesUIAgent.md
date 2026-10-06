## CoreServicesUIAgent

> `/System/Library/CoreServices/CoreServicesUIAgent.app/CoreServicesUIAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15b54` | `0x17d24` | **`+0x21d0`** |
| `__TEXT.__cstring` | `0xd13` | `0x1143` | **`+0x430`** |
| `__TEXT.__eh_frame` | `0x538` | `0x740` | **`+0x208`** |
| `__DATA_CONST.__const` | `0x8c0` | `0x990` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0x9af` | `0xa7f` | **`+0xd0`** |
| `__TEXT.__objc_stubs` | `0xf80` | `0x1020` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x2e19` | `0x2eb6` | **`+0x9d`** |
| `__TEXT.__const` | `0xac4` | `0xb34` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x570` | `0x5e0` | **`+0x70`** |
| `__DATA.__objc_selrefs` | `0xa30` | `0xa68` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0x808` | `0x83c` | **`+0x34`** |
| `__TEXT.__swift5_fieldmd` | `0x360` | `0x394` | **`+0x34`** |
| `__TEXT.__swift5_typeref` | `0x630` | `0x662` | **`+0x32`** |
| `__DATA.__data` | `0xd48` | `0xd78` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xd90` | `0xd60` | **`-0x30`** |
| `__TEXT.__objc_methtype` | `0x17d1` | `0x1801` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x240` | `0x268` | **`+0x28`** |
| `__DATA.__objc_const` | `0x11e8` | `0x1208` | **`+0x20`** |
| `__DATA.__objc_data` | `0xb68` | `0xb88` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1e9` | `0x209` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x5c` | `0x78` | **`+0x1c`** |
| `__DATA_CONST.__auth_ptr` | `0x228` | `0x240` | **`+0x18`** |
| `__DATA.__common` | `0xa0` | `0xb0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xe20` | `0xe30` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x718` | `0x720` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x128` | `0x124` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x5c` | `0x60` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x1c` | `0x20` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x1c` | `0x20` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-469.1.6.0.0
+469.1.7.0.0

-  Functions: 430
-  Symbols:   398
-  CStrings:  655
+  Functions: 450
+  Symbols:   403
+  CStrings:  687
Symbols:
+ _$s10Foundation3URLV6stringACSgSSh_tcfC
+ _$s10Foundation3URLVs23CustomStringConvertibleAAMc
+ _IXAppReplacementErrorDomain
+ _OBJC_CLASS_$_LSApplicationWorkspace
+ _OBJC_CLASS_$__LSOpenConfiguration
CStrings:
+ "AppMigrationNothingIsHappening"
+ "AppMigrationSomethingIsHappening"
+ "CoreServicesUIAgent/MigrationErrorHandler.swift"
+ "Could Not Move App Data and Settings from “%1$@”"
+ "Not Enough Free Space"
+ "Some data and settings failed to transfer. %@"
+ "The existing “%1$@” is being restored from backup. Try again later."
+ "The existing “%1$@” is busy. Try again later."
+ "The existing “%1$@” is installing. Try again later."
+ "The existing “%1$@” is updating. Try again later."
+ "Transferring your data to this app requires at least 1 GB of available storage. You can manage storage in Settings."
+ "_createCheckedThrowingContinuation(_:)"
+ "code"
+ "couldn't open %s: %@"
+ "defaultWorkspace"
+ "describes an app that is installing"
+ "describes an app that is restoring from backup"
+ "describes an app that is updating"
+ "describes an app whose install state is busy"
+ "domain"
+ "errorHandler"
+ "generic exposition on failure for app migration. Error's localized description is interpolated"
+ "generic failure explaination for app migration"
+ "migration failed for %@: %@"
+ "noteMigrationIsDoingSomethingWithNotification:"
+ "noteMigrationIsntDoingAnythingWithNotification:"
+ "openURL:configuration:completionHandler:"
+ "prefs:root=General&path=STORAGE_MGMT"
+ "setSensitive:"
+ "showing storage settings per user request"
+ "unexpected error code from IX %{public}ld"
+ "unexpected error from IX %{public}@"
+ "unexpectedly asked to localize name for error code %{public}ld"
+ "v24@?0@\"NSDictionary\"8@\"NSError\"16"
- "App Replacement Failed"
- "migration failed for %@: %@, releasing preflight on scene"
```
