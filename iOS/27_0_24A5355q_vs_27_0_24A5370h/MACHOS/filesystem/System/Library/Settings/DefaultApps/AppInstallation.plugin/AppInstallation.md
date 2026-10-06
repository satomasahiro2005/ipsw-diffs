## AppInstallation

> `/System/Library/Settings/DefaultApps/AppInstallation.plugin/AppInstallation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8030` | `0x8060` | **`+0x30`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4.0.30.0.0
+4.0.33.0.0
Functions:
~ sub_2f94 : 1288 -> 1280
~ sub_50d0 -> sub_50c8 : 660 -> 680
~ sub_63b8 -> sub_63c4 : 956 -> 980
~ sub_6f74 -> sub_6f98 : 136 -> 144
~ sub_8c58 -> sub_8c84 : 288 -> 292
```
