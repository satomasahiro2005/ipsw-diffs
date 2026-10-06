## BuddyMigrator

> `/System/Library/DataClassMigrators/BuddyMigrator.migrator/BuddyMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2db04` | `0x2db1c` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff
Functions:
~ sub_29b4 : 9384 -> 9392
~ sub_25dec -> sub_25df4 : 2056 -> 2060
~ sub_267b0 -> sub_267bc : 752 -> 756
~ sub_2a980 -> sub_2a990 : 672 -> 676
~ sub_2d870 -> sub_2d884 : 360 -> 364
CStrings:
+ "BuddyMigrator: Queueing Diagnostics & Usage mini-buddy for re-opt-in"
- "BuddyMigrator: Queueing Diagnostics & Usage mini-buddy for auto-opt-in"
```
