## settings

> `/System/Library/DataClassMigrators/PreferencesMigrator.migrator/settings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x154d0` | `0x154d8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
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

-27.0.37.105.0
+27.0.42.100.0
Functions:
~ sub_100001880 : 1052 -> 1068
~ sub_100001c9c -> sub_100001cac : 1856 -> 1840
~ sub_10000c794 : 344 -> 340
~ sub_10000c8ec -> sub_10000c8e8 : 152 -> 164
~ sub_10000edb4 -> sub_10000edbc : 476 -> 480
~ sub_10000ef90 -> sub_10000ef9c : 452 -> 448
```
