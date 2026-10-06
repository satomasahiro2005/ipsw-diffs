## IOMFB_bics_daemon

> `/usr/libexec/IOMFB_bics_daemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x31bdc` | `0x321bc` | **`+0x5e0`** |
| `__TEXT.__cstring` | `0x587c` | `0x5a1c` | **`+0x1a0`** |
| `__TEXT.__objc_methtype` | `0xb0` | `0x111` | **`+0x61`** |
| `__DATA.__objc_const` | `0x218` | `0x258` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x258` | `0x290` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x1350` | `0x1380` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xd60` | `0xd88` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x9c0` | `0x9d8` | **`+0x18`** |
| `__DATA_CONST.__const` | `0xf48` | `0xf60` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0xea` | `0xff` | **`+0x15`** |
| `__TEXT.__gcc_except_tab` | `0xaf8` | `0xb04` | **`+0xc`** |
| `__TEXT.__objc_classname` | `0x2a` | `0x1e` | **`-0xc`** |
| `__DATA.__common` | `0x28` | `0x20` | **`-0x8`** |
| `__DATA.__data` | `0xc40` | `0xc38` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x18` | `0x20` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-700.50.104.1.0
+700.50.108.0.0

-  Functions: 997
-  Symbols:   506
-  CStrings:  835
+  Functions: 1009
+  Symbols:   515
+  CStrings:  848
Symbols:
+ _XPC_ACTIVITY_ALLOW_BATTERY
+ _XPC_ACTIVITY_GRACE_PERIOD
+ _XPC_ACTIVITY_INTERVAL
+ _XPC_ACTIVITY_PRIORITY
+ _XPC_ACTIVITY_PRIORITY_UTILITY
+ _XPC_ACTIVITY_REPEATING
+ _xpc_activity_copy_criteria
+ _xpc_activity_set_criteria
+ _xpc_copy_description
CStrings:
+ "%s %s: drLTH keyed to a different MLB; deferring import to migration"
+ "@\"BICSXpcListener\""
+ "@32@0:8r*16^{bics_command_table_t=^{bics_command_entry_t}i}24"
+ "@40@0:8@16@24^{bics_command_table_t=^{bics_command_entry_t}i}32"
+ "BICS activity criteria: %s\n"
+ "BICSDaemonIntervalSeconds"
+ "BICSXpcClient"
+ "BICSXpcClient::_handleMessage without type"
+ "BICSXpcClient::initWithConnection"
+ "BICSXpcListener"
+ "BICSXpcListener client created %@"
+ "BICSXpcListener client removed %@"
+ "BICSXpcListener::initWithService %s"
+ "FactoryClearAllBICS"
+ "^{bics_command_table_t=^{bics_command_entry_t}i}"
+ "_table"
+ "com.apple.iomfb_bics_daemon.control"
+ "factory_clear_all_bics: armed %s; reboot required to complete"
+ "factory_clear_all_bics: clearing all BICS data for %s"
+ "factory_clear_all_bics: failed to arm %s"
+ "initWithConnection:listener:table:"
+ "initWithService:table:"
+ "overriding BICS daemon interval to %u s\n"
+ "primary"
+ "xpc_factory_clear_bics: refused on non-internal build"
- "@\"BICSMigrationListener\""
- "@24@0:8^{migration_table_t=^{migration_table_entry_t}i}16"
- "@32@0:8@16@24"
- "BICSMigrationClient"
- "BICSMigrationClient::_handleMessage without type"
- "BICSMigrationClient::initWithConnection"
- "BICSMigrationListener"
- "BICSMigrationListener client created %@"
- "BICSMigrationListener client removed %@"
- "BICSMigrationListener::initWithTable"
- "initWithConnection:listener:"
- "initWithTable:"
```
