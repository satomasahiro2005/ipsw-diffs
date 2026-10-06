## AddressBookLegacy

> `/System/Library/DataClassMigrators/AddressBookLegacy.migrator/AddressBookLegacy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2558` | `0x2550` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-12872.100.1.0.0
+12874.100.1.0.0
Functions:
~ sub_1ba0 : 1812 -> 1808
~ sub_2500 -> sub_24fc : 848 -> 844
```
