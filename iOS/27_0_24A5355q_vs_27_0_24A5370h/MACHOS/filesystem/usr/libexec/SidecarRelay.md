## SidecarRelay

> `/usr/libexec/SidecarRelay`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x87768` | `0x87934` | **`+0x1cc`** |
| `__TEXT.__objc_methname` | `0x24d9` | `0x2539` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x1a00` | `0x1a40` | **`+0x40`** |
| `__DATA.__data` | `0x38e8` | `0x38f8` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x810` | `0x820` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x1ffc` | `0x2004` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-400.34.0.0.0
+400.37.0.0.0

-  Functions: 4563
+  Functions: 4568

-  CStrings:  877
+  CStrings:  879
CStrings:
+ "400.37"
+ "initWithIdentifier:model:name:version:operatingSystemVersion:"
+ "operatingSystemVersion"
- "400.34"
```
