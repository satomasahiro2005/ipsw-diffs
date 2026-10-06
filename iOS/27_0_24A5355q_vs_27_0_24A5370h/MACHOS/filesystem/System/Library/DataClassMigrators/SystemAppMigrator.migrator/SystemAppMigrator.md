## SystemAppMigrator

> `/System/Library/DataClassMigrators/SystemAppMigrator.migrator/SystemAppMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7d4c` | `0x7d0c` | **`-0x40`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1655.0.0.0.0
+1660.0.0.0.0
Functions:
~ sub_1a24 : 1692 -> 1684
~ sub_3cd8 -> sub_3cd0 : 480 -> 476
~ sub_3eb8 -> sub_3eac : 1100 -> 1096
~ sub_4790 -> sub_4780 : 444 -> 440
~ sub_494c -> sub_4938 : 724 -> 712
~ sub_6d84 -> sub_6d64 : 452 -> 448
~ sub_6f48 -> sub_6f24 : 2636 -> 2624
~ sub_7d50 -> sub_7d20 : 1244 -> 1240
~ _MIArrayContainsOnlyClass : 272 -> 268
~ _MIArrayFilteredToContainOnlyClass : 352 -> 348
~ sub_8d14 -> sub_8cd8 : 280 -> 276
```
