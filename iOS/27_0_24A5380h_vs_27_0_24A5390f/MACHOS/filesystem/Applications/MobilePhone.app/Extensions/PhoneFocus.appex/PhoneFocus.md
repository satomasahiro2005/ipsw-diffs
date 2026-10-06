## PhoneFocus

> `/Applications/MobilePhone.app/Extensions/PhoneFocus.appex/PhoneFocus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9f00` | `0x9fb0` | **`+0xb0`** |
| `__TEXT.__eh_frame` | `0x380` | `0x3a8` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0xb40` | `0xb50` | **`+0x10`** |
| `__TEXT.__const` | `0xb18` | `0xb28` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x5a8` | `0x5b0` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x3f8` | `0x400` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x130` | `0x138` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3a0` | `0x3a8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x54` | `0x58` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x3c` | `0x40` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-3066.100.3.0.0
+3068.100.3.0.0

-  Functions: 245
+  Functions: 246
Functions:
~ sub_1000029f0 : 192 -> 176
+ sub_100002aa0
```
