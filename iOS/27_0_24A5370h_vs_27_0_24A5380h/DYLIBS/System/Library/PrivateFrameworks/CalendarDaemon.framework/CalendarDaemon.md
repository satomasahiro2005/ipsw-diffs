## CalendarDaemon

> `/System/Library/PrivateFrameworks/CalendarDaemon.framework/CalendarDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x1540` | `0x1b80` | **`+0x640`** |
| `__DATA_DIRTY.__objc_data` | `0x1400` | `0xdc0` | **`-0x640`** |
| `__TEXT.__text` | `0x76e0c` | `0x76ebc` | **`+0xb0`** |
| `__DATA_CONST.__got` | `0xa20` | `0xa70` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x6934` | `0x6954` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3520` | `0x3538` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0xce78` | `0xce80` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1d40` | `0x1d48` | **`+0x8`** |

### Other Changes

```diff

-1244.0.0.0.0
+1246.0.0.0.0

-  Functions: 2345
-  Symbols:   5595
+  Functions: 2347
+  Symbols:   5599
Symbols:
+ -[CADDatabaseConnectionPool performWithAllDatabasesWithConfiguration:options:block:]
+ -[CADDatabaseConnectionPool performWithConfiguration:options:databaseID:block:]
+ -[CADDatabaseSingleConnectionProvider performWithAllDatabasesWithConfiguration:options:block:]
+ -[CADDatabaseSingleConnectionProvider performWithConfiguration:options:databaseID:block:]
+ -[CADXPCImplementation(CADInternalOperationGroup) CADInternalGetMagicComposeRestrictedByMDM:]
+ -[ClientConnection _currentPriorityOptions]
+ -[ClientConnection withDatabaseID:options:perform:]
+ GCC_except_table72
+ _OBJC_CLASS_$_CalDeviceConfigurationReader
+ ___51-[ClientConnection withDatabaseID:options:perform:]_block_invoke
+ ___51-[ClientConnection withDatabaseID:options:perform:]_block_invoke_2
+ ___79-[CADDatabaseConnectionPool performWithConfiguration:options:databaseID:block:]_block_invoke
+ ___84-[CADDatabaseConnectionPool performWithAllDatabasesWithConfiguration:options:block:]_block_invoke
- -[CADDatabaseConnectionPool performWithAllDatabasesWithConfiguration:priority:block:]
- -[CADDatabaseConnectionPool performWithConfiguration:priority:databaseID:block:]
- -[CADDatabaseSingleConnectionProvider performWithAllDatabasesWithConfiguration:priority:block:]
- -[CADDatabaseSingleConnectionProvider performWithConfiguration:priority:databaseID:block:]
- -[ClientConnection _currentPriority]
- ___43-[ClientConnection withDatabaseID:perform:]_block_invoke
- ___43-[ClientConnection withDatabaseID:perform:]_block_invoke_2
- ___80-[CADDatabaseConnectionPool performWithConfiguration:priority:databaseID:block:]_block_invoke
- ___85-[CADDatabaseConnectionPool performWithAllDatabasesWithConfiguration:priority:block:]_block_invoke
```
