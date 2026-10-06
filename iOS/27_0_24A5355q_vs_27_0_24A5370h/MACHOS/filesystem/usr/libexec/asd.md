## asd

> `/usr/libexec/asd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8383a0` | `0x782940` | **`-0xb5a60`** |
| `__TEXT.__const` | `0xcaf30` | `0xcab40` | **`-0x3f0`** |
| `__DATA_CONST.__const` | `0x28fa8` | `0x29298` | **`+0x2f0`** |
| `__TEXT.__eh_frame` | `0x6c80` | `0x6c50` | **`-0x30`** |
| `__DATA.__common` | `0x244` | `0x22c` | **`-0x18`** |
| `__DATA.__data` | `0xebb0` | `0xebc0` | **`+0x10`** |
| `__TEXT.__cstring` | `0x2c62` | `0x2c72` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x3564` | `0x3574` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x3957` | `0x3967` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x200c` | `0x2014` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Functions: 6336
+  Functions: 6339

-  CStrings:  2698
+  CStrings:  2700
CStrings:
+ "Error verifying Ravioli: %s"
+ "serverJSON override active"
+ "serverJSONVerifiedOverride-"
- "Error verifying stored Ravioli: %s"
```
