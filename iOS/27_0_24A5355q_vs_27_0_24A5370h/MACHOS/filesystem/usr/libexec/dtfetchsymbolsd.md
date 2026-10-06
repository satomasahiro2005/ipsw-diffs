## dtfetchsymbolsd

> `/usr/libexec/dtfetchsymbolsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0x820` | `0x840` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x410` | `0x420` | **`+0x10`** |
| `__TEXT.__text` | `0x568c` | `0x5684` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   201
+  Symbols:   203
Symbols:
+ _swift_release_x28
+ _swift_retain_x28
Functions:
~ sub_1000022e8 : 1684 -> 1688
~ sub_1000035b4 -> sub_1000035b8 : 764 -> 740
~ sub_100003abc -> sub_100003aa8 : 280 -> 276
~ sub_100005580 -> sub_100005568 : 344 -> 340
~ sub_100005988 -> sub_10000596c : 256 -> 276
```
