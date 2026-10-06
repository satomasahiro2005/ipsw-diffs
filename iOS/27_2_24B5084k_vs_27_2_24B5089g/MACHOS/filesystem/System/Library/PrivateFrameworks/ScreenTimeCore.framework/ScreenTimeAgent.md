## ScreenTimeAgent

> `/System/Library/PrivateFrameworks/ScreenTimeCore.framework/ScreenTimeAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x170be4` | `0x170c1c` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x2fc0` | `0x2fd0` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x17300` | `0x172f0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x17f0` | `0x17f8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-655.1.6.1.0
+655.1.9.1.0

-  Symbols:   1658
+  Symbols:   1659
Symbols:
+ _$s15ScreenTimeSwift34MigrationSectionDismissalConstantsO12osVersionKeySSvgZ
+ _STIsChinaSKUHiddenBundleIdentifier
- _STIsImagePlaygroundBundleIdentifier
Functions:
~ sub_1000dcf60 : 1016 -> 1072
CStrings:
+ "Ignoring app %{public}@ (suppressed on China SKU)"
- "Ignoring app %{public}@ (Image Playground suppressed on China SKU)"
```
