## MobileAsset

> `/System/Library/PrivateFrameworks/MobileAsset.framework/MobileAsset`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8c500` | `0x8e060` | **`+0x1b60`** |
| `__TEXT.__cstring` | `0x13ae2` | `0x13e91` | **`+0x3af`** |
| `__AUTH_CONST.__cfstring` | `0xfdc0` | `0x10120` | **`+0x360`** |
| `__AUTH_CONST.__objc_const` | `0xa970` | `0xac90` | **`+0x320`** |
| `__TEXT.__oslogstring` | `0xb975` | `0xbba3` | **`+0x22e`** |
| `__TEXT.__objc_methlist` | `0x6d74` | `0x6f64` | **`+0x1f0`** |
| `__AUTH.__objc_data` | `0xb40` | `0xbe0` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x3808` | `0x38a8` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x1f20` | `0x1f88` | **`+0x68`** |
| `__TEXT.__gcc_except_tab` | `0x1338` | `0x1394` | **`+0x5c`** |
| `__DATA_CONST.__const` | `0x2758` | `0x27a0` | **`+0x48`** |
| `__DATA.__objc_ivar` | `0x90c` | `0x92c` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x478` | `0x488` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x280` | `0x290` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x248` | `0x258` | **`+0x10`** |

### Other Changes

