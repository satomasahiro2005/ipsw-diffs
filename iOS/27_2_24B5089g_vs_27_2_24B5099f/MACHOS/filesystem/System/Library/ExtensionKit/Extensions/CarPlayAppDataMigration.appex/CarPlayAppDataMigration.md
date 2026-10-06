## CarPlayAppDataMigration

> `/System/Library/ExtensionKit/Extensions/CarPlayAppDataMigration.appex/CarPlayAppDataMigration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x130a4` | `0x130dc` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0xa90` | `0xab8` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0xb70` | `0xb80` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x5c0` | `0x5c8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4b0` | `0x4b8` | **`+0x8`** |

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
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-591.2.0.0.0
+591.6.0.0.0

-  Symbols:   161
+  Symbols:   162
Symbols:
+ _swift_release_x22
Functions:
~ sub_100002f84 : 32 -> 68
~ sub_10000481c -> sub_100004840 : 588 -> 592
~ sub_100004a68 -> sub_100004a90 : 588 -> 592
~ sub_1000066c4 -> sub_1000066f0 : 284 -> 296
```
