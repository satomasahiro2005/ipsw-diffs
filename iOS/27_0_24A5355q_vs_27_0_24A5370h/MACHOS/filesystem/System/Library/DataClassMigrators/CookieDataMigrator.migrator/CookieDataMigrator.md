## CookieDataMigrator

> `/System/Library/DataClassMigrators/CookieDataMigrator.migrator/CookieDataMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa20` | `0xa10` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3886.100.1.0.0
+3888.100.1.0.0
Functions:
~ sub_b68 : 812 -> 804
~ sub_e94 -> sub_e8c : 1152 -> 1148
~ sub_1314 -> sub_1308 : 524 -> 520
```
