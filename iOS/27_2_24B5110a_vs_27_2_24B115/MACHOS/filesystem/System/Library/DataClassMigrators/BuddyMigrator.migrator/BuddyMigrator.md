## BuddyMigrator

> `/System/Library/DataClassMigrators/BuddyMigrator.migrator/BuddyMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2dbfc` | `0x2dbf8` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
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

-5411.2.4.0.0
+5411.2.5.0.0
Functions:
~ sub_296c : 8992 -> 8988
CStrings:
+ "BuddyMigrator: Queueing Diagnostics & Usage mini-buddy for re-opt-in"
- "BuddyMigrator: Queueing Diagnostics & Usage mini-buddy for auto-opt-in"
```
