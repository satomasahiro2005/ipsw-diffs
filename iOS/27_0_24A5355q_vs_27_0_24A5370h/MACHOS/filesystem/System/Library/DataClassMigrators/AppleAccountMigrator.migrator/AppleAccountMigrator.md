## AppleAccountMigrator

> `/System/Library/DataClassMigrators/AppleAccountMigrator.migrator/AppleAccountMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x200c` | `0x1fec` | **`-0x20`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1059.1.1.0.0
+1061.0.0.0.0
Functions:
~ sub_14ac : 660 -> 656
~ sub_1740 -> sub_173c : 688 -> 684
~ sub_19f0 -> sub_19e8 : 1120 -> 1108
~ sub_1e50 -> sub_1e3c : 808 -> 804
~ sub_2178 -> sub_2160 : 384 -> 380
~ sub_22f8 -> sub_22dc : 660 -> 656
```
