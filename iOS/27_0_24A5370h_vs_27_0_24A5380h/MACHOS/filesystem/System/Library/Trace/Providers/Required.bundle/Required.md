## Required

> `/System/Library/Trace/Providers/Required.bundle/Required`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x93b4` | `0x9354` | **`-0x60`** |
| `__TEXT.__unwind_info` | `0x378` | `0x380` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-196.0.0.0.0
+202.0.0.0.0
Functions:
~ sub_4afc : 272 -> 256
~ sub_4c0c -> sub_4bfc : 296 -> 276
~ sub_4edc -> sub_4eb8 : 432 -> 424
~ sub_508c -> sub_5060 : 664 -> 648
~ sub_6868 -> sub_682c : 804 -> 792
~ sub_7018 -> sub_6fd0 : 532 -> 520
~ sub_7d30 -> sub_7cdc : 212 -> 200
```
