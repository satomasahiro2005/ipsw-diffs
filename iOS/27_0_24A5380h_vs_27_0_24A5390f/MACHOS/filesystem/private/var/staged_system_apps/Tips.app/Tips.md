## Tips

> `/private/var/staged_system_apps/Tips.app/Tips`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8caec` | `0x8cb9c` | **`+0xb0`** |
| `__TEXT.__eh_frame` | `0xe34` | `0xe5c` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x3470` | `0x3480` | **`+0x10`** |
| `__TEXT.__const` | `0x55a4` | `0x55b4` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1a48` | `0x1a50` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xf68` | `0xf70` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xf58` | `0xf60` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1ea8` | `0x1eb0` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x64` | `0x68` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x5c` | `0x60` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-855.0.0.0.0
+857.0.0.0.0

-  Functions: 3039
-  Symbols:   1681
+  Functions: 3040
+  Symbols:   1684
Symbols:
+ _$s10AppIntents11EntityQueryP22displayRepresentations3forSDy0C0_2IDQZAA21DisplayRepresentationVGSayAHG_tYaKFTq
+ _$s10AppIntents11EntityQueryPAAE22displayRepresentations3forSDy0C0_2IDQZAA21DisplayRepresentationVGSayAHG_tYaKF
+ _$s10AppIntents11EntityQueryPAAE22displayRepresentations3forSDy0C0_2IDQZAA21DisplayRepresentationVGSayAHG_tYaKFTu
Functions:
~ sub_10007a2b8 : 192 -> 176
+ sub_10007a368
```
