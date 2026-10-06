## HDSViewService

> `/Applications/HDSViewService.app/HDSViewService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc021c` | `0xc0aac` | **`+0x890`** |
| `__TEXT.__oslogstring` | `0x72a5` | `0x7355` | **`+0xb0`** |
| `__DATA.__data` | `0x3f28` | `0x3ee8` | **`-0x40`** |
| `__TEXT.__cstring` | `0x6ce9` | `0x6d29` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x29f4` | `0x2a14` | **`+0x20`** |
| `__TEXT.__const` | `0x3a24` | `0x3a14` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1ff4` | `0x2000` | **`+0xc`** |
| `__TEXT.__constg_swiftt` | `0x37ec` | `0x37f4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1910` | `0x1918` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-405.10.26.0.0
+405.10.29.0.0

-  Functions: 2525
+  Functions: 2526

-  CStrings:  3166
+  CStrings:  3170
CStrings:
+ "HomePodSetupInteractor %s: session counterpart color unknown, keeping model value %hhu"
+ "HomePodSetupInteractor stereoRoleSelected: role = %d | session = %hhu | model = %hhu"
+ "Ignoring FALLBACK asset bundle for color %hhu (mappedProductType %s): %s"
+ "promptForStereoRole"
+ "stereoRoleSelected"
- "HomePodSetupInteractor stereoRoleSelected: role = %d | stereoCounterpartColor = %hhu"
```
