## MobileSlideShow

> `/System/Library/DataClassMigrators/MobileSlideShow.migrator/MobileSlideShow`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x288c` | `0x287c` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0
Functions:
~ sub_11a0 : 828 -> 824
~ sub_14dc -> sub_14d8 : 4616 -> 4608
~ sub_26e4 -> sub_26d8 : 636 -> 632
```
