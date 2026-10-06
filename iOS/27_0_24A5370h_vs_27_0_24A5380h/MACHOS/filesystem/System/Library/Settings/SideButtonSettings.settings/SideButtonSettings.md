## SideButtonSettings

> `/System/Library/Settings/SideButtonSettings.settings/SideButtonSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0xcc0` | `0xcd0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x668` | `0x670` | **`+0x8`** |
| `__TEXT.__text` | `0xe584` | `0xe57c` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.55.10.0.0
+3600.55.26.0.0

-  Symbols:   166
+  Symbols:   167
Symbols:
+ _swift_release_x25
Functions:
~ sub_a824 : 2096 -> 2092
~ sub_b284 -> sub_b280 : 412 -> 408
```
