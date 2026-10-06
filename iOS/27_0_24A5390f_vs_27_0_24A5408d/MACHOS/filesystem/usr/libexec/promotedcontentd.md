## promotedcontentd

> `/usr/libexec/promotedcontentd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3dd98c` | `0x3db3d0` | **`-0x25bc`** |
| `__DATA_CONST.__const` | `0x1c908` | `0x1c400` | **`-0x508`** |
| `__TEXT.__eh_frame` | `0x4c5c` | `0x48ec` | **`-0x370`** |
| `__TEXT.__oslogstring` | `0x10fdc` | `0x1123c` | **`+0x260`** |
| `__TEXT.__swift5_capture` | `0x12bc` | `0x1078` | **`-0x244`** |
| `__TEXT.__const` | `0x2b3aa` | `0x2b1da` | **`-0x1d0`** |
| `__DATA.__data` | `0xe6c8` | `0xe578` | **`-0x150`** |
| `__TEXT.__unwind_info` | `0x7178` | `0x70a0` | **`-0xd8`** |
| `__DATA.__objc_const` | `0x2b448` | `0x2b398` | **`-0xb0`** |
| `__TEXT.__auth_stubs` | `0x5ce0` | `0x5d50` | **`+0x70`** |
| `__TEXT.__objc_methname` | `0x2708d` | `0x2701d` | **`-0x70`** |
| `__TEXT.__constg_swiftt` | `0x6488` | `0x6420` | **`-0x68`** |
| `__TEXT.__swift5_fieldmd` | `0x4a24` | `0x49d8` | **`-0x4c`** |
| `__TEXT.__swift5_typeref` | `0x43a0` | `0x4366` | **`-0x3a`** |
| `__DATA_CONST.__auth_got` | `0x2e80` | `0x2eb8` | **`+0x38`** |
| `__TEXT.__cstring` | `0x15dd5` | `0x15e05` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x15228` | `0x151f8` | **`-0x30`** |
| `__DATA.__objc_selrefs` | `0x94a0` | `0x9480` | **`-0x20`** |
| `__DATA_CONST.__cfstring` | `0xf7e0` | `0xf800` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x18b8` | `0x18d8` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x3726` | `0x3706` | **`-0x20`** |
| `__TEXT.__swift_as_entry` | `0xf0` | `0xd8` | **`-0x18`** |
| `__TEXT.__swift_as_cont` | `0x26c` | `0x258` | **`-0x14`** |
| `__TEXT.__swift_as_ret` | `0x11c` | `0x108` | **`-0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x1608` | `0x1618` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x310` | `0x300` | **`-0x10`** |
| `__TEXT.__objc_classname` | `0x4c17` | `0x4c07` | **`-0x10`** |
| `__TEXT.__objc_methtype` | `0x512d` | `0x513d` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x158` | `0x150` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x5cc` | `0x5c8` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-557.1.26.0.0
+557.1.32.0.0

-  Functions: 11808
-  Symbols:   2297
+  Functions: 11744
+  Symbols:   2298
Symbols:
+ __exit
CStrings:
+ "@28@0:8B16@20"
+ "APMetricStorageEC can't be used outside of PCD."
+ "APMetricStorageEC created without a database manager; proto metric pipeline disabled."
+ "Metrics.ProtoMetricHandler"
+ "[EligibilitySnapshotRefresher] Built snapshot from a real keychain record (attempt %ld) — protoU13: %{bool}d, eduMode: %{bool}d, isChild: %{bool}d, maidEducation: %{bool}d"
+ "[EligibilitySnapshotRefresher] Keychain record still unavailable after %ld retries — leaving fail-closed default snapshot persisted; will correct on the next apAccountChanged"
+ "[EligibilitySnapshotRefresher] Keychain record unavailable (default account) — persisted fail-closed default snapshot (isChild=true); scheduling retries to correct once AdCore's write lands"
+ "[EligibilitySnapshotRefresher] Scheduling snapshot retry %ld/%ld in %fs"
+ "[EligibilitySnapshotRefresher] seedUserDefaultsIfMissing — UserDefaults empty; building initial snapshot from keychain + AdCore and writing"
+ "enableTelemetry=YES"
+ "initWithIsChild:databaseManager:"
+ "isPromotedContentDaemon"
+ "personalizedAdsEnforcementAgeSource"
- "APDatabasePathProvider"
- "[EligibilitySnapshotRefresher] Built snapshot — protoU13: %{bool}d, eduMode: %{bool}d, isChild: %{bool}d, maidEducation: %{bool}d"
- "[EligibilitySnapshotRefresher] seedUserDefaultsIfMissing — UserDefaults empty; building snapshot from keychain + AdCore and writing"
- "closeDatabaseConnection"
- "closeDatabaseConnectionWithCompletionHandler:"
- "connectionOpen"
- "databaseFilePath"
- "databaseName"
- "databasePath"
- "idleTimer"
- "migrationScriptsPath"
- "openDatabaseConnectionWithPath:"
- "v28@?0@\"NSNumber\"8B16@\"NSError\"20"
```
