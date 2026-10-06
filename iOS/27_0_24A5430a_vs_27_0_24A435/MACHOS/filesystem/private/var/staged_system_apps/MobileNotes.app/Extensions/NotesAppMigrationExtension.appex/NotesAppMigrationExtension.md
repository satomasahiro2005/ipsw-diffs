## NotesAppMigrationExtension

> `/private/var/staged_system_apps/MobileNotes.app/Extensions/NotesAppMigrationExtension.appex/NotesAppMigrationExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x84f58` | `0x84fc0` | **`+0x68`** |
| `__TEXT.__auth_stubs` | `0x22e0` | `0x22d0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x1178` | `0x1170` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   281
+  Symbols:   280
Symbols:
- _objc_retain_x9
Functions:
~ sub_100003ce8 : 268 -> 272
~ sub_100003df4 -> sub_100003df8 : 292 -> 296
~ sub_10000e1f4 -> sub_10000e1fc : 2392 -> 2388
~ sub_10001a440 -> sub_10001a444 : 4168 -> 4156
~ sub_1000266ac -> sub_1000266a4 : 3056 -> 3048
~ sub_1000351f8 -> sub_1000351e8 : 6572 -> 6624
~ sub_10003ec20 -> sub_10003ec44 : 5916 -> 5936
~ sub_10004246c -> sub_1000424a4 : 356 -> 360
~ sub_10005dfe0 -> sub_10005e01c : 648 -> 652
~ sub_1000636a0 -> sub_1000636e0 : 612 -> 620
~ sub_100063a34 -> sub_100063a7c : 1168 -> 1176
~ sub_100074cf4 -> sub_100074d44 : 1792 -> 1824
~ sub_100083674 -> sub_1000836e4 : 992 -> 984
```
