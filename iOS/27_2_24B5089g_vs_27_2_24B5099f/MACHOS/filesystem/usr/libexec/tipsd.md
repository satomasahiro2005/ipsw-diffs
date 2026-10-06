## tipsd

> `/usr/libexec/tipsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0x2e60` | `0x2e80` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x3821` | `0x3838` | **`+0x17`** |
| `__DATA.__objc_selrefs` | `0xec8` | `0xed0` | **`+0x8`** |
| `__TEXT.__text` | `0x18ccc` | `0x18cd4` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-866.2.2.0.0
+866.2.3.0.0

-  CStrings:  926
+  CStrings:  927
Functions:
~ sub_10000c644 : 436 -> 444
CStrings:
+ "setRequestingBundleId:"
```
