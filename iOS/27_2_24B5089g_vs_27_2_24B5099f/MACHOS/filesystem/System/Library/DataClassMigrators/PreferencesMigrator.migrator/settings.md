## settings

> `/System/Library/DataClassMigrators/PreferencesMigrator.migrator/settings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ab24` | `0x1ab28` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2027.1.6.0.0
+2027.1.8.0.0
Functions:
~ sub_100006f7c : 2032 -> 2036
~ sub_100007f3c -> sub_100007f40 : 104 -> 296
~ sub_100007fa4 -> sub_100008068 : 60 -> 104
~ sub_100007fe0 -> sub_1000080d0 : 296 -> 60
```
