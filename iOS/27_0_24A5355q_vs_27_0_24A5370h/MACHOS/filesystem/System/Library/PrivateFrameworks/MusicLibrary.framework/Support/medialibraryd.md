## medialibraryd

> `/System/Library/PrivateFrameworks/MusicLibrary.framework/Support/medialibraryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c710` | `0x1c9c8` | **`+0x2b8`** |
| `__TEXT.__objc_methname` | `0x4c45` | `0x4e83` | **`+0x23e`** |
| `__TEXT.__objc_stubs` | `0x3920` | `0x3ac0` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x17c2` | `0x1924` | **`+0x162`** |
| `__DATA_CONST.__cfstring` | `0x13c0` | `0x1480` | **`+0xc0`** |
| `__DATA.__objc_const` | `0x2688` | `0x2728` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0x1338` | `0x13a8` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x33c3` | `0x3422` | **`+0x5f`** |
| `__DATA_CONST.__const` | `0x1308` | `0x1358` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x1614` | `0x164c` | **`+0x38`** |
| `__TEXT.__objc_methtype` | `0x1024` | `0x104e` | **`+0x2a`** |
| `__DATA.__objc_ivar` | `0x168` | `0x178` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x460` | `0x470` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xc20` | `0xc30` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x628` | `0x630` | **`+0x8`** |
| `__TEXT.__const` | `0x180` | `0x188` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x778` | `0x780` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
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
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-4026.110.62.2.0
+4026.100.68.0.0

-  Functions: 605
-  Symbols:   378
-  CStrings:  1350
+  Functions: 611
+  Symbols:   381
+  CStrings:  1378
Symbols:
+ _ML3CanShowAlertToUser
+ _OBJC_CLASS_$_MSVSystemDialog
+ _OBJC_CLASS_$_MSVSystemDialogOptions
CStrings:
+ ""
+ "Database Inconsistency"
+ "Gathering disgnostics for database corruption at path=%{public}@"
+ "Ignore"
+ "MLLastDatabaseCorruptionIgnoreTime"
+ "Ok"
+ "Received database recreation request on client connection: %{public}@, diagnosticDescription=%p, reason=%d"
+ "Received request to attempt database recovery from client connection: %{public}@, path=%{public}@, reason=%d"
+ "T@\"NSString\",C,N,V_diagnosticDescription"
+ "The media library database is in an inconsistent state. Please use Tap To Radar to file a bug against Media Platform | Library to help debug this issue\n\n[This dialog is shown for internal users only, and will be dismissed in 30s with no selection.]"
+ "Tq,N,V_reason"
+ "_attemptDatabaseFileRecoveryAtPath:reason:diagnosticDescription:withCompletionHandler:"
+ "_attemptDatabaseFileRecoveryToHandleCorruptionAtPath:diagnosticDescription:withCompletionHandler:"
+ "_corruptedPathsLock"
+ "_corruptedPathsPromptingUser"
+ "_diagnosticDescription"
+ "_performDiagnosticAndGetDescriptionForReason:"
+ "_recreateDatabaseAtPath:diagnosticDescription:reason:withCompletionHandler:"
+ "diagnosticDescription"
+ "initWithOptions:"
+ "now"
+ "presentWithCompletion:"
+ "setAlertHeader:"
+ "setAlertMessage:"
+ "setAlternateButtonTitle:"
+ "setDefaultButtonTitle:"
+ "setDiagnosticDescription:"
+ "setReason:"
+ "setTimeout:"
+ "timeout"
+ "v16@?0@\"MSVSystemDialogResponse\"8"
+ "v48@0:8@16@24q32@?40"
+ "v48@0:8@16q24@32@?40"
- "Enqueueing recreation operation..."
- "Received database recreation request on client connection: %{public}@"
- "Received request to attempt database recovery from client connection: %{public}@"
- "_lastCorruptionRestoreAttemptDate"
- "_performDiagnosticWithReason:"
```
