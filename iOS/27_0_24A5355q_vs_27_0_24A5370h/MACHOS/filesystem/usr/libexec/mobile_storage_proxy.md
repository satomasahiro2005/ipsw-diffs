## mobile_storage_proxy

> `/usr/libexec/mobile_storage_proxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x1dc0` | `0x1dd0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xa40` | `0xa50` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x530` | `0x538` | **`+0x8`** |
| `__TEXT.__text` | `0x12fc4` | `0x12fbc` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   210
+  Symbols:   211
Symbols:
+ _objc_retain_x26
+ _objc_retain_x28
- _objc_retain_x27
Functions:
~ sub_100008a14 : 2468 -> 2472
~ sub_1000093b8 -> sub_1000093bc : 3420 -> 3428
~ sub_10000b3f0 -> sub_10000b3fc : 908 -> 888
~ sub_10000b7a0 -> sub_10000b798 : 504 -> 500
~ sub_10000fd00 -> sub_10000fcf4 : 720 -> 724
~ sub_1000108a8 -> sub_1000108a0 : 432 -> 436
~ sub_100010a58 -> sub_100010a54 : 592 -> 588
```
