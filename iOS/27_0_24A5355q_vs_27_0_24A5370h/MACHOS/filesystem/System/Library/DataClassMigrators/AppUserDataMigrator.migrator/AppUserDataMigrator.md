## AppUserDataMigrator

> `/System/Library/DataClassMigrators/AppUserDataMigrator.migrator/AppUserDataMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10dc` | `0x10d0` | **`-0xc`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1655.0.0.0.0
+1660.0.0.0.0
Functions:
~ _MIArrayContainsOnlyClass : 272 -> 268
~ _MIArrayFilteredToContainOnlyClass : 352 -> 348
~ sub_1e0c -> sub_1e04 : 280 -> 276
```
