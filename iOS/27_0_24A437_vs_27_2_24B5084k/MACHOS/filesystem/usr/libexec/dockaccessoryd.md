## dockaccessoryd

> `/usr/libexec/dockaccessoryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fb3bc` | `0x1fb3f8` | **`+0x3c`** |
| `__TEXT.__auth_stubs` | `0x39b0` | `0x39c0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1ce8` | `0x1cf0` | **`+0x8`** |

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
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-414.0.0.0.0
+431.0.0.0.0

-  Symbols:   1506
+  Symbols:   1507
Symbols:
+ _$s11DockKitCore0aC9AccessoryC22accessoryDidDisconnectyyFTj
Functions:
~ sub_1000b42cc : 456 -> 464
~ sub_10016b5b0 -> sub_10016b5b8 : 4188 -> 4240
```
