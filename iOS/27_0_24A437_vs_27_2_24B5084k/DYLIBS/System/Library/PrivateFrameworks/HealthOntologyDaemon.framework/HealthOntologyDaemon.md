## HealthOntologyDaemon

> `/System/Library/PrivateFrameworks/HealthOntologyDaemon.framework/HealthOntologyDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d664` | `0x2f59c` | **`+0x1f38`** |
| `__TEXT.__oslogstring` | `0x1dda` | `0x208a` | **`+0x2b0`** |
| `__AUTH_CONST.__cfstring` | `0x2240` | `0x2420` | **`+0x1e0`** |
| `__TEXT.__cstring` | `0x33bc` | `0x34ec` | **`+0x130`** |
| `__AUTH_CONST.__objc_const` | `0x3f40` | `0x4010` | **`+0xd0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1828` | `0x18e8` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x21ac` | `0x226c` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x668` | `0x6e8` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0xe90` | `0xf08` | **`+0x78`** |
| `__DATA_DIRTY.__objc_data` | `0xc80` | `0xcd0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x19f0` | `0x1a20` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x3f8` | `0x428` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x1ec` | `0x1f4` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x158` | `0x160` | **`+0x8`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

-  - /System/Library/Frameworks/Network.framework/Network

-  Functions: 1099
-  Symbols:   2144
-  CStrings:  452
+  Functions: 1138
+  Symbols:   2196
+  CStrings:  476
Symbols:
+ +[HDOntologyManifestUpdater _getManifestEntryWithUpdateCoordinator:URL:respectsOverriddenEnvironment:error:]
+ +[HDOntologyMercuryZipTSVImporter _handleResourceExtractionForArchiveEntry:entry:updateCoordinator:]
+ +[HDOntologyResourceDirectoryManager _activeDirectoryNameForEntry:]
+ +[HDOntologyResourceDirectoryManager _attemptDeleteOrphanedDirectoryAtURL:directoryName:fileManager:deletionErrors:]
+ +[HDOntologyResourceDirectoryManager _finalizeDeletionResultsWithAttemptedCount:deletionErrors:error:]
+ +[HDOntologyResourceDirectoryManager _isDirectoryAtURL:]
+ +[HDOntologyResourceDirectoryManager _processDirectoryItem:activeDirectoryNames:fileManager:deletionErrors:]
+ +[HDOntologyResourceDirectoryManager _shouldPreserveDirectoryNamed:activeDirectoryNames:]
+ +[HDOntologyResourceDirectoryManager _stagedDirectoryNameForEntry:]
+ +[HDOntologyResourceDirectoryManager _writeInfoPlistToBundleURL:bundleName:error:]
+ +[HDOntologyResourceDirectoryManager activeResourceDirectoryURLForEntry:baseResourcesDirectoryURL:]
+ +[HDOntologyResourceDirectoryManager activeResourceDirectoryURLForEntry:updateCoordinator:]
+ +[HDOntologyResourceDirectoryManager baseResourcesDirectoryURLForUpdateCoordinator:]
+ +[HDOntologyResourceDirectoryManager cleanupOrphanedDirectoriesExcluding:updateCoordinator:fileManager:error:]
+ +[HDOntologyResourceDirectoryManager createResourceDirectoryForEntry:updateCoordinator:fileManager:error:]
+ +[HDOntologyResourceDirectoryManager deleteResourceDirectoryForEntry:updateCoordinator:fileManager:error:]
+ +[HDOntologyResourceDirectoryManager extractResourceEntry:entry:updateCoordinator:fileManager:error:]
+ +[HDOntologyResourceDirectoryManager stagedResourceDirectoryURLForEntry:updateCoordinator:]
+ -[HDOntologyManifestUpdater initWithOntologyUpdateCoordinator:defaults:]
+ -[HDOntologyMercuryZipTSVPruner _deleteResourceDirectoriesForEntries:]
+ -[HDOntologyResourceDirectoryManager init]
+ -[HDOntologyShardImporter _publishMedicalHistoryVersionIfNeeded:]
+ -[HDOntologyShardImporter initWithOntologyUpdateCoordinator:medicalHistoryDefaults:]
+ -[HDOntologyShardImporter reconcileMedicalHistoryDefaultsWithError:]
+ -[HDOntologyShardPruner _activeResourceDirectoryNamesInTransaction:error:]
+ -[HDOntologyShardPruner _cleanupOrphanedResourceDirectoriesWithError:]
+ -[HDOntologyShardPruner _cleanupOrphanedResourceDirectoriesWithTransaction:error:]
+ -[HDOntologyUpdateCoordinator _reconcileMedicalHistoryDefaults]
+ -[HDOntologyUpdateCoordinator initWithDaemon:medicalHistoryDefaults:]
+ -[HDOntologyUpdateCoordinator initWithDaemon:scheduler:medicalHistoryDefaults:]
+ GCC_except_table14
+ GCC_except_table23
+ GCC_except_table71
+ GCC_except_table84
+ _HDOntologyZipResourcesPrefix
+ _HKErrorDomain
+ _HKHealthServicesPlatformRespectsOverriddenEnvironmentKey
+ _HKOntologyShardIdentifierMedicalHistory
+ _NSURLIsDirectoryKey
+ _OBJC_CLASS_$_HDOntologyResourceDirectoryManager
+ _OBJC_CLASS_$_NSPropertyListSerialization
+ _OBJC_IVAR_$_HDOntologyManifestUpdater._defaults
+ _OBJC_IVAR_$_HDOntologyShardImporter._medicalHistoryDefaults
+ _OBJC_METACLASS_$_HDOntologyResourceDirectoryManager
+ _OUTLINED_FUNCTION_17
+ _OUTLINED_FUNCTION_18
+ __OBJC_$_CLASS_METHODS_HDOntologyResourceDirectoryManager
+ __OBJC_$_INSTANCE_METHODS_HDOntologyResourceDirectoryManager
+ __OBJC_CLASS_RO_$_HDOntologyResourceDirectoryManager
+ __OBJC_METACLASS_RO_$_HDOntologyResourceDirectoryManager
+ ___110+[HDOntologyResourceDirectoryManager cleanupOrphanedDirectoriesExcluding:updateCoordinator:fileManager:error:]_block_invoke
+ ___52-[HDOntologyShardImporter _markImportedEntry:error:]_block_invoke_2
+ ___68-[HDOntologyShardImporter reconcileMedicalHistoryDefaultsWithError:]_block_invoke
+ ___70-[HDOntologyShardPruner _cleanupOrphanedResourceDirectoriesWithError:]_block_invoke
+ ___74-[HDOntologyShardPruner _activeResourceDirectoryNamesInTransaction:error:]_block_invoke
+ ___block_descriptor_72_e8_32s40s48s56r_e19_q24?0"NSURL"8^16lr56l8s32l8s40l8s48l8
+ ___block_descriptor_88_e8_32s40s48s56s64r72r_e32_v24?0"_HKZipArchiveEntry"8^B16ls32l8s40l8s48l8r64l8s56l8r72l8
- +[HDOntologyManifestUpdater _getManifestEntryWithUpdateCoordinator:URL:error:]
- GCC_except_table16
- GCC_except_table68
- GCC_except_table81
- ___block_descriptor_80_e8_32s40s48s56r64r_e32_v24?0"_HKZipArchiveEntry"8^B16ls32l8r56l8s40l8s48l8r64l8
CStrings:
+ "%@_%@_%ld_%ld.bundle"
+ "%{public}@: Cleaned up orphaned resource directories attempted %ld"
+ "%{public}@: Cleared medical history version from defaults"
+ "%{public}@: Deleted orphaned resource directory: %{public}@"
+ "%{public}@: Error reconciling medical history defaults: %{public}@"
+ "%{public}@: Failed to cleanup orphaned resource directories: %{public}@"
+ "%{public}@: Failed to delete resource directory for entry %{public}@: %{public}@"
+ "%{public}@: Failed to extract resource: '%{public}@' - %{public}@"
+ "%{public}@: No medicalHistoryDefaults, dropping clear"
+ "%{public}@: No medicalHistoryDefaults, dropping publish of version %{public}ld for %{public}@"
+ "%{public}@: Published medical history version %{public}ld to defaults"
+ "6.0"
+ "BNDL"
+ "CFBundleDevelopmentRegion"
+ "CFBundleIdentifier"
+ "CFBundleInfoDictionaryVersion"
+ "CFBundleName"
+ "CFBundlePackageType"
+ "Failed to delete %ld of %ld orphaned resource directories"
+ "Info.plist"
+ "MedicalHistoryImportedShardVersion"
+ "Resources/"
+ "com.apple.health.ontology.%@"
+ "en"
+ "resources"
- "1"
```
