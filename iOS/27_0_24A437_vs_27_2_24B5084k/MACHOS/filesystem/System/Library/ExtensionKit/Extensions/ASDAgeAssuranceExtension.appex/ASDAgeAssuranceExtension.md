## ASDAgeAssuranceExtension

> `/System/Library/ExtensionKit/Extensions/ASDAgeAssuranceExtension.appex/ASDAgeAssuranceExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6fec` | `0x7580` | **`+0x594`** |
| `__TEXT.__auth_stubs` | `0xbd0` | `0xc10` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x5f0` | `0x610` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x285` | `0x2a5` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x178` | `0x188` | **`+0x10`** |
| `__DATA.__data` | `0x2e8` | `0x2f0` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x29c` | `0x2a4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x220` | `0x218` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-13.0.52.2.1
+13.1.12.0.0

-  Functions: 137
-  Symbols:   148
+  Functions: 135
+  Symbols:   146
Symbols:
+ _objc_release_x26
- _objc_release_x25
- _objc_retain_x23
- _objc_retain_x25
CStrings:
+ "[%@] itemID: %s requesterLocalizedRegionID: %s icon provided: %s"
- "[%@] itemID: %s requesterLocalizedRegionID: %s"
```
