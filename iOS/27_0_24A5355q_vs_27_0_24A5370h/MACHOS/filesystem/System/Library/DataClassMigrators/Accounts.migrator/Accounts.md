## Accounts

> `/System/Library/DataClassMigrators/Accounts.migrator/Accounts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12f4` | `0x12e8` | **`-0xc`** |

### Same-size Content Changes

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1116.0.0.0.0
+1118.0.0.0.0
Functions:
~ sub_dc8 : 712 -> 708
~ sub_1270 -> sub_126c : 1256 -> 1252
~ sub_1758 -> sub_1750 : 372 -> 368
```
