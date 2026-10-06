## migrationd

> `/System/Library/PrivateFrameworks/MigrationKit.framework/migrationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1861c` | `0x185f4` | **`-0x28`** |
| `__DATA.__data` | `0x490` | `0x480` | **`-0x10`** |
| `__TEXT.__const` | `0x5ea` | `0x5da` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x390` | `0x388` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x700` | `0x6f8` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x455` | `0x44f` | **`-0x6`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1413.0.0.0.0
+1421.0.0.0.0

-  Functions: 412
-  Symbols:   433
+  Functions: 411
+  Symbols:   432
Symbols:
- _swift_runtimeSupportsNoncopyableTypes
Functions:
~ sub_100009698 : 2344 -> 2352
- sub_10000d5a8
```
