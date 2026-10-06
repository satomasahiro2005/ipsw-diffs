## AddressBookLegacy

> `/System/Library/PrivateFrameworks/AddressBookLegacy.framework/AddressBookLegacy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x78770` | `0x78cc8` | **`+0x558`** |
| `__TEXT.__oslogstring` | `0x2eff` | `0x306b` | **`+0x16c`** |
| `__TEXT.__cstring` | `0x26ff0` | `0x2708d` | **`+0x9d`** |
| `__AUTH_CONST.__cfstring` | `0xde40` | `0xde80` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1148` | `0x1170` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0xf00` | `0xf20` | **`+0x20`** |
| `__DATA.__bss` | `0x3b0` | `0x3c8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1aa8` | `0x1ac0` | **`+0x18`** |
| `__DATA.__data` | `0x2c8` | `0x2d0` | **`+0x8`** |

### Other Changes

```diff

-12877.100.1.0.0
+12880.200.11.0.0

-  Functions: 2633
-  Symbols:   4442
-  CStrings:  2552
+  Functions: 2645
+  Symbols:   4459
+  CStrings:  2562
Symbols:
+ _ABMigrationGateBegin
+ _ABMigrationGateEnd
+ _ABMigrationGateRenew
+ _ABMigrationGateTimeNow
+ _ABMigrationGateTimeNow.timebase_info
+ _ABMigrationGateWaitIfNeeded
+ __ABMigrationGateIsActive
+ __ABMigrationGateSetExpiry
+ __ABMigrationGateToken.once
+ __ABMigrationGateToken.token
+ ___ABIsMigratorProcess
+ ____ABMigrationGateToken_block_invoke
+ _mach_continuous_time
+ _mach_timebase_info
+ _notify_post
+ _notify_register_check
+ _notify_set_state
CStrings:
+ " ), all_person_ids(rowid, PersonLink%@) AS MATERIALIZED (SELECT pm.rowid, pm.PersonLink%@ FROM preferredmatched pm WHERE pm.PersonLink = -1 UNION ALL SELECT abp.rowid, abp.PersonLink%@ FROM preferredmatched pm JOIN ABPerson abp ON abp.PersonLink = pm.PersonLink WHERE pm.PersonLink != -1 %@) "
+ "AB Migration - claimed database gate; clients will wait"
+ "AB Migration - database gate cleared after %llus"
+ "AB Migration - deferring database access until migration completes"
+ "AB Migration - failed to get database gate token"
+ "AB Migration - gate wait timed out after %.0fs; proceeding"
+ "AB Migration - released database gate"
+ "AB Migration - renewed claim on database gate"
+ "ORDER BY 2, 1 "
+ "ORDER BY 3, 4, 5, 2, 1 "
+ "all_person_ids.PersonLink, all_person_ids.rowid "
+ "com.apple.AddressBook.migration-in-progress"
- " ), all_person_ids(rowid%@) AS NOT MATERIALIZED (SELECT pm.rowid%@ FROM preferredmatched pm WHERE pm.PersonLink = -1 UNION ALL SELECT abp.rowid%@ FROM preferredmatched pm JOIN ABPerson abp ON abp.PersonLink = pm.PersonLink WHERE pm.PersonLink != -1 ) "
- "abp.PersonLink "
```
