## Compass

> `/private/var/staged_system_apps/Compass.app/Compass`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xce44` | `0xce20` | **`-0x24`** |
| `__TEXT.__auth_stubs` | `0xa60` | `0xa70` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x540` | `0x548` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-363.30.5.8.1
+366.30.6.4.1

-  Symbols:   259
+  Symbols:   260
Symbols:
+ _swift_release_x24
Functions:
~ sub_10000585c : 856 -> 852
~ sub_100005e24 -> sub_100005e20 : 800 -> 796
~ sub_100006580 -> sub_100006578 : 304 -> 300
~ sub_10000696c -> sub_100006960 : 372 -> 368
~ sub_10000b614 -> sub_10000b604 : 492 -> 484
~ sub_10000b8f0 -> sub_10000b8d8 : 488 -> 484
~ sub_10000bc08 -> sub_10000bbec : 444 -> 440
~ sub_10000e234 -> sub_10000e214 : 280 -> 276
```
