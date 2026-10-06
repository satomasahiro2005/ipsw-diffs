## Siri

> `/System/Library/DataClassMigrators/Siri.migrator/Siri`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x415c` | `0x4734` | **`+0x5d8`** |
| `__TEXT.__oslogstring` | `0xc42` | `0xf28` | **`+0x2e6`** |
| `__TEXT.__objc_methname` | `0x965` | `0xbc6` | **`+0x261`** |
| `__TEXT.__objc_stubs` | `0xb20` | `0xc60` | **`+0x140`** |
| `__TEXT.__cstring` | `0x968` | `0xa14` | **`+0xac`** |
| `__DATA_CONST.__cfstring` | `0x6e0` | `0x740` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x1c4` | `0x218` | **`+0x54`** |
| `__DATA.__objc_selrefs` | `0x2f0` | `0x340` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x47` | `0x90` | **`+0x49`** |
| `__TEXT.__auth_stubs` | `0x4a0` | `0x4c0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x258` | `0x268` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xd8` | `0xe8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x130` | `0x138` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`

### Other Changes

```diff

-3605.24.1.1.1
+3605.30.1.1.1

-  Functions: 39
-  Symbols:   124
-  CStrings:  238
+  Functions: 46
+  Symbols:   126
+  CStrings:  262
Symbols:
+ _objc_release_x28
+ _objc_retain_x5
CStrings:
+ "%s App Access exclusion list migration has already been performed (isRestorePass=%{BOOL}d). Skipping."
+ "%s Marking restore-pass App Access exclusion list migration as complete."
+ "%s Not recording the backed-up App Access exclusion list marker (disposition=0x%lx, alreadyPresent=%{BOOL}d)."
+ "%s Pre-migration reset check: hasV1Flag=%{BOOL}d, isLinwoodEnabled=%{BOOL}d, isRestorePass=%{BOOL}d"
+ "%s Recording the backed-up App Access exclusion list marker so a restore from this device skips re-derivation."
+ "%s Restore-from-backup pass (restoredBackupBuildVersion=%@, backedUpMigratedMarker=%{BOOL}d) — the backup already carries a curated exclusion list. Leaving the restored kTCCServiceSiriAccess records alone."
+ "%s Restore-from-backup pass (restoredBackupBuildVersion=%@, backedUpMigratedMarker=%{BOOL}d) — the backup predates the exclusion list. Re-deriving even though the standard one-shot flag may be set."
+ "(unknown)"
+ "-[SiriMigrator _markAppAccessExclusionListMigratedInBackedUpDomainForDisposition:]"
+ "AppAccessExclusionListMigrated"
+ "AppAccessExclusionListRestoreMigrationPerformed"
+ "B24@0:8@16"
+ "B24@0:8I16B20"
+ "B28@0:8@16B24"
+ "_appAccessExclusionListMigrationActionForRestorePass:restoreMigrationAlreadyPerformed:migrationAlreadyPerformed:restoredBackupBuildVersion:hasBackedUpMigratedMarker:"
+ "_backupBuildVersionPredatesAppAccessExclusionList:"
+ "_markAppAccessExclusionListMigratedInBackedUpDomain"
+ "_markAppAccessExclusionListMigratedInBackedUpDomainForDisposition:"
+ "_markAppAccessExclusionListRestoreMigrationPerformed"
+ "_shouldRederiveAppAccessExclusionListForRestoredBackupBuildVersion:hasBackedUpMigratedMarker:"
+ "_shouldWriteBackedUpAppAccessExclusionListMarkerForDisposition:markerAlreadyPresent:"
+ "characterAtIndex:"
+ "length"
+ "q40@0:8B16B20B24@28B36"
+ "uppercaseString"
+ "v20@0:8I16"
- "%s One-time App Access exclusion list migration has already been performed. Skipping."
- "%s Pre-migration reset check: hasV1Flag=%{BOOL}d, isLinwoodEnabled=%{BOOL}d"
```
