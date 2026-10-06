## tipsd

> `/usr/libexec/tipsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18a7c` | `0x18b8c` | **`+0x110`** |
| `__TEXT.__cstring` | `0xe5c` | `0xe8c` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xd90` | `0xdb8` | **`+0x28`** |
| `__TEXT.__oslogstring` | `0x1706` | `0x172b` | **`+0x25`** |
| `__TEXT.__objc_methname` | `0x379f` | `0x37c0` | **`+0x21`** |
| `__TEXT.__objc_stubs` | `0x2e20` | `0x2e40` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xeb0` | `0xeb8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xd58` | `0xd60` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x700` | `0x708` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-857.0.0.0.0
+866.0.0.0.0

-  Functions: 486
+  Functions: 489

-  CStrings:  918
+  CStrings:  921
CStrings:
+ "XPC: fetchELabelURLsForCurrentDevice"
+ "fetchELabelURLsForCurrentDevice:"
+ "v32@?0@\"NSURL\"8@\"NSURL\"16@\"NSError\"24"
```
