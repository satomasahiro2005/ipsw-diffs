## appleidsetupd

> `/usr/libexec/appleidsetupd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__got` | `0x148` | `0x138` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0xa40` | `0xa30` | **`-0x10`** |
| `__TEXT.__text` | `0x7688` | `0x767c` | **`-0xc`** |
| `__DATA_CONST.__auth_got` | `0x528` | `0x520` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-122.0.0.0.0
+124.0.0.0.0

-  Symbols:   275
+  Symbols:   272
Symbols:
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- _swift_willThrowTypedImpl
Functions:
~ sub_100006590 : 1504 -> 1492
```
