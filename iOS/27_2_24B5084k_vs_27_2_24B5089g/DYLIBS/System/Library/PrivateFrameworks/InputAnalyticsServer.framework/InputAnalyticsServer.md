## InputAnalyticsServer

> `/System/Library/PrivateFrameworks/InputAnalyticsServer.framework/InputAnalyticsServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8153c` | `0x8240c` | **`+0xed0`** |
| `__TEXT.__oslogstring` | `0x7f20` | `0x8270` | **`+0x350`** |
| `__TEXT.__cstring` | `0x67f2` | `0x69c2` | **`+0x1d0`** |
| `__AUTH_CONST.__cfstring` | `0x6ea0` | `0x6fa0` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0xa7b0` | `0xa858` | **`+0xa8`** |
| `__AUTH_CONST.__objc_intobj` | `0x18f0` | `0x1968` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0x641c` | `0x6484` | **`+0x68`** |
| `__AUTH.__objc_data` | `0xb78` | `0xbc8` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x32e0` | `0x3330` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x15f8` | `0x1638` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x18d0` | `0x1908` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x1890` | `0x18b8` | **`+0x28`** |
| `__DATA.__bss` | `0x7f0` | `0x810` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1958` | `0x1968` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xbf8` | `0xc00` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x3e0` | `0x3e8` | **`+0x8`** |

### Other Changes

```diff

-154.1.4.0.0
+154.1.5.0.0

+  - /System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth

-  Functions: 2902
-  Symbols:   986
-  CStrings:  1542
+  Functions: 2923
+  Symbols:   989
+  CStrings:  1562
Symbols:
+ _CBCentralManagerOptionShowPowerAlertKey
+ _OBJC_CLASS_$_CBCentralManager
+ _objc_retain_x6
CStrings:
+ "A1603"
+ "A2051"
+ "A2538"
+ "A3085"
+ "BEGIN TRANSACTION;DROP TABLE IF EXISTS %1$@;CREATE TABLE %1$@ (date TEXT NOT NULL, pencilVersion INTEGER NOT NULL, usageType INTEGER NOT NULL, appInfo TEXT NOT NULL, inUseDisplay INTEGER NOT NULL, activeMinutes INTEGER, activeSeconds INTEGER, lastActivityTimestamp INTEGER, PRIMARY KEY (date, pencilVersion, usageType, appInfo, inUseDisplay));COMMIT;"
+ "Cannot migrate the pencil usage table: no database."
+ "Column lookup for the pencil usage table migration returned no row: %{private}s"
+ "Could not determine the pencil usage table's on-disk version. Leaving the table alone."
+ "Failed to bind the column name for the pencil usage table migration: %{private}s"
+ "Failed to get pencil version from CoreBluetooth. Falling back to the self.pencilVersion (last known pencil version)."
+ "Failed to migrate the pencil usage table to v2 with error %{private}s"
+ "Failed to prepare the column lookup for the pencil usage table migration: %{private}s"
+ "Migrated the pencil usage table to v2 (dropped the old table, added the inUseDisplay column)."
+ "No Apple Pencil among the %lu paired bluetooth device(s)."
+ "No migration defined to take the pencil usage table to version %ld."
+ "ROLLBACK;"
+ "SELECT COUNT(*) FROM pragma_table_info('%@') WHERE name = ?"
+ "inUseDisplay"
+ "pairedPencilVersion failed to get a pairing agent."
+ "pairingState"
```
