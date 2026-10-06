## ShazamUIPlugin

> `/System/Library/Snippets/UIPlugins/ShazamUIPlugin.bundle/ShazamUIPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6db4` | `0x6de4` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x860` | `0x870` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x438` | `0x440` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x278` | `0x270` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-3600.27.4.0.0
+3600.33.2.0.0

-  Symbols:   123
+  Symbols:   124
Symbols:
+ _objc_retain_x21
+ _swift_release_x23
- _swift_release_x24
Functions:
~ sub_2d3c : 2200 -> 2228
~ sub_3a4c -> sub_3a68 : 380 -> 376
~ sub_407c -> sub_4094 : 236 -> 256
~ sub_4168 -> sub_4194 : 244 -> 252
~ sub_4ba8 -> sub_4bdc : 280 -> 276
```
