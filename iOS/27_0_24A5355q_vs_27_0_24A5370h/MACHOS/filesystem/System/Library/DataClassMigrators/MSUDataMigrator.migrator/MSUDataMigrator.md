## MSUDataMigrator

> `/System/Library/DataClassMigrators/MSUDataMigrator.migrator/MSUDataMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x147c` | `0x1484` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xa8` | `0xa0` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2717.0.0.0.0
+2718.0.2.0.0
Functions:
~ _copy_path_for_booted_os_data : 552 -> 568
~ _delete_folder_contents : 848 -> 844
~ -[MSUDataMigrator performMigration] : 1572 -> 1568
```
