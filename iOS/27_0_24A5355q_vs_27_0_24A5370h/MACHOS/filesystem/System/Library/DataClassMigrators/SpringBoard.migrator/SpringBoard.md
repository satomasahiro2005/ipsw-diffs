## SpringBoard

> `/System/Library/DataClassMigrators/SpringBoard.migrator/SpringBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe298` | `0xe25c` | **`-0x3c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4615.3.107.0.0
+4621.0.0.0.0
Functions:
~ sub_1acc : 608 -> 604
~ sub_1d2c -> sub_1d28 : 2428 -> 2424
~ sub_279c -> sub_2794 : 500 -> 496
~ sub_303c -> sub_3030 : 496 -> 492
~ sub_322c -> sub_321c : 700 -> 696
~ sub_4c70 -> sub_4c5c : 608 -> 604
~ sub_5908 -> sub_58f0 : 816 -> 804
~ sub_600c -> sub_5fe8 : 392 -> 388
~ sub_619c -> sub_6174 : 436 -> 432
~ sub_be38 -> sub_be0c : 292 -> 288
~ sub_bf5c -> sub_bf2c : 528 -> 520
~ sub_c5fc -> sub_c5c4 : 288 -> 284
```
