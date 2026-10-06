## AudioUIPlugin

> `/System/Library/Snippets/UIPlugins/AudioUIPlugin.bundle/AudioUIPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0xf00` | `0xef0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x788` | `0x780` | **`-0x8`** |
| `__TEXT.__text` | `0xee50` | `0xee58` | **`+0x8`** |

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
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.27.4.0.0
+3600.33.2.0.0

-  Symbols:   129
+  Symbols:   128
Symbols:
- _swift_release_x24
Functions:
~ sub_5834 : 256 -> 264
~ sub_5dcc -> sub_5dd4 : 2040 -> 2036
~ sub_9a58 -> sub_9a5c : 280 -> 276
~ sub_a9b4 : 1036 -> 1044
```
