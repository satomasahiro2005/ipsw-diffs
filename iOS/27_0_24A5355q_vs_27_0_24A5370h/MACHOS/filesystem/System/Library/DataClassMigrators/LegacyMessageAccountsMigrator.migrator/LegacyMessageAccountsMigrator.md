## LegacyMessageAccountsMigrator

> `/System/Library/DataClassMigrators/LegacyMessageAccountsMigrator.migrator/LegacyMessageAccountsMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e00` | `0x1df4` | **`-0xc`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3891.100.17.2.4
+3893.100.7.0.0
Functions:
~ sub_e50 : 764 -> 760
~ sub_114c -> sub_1148 : 492 -> 488
~ sub_2080 -> sub_2078 : 980 -> 976
```
