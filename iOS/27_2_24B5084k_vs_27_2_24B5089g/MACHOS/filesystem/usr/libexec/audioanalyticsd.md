## audioanalyticsd

> `/usr/libexec/audioanalyticsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0x1980` | `0x1990` | **`+0x10`** |
| `__TEXT.__text` | `0x3e49c` | `0x3e4a8` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0xcc8` | `0xcd0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-300.202.0.0.0
+300.203.0.0.0

-  Symbols:   648
+  Symbols:   649
Symbols:
+ _$s8Dispatch0A3QoSV13userInitiatedACvgZ
Functions:
~ sub_100005a78 : 1220 -> 1232
~ sub_10002167c -> sub_100021688 : 12 -> 16
~ sub_100021688 -> sub_100021698 : 16 -> 12
~ sub_10002211c -> sub_100022128 : 16 -> 12
~ sub_10002212c -> sub_100022134 : 12 -> 16
```
