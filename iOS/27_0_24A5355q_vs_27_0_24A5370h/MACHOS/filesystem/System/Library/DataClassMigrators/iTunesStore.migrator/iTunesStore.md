## iTunesStore

> `/System/Library/DataClassMigrators/iTunesStore.migrator/iTunesStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x83e4` | `0x8408` | **`+0x24`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1453.0.4.0.0
+1453.0.5.0.0
Functions:
~ sub_31e0 : 656 -> 652
~ sub_3bf4 -> sub_3bf0 : 2188 -> 2184
~ sub_53ec -> sub_53e4 : 2248 -> 2244
~ sub_6718 -> sub_670c : 420 -> 416
~ sub_6a5c -> sub_6a4c : 1212 -> 1288
~ sub_6f18 -> sub_6f54 : 708 -> 700
~ sub_71dc -> sub_7210 : 1492 -> 1488
~ sub_7af8 -> sub_7b28 : 908 -> 904
~ sub_89d4 -> sub_8a00 : 1176 -> 1172
~ sub_8fe0 -> sub_9008 : 304 -> 300
```
