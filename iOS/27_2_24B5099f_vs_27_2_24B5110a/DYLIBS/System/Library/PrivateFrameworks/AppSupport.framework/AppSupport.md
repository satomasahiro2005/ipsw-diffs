## AppSupport

> `/System/Library/PrivateFrameworks/AppSupport.framework/AppSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2de74` | `0x2e038` | **`+0x1c4`** |
| `__DATA.__data` | `0x551` | `0x591` | **`+0x40`** |
| `__DATA.__bss` | `0x248` | `0x258` | **`+0x10`** |

### Other Changes

```diff

-2672.1.3.0.0
+2672.1.5.0.0

-  Symbols:   2472
+  Symbols:   2474
Symbols:
+ ___yieldRegisteredDatabases
+ ___yieldStateLock
Functions:
~ _CPSqliteDatabaseClose : 120 -> 180
~ _CPSqliteRegisterYieldNotifyBlock : 100 -> 140
~ _CPSqliteDatabaseSetShouldYieldWhenRequested : 280 -> 492
~ ___updateNotifyRegistration_block_invoke : 64 -> 204
```
