## ClarityPhotos

> `/Applications/ClarityPhotos.app/ClarityPhotos`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0x13b0` | `0x13a0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x9e0` | `0x9d8` | **`-0x8`** |
| `__TEXT.__text` | `0x12d48` | `0x12d40` | **`-0x8`** |

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

-158.0.0.0.0
+161.0.0.0.0

-  Symbols:   658
+  Symbols:   657
Symbols:
+ _swift_retain_x26
- _objc_release_x28
- _swift_retain_x25
Functions:
~ sub_100002f00 : 280 -> 276
~ sub_100006514 -> sub_100006510 : 80 -> 76
~ sub_10000b600 -> sub_10000b5f8 : 392 -> 388
~ sub_10000b79c -> sub_10000b790 : 400 -> 396
~ sub_10000be3c -> sub_10000be2c : 4044 -> 4064
~ sub_10000e85c -> sub_10000e860 : 200 -> 204
~ sub_100012818 -> sub_100012820 : 328 -> 332
~ sub_1000130a8 -> sub_1000130b4 : 344 -> 340
~ sub_100013200 -> sub_100013208 : 4380 -> 4364
```