```diff

-2215.0.16.0.0
+2215.0.20.0.0

-  Functions: 3066
-  Symbols:   5021
-  CStrings:  2826
+  Functions: 3106
+  Symbols:   5091
+  CStrings:  2858
Symbols:
+ +[MAAutoAssetMigrationInfo supportsSecureCoding]
+ +[MAAutoAssetMigrationResults supportsSecureCoding]
+ +[MAAutoAssetSet preinstalledAssetMigrationResults:]
+ -[MAAutoAssetMigrationInfo .cxx_destruct]
+ -[MAAutoAssetMigrationInfo assetSpecifier]
+ -[MAAutoAssetMigrationInfo assetType]
+ -[MAAutoAssetMigrationInfo assetVersion]
+ -[MAAutoAssetMigrationInfo description]
+ -[MAAutoAssetMigrationInfo encodeWithCoder:]
+ -[MAAutoAssetMigrationInfo hash]
+ -[MAAutoAssetMigrationInfo initWithCoder:]
+ -[MAAutoAssetMigrationInfo isEqual:]
+ -[MAAutoAssetMigrationInfo migrationError]
+ -[MAAutoAssetMigrationInfo migrationSucceeded]
+ -[MAAutoAssetMigrationInfo setAssetSpecifier:]
+ -[MAAutoAssetMigrationInfo setAssetType:]
+ -[MAAutoAssetMigrationInfo setAssetVersion:]
+ -[MAAutoAssetMigrationInfo setMigrationError:]
+ -[MAAutoAssetMigrationInfo setMigrationSucceeded:]
+ -[MAAutoAssetMigrationResults .cxx_destruct]
+ -[MAAutoAssetMigrationResults addFailedMigratedInfo:]
+ -[MAAutoAssetMigrationResults addFailedMigratedInfoForDescriptor:withError:]
+ -[MAAutoAssetMigrationResults addSetupError:]
+ -[MAAutoAssetMigrationResults addSuccessfullyMigratedInfo:]
+ -[MAAutoAssetMigrationResults addSuccessfullyMigratedInfoForDescriptor:]
+ -[MAAutoAssetMigrationResults description]
+ -[MAAutoAssetMigrationResults encodeWithCoder:]
+ -[MAAutoAssetMigrationResults failedMigratedAssetInfo]
+ -[MAAutoAssetMigrationResults hash]
+ -[MAAutoAssetMigrationResults infoFromDescriptor:]
+ -[MAAutoAssetMigrationResults infoFromDescriptor:withError:]
+ -[MAAutoAssetMigrationResults initWithCoder:]
+ -[MAAutoAssetMigrationResults init]
+ -[MAAutoAssetMigrationResults isEqual:]
+ -[MAAutoAssetMigrationResults setFailedMigrated:]
+ -[MAAutoAssetMigrationResults setSuccessfullyMigrated:]
+ -[MAAutoAssetMigrationResults setupErrors]
+ -[MAAutoAssetMigrationResults successfullyMigratedAssetInfo]
+ GCC_except_table229
+ _OBJC_CLASS_$_MAAutoAssetMigrationInfo
+ _OBJC_CLASS_$_MAAutoAssetMigrationResults
+ _OBJC_IVAR_$_MAAutoAssetMigrationInfo._assetSpecifier
+ _OBJC_IVAR_$_MAAutoAssetMigrationInfo._assetType
+ _OBJC_IVAR_$_MAAutoAssetMigrationInfo._assetVersion
+ _OBJC_IVAR_$_MAAutoAssetMigrationInfo._migrationError
+ _OBJC_IVAR_$_MAAutoAssetMigrationInfo._migrationSucceeded
+ _OBJC_IVAR_$_MAAutoAssetMigrationResults._failedMigratedAssetInfo
+ _OBJC_IVAR_$_MAAutoAssetMigrationResults._setupErrors
+ _OBJC_IVAR_$_MAAutoAssetMigrationResults._successfullyMigratedAssetInfo
+ _OBJC_METACLASS_$_MAAutoAssetMigrationInfo
+ _OBJC_METACLASS_$_MAAutoAssetMigrationResults
+ __OBJC_$_CLASS_METHODS_MAAutoAssetMigrationInfo
+ __OBJC_$_CLASS_METHODS_MAAutoAssetMigrationResults
+ __OBJC_$_CLASS_PROP_LIST_MAAutoAssetMigrationInfo
+ __OBJC_$_CLASS_PROP_LIST_MAAutoAssetMigrationResults
+ __OBJC_$_INSTANCE_METHODS_MAAutoAssetMigrationInfo
+ __OBJC_$_INSTANCE_METHODS_MAAutoAssetMigrationResults
+ __OBJC_$_INSTANCE_VARIABLES_MAAutoAssetMigrationInfo
+ __OBJC_$_INSTANCE_VARIABLES_MAAutoAssetMigrationResults
+ __OBJC_$_PROP_LIST_MAAutoAssetMigrationInfo
+ __OBJC_$_PROP_LIST_MAAutoAssetMigrationResults
+ __OBJC_CLASS_PROTOCOLS_$_MAAutoAssetMigrationInfo
+ __OBJC_CLASS_PROTOCOLS_$_MAAutoAssetMigrationResults
+ __OBJC_CLASS_RO_$_MAAutoAssetMigrationInfo
+ __OBJC_CLASS_RO_$_MAAutoAssetMigrationResults
+ __OBJC_METACLASS_RO_$_MAAutoAssetMigrationInfo
+ __OBJC_METACLASS_RO_$_MAAutoAssetMigrationResults
+ ___52+[MAAutoAssetSet preinstalledAssetMigrationResults:]_block_invoke
+ ___block_descriptor_48_e8_32r40r_e42_v24?0"SUCoreConnectMessage"8"NSError"16lr32l8r40l8
+ _kMobileAssetPreferencesInternalVariantAsSeed
CStrings:
+ "AssetMigrationInfo: { Type: %@ | Specifier: %@ | Version: %@ | MigrationSucceeded: %@ |  MigrationError: %@}\n"
+ "InternalVariantAsSeed"
+ "MA-AUTO-SET(REPLY):MIGRATION_RESULTS"
+ "MA-AUTO-SET:MIGRATION_RESULTS"
+ "MA-auto-set{_failedOperation:_failedOperation:preinstalledAssetMigrationResults} | failure reported by server | %{public}@"
+ "MA-auto-set{_failedOperation:_failedOperation:preinstalledAssetMigrationResults} | no response message from server | %{public}@"
+ "MA-auto-set{_failedOperation:preinstalledAssetMigrationResults} | unable to create shared SUCoreConnectClient for the client process"
+ "MA-auto-set{_successOperation:preinstalledAssetMigrationResults} | SUCCESS"
+ "MA-auto-set{preinstalledAssetMigrationResults} connection client initialized for server connection"
+ "PreinstalledMigrationCookieNotFound"
+ "PreinstalledMigrationCookieParseFailed"
+ "PreinstalledMigrationCreateResultsFailed"
+ "PreinstalledMigrationDecryptAssetFailed"
+ "PreinstalledMigrationFailedCreateDesc"
+ "PreinstalledMigrationInvalidPlist"
+ "PreinstalledMigrationMalformedDir"
+ "PreinstalledMigrationMoveFailed"
+ "PreinstalledMigrationNoAssetsForType"
+ "PreinstalledMigrationNonAutoAsset"
+ "PreinstalledMigrationPersistResultsFailed"
+ "PreinstalledMigrationRepoReadError"
+ "PreinstalledMigrationResultsNotFound"
+ "PreinstalledMigrationSetClassFailed"
+ "TIMEOUT-30"
+ "[MigrationResults>>>\nSuccessully migrated assets:\n%@\nFailed migrated assets:\n%@\nSetupError:\n%@\n<<<]"
+ "failedInfo"
+ "migrationError"
+ "migrationResults"
+ "migrationSuccess"
+ "preinstalledAssetMigrationResults"
+ "setupErrors"
+ "successInfo"
```
