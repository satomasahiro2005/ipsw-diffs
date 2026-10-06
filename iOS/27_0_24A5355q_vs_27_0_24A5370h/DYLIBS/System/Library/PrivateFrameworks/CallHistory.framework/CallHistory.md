## CallHistory

> `/System/Library/PrivateFrameworks/CallHistory.framework/CallHistory`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b82a8` | `0x1b8390` | **`+0xe8`** |
| `__AUTH_CONST.__objc_const` | `0x14f48` | `0x15020` | **`+0xd8`** |
| `__TEXT.__oslogstring` | `0x6059` | `0x5fc9` | **`-0x90`** |
| `__TEXT.__objc_methlist` | `0x39d4` | `0x3a2c` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x1c50` | `0x1ca0` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x3820` | `0x3860` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x2540` | `0x2578` | **`+0x38`** |
| `__TEXT.__const` | `0x1e790` | `0x1e7b0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x4224` | `0x4244` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1608` | `0x1610` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x468` | `0x470` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6810` | `0x6818` | **`+0x8`** |

### Other Changes

```diff

-139.100.27.2.9
+143.100.11.2.1

-  Functions: 12425
-  Symbols:   4938
-  CStrings:  1069
+  Functions: 12433
+  Symbols:   4953
+  CStrings:  1066
Symbols:
+ +[SaintDavidsCounts(Additions) managedSaintDavidsCountsForTypeCode:count:inManagedObjectContext:]
+ +[SaintDavidsCounts(CoreDataProperties) fetchRequest]
+ -[CallDBManagerClient _createDatabaseIsPermanent:]
+ -[CallDBManagerClient _validateDatabaseIsPermanent:]
+ -[CallRecord(Additions) compositeSaintDavidsCountsForContext:]
+ -[SaintDavidsCounts(Additions) copyWithContext:]
+ GCC_except_table112
+ GCC_except_table127
+ GCC_except_table129
+ GCC_except_table131
+ GCC_except_table143
+ GCC_except_table147
+ GCC_except_table151
+ GCC_except_table19
+ GCC_except_table36
+ GCC_except_table38
+ _CHAppProtectionReadEntitlementKey
+ _CHCloudSyncEntitlementKey
+ _OBJC_CLASS_$_SaintDavidsCounts
+ _OBJC_METACLASS_$_SaintDavidsCounts
+ _OUTLINED_FUNCTION_5
+ _OUTLINED_FUNCTION_6
+ __OBJC_$_CLASS_METHODS_SaintDavidsCounts(Additions|CoreDataProperties)
+ __OBJC_$_INSTANCE_METHODS_SaintDavidsCounts(Additions|CoreDataProperties)
+ __OBJC_CLASS_RO_$_SaintDavidsCounts
+ __OBJC_METACLASS_RO_$_SaintDavidsCounts
+ _kCHDBSaintDavidsCounts
- GCC_except_table111
- GCC_except_table126
- GCC_except_table128
- GCC_except_table130
- GCC_except_table142
- GCC_except_table146
- GCC_except_table150
- GCC_except_table17
- GCC_except_table35
- GCC_except_table37
- _CHAppProtectionReadEntitlement
- _CHCloudSyncEntitlement
CStrings:
+ "143.100.11.2.1"
+ "143.100.11.2.1~23"
+ "Could not acquire database directory URL: %hhu"
+ "Could not find SaintDavidsCounts entity with name %{public}@ in context %{public}@. Falling back to convenience initializer."
+ "Creating temporary data store: %{public}@ for version: %ld"
+ "Data store (permanent:%{public}i) database location returned error code %{public}@"
+ "Database (permanent:%{public}i) file does not exist at path: %{public}@"
+ "Database (permanent:%{public}i) file doesn't exist; poking sync helper. Error code: %{public}@"
+ "Database (permanent:%{public}i) metadata valid but data store check failed with code: %{public}@; poking sync helper"
+ "Database (permanent:%{public}i) validated successfully"
+ "Database (permanent:%{public}i) validation failed, poking sync helper"
+ "Failed to add data store (permanent:%{public}i) at location: %{public}@ after successful validation"
+ "Not attempting to create helper connection because we're missing the %@ entitlement"
+ "SaintDavidsCounts"
+ "createDatabase client (permanent:%{public}i)"
+ "createDatabase client (permanent:%{public}i, location: %{public}@)"
+ "saintDavidsCounts"
- "139.100.27.2.9"
- "139.100.27.2.9~4"
- "Creating temporary data store: %{public}@"
- "Failed to add permanent data store at location: %{public}@ after successful validation"
- "Failed to add temporary data store at location: %{public}@ after successful validation"
- "Got error code: %{public}@ while getting permanent data store database location"
- "Got error code: %{public}@ while getting temporary data store database location"
- "Permanent database file does not exist at path: %{public}@"
- "Permanent database file doesn't exist; poking sync helper. Error code: %{public}@"
- "Permanent database metadata valid but data store check failed with code: %{public}@; poking sync helper"
- "Permanent database validated successfully"
- "Permanent database validation failed, poking sync helper"
- "Temporary database file does not exist at path: %{public}@"
- "Temporary database file doesn't exist; poking sync helper. Error code: %{public}@"
- "Temporary database metadata valid but data store check failed with code: %{public}@; poking sync helper"
- "Temporary database validated successfully"
- "Temporary database validation failed; poking sync helper"
- "createPermanent client: %{public}@"
- "createTemporary client"
- "createTemporary client location: %{public}@"
```
